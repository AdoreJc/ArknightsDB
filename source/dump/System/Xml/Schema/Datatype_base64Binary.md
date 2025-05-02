# Datatype_base64Binary

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_base64Binary : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }
	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }

	// RVA: 0x62e0e90 VA: 0x75988f8e90
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62e0e9c VA: 0x75988f8e9c
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e0ef4 VA: 0x75988f8ef4
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e0efc VA: 0x75988f8efc
	public override Type get_ValueType() { }
	// RVA: 0x62e0f54 VA: 0x75988f8f54
	internal override Type get_ListValueType() { }
	// RVA: 0x62e0fac VA: 0x75988f8fac
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62e0fb4 VA: 0x75988f8fb4
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e1070 VA: 0x75988f9070
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e122c VA: 0x75988f922c
	public Void .ctor() { }
	// RVA: 0x62e1280 VA: 0x75988f9280
	private static Void .cctor() { }
}
```