# XmlNodeWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Properties

- `Object WrappedNode`

- `XmlNodeType NodeType`

- `IXmlNode ParentNode`

- `String Value`

- `String NamespaceUri`


## Methods

- `Object get_WrappedNode()`

- `XmlNodeType get_NodeType()`

- `IXmlNode get_ParentNode()`

- `String get_Value()`

- `Void set_Value(String)`

- `IXmlNode AppendChild(IXmlNode)`

- `String get_NamespaceUri()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
internal class XmlNodeWrapper : IXmlNode
{
	private readonly XmlNode _node; // 0x10
	private List`1 _childNodes; // 0x18
	private List`1 _attributes; // 0x20

	public Object WrappedNode { get; }
	public XmlNodeType NodeType { get; }
	public virtual String LocalName { get; }
	public List`1 ChildNodes { get; }
	public List`1 Attributes { get; }
	public IXmlNode ParentNode { get; }
	public String Value { get; set; }
	public String NamespaceUri { get; }

	// RVA: 0x61ab1dc VA: 0x75987c31dc
	public Void .ctor(XmlNode node) { }
	// RVA: 0x61abd1c VA: 0x75987c3d1c
	public Object get_WrappedNode() { }
	// RVA: 0x61abd24 VA: 0x75987c3d24
	public XmlNodeType get_NodeType() { }
	// RVA: 0x61abd44 VA: 0x75987c3d44
	public virtual String get_LocalName() { }
	// RVA: 0x61abd68 VA: 0x75987c3d68
	public List`1 get_ChildNodes() { }
	// RVA: 0x61ac158 VA: 0x75987c4158
	internal static IXmlNode WrapNode(XmlNode node) { }
	// RVA: 0x61ac34c VA: 0x75987c434c
	public List`1 get_Attributes() { }
	// RVA: 0x61ac784 VA: 0x75987c4784
	public IXmlNode get_ParentNode() { }
	// RVA: 0x61ac824 VA: 0x75987c4824
	public String get_Value() { }
	// RVA: 0x61ab978 VA: 0x75987c3978
	public Void set_Value(String value) { }
	// RVA: 0x61ac844 VA: 0x75987c4844
	public IXmlNode AppendChild(IXmlNode newChild) { }
	// RVA: 0x61ac904 VA: 0x75987c4904
	public String get_NamespaceUri() { }
}
```