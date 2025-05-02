# DigestHeaderParser

**Namespace:** `System.Net`


## Fields

- `String header`

- `Int32 length`

- `Int32 pos`


## Properties

- `String Realm`

- `String Opaque`

- `String Nonce`

- `String Algorithm`

- `String QOP`


## Methods

- `String get_Realm()`

- `String get_Opaque()`

- `String get_Nonce()`

- `String get_Algorithm()`

- `String get_QOP()`

- `Boolean Parse()`

- `Void SkipWhitespace()`

- `String GetKey()`

- `Boolean GetKeywordAndValue(out, out)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class DigestHeaderParser
{
	private String header; // 0x10
	private Int32 length; // 0x18
	private Int32 pos; // 0x1c
	private static String[] keywords; // 0x0
	private String[] values; // 0x20

	public String Realm { get; }
	public String Opaque { get; }
	public String Nonce { get; }
	public String Algorithm { get; }
	public String QOP { get; }

	// RVA: 0x6323504 VA: 0x759893b504
	public Void .ctor(String header) { }
	// RVA: 0x63235cc VA: 0x759893b5cc
	public String get_Realm() { }
	// RVA: 0x63235f4 VA: 0x759893b5f4
	public String get_Opaque() { }
	// RVA: 0x6323620 VA: 0x759893b620
	public String get_Nonce() { }
	// RVA: 0x632364c VA: 0x759893b64c
	public String get_Algorithm() { }
	// RVA: 0x6323678 VA: 0x759893b678
	public String get_QOP() { }
	// RVA: 0x63236a4 VA: 0x759893b6a4
	public Boolean Parse() { }
	// RVA: 0x6323a50 VA: 0x759893ba50
	private Void SkipWhitespace() { }
	// RVA: 0x6323ad0 VA: 0x759893bad0
	private String GetKey() { }
	// RVA: 0x632388c VA: 0x759893b88c
	private Boolean GetKeywordAndValue(out String key, out String value) { }
	// RVA: 0x6323b60 VA: 0x759893bb60
	private static Void .cctor() { }
}
```