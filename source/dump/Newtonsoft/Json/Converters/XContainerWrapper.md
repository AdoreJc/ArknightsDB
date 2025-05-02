# XContainerWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Properties

- `XContainer Container`


## Methods

- `XContainer get_Container()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
internal class XContainerWrapper : XObjectWrapper
{
	private List`1 _childNodes; // 0x18

	private XContainer Container { get; }
	public override List`1 ChildNodes { get; }
	public override IXmlNode ParentNode { get; }

	// RVA: 0x61ae484 VA: 0x75987c6484
	private XContainer get_Container() { }
	// RVA: 0x61acbf8 VA: 0x75987c4bf8
	public Void .ctor(XContainer container) { }
	// RVA: 0x61acdd0 VA: 0x75987c4dd0
	public override List`1 get_ChildNodes() { }
	// RVA: 0x61ae4fc VA: 0x75987c64fc
	public override IXmlNode get_ParentNode() { }
	// RVA: 0x61addec VA: 0x75987c5dec
	internal static IXmlNode WrapNode(XObject node) { }
	// RVA: 0x61adbc4 VA: 0x75987c5bc4
	public override IXmlNode AppendChild(IXmlNode newChild) { }
}
```