# Number

**Namespace:** ` `


## Dump
```C#
// Dll : System.Numerics.dll
// Namespace : 
private class Number
{
	private static String[] s_posCurrencyFormats; // 0x0
	private static String[] s_negCurrencyFormats; // 0x8
	private static String[] s_posPercentFormats; // 0x10
	private static String[] s_negPercentFormats; // 0x18
	private static String[] s_negNumberFormats; // 0x20
	private static String s_posNumberFormat; // 0x28


	// RVA: 0x626e2c4 VA: 0x75988862c4
	internal static Void Int32ToDecChars(Char* buffer, ref Int32 index, UInt32 value, Int32 digits) { }
	// RVA: 0x626cbbc VA: 0x7598884bbc
	internal static Char ParseFormatSpecifier(ReadOnlySpan`1 format, out Int32 digits) { }
	// RVA: 0x626ccfc VA: 0x7598884cfc
	internal static Void NumberToString(ref ValueStringBuilder sb, ref NumberBuffer number, Char format, Int32 nMaxDigits, NumberFormatInfo info, Boolean isDecimal) { }
	// RVA: 0x626e3f4 VA: 0x75988863f4
	private static Void FormatCurrency(ref ValueStringBuilder sb, ref NumberBuffer number, Int32 nMinDigits, Int32 nMaxDigits, NumberFormatInfo info) { }
	// RVA: 0x626f610 VA: 0x7598887610
	private static Int32 wcslen(Char* s) { }
	// RVA: 0x626e654 VA: 0x7598886654
	private static Void FormatFixed(ref ValueStringBuilder sb, ref NumberBuffer number, Int32 nMinDigits, Int32 nMaxDigits, NumberFormatInfo info, Int32[] groupDigits, String sDecimal, String sGroup) { }
	// RVA: 0x626eb90 VA: 0x7598886b90
	private static Void FormatNumber(ref ValueStringBuilder sb, ref NumberBuffer number, Int32 nMinDigits, Int32 nMaxDigits, NumberFormatInfo info) { }
	// RVA: 0x626edd8 VA: 0x7598886dd8
	private static Void FormatScientific(ref ValueStringBuilder sb, ref NumberBuffer number, Int32 nMinDigits, Int32 nMaxDigits, NumberFormatInfo info, Char expChar) { }
	// RVA: 0x626f7ec VA: 0x75988877ec
	private static Void FormatExponent(ref ValueStringBuilder sb, NumberFormatInfo info, Int32 value, Char expChar, Int32 minDigits, Boolean positiveSign) { }
	// RVA: 0x626f014 VA: 0x7598887014
	private static Void FormatGeneral(ref ValueStringBuilder sb, ref NumberBuffer number, Int32 nMinDigits, Int32 nMaxDigits, NumberFormatInfo info, Char expChar, Boolean bSuppressScientific) { }
	// RVA: 0x626f3b0 VA: 0x75988873b0
	private static Void FormatPercent(ref ValueStringBuilder sb, ref NumberBuffer number, Int32 nMinDigits, Int32 nMaxDigits, NumberFormatInfo info) { }
	// RVA: 0x626e320 VA: 0x7598886320
	private static Void RoundNumber(ref NumberBuffer number, Int32 pos) { }
	// RVA: 0x626fadc VA: 0x7598887adc
	private static Int32 FindSection(ReadOnlySpan`1 format, Int32 section) { }
	// RVA: 0x626d244 VA: 0x7598885244
	internal static Void NumberToStringFormat(ref ValueStringBuilder sb, ref NumberBuffer number, ReadOnlySpan`1 format, NumberFormatInfo info) { }
	// RVA: 0x626fc10 VA: 0x7598887c10
	private static Void .cctor() { }
}
```