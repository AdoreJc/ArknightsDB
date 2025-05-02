# SchemaInfo

**Namespace:** `System.Xml.Schema`


## Fields

- `XmlQualifiedName docTypeName`

- `String internalDtdSubset`

- `Boolean hasNonCDataAttributes`

- `Boolean hasDefaultAttributes`

- `SchemaType schemaType`


## Properties

- `XmlQualifiedName DocTypeName`


## Methods

- `Void set_DocTypeName(XmlQualifiedName)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class SchemaInfo : IDtdInfo
{
	private Dictionary`2 elementDecls; // 0x10
	private Dictionary`2 undeclaredElementDecls; // 0x18
	private Dictionary`2 generalEntities; // 0x20
	private Dictionary`2 parameterEntities; // 0x28
	private XmlQualifiedName docTypeName; // 0x30
	private String internalDtdSubset; // 0x38
	private Boolean hasNonCDataAttributes; // 0x40
	private Boolean hasDefaultAttributes; // 0x41
	private Dictionary`2 targetNamespaces; // 0x48
	private Dictionary`2 attributeDecls; // 0x50
	private SchemaType schemaType; // 0x58
	private Dictionary`2 elementDeclsByType; // 0x60
	private Dictionary`2 notations; // 0x68

	public XmlQualifiedName DocTypeName { set; }
	internal String InternalDtdSubset { set; }
	internal Dictionary`2 ElementDecls { get; }
	internal Dictionary`2 UndeclaredElementDecls { get; }
	internal Dictionary`2 GeneralEntities { get; }
	internal Dictionary`2 ParameterEntities { get; }
	internal SchemaType SchemaType { get; set; }
	internal Dictionary`2 Notations { get; }
	private Boolean System.Xml.IDtdInfo.HasDefaultAttributes { get; }
	private Boolean System.Xml.IDtdInfo.HasNonCDataAttributes { get; }
	private XmlQualifiedName System.Xml.IDtdInfo.Name { get; }
	private String System.Xml.IDtdInfo.InternalDtdSubset { get; }

	// RVA: 0x62ec1e8 VA: 0x75989041e8
	internal Void .ctor() { }
	// RVA: 0x62ec3e0 VA: 0x75989043e0
	public Void set_DocTypeName(XmlQualifiedName value) { }
	// RVA: 0x62ec3e8 VA: 0x75989043e8
	internal Void set_InternalDtdSubset(String value) { }
	// RVA: 0x62ec3f0 VA: 0x75989043f0
	internal Dictionary`2 get_ElementDecls() { }
	// RVA: 0x62ec3f8 VA: 0x75989043f8
	internal Dictionary`2 get_UndeclaredElementDecls() { }
	// RVA: 0x62ec400 VA: 0x7598904400
	internal Dictionary`2 get_GeneralEntities() { }
	// RVA: 0x62ec48c VA: 0x759890448c
	internal Dictionary`2 get_ParameterEntities() { }
	// RVA: 0x62ec518 VA: 0x7598904518
	internal SchemaType get_SchemaType() { }
	// RVA: 0x62ec520 VA: 0x7598904520
	internal Void set_SchemaType(SchemaType value) { }
	// RVA: 0x62ec528 VA: 0x7598904528
	internal Dictionary`2 get_Notations() { }
	// RVA: 0x62ec5b4 VA: 0x75989045b4
	internal Void Finish() { }
	// RVA: 0x62ec768 VA: 0x7598904768
	private Boolean System.Xml.IDtdInfo.get_HasDefaultAttributes() { }
	// RVA: 0x62ec770 VA: 0x7598904770
	private Boolean System.Xml.IDtdInfo.get_HasNonCDataAttributes() { }
	// RVA: 0x62ec778 VA: 0x7598904778
	private IDtdAttributeListInfo System.Xml.IDtdInfo.LookupAttributeList(String prefix, String localName) { }
	// RVA: 0x62ec844 VA: 0x7598904844
	private IDtdEntityInfo System.Xml.IDtdInfo.LookupEntity(String name) { }
	// RVA: 0x62ec8fc VA: 0x75989048fc
	private XmlQualifiedName System.Xml.IDtdInfo.get_Name() { }
	// RVA: 0x62ec904 VA: 0x7598904904
	private String System.Xml.IDtdInfo.get_InternalDtdSubset() { }
}
```