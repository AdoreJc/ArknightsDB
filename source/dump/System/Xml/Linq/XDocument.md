# XDocument

**Namespace:** `System.Xml.Linq`


## Fields

- `XDeclaration _declaration`


## Properties

- `XDeclaration Declaration`

- `XElement Root`


## Methods

- `XDeclaration get_Declaration()`

- `Void set_Declaration(XDeclaration)`

- `XElement get_Root()`

- `T GetFirstNode()`

- `Void ValidateDocument(XNode, XmlNodeType, XmlNodeType)`


## Dump
```C#
// Dll : System.Xml.Linq.dll
// Namespace : System.Xml.Linq
public class XDocument : XContainer
{
	private XDeclaration _declaration; // 0x30

	public XDeclaration Declaration { get; set; }
	public override XmlNodeType NodeType { get; }
	public XElement Root { get; }

	// RVA: 0x6282358 VA: 0x759889a358
	public Void .ctor() { }
	// RVA: 0x6282360 VA: 0x759889a360
	public Void .ctor(XDocument other) { }
	// RVA: 0x62823f0 VA: 0x759889a3f0
	public XDeclaration get_Declaration() { }
	// RVA: 0x62823f8 VA: 0x759889a3f8
	public Void set_Declaration(XDeclaration value) { }
	// RVA: 0x6282400 VA: 0x759889a400
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x6282408 VA: 0x759889a408
	public XElement get_Root() { }
	// RVA: 0x6282450 VA: 0x759889a450
	public override Void WriteTo(XmlWriter writer) { }
	// RVA: 0x6282580 VA: 0x759889a580
	internal override Void AddAttribute(XAttribute a) { }
	// RVA: 0x62825d0 VA: 0x759889a5d0
	internal override Void AddAttributeSkipNotify(XAttribute a) { }
	// RVA: 0x6282620 VA: 0x759889a620
	internal override XNode CloneNode() { }
	// RVA: 0x VA: 0x0
	private T GetFirstNode() { }
	// RVA: 0x6282680 VA: 0x759889a680
	internal static Boolean IsWhitespace(String s) { }
	// RVA: 0x628270c VA: 0x759889a70c
	internal override Void ValidateNode(XNode node, XNode previous) { }
	// RVA: 0x62828b4 VA: 0x759889a8b4
	private Void ValidateDocument(XNode previous, XmlNodeType allowBefore, XmlNodeType allowAfter) { }
	// RVA: 0x62829e0 VA: 0x759889a9e0
	internal override Void ValidateString(String s) { }
}
```