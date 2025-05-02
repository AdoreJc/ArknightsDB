# XmlEntity

**Namespace:** `System.Xml`


## Fields

- `String publicId`

- `String systemId`

- `String notationName`

- `String name`

- `String unparsedReplacementStr`

- `String baseURI`

- `XmlLinkedNode lastChild`

- `Boolean childrenFoliating`


## Properties

- `String SystemId`


## Methods

- `String get_SystemId()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlEntity : XmlNode
{
	private String publicId; // 0x18
	private String systemId; // 0x20
	private String notationName; // 0x28
	private String name; // 0x30
	private String unparsedReplacementStr; // 0x38
	private String baseURI; // 0x40
	private XmlLinkedNode lastChild; // 0x48
	private Boolean childrenFoliating; // 0x50

	public override Boolean IsReadOnly { get; }
	public override String Name { get; }
	public override String LocalName { get; }
	public override String InnerText { get; set; }
	internal override Boolean IsContainer { get; }
	internal override XmlLinkedNode LastNode { get; set; }
	public override XmlNodeType NodeType { get; }
	public String SystemId { get; }
	public override String InnerXml { set; }
	public override String BaseURI { get; }

	// RVA: 0x62aec58 VA: 0x75988c6c58
	internal Void .ctor(String name, String strdata, String publicId, String systemId, String notationName, XmlDocument doc) { }
	// RVA: 0x62aeda8 VA: 0x75988c6da8
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62aee08 VA: 0x75988c6e08
	public override Boolean get_IsReadOnly() { }
	// RVA: 0x62aee10 VA: 0x75988c6e10
	public override String get_Name() { }
	// RVA: 0x62aee18 VA: 0x75988c6e18
	public override String get_LocalName() { }
	// RVA: 0x62aee20 VA: 0x75988c6e20
	public override String get_InnerText() { }
	// RVA: 0x62aee24 VA: 0x75988c6e24
	public override Void set_InnerText(String value) { }
	// RVA: 0x62aee84 VA: 0x75988c6e84
	internal override Boolean get_IsContainer() { }
	// RVA: 0x62aee8c VA: 0x75988c6e8c
	internal override XmlLinkedNode get_LastNode() { }
	// RVA: 0x62aef64 VA: 0x75988c6f64
	internal override Void set_LastNode(XmlLinkedNode value) { }
	// RVA: 0x62aef6c VA: 0x75988c6f6c
	internal override Boolean IsValidChildType(XmlNodeType type) { }
	// RVA: 0x62aefa8 VA: 0x75988c6fa8
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62aefb0 VA: 0x75988c6fb0
	public String get_SystemId() { }
	// RVA: 0x62aefb8 VA: 0x75988c6fb8
	public override Void set_InnerXml(String value) { }
	// RVA: 0x62af018 VA: 0x75988c7018
	public override String get_BaseURI() { }
	// RVA: 0x62af020 VA: 0x75988c7020
	internal Void SetBaseURI(String inBaseURI) { }
}
```