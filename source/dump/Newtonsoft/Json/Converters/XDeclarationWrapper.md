# XDeclarationWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Fields

- `XDeclaration <Declaration>k__BackingField`


## Properties

- `String Version`

- `String Encoding`

- `String Standalone`


## Methods

- `Void set_Declaration(XDeclaration)`

- `String get_Version()`

- `String get_Encoding()`

- `String get_Standalone()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
internal class XDeclarationWrapper : XObjectWrapper, IXmlDeclaration, IXmlNode
{
	private XDeclaration <Declaration>k__BackingField; // 0x18

	internal XDeclaration Declaration { get; set; }
	public override XmlNodeType NodeType { get; }
	public String Version { get; }
	public String Encoding { get; }
	public String Standalone { get; }

	// RVA: 0x61ac928 VA: 0x75987c4928
	internal XDeclaration get_Declaration() { }
	// RVA: 0x61ac930 VA: 0x75987c4930
	private Void set_Declaration(XDeclaration value) { }
	// RVA: 0x61ac938 VA: 0x75987c4938
	public Void .ctor(XDeclaration declaration) { }
	// RVA: 0x61ac9ec VA: 0x75987c49ec
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x61ac9f4 VA: 0x75987c49f4
	public String get_Version() { }
	// RVA: 0x61aca10 VA: 0x75987c4a10
	public String get_Encoding() { }
	// RVA: 0x61aca2c VA: 0x75987c4a2c
	public String get_Standalone() { }
}
```