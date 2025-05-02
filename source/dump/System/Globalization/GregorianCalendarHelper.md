# GregorianCalendarHelper

**Namespace:** `System.Globalization`


## Methods

- `Int32 GetYearOffset(Int32, Int32, Boolean)`

- `Int32 GetDayOfMonth(DateTime)`

- `DayOfWeek GetDayOfWeek(DateTime)`

- `Int32 GetDaysInMonth(Int32, Int32, Int32)`

- `Int32 GetDaysInYear(Int32, Int32)`

- `Int32 GetEra(DateTime)`

- `Int32 GetMonth(DateTime)`

- `Int32 GetMonthsInYear(Int32, Int32)`

- `Int32 GetYear(DateTime)`

- `Boolean IsLeapYear(Int32, Int32)`

- `DateTime ToDateTime(Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32)`

- `Int32 ToFourDigitYear(Int32, Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
internal class GregorianCalendarHelper
{
	internal static readonly Int32[] DaysToMonth365; // 0x0
	internal static readonly Int32[] DaysToMonth366; // 0x8
	internal Int32 m_maxYear; // 0x10
	internal Int32 m_minYear; // 0x14
	internal Calendar m_Cal; // 0x18
	internal EraInfo[] m_EraInfo; // 0x20
	internal Int32[] m_eras; // 0x28
	internal DateTime m_minDate; // 0x30

	internal Int32 MaxYear { get; }
	public Int32[] Eras { get; }

	// RVA: 0x605c760 VA: 0x7598674760
	internal Int32 get_MaxYear() { }
	// RVA: 0x605c768 VA: 0x7598674768
	internal Void .ctor(Calendar cal, EraInfo[] eraInfo) { }
	// RVA: 0x605c808 VA: 0x7598674808
	private Int32 GetYearOffset(Int32 year, Int32 era, Boolean throwOnError) { }
	// RVA: 0x605cafc VA: 0x7598674afc
	internal Int32 GetGregorianYear(Int32 year, Int32 era) { }
	// RVA: 0x605cb18 VA: 0x7598674b18
	internal Boolean IsValidYear(Int32 year, Int32 era) { }
	// RVA: 0x605cb34 VA: 0x7598674b34
	internal virtual Int32 GetDatePart(Int64 ticks, Int32 part) { }
	// RVA: 0x605cf28 VA: 0x7598674f28
	internal static Int64 GetAbsoluteDate(Int32 year, Int32 month, Int32 day) { }
	// RVA: 0x605d110 VA: 0x7598675110
	internal static Int64 DateToTicks(Int32 year, Int32 month, Int32 day) { }
	// RVA: 0x605d190 VA: 0x7598675190
	internal static Int64 TimeToTicks(Int32 hour, Int32 minute, Int32 second, Int32 millisecond) { }
	// RVA: 0x605cd40 VA: 0x7598674d40
	internal Void CheckTicksRange(Int64 ticks) { }
	// RVA: 0x605d34c VA: 0x759867534c
	public Int32 GetDayOfMonth(DateTime time) { }
	// RVA: 0x605d3cc VA: 0x75986753cc
	public DayOfWeek GetDayOfWeek(DateTime time) { }
	// RVA: 0x605d498 VA: 0x7598675498
	public Int32 GetDaysInMonth(Int32 year, Int32 month, Int32 era) { }
	// RVA: 0x605d624 VA: 0x7598675624
	public Int32 GetDaysInYear(Int32 year, Int32 era) { }
	// RVA: 0x605d694 VA: 0x7598675694
	public Int32 GetEra(DateTime time) { }
	// RVA: 0x605d7a4 VA: 0x75986757a4
	public Int32[] get_Eras() { }
	// RVA: 0x605d8ac VA: 0x75986758ac
	public Int32 GetMonth(DateTime time) { }
	// RVA: 0x605d92c VA: 0x759867592c
	public Int32 GetMonthsInYear(Int32 year, Int32 era) { }
	// RVA: 0x605d944 VA: 0x7598675944
	public Int32 GetYear(DateTime time) { }
	// RVA: 0x605da74 VA: 0x7598675a74
	public Boolean IsLeapYear(Int32 year, Int32 era) { }
	// RVA: 0x605dae4 VA: 0x7598675ae4
	public DateTime ToDateTime(Int32 year, Int32 month, Int32 day, Int32 hour, Int32 minute, Int32 second, Int32 millisecond, Int32 era) { }
	// RVA: 0x605dbe8 VA: 0x7598675be8
	public Int32 ToFourDigitYear(Int32 year, Int32 twoDigitYearMax) { }
	// RVA: 0x605dd70 VA: 0x7598675d70
	private static Void .cctor() { }
}
```