# XmlElement

**Namespace:** `System.Xml`


## Fields

- `XmlName name`

- `XmlAttributeCollection attributes`

- `XmlLinkedNode lastChild`


## Properties

- `Boolean IsEmpty`


## Methods

- `Boolean get_IsEmpty()`

- `Void set_IsEmpty(Boolean)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlElement : XmlLinkedNode
{
	private XmlName name; // 0x20
	private XmlAttributeCollection attributes; // 0x28
	private XmlLinkedNode lastChild; // 0x30

	internal XmlName XmlName { get; set; }
	public override String Name { get; }
	public override String LocalName { get; }
	public override String NamespaceURI { get; }
	public override String Prefix { get; }
	public override XmlNodeType NodeType { get; }
	public override XmlNode ParentNode { get; }
	public override XmlDocument OwnerDocument { get; }
	internal override Boolean IsContainer { get; }
	public Boolean IsEmpty { get; set; }
	internal override XmlLinkedNode LastNode { get; set; }
	public override XmlAttributeCollection Attributes { get; }
	public virtual Boolean HasAttributes { get; }
	public override String InnerXml { set; }
	public override String InnerText { get; set; }
	public override XmlNode NextSibling { get; }

	// RVA: 0x62ad9e8 VA: 0x75988c59e8
	internal Void .ctor(XmlName name, Boolean empty, XmlDocument doc) { }
	// RVA: 0x62adb48 VA: 0x75988c5b48
	protected internal Void .ctor(String prefix, String localName, String namespaceURI, XmlDocument doc) { }
	// RVA: 0x62adb8c VA: 0x75988c5b8c
	internal XmlName get_XmlName() { }
	// RVA: 0x62adb94 VA: 0x75988c5b94
	internal Void set_XmlName(XmlName value) { }
	// RVA: 0x62adb9c VA: 0x75988c5b9c
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62ae180 VA: 0x75988c6180
	public override String get_Name() { }
	// RVA: 0x62ae364 VA: 0x75988c6364
	public override String get_LocalName() { }
	// RVA: 0x62ae380 VA: 0x75988c6380
	public override String get_NamespaceURI() { }
	// RVA: 0x62ae39c VA: 0x75988c639c
	public override String get_Prefix() { }
	// RVA: 0x62ae3b8 VA: 0x75988c63b8
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62ae3c0 VA: 0x75988c63c0
	public override XmlNode get_ParentNode() { }
	// RVA: 0x62ae3c8 VA: 0x75988c63c8
	public override XmlDocument get_OwnerDocument() { }
	// RVA: 0x62ae3e4 VA: 0x75988c63e4
	internal override Boolean get_IsContainer() { }
	// RVA: 0x62ae3ec VA: 0x75988c63ec
	internal override XmlNode AppendChildForLoad(XmlNode newChild, XmlDocument doc) { }
	// RVA: 0x62ae10c VA: 0x75988c610c
	public Boolean get_IsEmpty() { }
	// RVA: 0x62ae11c VA: 0x75988c611c
	public Void set_IsEmpty(Boolean value) { }
	// RVA: 0x62ae5d0 VA: 0x75988c65d0
	internal override XmlLinkedNode get_LastNode() { }
	// RVA: 0x62ae5e0 VA: 0x75988c65e0
	internal override Void set_LastNode(XmlLinkedNode value) { }
	// RVA: 0x62ae5e8 VA: 0x75988c65e8
	internal override Boolean IsValidChildType(XmlNodeType type) { }
	// RVA: 0x62ae60c VA: 0x75988c660c
	public override XmlAttributeCollection get_Attributes() { }
	// RVA: 0x62ae758 VA: 0x75988c6758
	public virtual Boolean get_HasAttributes() { }
	// RVA: 0x62ae780 VA: 0x75988c6780
	public virtual XmlAttribute SetAttributeNode(XmlAttribute newAttr) { }
	// RVA: 0x62ae898 VA: 0x75988c6898
	public virtual Void RemoveAllAttributes() { }
	// RVA: 0x62ae8d4 VA: 0x75988c68d4
	public override Void RemoveAll() { }
	// RVA: 0x62ae5cc VA: 0x75988c65cc
	internal Void RemoveAllChildren() { }
	// RVA: 0x62ae960 VA: 0x75988c6960
	public override Void set_InnerXml(String value) { }
	// RVA: 0x62aea50 VA: 0x75988c6a50
	public override String get_InnerText() { }
	// RVA: 0x62aeb5c VA: 0x75988c6b5c
	public override Void set_InnerText(String value) { }
	// RVA: 0x62aec14 VA: 0x75988c6c14
	public override XmlNode get_NextSibling() { }
	// RVA: 0x62aec50 VA: 0x75988c6c50
	internal override Void SetParent(XmlNode node) { }
}
```