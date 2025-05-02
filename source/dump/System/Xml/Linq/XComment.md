# XComment

**Namespace:** `System.Xml.Linq`


## Properties

- `String Value`


## Methods

- `String get_Value()`


## Dump
```C#
// Dll : System.Xml.Linq.dll
// Namespace : System.Xml.Linq
public class XComment : XNode
{
	internal String value; // 0x28

	public override XmlNodeType NodeType { get; }
	public String Value { get; }

	// RVA: 0x627ff84 VA: 0x7598897f84
	public Void .ctor(String value) { }
	// RVA: 0x628000c VA: 0x759889800c
	public Void .ctor(XComment other) { }
	// RVA: 0x628008c VA: 0x759889808c
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x6280094 VA: 0x7598898094
	public String get_Value() { }
	// RVA: 0x628009c VA: 0x759889809c
	public override Void WriteTo(XmlWriter writer) { }
	// RVA: 0x6280110 VA: 0x7598898110
	internal override XNode CloneNode() { }
}
```