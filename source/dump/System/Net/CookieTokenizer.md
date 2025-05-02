# CookieTokenizer

**Namespace:** `System.Net`


## Fields

- `Boolean m_eofCookie`

- `Int32 m_index`

- `Int32 m_length`

- `String m_name`

- `Boolean m_quoted`

- `Int32 m_start`

- `CookieToken m_token`

- `Int32 m_tokenLength`

- `String m_tokenStream`

- `String m_value`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class CookieTokenizer
{
	private Boolean m_eofCookie; // 0x10
	private Int32 m_index; // 0x14
	private Int32 m_length; // 0x18
	private String m_name; // 0x20
	private Boolean m_quoted; // 0x28
	private Int32 m_start; // 0x2c
	private CookieToken m_token; // 0x30
	private Int32 m_tokenLength; // 0x34
	private String m_tokenStream; // 0x38
	private String m_value; // 0x40
	private static RecognizedAttribute[] RecognizedAttributes; // 0x0
	private static RecognizedAttribute[] RecognizedServerAttributes; // 0x8

	internal Boolean EndOfCookie { get; set; }
	internal Boolean Eof { get; }
	internal String Name { get; set; }
	internal Boolean Quoted { get; set; }
	internal CookieToken Token { get; set; }
	internal String Value { get; set; }

	// RVA: 0x6437ea4 VA: 0x7598a4fea4
	internal Void .ctor(String tokenStream) { }
	// RVA: 0x6437ee4 VA: 0x7598a4fee4
	internal Boolean get_EndOfCookie() { }
	// RVA: 0x6437eec VA: 0x7598a4feec
	internal Void set_EndOfCookie(Boolean value) { }
	// RVA: 0x6437ef8 VA: 0x7598a4fef8
	internal Boolean get_Eof() { }
	// RVA: 0x6437f08 VA: 0x7598a4ff08
	internal String get_Name() { }
	// RVA: 0x6437f10 VA: 0x7598a4ff10
	internal Void set_Name(String value) { }
	// RVA: 0x6437f18 VA: 0x7598a4ff18
	internal Boolean get_Quoted() { }
	// RVA: 0x6437f20 VA: 0x7598a4ff20
	internal Void set_Quoted(Boolean value) { }
	// RVA: 0x6437f2c VA: 0x7598a4ff2c
	internal CookieToken get_Token() { }
	// RVA: 0x6437f34 VA: 0x7598a4ff34
	internal Void set_Token(CookieToken value) { }
	// RVA: 0x6437f3c VA: 0x7598a4ff3c
	internal String get_Value() { }
	// RVA: 0x6437f44 VA: 0x7598a4ff44
	internal Void set_Value(String value) { }
	// RVA: 0x6437f4c VA: 0x7598a4ff4c
	internal String Extract() { }
	// RVA: 0x6437fd4 VA: 0x7598a4ffd4
	internal CookieToken FindNext(Boolean ignoreComma, Boolean ignoreEquals) { }
	// RVA: 0x6438278 VA: 0x7598a50278
	internal CookieToken Next(Boolean first, Boolean parseResponseCookies) { }
	// RVA: 0x64383a0 VA: 0x7598a503a0
	internal Void Reset() { }
	// RVA: 0x6438420 VA: 0x7598a50420
	internal CookieToken TokenFromName(Boolean parseResponseCookies) { }
	// RVA: 0x6438600 VA: 0x7598a50600
	private static Void .cctor() { }
}
```