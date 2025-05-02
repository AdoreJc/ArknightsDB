# CalendarData

**Namespace:** `System.Globalization`


## Methods

- `Void InitializeEraNames(String, Int32)`

- `Void InitializeAbbreviatedEraNames(String, Int32)`

- `Boolean fill_calendar_data(String, Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
internal class CalendarData
{
	internal const Int32 MAX_CALENDARS; // 0x0
	internal String sNativeName; // 0x10
	internal String[] saShortDates; // 0x18
	internal String[] saYearMonths; // 0x20
	internal String[] saLongDates; // 0x28
	internal String sMonthDay; // 0x30
	internal String[] saEraNames; // 0x38
	internal String[] saAbbrevEraNames; // 0x40
	internal String[] saAbbrevEnglishEraNames; // 0x48
	internal String[] saDayNames; // 0x50
	internal String[] saAbbrevDayNames; // 0x58
	internal String[] saSuperShortDayNames; // 0x60
	internal String[] saMonthNames; // 0x68
	internal String[] saAbbrevMonthNames; // 0x70
	internal String[] saMonthGenitiveNames; // 0x78
	internal String[] saAbbrevMonthGenitiveNames; // 0x80
	internal String[] saLeapYearMonthNames; // 0x88
	internal Int32 iTwoDigitYearMax; // 0x90
	internal Int32 iCurrentEra; // 0x94
	internal Boolean bUseUserOverrides; // 0x98
	internal static CalendarData Invariant; // 0x0
	private static String[] HEBREW_MONTH_NAMES; // 0x8
	private static String[] HEBREW_LEAP_MONTH_NAMES; // 0x10


	// RVA: 0x6057b70 VA: 0x759866fb70
	private Void .ctor() { }
	// RVA: 0x6057b80 VA: 0x759866fb80
	private static Void .cctor() { }
	// RVA: 0x6059a44 VA: 0x7598671a44
	internal Void .ctor(String localeName, Int32 calendarId, Boolean bUseUserOverrides) { }
	// RVA: 0x605a1a4 VA: 0x75986721a4
	private Void InitializeEraNames(String localeName, Int32 calendarId) { }
	// RVA: 0x605aac4 VA: 0x7598672ac4
	private static String[] GetJapaneseEraNames() { }
	// RVA: 0x605a9d8 VA: 0x75986729d8
	private static String[] GetJapaneseEnglishEraNames() { }
	// RVA: 0x605a62c VA: 0x759867262c
	private Void InitializeAbbreviatedEraNames(String localeName, Int32 calendarId) { }
	// RVA: 0x6057470 VA: 0x759866f470
	internal static CalendarData GetCalendarData(Int32 calendarId) { }
	// RVA: 0x605ae00 VA: 0x7598672e00
	private static String CalendarIdToCultureName(Int32 calendarId) { }
	// RVA: 0x6057b68 VA: 0x759866fb68
	public static Int32 nativeGetTwoDigitYearMax(Int32 calID) { }
	// RVA: 0x605a0d0 VA: 0x75986720d0
	private static Boolean nativeGetCalendarData(CalendarData data, String localeName, Int32 calendarId) { }
	// RVA: 0x605aecc VA: 0x7598672ecc
	private Boolean fill_calendar_data(String localeName, Int32 datetimeIndex) { }
}
```