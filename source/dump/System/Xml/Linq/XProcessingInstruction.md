# XProcessingInstruction

**Namespace:** `System.Xml.Linq`


## Properties

- `String Data`

- `String Target`


## Methods

- `String get_Data()`

- `String get_Target()`


## Dump
```C#
// Dll : System.Xml.Linq.dll
// Namespace : System.Xml.Linq
public class XProcessingInstruction : XNode
{
	internal String target; // 0x28
	internal String data; // 0x30

	public String Data { get; }
	public override XmlNodeType NodeType { get; }
	public String Target { get; }

	// RVA: 0x6285758 VA: 0x759889d758
	public Void .ctor(String target, String data) { }
	// RVA: 0x62858d4 VA: 0x759889d8d4
	public Void .ctor(XProcessingInstruction other) { }
	// RVA: 0x6285964 VA: 0x759889d964
	public String get_Data() { }
	// RVA: 0x628596c VA: 0x759889d96c
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x6285974 VA: 0x759889d974
	public String get_Target() { }
	// RVA: 0x628597c VA: 0x759889d97c
	public override Void WriteTo(XmlWriter writer) { }
	// RVA: 0x62859f0 VA: 0x759889d9f0
	internal override XNode CloneNode() { }
	// RVA: 0x62857f4 VA: 0x759889d7f4
	private static Void ValidateName(String name) { }
}
```