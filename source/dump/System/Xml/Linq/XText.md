# XText

**Namespace:** `System.Xml.Linq`


## Properties

- `String Value`


## Methods

- `String get_Value()`

- `Void set_Value(String)`


## Dump
```C#
// Dll : System.Xml.Linq.dll
// Namespace : System.Xml.Linq
public class XText : XNode
{
	internal String text; // 0x28

	public override XmlNodeType NodeType { get; }
	public String Value { get; set; }

	// RVA: 0x627fda4 VA: 0x7598897da4
	public Void .ctor(String value) { }
	// RVA: 0x627fe28 VA: 0x7598897e28
	public Void .ctor(XText other) { }
	// RVA: 0x6285a50 VA: 0x759889da50
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x6285a58 VA: 0x759889da58
	public String get_Value() { }
	// RVA: 0x62818cc VA: 0x75988998cc
	public Void set_Value(String value) { }
	// RVA: 0x6285a60 VA: 0x759889da60
	public override Void WriteTo(XmlWriter writer) { }
	// RVA: 0x6285b54 VA: 0x759889db54
	internal override Void AppendText(StringBuilder sb) { }
	// RVA: 0x6285b78 VA: 0x759889db78
	internal override XNode CloneNode() { }
}
```