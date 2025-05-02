# XmlEntityReference

**Namespace:** `System.Xml`


## Fields

- `String name`

- `XmlLinkedNode lastChild`


## Methods

- `String ConstructBaseURI(String, String)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlEntityReference : XmlLinkedNode
{
	private String name; // 0x20
	private XmlLinkedNode lastChild; // 0x28

	public override String Name { get; }
	public override String LocalName { get; }
	public override String Value { get; set; }
	public override XmlNodeType NodeType { get; }
	public override Boolean IsReadOnly { get; }
	internal override Boolean IsContainer { get; }
	internal override XmlLinkedNode LastNode { get; set; }
	public override String BaseURI { get; }
	internal String ChildBaseURI { get; }

	// RVA: 0x62af028 VA: 0x75988c7028
	protected internal Void .ctor(String name, XmlDocument doc) { }
	// RVA: 0x62af12c VA: 0x75988c712c
	public override String get_Name() { }
	// RVA: 0x62af134 VA: 0x75988c7134
	public override String get_LocalName() { }
	// RVA: 0x62af13c VA: 0x75988c713c
	public override String get_Value() { }
	// RVA: 0x62af144 VA: 0x75988c7144
	public override Void set_Value(String value) { }
	// RVA: 0x62af1a4 VA: 0x75988c71a4
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62af1ac VA: 0x75988c71ac
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62af1e4 VA: 0x75988c71e4
	public override Boolean get_IsReadOnly() { }
	// RVA: 0x62af1ec VA: 0x75988c71ec
	internal override Boolean get_IsContainer() { }
	// RVA: 0x62af1f4 VA: 0x75988c71f4
	internal override Void SetParent(XmlNode node) { }
	// RVA: 0x62af924 VA: 0x75988c7924
	internal override Void SetParentForLoad(XmlNode node) { }
	// RVA: 0x62af934 VA: 0x75988c7934
	internal override XmlLinkedNode get_LastNode() { }
	// RVA: 0x62af93c VA: 0x75988c793c
	internal override Void set_LastNode(XmlLinkedNode value) { }
	// RVA: 0x62af944 VA: 0x75988c7944
	internal override Boolean IsValidChildType(XmlNodeType type) { }
	// RVA: 0x62af968 VA: 0x75988c7968
	public override String get_BaseURI() { }
	// RVA: 0x62af998 VA: 0x75988c7998
	private String ConstructBaseURI(String baseURI, String systemId) { }
	// RVA: 0x62afa6c VA: 0x75988c7a6c
	internal String get_ChildBaseURI() { }
}
```