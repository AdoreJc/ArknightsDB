# CodePageDataItem

**Namespace:** `System.Globalization`


## Properties

- `String WebName`

- `String HeaderName`


## Methods

- `String get_WebName()`

- `String get_HeaderName()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
internal class CodePageDataItem
{
	internal Int32 m_dataIndex; // 0x10
	internal Int32 m_uiFamilyCodePage; // 0x14
	internal String m_webName; // 0x18
	internal String m_headerName; // 0x20
	internal String m_bodyName; // 0x28
	internal UInt32 m_flags; // 0x30
	private static readonly Char[] sep; // 0x0

	public String WebName { get; }
	public String HeaderName { get; }

	// RVA: 0x6066b14 VA: 0x759867eb14
	internal Void .ctor(Int32 dataIndex) { }
	// RVA: 0x6066bb8 VA: 0x759867ebb8
	internal static String CreateString(String pStrings, UInt32 index) { }
	// RVA: 0x6066c6c VA: 0x759867ec6c
	public String get_WebName() { }
	// RVA: 0x6066d3c VA: 0x759867ed3c
	public String get_HeaderName() { }
	// RVA: 0x6066e0c VA: 0x759867ee0c
	private static Void .cctor() { }
}
```