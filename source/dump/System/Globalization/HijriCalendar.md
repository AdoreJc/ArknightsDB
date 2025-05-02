# HijriCalendar

**Namespace:** `System.Globalization`


## Fields

- `Int32 m_HijriAdvance`


## Properties

- `Int32 HijriAdjustment`


## Methods

- `Int64 GetAbsoluteDateHijri(Int32, Int32, Int32)`

- `Int64 DaysUpToHijriYear(Int32)`

- `Int32 get_HijriAdjustment()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class HijriCalendar : Calendar
{
	public static readonly Int32 HijriEra; // 0x0
	internal static readonly Int32[] HijriMonthDays; // 0x8
	private Int32 m_HijriAdvance; // 0x1c
	internal static readonly DateTime calendarMinValue; // 0x10
	internal static readonly DateTime calendarMaxValue; // 0x18

	public override DateTime MinSupportedDateTime { get; }
	public override DateTime MaxSupportedDateTime { get; }
	internal override Int32 ID { get; }
	public Int32 HijriAdjustment { get; }
	public override Int32[] Eras { get; }
	public override Int32 TwoDigitYearMax { get; set; }

	// RVA: 0x605de54 VA: 0x7598675e54
	public override DateTime get_MinSupportedDateTime() { }
	// RVA: 0x605deac VA: 0x7598675eac
	public override DateTime get_MaxSupportedDateTime() { }
	// RVA: 0x605df04 VA: 0x7598675f04
	public Void .ctor() { }
	// RVA: 0x605df20 VA: 0x7598675f20
	internal override Int32 get_ID() { }
	// RVA: 0x605df28 VA: 0x7598675f28
	private Int64 GetAbsoluteDateHijri(Int32 y, Int32 m, Int32 d) { }
	// RVA: 0x605dff0 VA: 0x7598675ff0
	private Int64 DaysUpToHijriYear(Int32 HijriYear) { }
	// RVA: 0x605e0ac VA: 0x75986760ac
	public Int32 get_HijriAdjustment() { }
	// RVA: 0x605e114 VA: 0x7598676114
	private static Int32 GetAdvanceHijriDate() { }
	// RVA: 0x605e11c VA: 0x759867611c
	internal static Void CheckTicksRange(Int64 ticks) { }
	// RVA: 0x605e300 VA: 0x7598676300
	internal static Void CheckEraRange(Int32 era) { }
	// RVA: 0x605e3d0 VA: 0x75986763d0
	internal static Void CheckYearRange(Int32 year, Int32 era) { }
	// RVA: 0x605e528 VA: 0x7598676528
	internal static Void CheckYearMonthRange(Int32 year, Int32 month, Int32 era) { }
	// RVA: 0x605e6b0 VA: 0x75986766b0
	internal virtual Int32 GetDatePart(Int64 ticks, Int32 part) { }
	// RVA: 0x605e920 VA: 0x7598676920
	public override Int32 GetDayOfMonth(DateTime time) { }
	// RVA: 0x605e9a4 VA: 0x75986769a4
	public override DayOfWeek GetDayOfWeek(DateTime time) { }
	// RVA: 0x605ea4c VA: 0x7598676a4c
	public override Int32 GetDaysInMonth(Int32 year, Int32 month, Int32 era) { }
	// RVA: 0x605eb18 VA: 0x7598676b18
	public override Int32 GetDaysInYear(Int32 year, Int32 era) { }
	// RVA: 0x605ebac VA: 0x7598676bac
	public override Int32 GetEra(DateTime time) { }
	// RVA: 0x605ec48 VA: 0x7598676c48
	public override Int32[] get_Eras() { }
	// RVA: 0x605ece4 VA: 0x7598676ce4
	public override Int32 GetMonth(DateTime time) { }
	// RVA: 0x605ed68 VA: 0x7598676d68
	public override Int32 GetMonthsInYear(Int32 year, Int32 era) { }
	// RVA: 0x605edd4 VA: 0x7598676dd4
	public override Int32 GetYear(DateTime time) { }
	// RVA: 0x605ee58 VA: 0x7598676e58
	public override Boolean IsLeapYear(Int32 year, Int32 era) { }
	// RVA: 0x605eef8 VA: 0x7598676ef8
	public override DateTime ToDateTime(Int32 year, Int32 month, Int32 day, Int32 hour, Int32 minute, Int32 second, Int32 millisecond, Int32 era) { }
	// RVA: 0x605f0d8 VA: 0x75986770d8
	public override Int32 get_TwoDigitYearMax() { }
	// RVA: 0x605f11c VA: 0x759867711c
	public override Void set_TwoDigitYearMax(Int32 value) { }
	// RVA: 0x605f234 VA: 0x7598677234
	public override Int32 ToFourDigitYear(Int32 year) { }
	// RVA: 0x605f370 VA: 0x7598677370
	private static Void .cctor() { }
}
```