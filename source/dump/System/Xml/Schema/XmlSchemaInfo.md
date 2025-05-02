# XmlSchemaInfo

**Namespace:** `System.Xml.Schema`


## Fields

- `Boolean isDefault`

- `Boolean isNil`

- `XmlSchemaElement schemaElement`

- `XmlSchemaAttribute schemaAttribute`

- `XmlSchemaType schemaType`

- `XmlSchemaSimpleType memberType`

- `XmlSchemaValidity validity`

- `XmlSchemaContentType contentType`


## Properties

- `XmlSchemaValidity Validity`

- `Boolean IsDefault`

- `Boolean IsNil`

- `XmlSchemaSimpleType MemberType`

- `XmlSchemaType SchemaType`

- `XmlSchemaElement SchemaElement`

- `XmlSchemaAttribute SchemaAttribute`


## Methods

- `XmlSchemaValidity get_Validity()`

- `Boolean get_IsDefault()`

- `Boolean get_IsNil()`

- `XmlSchemaSimpleType get_MemberType()`

- `XmlSchemaType get_SchemaType()`

- `XmlSchemaElement get_SchemaElement()`

- `XmlSchemaAttribute get_SchemaAttribute()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
public class XmlSchemaInfo : IXmlSchemaInfo
{
	private Boolean isDefault; // 0x10
	private Boolean isNil; // 0x11
	private XmlSchemaElement schemaElement; // 0x18
	private XmlSchemaAttribute schemaAttribute; // 0x20
	private XmlSchemaType schemaType; // 0x28
	private XmlSchemaSimpleType memberType; // 0x30
	private XmlSchemaValidity validity; // 0x38
	private XmlSchemaContentType contentType; // 0x3c

	public XmlSchemaValidity Validity { get; }
	public Boolean IsDefault { get; }
	public Boolean IsNil { get; }
	public XmlSchemaSimpleType MemberType { get; }
	public XmlSchemaType SchemaType { get; }
	public XmlSchemaElement SchemaElement { get; }
	public XmlSchemaAttribute SchemaAttribute { get; }

	// RVA: 0x62efb70 VA: 0x7598907b70
	public Void .ctor() { }
	// RVA: 0x62efbe8 VA: 0x7598907be8
	internal Void .ctor(XmlSchemaValidity validity) { }
	// RVA: 0x62efc18 VA: 0x7598907c18
	public XmlSchemaValidity get_Validity() { }
	// RVA: 0x62efc20 VA: 0x7598907c20
	public Boolean get_IsDefault() { }
	// RVA: 0x62efc28 VA: 0x7598907c28
	public Boolean get_IsNil() { }
	// RVA: 0x62efc30 VA: 0x7598907c30
	public XmlSchemaSimpleType get_MemberType() { }
	// RVA: 0x62efc38 VA: 0x7598907c38
	public XmlSchemaType get_SchemaType() { }
	// RVA: 0x62efc40 VA: 0x7598907c40
	public XmlSchemaElement get_SchemaElement() { }
	// RVA: 0x62efc48 VA: 0x7598907c48
	public XmlSchemaAttribute get_SchemaAttribute() { }
	// RVA: 0x62efb8c VA: 0x7598907b8c
	internal Void Clear() { }
}
```