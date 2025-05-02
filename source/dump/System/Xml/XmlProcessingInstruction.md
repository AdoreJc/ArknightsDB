# XmlProcessingInstruction

**Namespace:** `System.Xml`


## Fields

- `String target`

- `String data`


## Properties

- `String Data`


## Methods

- `Void set_Data(String)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlProcessingInstruction : XmlLinkedNode
{
	private String target; // 0x20
	private String data; // 0x28

	public override String Name { get; }
	public override String LocalName { get; }
	public override String Value { get; set; }
	public String Data { set; }
	public override String InnerText { get; set; }
	public override XmlNodeType NodeType { get; }

	// RVA: 0x62b2924 VA: 0x75988ca924
	protected internal Void .ctor(String target, String data, XmlDocument doc) { }
	// RVA: 0x62b7688 VA: 0x75988cf688
	public override String get_Name() { }
	// RVA: 0x62b76dc VA: 0x75988cf6dc
	public override String get_LocalName() { }
	// RVA: 0x62b76e8 VA: 0x75988cf6e8
	public override String get_Value() { }
	// RVA: 0x62b76f0 VA: 0x75988cf6f0
	public override Void set_Value(String value) { }
	// RVA: 0x62b76f4 VA: 0x75988cf6f4
	public Void set_Data(String value) { }
	// RVA: 0x62b77b8 VA: 0x75988cf7b8
	public override String get_InnerText() { }
	// RVA: 0x62b77c0 VA: 0x75988cf7c0
	public override Void set_InnerText(String value) { }
	// RVA: 0x62b77c4 VA: 0x75988cf7c4
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62b77cc VA: 0x75988cf7cc
	public override XmlNode CloneNode(Boolean deep) { }
}
```