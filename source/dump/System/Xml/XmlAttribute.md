# XmlAttribute

**Namespace:** `System.Xml`


## Fields

- `XmlName name`

- `XmlLinkedNode lastChild`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlAttribute : XmlNode
{
	private XmlName name; // 0x18
	private XmlLinkedNode lastChild; // 0x20

	internal XmlName XmlName { get; set; }
	public override XmlNode ParentNode { get; }
	public override String Name { get; }
	public override String LocalName { get; }
	public override String NamespaceURI { get; }
	public override String Prefix { get; }
	public override XmlNodeType NodeType { get; }
	public override XmlDocument OwnerDocument { get; }
	public override String Value { get; set; }
	public override String InnerText { set; }
	internal override Boolean IsContainer { get; }
	internal override XmlLinkedNode LastNode { get; set; }
	public virtual Boolean Specified { get; }
	public virtual XmlElement OwnerElement { get; }
	public override String InnerXml { set; }
	public override String BaseURI { get; }

	// RVA: 0x62a5dd4 VA: 0x75988bddd4
	internal Void .ctor(XmlName name, XmlDocument doc) { }
	// RVA: 0x62a5fd0 VA: 0x75988bdfd0
	protected internal Void .ctor(String prefix, String localName, String namespaceURI, XmlDocument doc) { }
	// RVA: 0x62a6128 VA: 0x75988be128
	internal XmlName get_XmlName() { }
	// RVA: 0x62a6130 VA: 0x75988be130
	internal Void set_XmlName(XmlName value) { }
	// RVA: 0x62a6138 VA: 0x75988be138
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62a6200 VA: 0x75988be200
	public override XmlNode get_ParentNode() { }
	// RVA: 0x62a6208 VA: 0x75988be208
	public override String get_Name() { }
	// RVA: 0x62a6224 VA: 0x75988be224
	public override String get_LocalName() { }
	// RVA: 0x62a6240 VA: 0x75988be240
	public override String get_NamespaceURI() { }
	// RVA: 0x62a625c VA: 0x75988be25c
	public override String get_Prefix() { }
	// RVA: 0x62a6278 VA: 0x75988be278
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62a6280 VA: 0x75988be280
	public override XmlDocument get_OwnerDocument() { }
	// RVA: 0x62a629c VA: 0x75988be29c
	public override String get_Value() { }
	// RVA: 0x62a62ac VA: 0x75988be2ac
	public override Void set_Value(String value) { }
	// RVA: 0x62a62bc VA: 0x75988be2bc
	public override Void set_InnerText(String value) { }
	// RVA: 0x62a6320 VA: 0x75988be320
	internal Boolean PrepareOwnerElementInElementIdAttrMap() { }
	// RVA: 0x62a63d0 VA: 0x75988be3d0
	internal Void ResetOwnerElementInElementIdAttrMap(String oldInnerText) { }
	// RVA: 0x62a6600 VA: 0x75988be600
	internal override Boolean get_IsContainer() { }
	// RVA: 0x62a6608 VA: 0x75988be608
	internal override XmlNode AppendChildForLoad(XmlNode newChild, XmlDocument doc) { }
	// RVA: 0x62a6874 VA: 0x75988be874
	internal override XmlLinkedNode get_LastNode() { }
	// RVA: 0x62a687c VA: 0x75988be87c
	internal override Void set_LastNode(XmlLinkedNode value) { }
	// RVA: 0x62a6884 VA: 0x75988be884
	internal override Boolean IsValidChildType(XmlNodeType type) { }
	// RVA: 0x62a689c VA: 0x75988be89c
	public virtual Boolean get_Specified() { }
	// RVA: 0x62a68a4 VA: 0x75988be8a4
	public override XmlNode RemoveChild(XmlNode oldChild) { }
	// RVA: 0x62a691c VA: 0x75988be91c
	public override XmlNode AppendChild(XmlNode newChild) { }
	// RVA: 0x62a6994 VA: 0x75988be994
	public virtual XmlElement get_OwnerElement() { }
	// RVA: 0x62a6a10 VA: 0x75988bea10
	public override Void set_InnerXml(String value) { }
	// RVA: 0x62a6a9c VA: 0x75988bea9c
	public override String get_BaseURI() { }
	// RVA: 0x62a6b34 VA: 0x75988beb34
	internal override Void SetParent(XmlNode node) { }
}
```