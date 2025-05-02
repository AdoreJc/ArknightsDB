# XmlText

**Namespace:** `System.Xml`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlText : XmlCharacterData
{

	public override String Name { get; }
	public override String LocalName { get; }
	public override XmlNodeType NodeType { get; }
	public override XmlNode ParentNode { get; }
	public override String Value { get; set; }
	internal override Boolean IsText { get; }

	// RVA: 0x62b1450 VA: 0x75988c9450
	internal Void .ctor(String strData) { }
	// RVA: 0x62b1448 VA: 0x75988c9448
	protected internal Void .ctor(String strData, XmlDocument doc) { }
	// RVA: 0x62b79ec VA: 0x75988cf9ec
	public override String get_Name() { }
	// RVA: 0x62b7a14 VA: 0x75988cfa14
	public override String get_LocalName() { }
	// RVA: 0x62b7a3c VA: 0x75988cfa3c
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62b7a44 VA: 0x75988cfa44
	public override XmlNode get_ParentNode() { }
	// RVA: 0x62b7ac8 VA: 0x75988cfac8
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62b7b24 VA: 0x75988cfb24
	public override String get_Value() { }
	// RVA: 0x62b7b34 VA: 0x75988cfb34
	public override Void set_Value(String value) { }
	// RVA: 0x62b7c08 VA: 0x75988cfc08
	internal override Boolean get_IsText() { }
}
```