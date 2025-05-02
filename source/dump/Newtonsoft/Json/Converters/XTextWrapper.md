# XTextWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Properties

- `XText Text`


## Methods

- `XText get_Text()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
internal class XTextWrapper : XObjectWrapper
{

	private XText Text { get; }
	public override String Value { get; }
	public override IXmlNode ParentNode { get; }

	// RVA: 0x61adca0 VA: 0x75987c5ca0
	private XText get_Text() { }
	// RVA: 0x61add18 VA: 0x75987c5d18
	public Void .ctor(XText text) { }
	// RVA: 0x61add8c VA: 0x75987c5d8c
	public override String get_Value() { }
	// RVA: 0x61adda8 VA: 0x75987c5da8
	public override IXmlNode get_ParentNode() { }
}
```