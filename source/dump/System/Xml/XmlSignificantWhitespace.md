# XmlSignificantWhitespace

**Namespace:** `System.Xml`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlSignificantWhitespace : XmlCharacterData
{

	public override String Name { get; }
	public override String LocalName { get; }
	public override XmlNodeType NodeType { get; }
	public override XmlNode ParentNode { get; }
	public override String Value { get; set; }
	internal override Boolean IsText { get; }

	// RVA: 0x62b27dc VA: 0x75988ca7dc
	protected internal Void .ctor(String strData, XmlDocument doc) { }
	// RVA: 0x62b7804 VA: 0x75988cf804
	public override String get_Name() { }
	// RVA: 0x62b782c VA: 0x75988cf82c
	public override String get_LocalName() { }
	// RVA: 0x62b7854 VA: 0x75988cf854
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62b785c VA: 0x75988cf85c
	public override XmlNode get_ParentNode() { }
	// RVA: 0x62b78e4 VA: 0x75988cf8e4
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62b7940 VA: 0x75988cf940
	public override String get_Value() { }
	// RVA: 0x62b7950 VA: 0x75988cf950
	public override Void set_Value(String value) { }
	// RVA: 0x62b79e4 VA: 0x75988cf9e4
	internal override Boolean get_IsText() { }
}
```