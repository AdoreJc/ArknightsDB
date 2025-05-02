# DomNameTable

**Namespace:** `System.Xml`


## Fields

- `Int32 count`

- `Int32 mask`

- `XmlDocument ownerDocument`

- `XmlNameTable nameTable`


## Methods

- `XmlName GetName(String, String, String, IXmlSchemaInfo)`

- `XmlName AddName(String, String, String, IXmlSchemaInfo)`

- `Void Grow()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class DomNameTable
{
	private XmlName[] entries; // 0x10
	private Int32 count; // 0x18
	private Int32 mask; // 0x1c
	private XmlDocument ownerDocument; // 0x20
	private XmlNameTable nameTable; // 0x28


	// RVA: 0x62a57fc VA: 0x75988bd7fc
	public Void .ctor(XmlDocument document) { }
	// RVA: 0x62a58bc VA: 0x75988bd8bc
	public XmlName GetName(String prefix, String localName, String ns, IXmlSchemaInfo schemaInfo) { }
	// RVA: 0x62a5a18 VA: 0x75988bda18
	public XmlName AddName(String prefix, String localName, String ns, IXmlSchemaInfo schemaInfo) { }
	// RVA: 0x62a5c84 VA: 0x75988bdc84
	private Void Grow() { }
}
```