# XAttributeWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Properties

- `XAttribute Attribute`


## Methods

- `XAttribute get_Attribute()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
internal class XAttributeWrapper : XObjectWrapper
{

	private XAttribute Attribute { get; }
	public override String Value { get; }
	public override String LocalName { get; }
	public override String NamespaceUri { get; }
	public override IXmlNode ParentNode { get; }

	// RVA: 0x61ae6c0 VA: 0x75987c66c0
	private XAttribute get_Attribute() { }
	// RVA: 0x61ad948 VA: 0x75987c5948
	public Void .ctor(XAttribute attribute) { }
	// RVA: 0x61ae738 VA: 0x75987c6738
	public override String get_Value() { }
	// RVA: 0x61ae754 VA: 0x75987c6754
	public override String get_LocalName() { }
	// RVA: 0x61ae778 VA: 0x75987c6778
	public override String get_NamespaceUri() { }
	// RVA: 0x61ae79c VA: 0x75987c679c
	public override IXmlNode get_ParentNode() { }
}
```