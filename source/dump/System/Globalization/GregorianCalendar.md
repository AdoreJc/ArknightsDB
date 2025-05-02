# GregorianCalendar

**Namespace:** `System.Globalization`


## Methods

- `Void OnDeserialized(StreamingContext)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class GregorianCalendar : Calendar
{
	internal GregorianCalendarTypes m_type; // 0x1c
	internal static readonly Int32[] DaysToMonth365; // 0x0
	internal static readonly Int32[] DaysToMonth366; // 0x8
	private static Calendar s_defaultInstance; // 0x10

	public override DateTime MinSupportedDateTime { get; }
	public override DateTime MaxSupportedDateTime { get; }
	internal override Int32 ID { get; }
	public override Int32[] Eras { get; }
	public override Int32 TwoDigitYearMax { get; set; }

	// RVA: 0x605aed0 VA: 0x7598672ed0
	private Void OnDeserialized(StreamingContext ctx) { }
	// RVA: 0x605afac VA: 0x7598672fac
	public override DateTime get_MinSupportedDateTime() { }
	// RVA: 0x605b004 VA: 0x7598673004
	public override DateTime get_MaxSupportedDateTime() { }
	// RVA: 0x605b05c VA: 0x759867305c
	internal static Calendar GetDefaultInstance() { }
	// RVA: 0x605b138 VA: 0x7598673138
	public Void .ctor() { }
	// RVA: 0x605b164 VA: 0x7598673164
	public Void .ctor(GregorianCalendarTypes type) { }
	// RVA: 0x605b2b8 VA: 0x75986732b8
	internal override Int32 get_ID() { }
	// RVA: 0x605b2c0 VA: 0x75986732c0
	internal virtual Int32 GetDatePart(Int64 ticks, Int32 part) { }
	// RVA: 0x605b4bc VA: 0x75986734bc
	internal static Int64 GetAbsoluteDate(Int32 year, Int32 month, Int32 day) { }
	// RVA: 0x605b6a4 VA: 0x75986736a4
	public override Int32 GetDayOfMonth(DateTime time) { }
	// RVA: 0x605b728 VA: 0x7598673728
	public override DayOfWeek GetDayOfWeek(DateTime time) { }
	// RVA: 0x605b7d0 VA: 0x75986737d0
	public override Int32 GetDaysInMonth(Int32 year, Int32 month, Int32 era) { }
	// RVA: 0x605ba80 VA: 0x7598673a80
	public override Int32 GetDaysInYear(Int32 year, Int32 era) { }
	// RVA: 0x605bc14 VA: 0x7598673c14
	public override Int32 GetEra(DateTime time) { }
	// RVA: 0x605bc1c VA: 0x7598673c1c
	public override Int32[] get_Eras() { }
	// RVA: 0x605bc80 VA: 0x7598673c80
	public override Int32 GetMonth(DateTime time) { }
	// RVA: 0x605bd04 VA: 0x7598673d04
	public override Int32 GetMonthsInYear(Int32 year, Int32 era) { }
	// RVA: 0x605be54 VA: 0x7598673e54
	public override Int32 GetYear(DateTime time) { }
	// RVA: 0x605bed8 VA: 0x7598673ed8
	public override Boolean IsLeapYear(Int32 year, Int32 era) { }
	// RVA: 0x605c074 VA: 0x7598674074
	public override DateTime ToDateTime(Int32 year, Int32 month, Int32 day, Int32 hour, Int32 minute, Int32 second, Int32 millisecond, Int32 era) { }
	// RVA: 0x605c114 VA: 0x7598674114
	internal override Boolean TryToDateTime(Int32 year, Int32 month, Int32 day, Int32 hour, Int32 minute, Int32 second, Int32 millisecond, Int32 era, out DateTime result) { }
	// RVA: 0x605c208 VA: 0x7598674208
	public override Int32 get_TwoDigitYearMax() { }
	// RVA: 0x605c24c VA: 0x759867424c
	public override Void set_TwoDigitYearMax(Int32 value) { }
	// RVA: 0x605c364 VA: 0x7598674364
	public override Int32 ToFourDigitYear(Int32 year) { }
	// RVA: 0x605c484 VA: 0x7598674484
	private static Void .cctor() { }
}
```