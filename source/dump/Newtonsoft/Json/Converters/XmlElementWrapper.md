# XmlElementWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Properties

- `Boolean IsEmpty`


## Methods

- `Void SetAttributeNode(IXmlNode)`

- `String GetPrefixOfNamespace(String)`

- `Boolean get_IsEmpty()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
internal class XmlElementWrapper : XmlNodeWrapper, IXmlElement, IXmlNode
{
	private readonly XmlElement _element; // 0x28

	public Boolean IsEmpty { get; }

	// RVA: 0x61ab7f0 VA: 0x75987c37f0
	public Void .ctor(XmlElement element) { }
	// RVA: 0x61abaec VA: 0x75987c3aec
	public Void SetAttributeNode(IXmlNode attribute) { }
	// RVA: 0x61abbd4 VA: 0x75987c3bd4
	public String GetPrefixOfNamespace(String namespaceUri) { }
	// RVA: 0x61abbf8 VA: 0x75987c3bf8
	public Boolean get_IsEmpty() { }
}
```