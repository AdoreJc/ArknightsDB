# StringMap

**Namespace:** `Torappu.I18N`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.I18N
public class StringMap
{
	private static Dictionary`2 s_stringResDict; // 0x0
	public const String I18N_STRING_MAP_PATH; // 0x0


	// RVA: 0x35bb2f4 VA: 0x7595bd32f4
	public static String Get(String key) { }
	// RVA: 0x35bb438 VA: 0x7595bd3438
	public static Void LoadStringMap() { }
	// RVA: 0x35bb7cc VA: 0x7595bd37cc
	public static Void LoadStringMapFromText(String stringMapStr, ref Dictionary`2 strMap, Action`1 onInvalidLine, Boolean processEscapeChar) { }
	// RVA: 0x35bbb68 VA: 0x7595bd3b68
	public Void .ctor() { }
	// RVA: 0x35bbb70 VA: 0x7595bd3b70
	private static Void .cctor() { }
}
```