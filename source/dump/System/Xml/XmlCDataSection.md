# XmlCDataSection

**Namespace:** `System.Xml`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlCDataSection : XmlCharacterData
{

	public override String Name { get; }
	public override String LocalName { get; }
	public override XmlNodeType NodeType { get; }
	public override XmlNode ParentNode { get; }
	internal override Boolean IsText { get; }

	// RVA: 0x62a7f0c VA: 0x75988bff0c
	protected internal Void .ctor(String data, XmlDocument doc) { }
	// RVA: 0x62a7f74 VA: 0x75988bff74
	public override String get_Name() { }
	// RVA: 0x62a7f9c VA: 0x75988bff9c
	public override String get_LocalName() { }
	// RVA: 0x62a7fc4 VA: 0x75988bffc4
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62a7fcc VA: 0x75988bffcc
	public override XmlNode get_ParentNode() { }
	// RVA: 0x62a8050 VA: 0x75988c0050
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62a80ac VA: 0x75988c00ac
	internal override Boolean get_IsText() { }
}
```