# Datatype_anyURI

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_anyURI : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }
	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }

	// RVA: 0x62e1354 VA: 0x75988f9354
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62e1360 VA: 0x75988f9360
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e13b8 VA: 0x75988f93b8
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e13c0 VA: 0x75988f93c0
	public override Type get_ValueType() { }
	// RVA: 0x62e1418 VA: 0x75988f9418
	internal override Type get_ListValueType() { }
	// RVA: 0x62e1470 VA: 0x75988f9470
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62e1478 VA: 0x75988f9478
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e1564 VA: 0x75988f9564
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e18e8 VA: 0x75988f98e8
	public Void .ctor() { }
	// RVA: 0x62e193c VA: 0x75988f993c
	private static Void .cctor() { }
}
```