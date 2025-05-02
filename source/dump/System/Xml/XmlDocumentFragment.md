# XmlDocumentFragment

**Namespace:** `System.Xml`


## Fields

- `XmlLinkedNode lastChild`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlDocumentFragment : XmlNode
{
	private XmlLinkedNode lastChild; // 0x18

	public override String Name { get; }
	public override String LocalName { get; }
	public override XmlNodeType NodeType { get; }
	public override XmlNode ParentNode { get; }
	public override XmlDocument OwnerDocument { get; }
	public override String InnerXml { set; }
	internal override Boolean IsContainer { get; }
	internal override XmlLinkedNode LastNode { get; set; }

	// RVA: 0x62ad0ec VA: 0x75988c50ec
	protected internal Void .ctor(XmlDocument ownerDocument) { }
	// RVA: 0x62ad180 VA: 0x75988c5180
	public override String get_Name() { }
	// RVA: 0x62ad1a8 VA: 0x75988c51a8
	public override String get_LocalName() { }
	// RVA: 0x62ad1d0 VA: 0x75988c51d0
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62ad1d8 VA: 0x75988c51d8
	public override XmlNode get_ParentNode() { }
	// RVA: 0x62ad1e0 VA: 0x75988c51e0
	public override XmlDocument get_OwnerDocument() { }
	// RVA: 0x62ad258 VA: 0x75988c5258
	public override Void set_InnerXml(String value) { }
	// RVA: 0x62ad50c VA: 0x75988c550c
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62ad590 VA: 0x75988c5590
	internal override Boolean get_IsContainer() { }
	// RVA: 0x62ad598 VA: 0x75988c5598
	internal override XmlLinkedNode get_LastNode() { }
	// RVA: 0x62ad5a0 VA: 0x75988c55a0
	internal override Void set_LastNode(XmlLinkedNode value) { }
	// RVA: 0x62ad5a8 VA: 0x75988c55a8
	internal override Boolean IsValidChildType(XmlNodeType type) { }
	// RVA: 0x62ad614 VA: 0x75988c5614
	internal override Boolean CanInsertAfter(XmlNode newChild, XmlNode refChild) { }
}
```