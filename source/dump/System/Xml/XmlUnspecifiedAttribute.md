# XmlUnspecifiedAttribute

**Namespace:** `System.Xml`


## Fields

- `Boolean fSpecified`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class XmlUnspecifiedAttribute : XmlAttribute
{
	private Boolean fSpecified; // 0x28

	public override Boolean Specified { get; }
	public override String InnerText { set; }

	// RVA: 0x62b2978 VA: 0x75988ca978
	protected internal Void .ctor(String prefix, String localName, String namespaceURI, XmlDocument doc) { }
	// RVA: 0x62b7c10 VA: 0x75988cfc10
	public override Boolean get_Specified() { }
	// RVA: 0x62b7c18 VA: 0x75988cfc18
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62b7d48 VA: 0x75988cfd48
	public override Void set_InnerText(String value) { }
	// RVA: 0x62b7d68 VA: 0x75988cfd68
	public override XmlNode RemoveChild(XmlNode oldChild) { }
	// RVA: 0x62b7d88 VA: 0x75988cfd88
	public override XmlNode AppendChild(XmlNode newChild) { }
	// RVA: 0x62b7da8 VA: 0x75988cfda8
	internal Void SetSpecified(Boolean f) { }
}
```