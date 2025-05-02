# XmlSchemaSimpleTypeList

**Namespace:** `System.Xml.Schema`


## Fields

- `XmlQualifiedName itemTypeName`

- `XmlSchemaSimpleType itemType`

- `XmlSchemaSimpleType baseItemType`


## Properties

- `XmlSchemaSimpleType ItemType`

- `XmlSchemaSimpleType BaseItemType`


## Methods

- `Void set_ItemType(XmlSchemaSimpleType)`

- `XmlSchemaSimpleType get_BaseItemType()`

- `Void set_BaseItemType(XmlSchemaSimpleType)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
public class XmlSchemaSimpleTypeList : XmlSchemaSimpleTypeContent
{
	private XmlQualifiedName itemTypeName; // 0x10
	private XmlSchemaSimpleType itemType; // 0x18
	private XmlSchemaSimpleType baseItemType; // 0x20

	public XmlSchemaSimpleType ItemType { set; }
	public XmlSchemaSimpleType BaseItemType { get; set; }

	// RVA: 0x62f01c8 VA: 0x75989081c8
	public Void set_ItemType(XmlSchemaSimpleType value) { }
	// RVA: 0x62f01d0 VA: 0x75989081d0
	public XmlSchemaSimpleType get_BaseItemType() { }
	// RVA: 0x62f01d8 VA: 0x75989081d8
	public Void set_BaseItemType(XmlSchemaSimpleType value) { }
	// RVA: 0x62f01e0 VA: 0x75989081e0
	public Void .ctor() { }
}
```