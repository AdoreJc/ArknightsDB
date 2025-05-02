# XAttribute

**Namespace:** `System.Xml.Linq`


## Properties

- `Boolean IsNamespaceDeclaration`

- `XName Name`

- `String Value`


## Methods

- `Boolean get_IsNamespaceDeclaration()`

- `XName get_Name()`

- `String get_Value()`


## Dump
```C#
// Dll : System.Xml.Linq.dll
// Namespace : System.Xml.Linq
public class XAttribute : XObject
{
	internal XAttribute next; // 0x20
	internal XName name; // 0x28
	internal String value; // 0x30

	public Boolean IsNamespaceDeclaration { get; }
	public XName Name { get; }
	public override XmlNodeType NodeType { get; }
	public String Value { get; }

	// RVA: 0x627edf8 VA: 0x7598896df8
	public Void .ctor(XName name, Object value) { }
	// RVA: 0x627f510 VA: 0x7598897510
	public Void .ctor(XAttribute other) { }
	// RVA: 0x627f5a0 VA: 0x75988975a0
	public Boolean get_IsNamespaceDeclaration() { }
	// RVA: 0x627f658 VA: 0x7598897658
	public XName get_Name() { }
	// RVA: 0x627f660 VA: 0x7598897660
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x627f668 VA: 0x7598897668
	public String get_Value() { }
	// RVA: 0x627f670 VA: 0x7598897670
	public override String ToString() { }
	// RVA: 0x627fa44 VA: 0x7598897a44
	internal String GetPrefixOfNamespace(XNamespace ns) { }
	// RVA: 0x627f2e0 VA: 0x75988972e0
	private static Void ValidateAttribute(XName name, String value) { }
}
```