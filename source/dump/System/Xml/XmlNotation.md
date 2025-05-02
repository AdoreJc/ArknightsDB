# XmlNotation

**Namespace:** `System.Xml`


## Fields

- `String publicId`

- `String systemId`

- `String name`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlNotation : XmlNode
{
	private String publicId; // 0x18
	private String systemId; // 0x20
	private String name; // 0x28

	public override String Name { get; }
	public override String LocalName { get; }
	public override XmlNodeType NodeType { get; }
	public override Boolean IsReadOnly { get; }
	public override String InnerXml { set; }

	// RVA: 0x62b2cbc VA: 0x75988cacbc
	internal Void .ctor(String name, String publicId, String systemId, XmlDocument doc) { }
	// RVA: 0x62b75a8 VA: 0x75988cf5a8
	public override String get_Name() { }
	// RVA: 0x62b75b0 VA: 0x75988cf5b0
	public override String get_LocalName() { }
	// RVA: 0x62b75b8 VA: 0x75988cf5b8
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62b75c0 VA: 0x75988cf5c0
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62b7620 VA: 0x75988cf620
	public override Boolean get_IsReadOnly() { }
	// RVA: 0x62b7628 VA: 0x75988cf628
	public override Void set_InnerXml(String value) { }
}
```