# XmlDocumentTypeWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Properties

- `String Name`

- `String System`

- `String Public`

- `String InternalSubset`


## Methods

- `String get_Name()`

- `String get_System()`

- `String get_Public()`

- `String get_InternalSubset()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
internal class XmlDocumentTypeWrapper : XmlNodeWrapper, IXmlDocumentType, IXmlNode
{
	private readonly XmlDocumentType _documentType; // 0x28

	public String Name { get; }
	public String System { get; }
	public String Public { get; }
	public String InternalSubset { get; }
	public override String LocalName { get; }

	// RVA: 0x61ab688 VA: 0x75987c3688
	public Void .ctor(XmlDocumentType documentType) { }
	// RVA: 0x61abc68 VA: 0x75987c3c68
	public String get_Name() { }
	// RVA: 0x61abc88 VA: 0x75987c3c88
	public String get_System() { }
	// RVA: 0x61abca4 VA: 0x75987c3ca4
	public String get_Public() { }
	// RVA: 0x61abcc0 VA: 0x75987c3cc0
	public String get_InternalSubset() { }
	// RVA: 0x61abcdc VA: 0x75987c3cdc
	public override String get_LocalName() { }
}
```