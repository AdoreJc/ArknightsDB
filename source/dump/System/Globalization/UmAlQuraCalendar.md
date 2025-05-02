# UmAlQuraCalendar

**Namespace:** `System.Globalization`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class UmAlQuraCalendar : Calendar
{
	private static readonly DateMapping[] HijriYearInfo; // 0x0
	internal static DateTime minDate; // 0x8
	internal static DateTime maxDate; // 0x10

	public override DateTime MinSupportedDateTime { get; }
	public override DateTime MaxSupportedDateTime { get; }
	internal override Int32 BaseCalendarID { get; }
	internal override Int32 ID { get; }
	public override Int32[] Eras { get; }
	public override Int32 TwoDigitYearMax { get; set; }

	// RVA: 0x6063678 VA: 0x759867b678
	private static DateMapping[] InitDateMapping() { }
	// RVA: 0x606381c VA: 0x759867b81c
	public override DateTime get_MinSupportedDateTime() { }
	// RVA: 0x6063874 VA: 0x759867b874
	public override DateTime get_MaxSupportedDateTime() { }
	// RVA: 0x60638cc VA: 0x759867b8cc
	public Void .ctor() { }
	// RVA: 0x60638d4 VA: 0x759867b8d4
	internal override Int32 get_BaseCalendarID() { }
	// RVA: 0x60638dc VA: 0x759867b8dc
	internal override Int32 get_ID() { }
	// RVA: 0x60638e4 VA: 0x759867b8e4
	private static Void ConvertHijriToGregorian(Int32 HijriYear, Int32 HijriMonth, Int32 HijriDay, ref Int32 yg, ref Int32 mg, ref Int32 dg) { }
	// RVA: 0x6063a48 VA: 0x759867ba48
	private static Int64 GetAbsoluteDateUmAlQura(Int32 year, Int32 month, Int32 day) { }
	// RVA: 0x6063b10 VA: 0x759867bb10
	internal static Void CheckTicksRange(Int64 ticks) { }
	// RVA: 0x6063d50 VA: 0x759867bd50
	internal static Void CheckEraRange(Int32 era) { }
	// RVA: 0x6063dcc VA: 0x759867bdcc
	internal static Void CheckYearRange(Int32 year, Int32 era) { }
	// RVA: 0x6063f14 VA: 0x759867bf14
	internal static Void CheckYearMonthRange(Int32 year, Int32 month, Int32 era) { }
	// RVA: 0x6063ff4 VA: 0x759867bff4
	private static Void ConvertGregorianToHijri(DateTime time, ref Int32 HijriYear, ref Int32 HijriMonth, ref Int32 HijriDay) { }
	// RVA: 0x60642e0 VA: 0x759867c2e0
	internal virtual Int32 GetDatePart(DateTime time, Int32 part) { }
	// RVA: 0x6064470 VA: 0x759867c470
	public override Int32 GetDayOfMonth(DateTime time) { }
	// RVA: 0x6064484 VA: 0x759867c484
	public override DayOfWeek GetDayOfWeek(DateTime time) { }
	// RVA: 0x606452c VA: 0x759867c52c
	public override Int32 GetDaysInMonth(Int32 year, Int32 month, Int32 era) { }
	// RVA: 0x60645e4 VA: 0x759867c5e4
	internal static Int32 RealGetDaysInYear(Int32 year) { }
	// RVA: 0x6064684 VA: 0x759867c684
	public override Int32 GetDaysInYear(Int32 year, Int32 era) { }
	// RVA: 0x60646f0 VA: 0x759867c6f0
	public override Int32 GetEra(DateTime time) { }
	// RVA: 0x6064784 VA: 0x759867c784
	public override Int32[] get_Eras() { }
	// RVA: 0x60647e8 VA: 0x759867c7e8
	public override Int32 GetMonth(DateTime time) { }
	// RVA: 0x60647fc VA: 0x759867c7fc
	public override Int32 GetMonthsInYear(Int32 year, Int32 era) { }
	// RVA: 0x6064868 VA: 0x759867c868
	public override Int32 GetYear(DateTime time) { }
	// RVA: 0x606487c VA: 0x759867c87c
	public override Boolean IsLeapYear(Int32 year, Int32 era) { }
	// RVA: 0x60648f4 VA: 0x759867c8f4
	public override DateTime ToDateTime(Int32 year, Int32 month, Int32 day, Int32 hour, Int32 minute, Int32 second, Int32 millisecond, Int32 era) { }
	// RVA: 0x6064b48 VA: 0x759867cb48
	public override Int32 get_TwoDigitYearMax() { }
	// RVA: 0x6064b84 VA: 0x759867cb84
	public override Void set_TwoDigitYearMax(Int32 value) { }
	// RVA: 0x6064ca4 VA: 0x759867cca4
	public override Int32 ToFourDigitYear(Int32 year) { }
	// RVA: 0x6064de0 VA: 0x759867cde0
	private static Void .cctor() { }
}
```