# CultureData

**Namespace:** `System.Globalization`


## Fields

- `String sAM1159`

- `String sPM2359`

- `String sTimeSeparator`

- `Int32 iFirstDayOfWeek`

- `Int32 iFirstWeekOfYear`

- `String sISO639Language`

- `Boolean bUseOverrides`

- `Int32 calendarId`

- `Int32 numberIndex`

- `Int32 iDefaultAnsiCodePage`

- `Int32 iDefaultOemCodePage`

- `Int32 iDefaultMacCodePage`

- `Int32 iDefaultEbcdicCodePage`

- `Boolean isRightToLeft`

- `String sListSeparator`


## Methods

- `Void fill_culture_data(Int32)`

- `CalendarData GetCalendar(Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
internal class CultureData
{
	private String sAM1159; // 0x10
	private String sPM2359; // 0x18
	private String sTimeSeparator; // 0x20
	private String[] saLongTimes; // 0x28
	private String[] saShortTimes; // 0x30
	private Int32 iFirstDayOfWeek; // 0x38
	private Int32 iFirstWeekOfYear; // 0x3c
	private Int32[] waCalendars; // 0x40
	private CalendarData[] calendars; // 0x48
	private String sISO639Language; // 0x50
	private readonly String sRealName; // 0x58
	private Boolean bUseOverrides; // 0x60
	private Int32 calendarId; // 0x64
	private Int32 numberIndex; // 0x68
	private Int32 iDefaultAnsiCodePage; // 0x6c
	private Int32 iDefaultOemCodePage; // 0x70
	private Int32 iDefaultMacCodePage; // 0x74
	private Int32 iDefaultEbcdicCodePage; // 0x78
	private Boolean isRightToLeft; // 0x7c
	private String sListSeparator; // 0x80
	private static CultureData s_Invariant; // 0x0

	public static CultureData Invariant { get; }
	internal String[] LongTimes { get; }
	internal String[] ShortTimes { get; }
	internal String SISO639LANGNAME { get; }
	internal Int32 IFIRSTDAYOFWEEK { get; }
	internal Int32 IFIRSTWEEKOFYEAR { get; }
	internal String SAM1159 { get; }
	internal String SPM2359 { get; }
	internal String TimeSeparator { get; }
	internal Int32[] CalendarIds { get; }
	internal Boolean IsInvariantCulture { get; }
	internal String CultureName { get; }
	internal String SCOMPAREINFO { get; }
	internal String STEXTINFO { get; }
	internal Int32 IDEFAULTOEMCODEPAGE { get; }
	internal Boolean UseUserOverride { get; }

	// RVA: 0x60655d0 VA: 0x759867d5d0
	private Void .ctor(String name) { }
	// RVA: 0x6065600 VA: 0x759867d600
	public static CultureData get_Invariant() { }
	// RVA: 0x6065ab0 VA: 0x759867dab0
	public static CultureData GetCultureData(String cultureName, Boolean useUserOverride) { }
	// RVA: 0x6065ba8 VA: 0x759867dba8
	public static CultureData GetCultureData(String cultureName, Boolean useUserOverride, Int32 datetimeIndex, Int32 calendarId, Int32 numberIndex, String iso2lang, Int32 ansiCodePage, Int32 oemCodePage, Int32 macCodePage, Int32 ebcdicCodePage, Boolean rightToLeft, String listSeparator) { }
	// RVA: 0x6065cec VA: 0x759867dcec
	private Void fill_culture_data(Int32 datetimeIndex) { }
	// RVA: 0x6065cf0 VA: 0x759867dcf0
	public CalendarData GetCalendar(Int32 calendarId) { }
	// RVA: 0x6065e28 VA: 0x759867de28
	internal String[] get_LongTimes() { }
	// RVA: 0x6065e40 VA: 0x759867de40
	internal String[] get_ShortTimes() { }
	// RVA: 0x6065e58 VA: 0x759867de58
	internal String get_SISO639LANGNAME() { }
	// RVA: 0x6065e60 VA: 0x759867de60
	internal Int32 get_IFIRSTDAYOFWEEK() { }
	// RVA: 0x6065e68 VA: 0x759867de68
	internal Int32 get_IFIRSTWEEKOFYEAR() { }
	// RVA: 0x6065e70 VA: 0x759867de70
	internal String get_SAM1159() { }
	// RVA: 0x6065e78 VA: 0x759867de78
	internal String get_SPM2359() { }
	// RVA: 0x6065e80 VA: 0x759867de80
	internal String get_TimeSeparator() { }
	// RVA: 0x6065e88 VA: 0x759867de88
	internal Int32[] get_CalendarIds() { }
	// RVA: 0x606604c VA: 0x759867e04c
	internal CalendarId[] GetCalendarIds() { }
	// RVA: 0x6066124 VA: 0x759867e124
	internal Boolean get_IsInvariantCulture() { }
	// RVA: 0x6066130 VA: 0x759867e130
	internal String get_CultureName() { }
	// RVA: 0x6066138 VA: 0x759867e138
	internal String get_SCOMPAREINFO() { }
	// RVA: 0x6066178 VA: 0x759867e178
	internal String get_STEXTINFO() { }
	// RVA: 0x6066180 VA: 0x759867e180
	internal Int32 get_IDEFAULTOEMCODEPAGE() { }
	// RVA: 0x6066188 VA: 0x759867e188
	internal Boolean get_UseUserOverride() { }
	// RVA: 0x6066190 VA: 0x759867e190
	internal String[] EraNames(Int32 calendarId) { }
	// RVA: 0x60661ac VA: 0x759867e1ac
	internal String[] AbbrevEraNames(Int32 calendarId) { }
	// RVA: 0x60661c8 VA: 0x759867e1c8
	internal String[] AbbreviatedEnglishEraNames(Int32 calendarId) { }
	// RVA: 0x60661e4 VA: 0x759867e1e4
	internal String[] ShortDates(Int32 calendarId) { }
	// RVA: 0x6066200 VA: 0x759867e200
	internal String[] LongDates(Int32 calendarId) { }
	// RVA: 0x606621c VA: 0x759867e21c
	internal String[] YearMonths(Int32 calendarId) { }
	// RVA: 0x6066238 VA: 0x759867e238
	internal String[] DayNames(Int32 calendarId) { }
	// RVA: 0x6066254 VA: 0x759867e254
	internal String[] AbbreviatedDayNames(Int32 calendarId) { }
	// RVA: 0x6066270 VA: 0x759867e270
	internal String[] MonthNames(Int32 calendarId) { }
	// RVA: 0x606628c VA: 0x759867e28c
	internal String[] GenitiveMonthNames(Int32 calendarId) { }
	// RVA: 0x60662a8 VA: 0x759867e2a8
	internal String[] AbbreviatedMonthNames(Int32 calendarId) { }
	// RVA: 0x60662c4 VA: 0x759867e2c4
	internal String[] AbbreviatedGenitiveMonthNames(Int32 calendarId) { }
	// RVA: 0x60662e0 VA: 0x759867e2e0
	internal String[] LeapYearMonthNames(Int32 calendarId) { }
	// RVA: 0x60662fc VA: 0x759867e2fc
	internal String MonthDay(Int32 calendarId) { }
	// RVA: 0x6066318 VA: 0x759867e318
	internal String DateSeparator(Int32 calendarId) { }
	// RVA: 0x60663c4 VA: 0x759867e3c4
	private static String GetDateSeparator(String format) { }
	// RVA: 0x606640c VA: 0x759867e40c
	private static String GetSeparator(String format, String timeParts) { }
	// RVA: 0x6066510 VA: 0x759867e510
	private static Int32 IndexOfTimePart(String format, Int32 startIndex, String timeParts) { }
	// RVA: 0x60665fc VA: 0x759867e5fc
	private static String UnescapeNlsString(String str, Int32 start, Int32 end) { }
	// RVA: 0x60667a0 VA: 0x759867e7a0
	internal static String[] ReescapeWin32Strings(String[] array) { }
	// RVA: 0x60667a4 VA: 0x759867e7a4
	internal static String ReescapeWin32String(String str) { }
	// RVA: 0x60667a8 VA: 0x759867e7a8
	private static Int32 strlen(Byte* s) { }
	// RVA: 0x60667c0 VA: 0x759867e7c0
	private static String idx2string(Byte* data, Int32 idx) { }
	// RVA: 0x6066804 VA: 0x759867e804
	private Int32[] create_group_sizes_array(Int32 gs0, Int32 gs1) { }
	// RVA: 0x60668b8 VA: 0x759867e8b8
	internal Void GetNFIValues(NumberFormatInfo nfi) { }
	// RVA: 0x6066b10 VA: 0x759867eb10
	private static Byte* fill_number_data(Int32 index, ref NumberFormatEntryManaged nfe) { }
}
```