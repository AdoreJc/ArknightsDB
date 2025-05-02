# XmlDeclarationWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Properties

- `String Version`

- `String Encoding`

- `String Standalone`


## Methods

- `String get_Version()`

- `String get_Encoding()`

- `String get_Standalone()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
internal class XmlDeclarationWrapper : XmlNodeWrapper, IXmlDeclaration, IXmlNode
{
	private readonly XmlDeclaration _declaration; // 0x28

	public String Version { get; }
	public String Encoding { get; }
	public String Standalone { get; }

	// RVA: 0x61ab5a4 VA: 0x75987c35a4
	public Void .ctor(XmlDeclaration declaration) { }
	// RVA: 0x61abc14 VA: 0x75987c3c14
	public String get_Version() { }
	// RVA: 0x61abc30 VA: 0x75987c3c30
	public String get_Encoding() { }
	// RVA: 0x61abc4c VA: 0x75987c3c4c
	public String get_Standalone() { }
}
```