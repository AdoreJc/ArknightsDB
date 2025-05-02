# XElementWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Properties

- `XElement Element`

- `Boolean IsEmpty`


## Methods

- `XElement get_Element()`

- `Void SetAttributeNode(IXmlNode)`

- `String GetPrefixOfNamespace(String)`

- `Boolean get_IsEmpty()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
internal class XElementWrapper : XContainerWrapper, IXmlElement, IXmlNode
{
	private List`1 _attributes; // 0x20

	private XElement Element { get; }
	public override List`1 Attributes { get; }
	public override String Value { get; }
	public override String LocalName { get; }
	public override String NamespaceUri { get; }
	public Boolean IsEmpty { get; }

	// RVA: 0x61ae7e0 VA: 0x75987c67e0
	private XElement get_Element() { }
	// RVA: 0x61ad7d4 VA: 0x75987c57d4
	public Void .ctor(XElement element) { }
	// RVA: 0x61ae858 VA: 0x75987c6858
	public Void SetAttributeNode(IXmlNode attribute) { }
	// RVA: 0x61ae904 VA: 0x75987c6904
	public override List`1 get_Attributes() { }
	// RVA: 0x61af16c VA: 0x75987c716c
	public override IXmlNode AppendChild(IXmlNode newChild) { }
	// RVA: 0x61af1a0 VA: 0x75987c71a0
	public override String get_Value() { }
	// RVA: 0x61af1bc VA: 0x75987c71bc
	public override String get_LocalName() { }
	// RVA: 0x61af1e0 VA: 0x75987c71e0
	public override String get_NamespaceUri() { }
	// RVA: 0x61af12c VA: 0x75987c712c
	public String GetPrefixOfNamespace(String namespaceUri) { }
	// RVA: 0x61af204 VA: 0x75987c7204
	public Boolean get_IsEmpty() { }
}
```