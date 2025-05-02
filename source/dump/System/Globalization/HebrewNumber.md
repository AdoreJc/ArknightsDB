# HebrewNumber

**Namespace:** `System.Globalization`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
internal class HebrewNumber
{
	private static readonly HebrewValue[] s_hebrewValues; // 0x0
	private static Char s_maxHebrewNumberCh; // 0x8
	private static readonly HS[] s_numberPasingState; // 0x10


	// RVA: 0x604d8b4 VA: 0x75986658b4
	internal static String ToString(Int32 Number) { }
	// RVA: 0x604db0c VA: 0x7598665b0c
	internal static HebrewNumberParsingState ParseByChar(Char ch, ref HebrewNumberParsingContext context) { }
	// RVA: 0x604dc9c VA: 0x7598665c9c
	internal static Boolean IsDigit(Char ch) { }
	// RVA: 0x604dd6c VA: 0x7598665d6c
	private static Void .cctor() { }
}
```