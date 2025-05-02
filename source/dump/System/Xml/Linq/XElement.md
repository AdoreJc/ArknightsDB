# XElement

**Namespace:** `System.Xml.Linq`


## Properties

- `Boolean IsEmpty`

- `XName Name`

- `String Value`


## Methods

- `Boolean get_IsEmpty()`

- `XName get_Name()`

- `String get_Value()`

- `XAttribute Attribute(XName)`

- `String GetPrefixOfNamespace(XNamespace)`

- `String GetNamespaceOfPrefixInScope(String, XElement)`


## Dump
```C#
// Dll : System.Xml.Linq.dll
// Namespace : System.Xml.Linq
public class XElement : XContainer
{
	internal XName name; // 0x30
	internal XAttribute lastAttr; // 0x38

	public Boolean IsEmpty { get; }
	public XName Name { get; }
	public override XmlNodeType NodeType { get; }
	public String Value { get; }

	// RVA: 0x6282cb4 VA: 0x759889acb4
	public Void .ctor(XName name) { }
	// RVA: 0x6282d34 VA: 0x759889ad34
	public Void .ctor(XElement other) { }
	// RVA: 0x628122c VA: 0x759889922c
	public Void .ctor(XStreamingElement other) { }
	// RVA: 0x6282e54 VA: 0x759889ae54
	public Boolean get_IsEmpty() { }
	// RVA: 0x6282e64 VA: 0x759889ae64
	public XName get_Name() { }
	// RVA: 0x6282e6c VA: 0x759889ae6c
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x6282e74 VA: 0x759889ae74
	public String get_Value() { }
	// RVA: 0x6282f08 VA: 0x759889af08
	public XAttribute Attribute(XName name) { }
	// RVA: 0x6282f44 VA: 0x759889af44
	public IEnumerable`1 Attributes() { }
	// RVA: 0x627fb7c VA: 0x7598897b7c
	public String GetPrefixOfNamespace(XNamespace ns) { }
	// RVA: 0x62830ec VA: 0x759889b0ec
	public override Void WriteTo(XmlWriter writer) { }
	// RVA: 0x6283350 VA: 0x759889b350
	internal override Void AddAttribute(XAttribute a) { }
	// RVA: 0x6283558 VA: 0x759889b558
	internal override Void AddAttributeSkipNotify(XAttribute a) { }
	// RVA: 0x6283440 VA: 0x759889b440
	internal Void AppendAttribute(XAttribute a) { }
	// RVA: 0x6282de4 VA: 0x759889ade4
	internal Void AppendAttributeSkipNotify(XAttribute a) { }
	// RVA: 0x6283648 VA: 0x759889b648
	internal override XNode CloneNode() { }
	// RVA: 0x6282f4c VA: 0x759889af4c
	private IEnumerable`1 GetAttributes(XName name) { }
	// RVA: 0x6282ff8 VA: 0x759889aff8
	private String GetNamespaceOfPrefixInScope(String prefix, XElement outOfScope) { }
	// RVA: 0x62836dc VA: 0x759889b6dc
	internal override Void ValidateNode(XNode node, XNode previous) { }
}
```