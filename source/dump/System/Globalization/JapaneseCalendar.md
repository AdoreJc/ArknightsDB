# JapaneseCalendar

**Namespace:** `System.Globalization`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class JapaneseCalendar : Calendar
{
	internal static readonly DateTime calendarMinValue; // 0x0
	internal static EraInfo[] japaneseEraInfo; // 0x8
	internal static Calendar s_defaultInstance; // 0x10
	internal GregorianCalendarHelper helper; // 0x20

	public override DateTime MinSupportedDateTime { get; }
	public override DateTime MaxSupportedDateTime { get; }
	internal override Int32 ID { get; }
	public override Int32[] Eras { get; }
	public override Int32 TwoDigitYearMax { get; set; }

	// RVA: 0x605f48c VA: 0x759867748c
	public override DateTime get_MinSupportedDateTime() { }
	// RVA: 0x605f4e4 VA: 0x75986774e4
	public override DateTime get_MaxSupportedDateTime() { }
	// RVA: 0x605f53c VA: 0x759867753c
	internal static EraInfo[] GetEraInfo() { }
	// RVA: 0x605f9f4 VA: 0x75986779f4
	private static EraInfo[] GetErasFromRegistry() { }
	// RVA: 0x605f9fc VA: 0x75986779fc
	internal static Calendar GetDefaultInstance() { }
	// RVA: 0x605fac0 VA: 0x7598677ac0
	public Void .ctor() { }
	// RVA: 0x605fc98 VA: 0x7598677c98
	internal override Int32 get_ID() { }
	// RVA: 0x605fca0 VA: 0x7598677ca0
	public override Int32 GetDaysInMonth(Int32 year, Int32 month, Int32 era) { }
	// RVA: 0x605fcb8 VA: 0x7598677cb8
	public override Int32 GetDaysInYear(Int32 year, Int32 era) { }
	// RVA: 0x605fcd0 VA: 0x7598677cd0
	public override Int32 GetDayOfMonth(DateTime time) { }
	// RVA: 0x605fce8 VA: 0x7598677ce8
	public override DayOfWeek GetDayOfWeek(DateTime time) { }
	// RVA: 0x605fd00 VA: 0x7598677d00
	public override Int32 GetMonthsInYear(Int32 year, Int32 era) { }
	// RVA: 0x605fd24 VA: 0x7598677d24
	public override Int32 GetEra(DateTime time) { }
	// RVA: 0x605fd3c VA: 0x7598677d3c
	public override Int32 GetMonth(DateTime time) { }
	// RVA: 0x605fd54 VA: 0x7598677d54
	public override Int32 GetYear(DateTime time) { }
	// RVA: 0x605fd6c VA: 0x7598677d6c
	public override Boolean IsLeapYear(Int32 year, Int32 era) { }
	// RVA: 0x605fd84 VA: 0x7598677d84
	public override DateTime ToDateTime(Int32 year, Int32 month, Int32 day, Int32 hour, Int32 minute, Int32 second, Int32 millisecond, Int32 era) { }
	// RVA: 0x605fda4 VA: 0x7598677da4
	public override Int32 ToFourDigitYear(Int32 year) { }
	// RVA: 0x605fef4 VA: 0x7598677ef4
	public override Int32[] get_Eras() { }
	// RVA: 0x605abb0 VA: 0x7598672bb0
	internal static String[] EraNames() { }
	// RVA: 0x605acd8 VA: 0x7598672cd8
	internal static String[] EnglishEraNames() { }
	// RVA: 0x605ff0c VA: 0x7598677f0c
	internal override Boolean IsValidYear(Int32 year, Int32 era) { }
	// RVA: 0x605ff34 VA: 0x7598677f34
	public override Int32 get_TwoDigitYearMax() { }
	// RVA: 0x605ff78 VA: 0x7598677f78
	public override Void set_TwoDigitYearMax(Int32 value) { }
	// RVA: 0x60600b4 VA: 0x75986780b4
	private static Void .cctor() { }
}
```