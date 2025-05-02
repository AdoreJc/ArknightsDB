# ThaiBuddhistCalendar

**Namespace:** `System.Globalization`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class ThaiBuddhistCalendar : Calendar
{
	internal static EraInfo[] thaiBuddhistEraInfo; // 0x0
	internal GregorianCalendarHelper helper; // 0x20

	public override DateTime MinSupportedDateTime { get; }
	public override DateTime MaxSupportedDateTime { get; }
	internal override Int32 ID { get; }
	public override Int32[] Eras { get; }
	public override Int32 TwoDigitYearMax { get; set; }

	// RVA: 0x6063078 VA: 0x759867b078
	public override DateTime get_MinSupportedDateTime() { }
	// RVA: 0x60630d0 VA: 0x759867b0d0
	public override DateTime get_MaxSupportedDateTime() { }
	// RVA: 0x6063128 VA: 0x759867b128
	public Void .ctor() { }
	// RVA: 0x60631dc VA: 0x759867b1dc
	internal override Int32 get_ID() { }
	// RVA: 0x60631e4 VA: 0x759867b1e4
	public override Int32 GetDaysInMonth(Int32 year, Int32 month, Int32 era) { }
	// RVA: 0x6063200 VA: 0x759867b200
	public override Int32 GetDaysInYear(Int32 year, Int32 era) { }
	// RVA: 0x606321c VA: 0x759867b21c
	public override Int32 GetDayOfMonth(DateTime time) { }
	// RVA: 0x6063238 VA: 0x759867b238
	public override DayOfWeek GetDayOfWeek(DateTime time) { }
	// RVA: 0x6063254 VA: 0x759867b254
	public override Int32 GetMonthsInYear(Int32 year, Int32 era) { }
	// RVA: 0x6063270 VA: 0x759867b270
	public override Int32 GetEra(DateTime time) { }
	// RVA: 0x606328c VA: 0x759867b28c
	public override Int32 GetMonth(DateTime time) { }
	// RVA: 0x60632a8 VA: 0x759867b2a8
	public override Int32 GetYear(DateTime time) { }
	// RVA: 0x60632c4 VA: 0x759867b2c4
	public override Boolean IsLeapYear(Int32 year, Int32 era) { }
	// RVA: 0x60632e0 VA: 0x759867b2e0
	public override DateTime ToDateTime(Int32 year, Int32 month, Int32 day, Int32 hour, Int32 minute, Int32 second, Int32 millisecond, Int32 era) { }
	// RVA: 0x6063304 VA: 0x759867b304
	public override Int32[] get_Eras() { }
	// RVA: 0x6063320 VA: 0x759867b320
	public override Int32 get_TwoDigitYearMax() { }
	// RVA: 0x606335c VA: 0x759867b35c
	public override Void set_TwoDigitYearMax(Int32 value) { }
	// RVA: 0x60634b8 VA: 0x759867b4b8
	public override Int32 ToFourDigitYear(Int32 year) { }
	// RVA: 0x6063568 VA: 0x759867b568
	private static Void .cctor() { }
}
```