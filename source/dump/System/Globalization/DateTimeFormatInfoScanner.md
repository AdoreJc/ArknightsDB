# DateTimeFormatInfoScanner

**Namespace:** `System.Globalization`


## Fields

- `FoundDatePattern _ymdFlags`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
internal class DateTimeFormatInfoScanner
{
	internal List`1 m_dateWords; // 0x10
	private static Dictionary`2 s_knownWords; // 0x0
	private FoundDatePattern _ymdFlags; // 0x18

	private static Dictionary`2 KnownWords { get; }

	// RVA: 0x604c1d4 VA: 0x75986641d4
	private static Dictionary`2 get_KnownWords() { }
	// RVA: 0x604c5e4 VA: 0x75986645e4
	internal static Int32 SkipWhiteSpacesAndNonLetter(String pattern, Int32 currentIndex) { }
	// RVA: 0x604c6e0 VA: 0x75986646e0
	internal Void AddDateWordOrPostfix(String formatPostfix, String str) { }
	// RVA: 0x604cb20 VA: 0x7598664b20
	internal Int32 AddDateWords(String pattern, Int32 index, String formatPostfix) { }
	// RVA: 0x604ccf8 VA: 0x7598664cf8
	internal static Int32 ScanRepeatChar(String pattern, Char ch, Int32 index, out Int32 count) { }
	// RVA: 0x604c9b4 VA: 0x75986649b4
	internal Void AddIgnorableSymbols(String text) { }
	// RVA: 0x604cd7c VA: 0x7598664d7c
	internal Void ScanDateWord(String pattern) { }
	// RVA: 0x604cfb8 VA: 0x7598664fb8
	internal String[] GetDateWordsOfDTFI(DateTimeFormatInfo dtfi) { }
	// RVA: 0x604d2a4 VA: 0x75986652a4
	internal static FORMATFLAGS GetFormatFlagGenitiveMonth(String[] monthNames, String[] genitveMonthNames, String[] abbrevMonthNames, String[] genetiveAbbrevMonthNames) { }
	// RVA: 0x604d38c VA: 0x759866538c
	internal static FORMATFLAGS GetFormatFlagUseSpaceInMonthNames(String[] monthNames, String[] genitveMonthNames, String[] abbrevMonthNames, String[] genetiveAbbrevMonthNames) { }
	// RVA: 0x604d780 VA: 0x7598665780
	internal static FORMATFLAGS GetFormatFlagUseSpaceInDayNames(String[] dayNames, String[] abbrevDayNames) { }
	// RVA: 0x604d7b0 VA: 0x75986657b0
	internal static FORMATFLAGS GetFormatFlagUseHebrewCalendar(Int32 calID) { }
	// RVA: 0x604d2e4 VA: 0x75986652e4
	private static Boolean EqualStringArrays(String[] array1, String[] array2) { }
	// RVA: 0x604d68c VA: 0x759866568c
	private static Boolean ArrayElementsHaveSpace(String[] array) { }
	// RVA: 0x604d430 VA: 0x7598665430
	private static Boolean ArrayElementsBeginWithDigit(String[] array) { }
	// RVA: 0x604d7c0 VA: 0x75986657c0
	public Void .ctor() { }
}
```