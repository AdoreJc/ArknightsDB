# Datatype_List

**Namespace:** `System.Xml.Schema`


## Fields

- `DatatypeImplementation itemType`

- `Int32 minListSize`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_List : Datatype_anySimpleType
{
	private DatatypeImplementation itemType; // 0x38
	private Int32 minListSize; // 0x40

	public override Type ValueType { get; }
	public override XmlTokenizedType TokenizedType { get; }
	internal override Type ListValueType { get; }
	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }

	// RVA: 0x62dcf3c VA: 0x75988f4f3c
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62dc9e4 VA: 0x75988f49e4
	internal Void .ctor(DatatypeImplementation type, Int32 minListSize) { }
	// RVA: 0x62dd1e0 VA: 0x75988f51e0
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62dd47c VA: 0x75988f547c
	public override Type get_ValueType() { }
	// RVA: 0x62dd48c VA: 0x75988f548c
	public override XmlTokenizedType get_TokenizedType() { }
	// RVA: 0x62dd4ac VA: 0x75988f54ac
	internal override Type get_ListValueType() { }
	// RVA: 0x62dd4d0 VA: 0x75988f54d0
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62dd528 VA: 0x75988f5528
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62dd548 VA: 0x75988f5548
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
}
```