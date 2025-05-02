# XmlWhitespace

**Namespace:** `System.Xml`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlWhitespace : XmlCharacterData
{

	public override String Name { get; }
	public override String LocalName { get; }
	public override XmlNodeType NodeType { get; }
	public override XmlNode ParentNode { get; }
	public override String Value { get; set; }
	internal override Boolean IsText { get; }

	// RVA: 0x62b2880 VA: 0x75988ca880
	protected internal Void .ctor(String strData, XmlDocument doc) { }
	// RVA: 0x62b7db4 VA: 0x75988cfdb4
	public override String get_Name() { }
	// RVA: 0x62b7ddc VA: 0x75988cfddc
	public override String get_LocalName() { }
	// RVA: 0x62b7e04 VA: 0x75988cfe04
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62b7e0c VA: 0x75988cfe0c
	public override XmlNode get_ParentNode() { }
	// RVA: 0x62b7e94 VA: 0x75988cfe94
	public override String get_Value() { }
	// RVA: 0x62b7ea4 VA: 0x75988cfea4
	public override Void set_Value(String value) { }
	// RVA: 0x62b7f38 VA: 0x75988cff38
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62b7f94 VA: 0x75988cff94
	internal override Boolean get_IsText() { }
}
```