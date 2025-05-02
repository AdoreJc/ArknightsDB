# TaiwanCalendar

**Namespace:** `System.Globalization`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class TaiwanCalendar : Calendar
{
	internal static EraInfo[] taiwanEraInfo; // 0x0
	internal static Calendar s_defaultInstance; // 0x8
	internal GregorianCalendarHelper helper; // 0x20
	internal static readonly DateTime calendarMinValue; // 0x10

	public override DateTime MinSupportedDateTime { get; }
	public override DateTime MaxSupportedDateTime { get; }
	internal override Int32 ID { get; }
	public override Int32[] Eras { get; }
	public override Int32 TwoDigitYearMax { get; set; }

	// RVA: 0x6061308 VA: 0x7598679308
	internal static Calendar GetDefaultInstance() { }
	// RVA: 0x60615a4 VA: 0x75986795a4
	public override DateTime get_MinSupportedDateTime() { }
	// RVA: 0x60615fc VA: 0x75986795fc
	public override DateTime get_MaxSupportedDateTime() { }
	// RVA: 0x60613cc VA: 0x75986793cc
	public Void .ctor() { }
	// RVA: 0x6061654 VA: 0x7598679654
	internal override Int32 get_ID() { }
	// RVA: 0x606165c VA: 0x759867965c
	public override Int32 GetDaysInMonth(Int32 year, Int32 month, Int32 era) { }
	// RVA: 0x6061674 VA: 0x7598679674
	public override Int32 GetDaysInYear(Int32 year, Int32 era) { }
	// RVA: 0x606168c VA: 0x759867968c
	public override Int32 GetDayOfMonth(DateTime time) { }
	// RVA: 0x60616a4 VA: 0x75986796a4
	public override DayOfWeek GetDayOfWeek(DateTime time) { }
	// RVA: 0x60616bc VA: 0x75986796bc
	public override Int32 GetMonthsInYear(Int32 year, Int32 era) { }
	// RVA: 0x60616e0 VA: 0x75986796e0
	public override Int32 GetEra(DateTime time) { }
	// RVA: 0x60616f8 VA: 0x75986796f8
	public override Int32 GetMonth(DateTime time) { }
	// RVA: 0x6061710 VA: 0x7598679710
	public override Int32 GetYear(DateTime time) { }
	// RVA: 0x6061728 VA: 0x7598679728
	public override Boolean IsLeapYear(Int32 year, Int32 era) { }
	// RVA: 0x6061740 VA: 0x7598679740
	public override DateTime ToDateTime(Int32 year, Int32 month, Int32 day, Int32 hour, Int32 minute, Int32 second, Int32 millisecond, Int32 era) { }
	// RVA: 0x6061760 VA: 0x7598679760
	public override Int32[] get_Eras() { }
	// RVA: 0x6061778 VA: 0x7598679778
	public override Int32 get_TwoDigitYearMax() { }
	// RVA: 0x60617bc VA: 0x75986797bc
	public override Void set_TwoDigitYearMax(Int32 value) { }
	// RVA: 0x60618f8 VA: 0x75986798f8
	public override Int32 ToFourDigitYear(Int32 year) { }
	// RVA: 0x6061a48 VA: 0x7598679a48
	private static Void .cctor() { }
}
```