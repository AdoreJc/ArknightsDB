# XDocumentTypeWrapper

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
internal class XDocumentTypeWrapper : XObjectWrapper, IXmlDocumentType, IXmlNode
{
	private readonly XDocumentType _documentType; // 0x18

	public String Name { get; }
	public String System { get; }
	public String Public { get; }
	public String InternalSubset { get; }
	public override String LocalName { get; }

	// RVA: 0x61aca48 VA: 0x75987c4a48
	public Void .ctor(XDocumentType documentType) { }
	// RVA: 0x61acacc VA: 0x75987c4acc
	public String get_Name() { }
	// RVA: 0x61acae8 VA: 0x75987c4ae8
	public String get_System() { }
	// RVA: 0x61acb04 VA: 0x75987c4b04
	public String get_Public() { }
	// RVA: 0x61acb20 VA: 0x75987c4b20
	public String get_InternalSubset() { }
	// RVA: 0x61acb3c VA: 0x75987c4b3c
	public override String get_LocalName() { }
}
```