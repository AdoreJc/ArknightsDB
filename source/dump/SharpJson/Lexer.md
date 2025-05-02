# Lexer

**Namespace:** `SharpJson`


## Fields

- `Int32 <lineNumber>k__BackingField`

- `Boolean <parseNumbersAsFloat>k__BackingField`

- `Int32 index`

- `Boolean success`


## Properties

- `Boolean hasError`

- `Int32 lineNumber`

- `Boolean parseNumbersAsFloat`


## Methods

- `Boolean get_hasError()`

- `Int32 get_lineNumber()`

- `Void set_lineNumber(Int32)`

- `Boolean get_parseNumbersAsFloat()`

- `Void set_parseNumbersAsFloat(Boolean)`

- `Void Reset()`

- `String ParseString()`

- `String GetNumberString()`

- `Single ParseFloatNumber()`

- `Double ParseDoubleNumber()`

- `Int32 GetLastIndexOfNumber(Int32)`

- `Void SkipWhiteSpaces()`

- `Token LookAhead()`

- `Token NextToken()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : SharpJson
internal class Lexer
{
	private Int32 <lineNumber>k__BackingField; // 0x10
	private Boolean <parseNumbersAsFloat>k__BackingField; // 0x14
	private Char[] json; // 0x18
	private Int32 index; // 0x20
	private Boolean success; // 0x24
	private Char[] stringBuffer; // 0x28

	public Boolean hasError { get; }
	public Int32 lineNumber { get; set; }
	public Boolean parseNumbersAsFloat { get; set; }

	// RVA: 0x61c2e58 VA: 0x75987dae58
	public Boolean get_hasError() { }
	// RVA: 0x61c2e68 VA: 0x75987dae68
	public Int32 get_lineNumber() { }
	// RVA: 0x61c2e70 VA: 0x75987dae70
	private Void set_lineNumber(Int32 value) { }
	// RVA: 0x61c2e78 VA: 0x75987dae78
	public Boolean get_parseNumbersAsFloat() { }
	// RVA: 0x61c2e80 VA: 0x75987dae80
	public Void set_parseNumbersAsFloat(Boolean value) { }
	// RVA: 0x61c2e8c VA: 0x75987dae8c
	public Void .ctor(String text) { }
	// RVA: 0x61c2f3c VA: 0x75987daf3c
	public Void Reset() { }
	// RVA: 0x61c2f50 VA: 0x75987daf50
	public String ParseString() { }
	// RVA: 0x61c3460 VA: 0x75987db460
	private String GetNumberString() { }
	// RVA: 0x61c3528 VA: 0x75987db528
	public Single ParseFloatNumber() { }
	// RVA: 0x61c35c4 VA: 0x75987db5c4
	public Double ParseDoubleNumber() { }
	// RVA: 0x61c34a8 VA: 0x75987db4a8
	private Int32 GetLastIndexOfNumber(Int32 index) { }
	// RVA: 0x61c33ac VA: 0x75987db3ac
	private Void SkipWhiteSpaces() { }
	// RVA: 0x61c3660 VA: 0x75987db660
	public Token LookAhead() { }
	// RVA: 0x61c38e4 VA: 0x75987db8e4
	public Token NextToken() { }
	// RVA: 0x61c3690 VA: 0x75987db690
	private static Token NextToken(Char[] json, ref Int32 index) { }
}
```