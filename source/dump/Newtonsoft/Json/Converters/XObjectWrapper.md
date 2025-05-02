# XObjectWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Properties

- `Object WrappedNode`


## Methods

- `Object get_WrappedNode()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
internal class XObjectWrapper : IXmlNode
{
	private static readonly List`1 EmptyChildNodes; // 0x0
	private readonly XObject _xmlObject; // 0x10

	public Object WrappedNode { get; }
	public virtual XmlNodeType NodeType { get; }
	public virtual String LocalName { get; }
	public virtual List`1 ChildNodes { get; }
	public virtual List`1 Attributes { get; }
	public virtual IXmlNode ParentNode { get; }
	public virtual String Value { get; }
	public virtual String NamespaceUri { get; }

	// RVA: 0x61ac9bc VA: 0x75987c49bc
	public Void .ctor(XObject xmlObject) { }
	// RVA: 0x61ae540 VA: 0x75987c6540
	public Object get_WrappedNode() { }
	// RVA: 0x61ae548 VA: 0x75987c6548
	public virtual XmlNodeType get_NodeType() { }
	// RVA: 0x61ae568 VA: 0x75987c6568
	public virtual String get_LocalName() { }
	// RVA: 0x61ae570 VA: 0x75987c6570
	public virtual List`1 get_ChildNodes() { }
	// RVA: 0x61ae5c8 VA: 0x75987c65c8
	public virtual List`1 get_Attributes() { }
	// RVA: 0x61ae5d0 VA: 0x75987c65d0
	public virtual IXmlNode get_ParentNode() { }
	// RVA: 0x61ae5d8 VA: 0x75987c65d8
	public virtual String get_Value() { }
	// RVA: 0x61ae5e0 VA: 0x75987c65e0
	public virtual IXmlNode AppendChild(IXmlNode newChild) { }
	// RVA: 0x61ae620 VA: 0x75987c6620
	public virtual String get_NamespaceUri() { }
	// RVA: 0x61ae628 VA: 0x75987c6628
	private static Void .cctor() { }
}
```