# XCommentWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Properties

- `XComment Text`


## Methods

- `XComment get_Text()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
internal class XCommentWrapper : XObjectWrapper
{

	private XComment Text { get; }
	public override String Value { get; }
	public override IXmlNode ParentNode { get; }

	// RVA: 0x61ae288 VA: 0x75987c6288
	private XComment get_Text() { }
	// RVA: 0x61ae300 VA: 0x75987c6300
	public Void .ctor(XComment text) { }
	// RVA: 0x61ae374 VA: 0x75987c6374
	public override String get_Value() { }
	// RVA: 0x61ae390 VA: 0x75987c6390
	public override IXmlNode get_ParentNode() { }
}
```