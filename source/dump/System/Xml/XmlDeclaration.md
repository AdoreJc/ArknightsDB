# XmlDeclaration

**Namespace:** `System.Xml`


## Fields

- `String version`

- `String encoding`

- `String standalone`


## Properties

- `String Version`

- `String Encoding`

- `String Standalone`


## Methods

- `String get_Version()`

- `String get_Encoding()`

- `Void set_Encoding(String)`

- `String get_Standalone()`

- `Void set_Standalone(String)`

- `Boolean IsValidXmlVersion(String)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlDeclaration : XmlLinkedNode
{
	private String version; // 0x20
	private String encoding; // 0x28
	private String standalone; // 0x30

	public String Version { get; set; }
	public String Encoding { get; set; }
	public String Standalone { get; set; }
	public override String Value { get; set; }
	public override String InnerText { get; set; }
	public override String Name { get; }
	public override String LocalName { get; }
	public override XmlNodeType NodeType { get; }

	// RVA: 0x62a8610 VA: 0x75988c0610
	protected internal Void .ctor(String version, String encoding, String standalone, XmlDocument doc) { }
	// RVA: 0x62a89ec VA: 0x75988c09ec
	public String get_Version() { }
	// RVA: 0x62a89f4 VA: 0x75988c09f4
	internal Void set_Version(String value) { }
	// RVA: 0x62a89fc VA: 0x75988c09fc
	public String get_Encoding() { }
	// RVA: 0x62a8824 VA: 0x75988c0824
	public Void set_Encoding(String value) { }
	// RVA: 0x62a8a04 VA: 0x75988c0a04
	public String get_Standalone() { }
	// RVA: 0x62a8894 VA: 0x75988c0894
	public Void set_Standalone(String value) { }
	// RVA: 0x62a8a0c VA: 0x75988c0a0c
	public override String get_Value() { }
	// RVA: 0x62a8a1c VA: 0x75988c0a1c
	public override Void set_Value(String value) { }
	// RVA: 0x62a8a2c VA: 0x75988c0a2c
	public override String get_InnerText() { }
	// RVA: 0x62a8b94 VA: 0x75988c0b94
	public override Void set_InnerText(String value) { }
	// RVA: 0x62a8d40 VA: 0x75988c0d40
	public override String get_Name() { }
	// RVA: 0x62a8d80 VA: 0x75988c0d80
	public override String get_LocalName() { }
	// RVA: 0x62a8d8c VA: 0x75988c0d8c
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62a8d94 VA: 0x75988c0d94
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62a87a8 VA: 0x75988c07a8
	private Boolean IsValidXmlVersion(String ver) { }
}
```