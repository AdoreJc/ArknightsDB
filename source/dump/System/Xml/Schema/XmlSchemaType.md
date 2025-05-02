# XmlSchemaType

**Namespace:** `System.Xml.Schema`


## Fields

- `XmlSchemaDerivationMethod final`

- `XmlSchemaDerivationMethod derivedBy`

- `XmlSchemaType baseSchemaType`

- `XmlSchemaDatatype datatype`

- `SchemaElementDecl elementDecl`

- `XmlQualifiedName qname`

- `XmlSchemaContentType contentType`


## Properties

- `XmlQualifiedName QualifiedName`

- `XmlSchemaType BaseXmlSchemaType`

- `XmlSchemaDatatype Datatype`

- `XmlTypeCode TypeCode`


## Methods

- `XmlQualifiedName get_QualifiedName()`

- `XmlSchemaType get_BaseXmlSchemaType()`

- `XmlSchemaDatatype get_Datatype()`

- `XmlTypeCode get_TypeCode()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
public class XmlSchemaType : XmlSchemaAnnotated
{
	private XmlSchemaDerivationMethod final; // 0x10
	private XmlSchemaDerivationMethod derivedBy; // 0x14
	private XmlSchemaType baseSchemaType; // 0x18
	private XmlSchemaDatatype datatype; // 0x20
	private SchemaElementDecl elementDecl; // 0x28
	private XmlQualifiedName qname; // 0x30
	private XmlSchemaContentType contentType; // 0x38

	public XmlQualifiedName QualifiedName { get; }
	public XmlSchemaType BaseXmlSchemaType { get; }
	public XmlSchemaDatatype Datatype { get; }
	public virtual Boolean IsMixed { set; }
	public XmlTypeCode TypeCode { get; }
	internal XmlValueConverter ValueConverter { get; }
	internal SchemaElementDecl ElementDecl { get; set; }

	// RVA: 0x62f03a0 VA: 0x75989083a0
	public static XmlSchemaSimpleType GetBuiltInSimpleType(XmlTypeCode typeCode) { }
	// RVA: 0x62f03f8 VA: 0x75989083f8
	public XmlQualifiedName get_QualifiedName() { }
	// RVA: 0x62f0410 VA: 0x7598908410
	public XmlSchemaType get_BaseXmlSchemaType() { }
	// RVA: 0x62f0418 VA: 0x7598908418
	public XmlSchemaDatatype get_Datatype() { }
	// RVA: 0x62f0420 VA: 0x7598908420
	public virtual Void set_IsMixed(Boolean value) { }
	// RVA: 0x62ed05c VA: 0x759890505c
	public XmlTypeCode get_TypeCode() { }
	// RVA: 0x62ed704 VA: 0x7598905704
	internal XmlValueConverter get_ValueConverter() { }
	// RVA: 0x62ee77c VA: 0x759890677c
	internal Void SetQualifiedName(XmlQualifiedName value) { }
	// RVA: 0x62f0424 VA: 0x7598908424
	internal Void SetBaseSchemaType(XmlSchemaType value) { }
	// RVA: 0x62f042c VA: 0x759890842c
	internal Void SetDerivedBy(XmlSchemaDerivationMethod value) { }
	// RVA: 0x62f0434 VA: 0x7598908434
	internal Void SetDatatype(XmlSchemaDatatype value) { }
	// RVA: 0x62ee7d4 VA: 0x75989067d4
	internal SchemaElementDecl get_ElementDecl() { }
	// RVA: 0x62ee7a8 VA: 0x75989067a8
	internal Void set_ElementDecl(SchemaElementDecl value) { }
	// RVA: 0x62f043c VA: 0x759890843c
	internal Void SetContentType(XmlSchemaContentType value) { }
	// RVA: 0x62eec14 VA: 0x7598906c14
	public Void .ctor() { }
}
```