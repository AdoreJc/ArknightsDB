# fsJsonParser

**Namespace:** `FullSerializer`


## Fields

- `Int32 _start`

- `String _input`


## Methods

- `fsResult MakeFailure(String)`

- `Boolean TryMoveNext()`

- `Boolean HasValue()`

- `Boolean HasValue(Int32)`

- `Char Character()`

- `Char Character(Int32)`

- `Void SkipSpace()`

- `Boolean IsHex(Char)`

- `UInt32 ParseSingleChar(Char, UInt32)`

- `UInt32 ParseUnicode(Char, Char, Char, Char)`

- `fsResult TryUnescapeChar(out)`

- `fsResult TryParseExact(String)`

- `fsResult TryParseTrue(out)`

- `fsResult TryParseFalse(out)`

- `fsResult TryParseNull(out)`

- `Boolean IsSeparator(Char)`

- `fsResult TryParseNumber(out)`

- `fsResult TryParseString(out)`

- `fsResult TryParseArray(out)`

- `fsResult TryParseObject(out)`

- `fsResult RunParse(out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer
public class fsJsonParser
{
	private Int32 _start; // 0x10
	private String _input; // 0x18
	private readonly StringBuilder _cachedStringBuilder; // 0x20


	// RVA: 0x3498238 VA: 0x7595ab0238
	private fsResult MakeFailure(String message) { }
	// RVA: 0x34984e8 VA: 0x7595ab04e8
	private Boolean TryMoveNext() { }
	// RVA: 0x3498524 VA: 0x7595ab0524
	private Boolean HasValue() { }
	// RVA: 0x3498558 VA: 0x7595ab0558
	private Boolean HasValue(Int32 offset) { }
	// RVA: 0x3498590 VA: 0x7595ab0590
	private Char Character() { }
	// RVA: 0x3498598 VA: 0x7595ab0598
	private Char Character(Int32 offset) { }
	// RVA: 0x34985c0 VA: 0x7595ab05c0
	private Void SkipSpace() { }
	// RVA: 0x349887c VA: 0x7595ab087c
	private Boolean IsHex(Char c) { }
	// RVA: 0x34988b8 VA: 0x7595ab08b8
	private UInt32 ParseSingleChar(Char c1, UInt32 multipliyer) { }
	// RVA: 0x3498910 VA: 0x7595ab0910
	private UInt32 ParseUnicode(Char c1, Char c2, Char c3, Char c4) { }
	// RVA: 0x3498a80 VA: 0x7595ab0a80
	private fsResult TryUnescapeChar(out Char escaped) { }
	// RVA: 0x349912c VA: 0x7595ab112c
	private fsResult TryParseExact(String content) { }
	// RVA: 0x34992b8 VA: 0x7595ab12b8
	private fsResult TryParseTrue(out fsData data) { }
	// RVA: 0x34993bc VA: 0x7595ab13bc
	private fsResult TryParseFalse(out fsData data) { }
	// RVA: 0x34994c0 VA: 0x7595ab14c0
	private fsResult TryParseNull(out fsData data) { }
	// RVA: 0x34995d4 VA: 0x7595ab15d4
	private Boolean IsSeparator(Char c) { }
	// RVA: 0x3499658 VA: 0x7595ab1658
	private fsResult TryParseNumber(out fsData data) { }
	// RVA: 0x3499964 VA: 0x7595ab1964
	private fsResult TryParseString(out String str) { }
	// RVA: 0x3499c48 VA: 0x7595ab1c48
	private fsResult TryParseArray(out fsData arr) { }
	// RVA: 0x349a2c0 VA: 0x7595ab22c0
	private fsResult TryParseObject(out fsData obj) { }
	// RVA: 0x3499fbc VA: 0x7595ab1fbc
	private fsResult RunParse(out fsData data) { }
	// RVA: 0x349a7d0 VA: 0x7595ab27d0
	public static fsResult Parse(String input, out fsData data) { }
	// RVA: 0x349a940 VA: 0x7595ab2940
	public static fsData Parse(String input) { }
	// RVA: 0x349a8a4 VA: 0x7595ab28a4
	private Void .ctor(String input) { }
}
```