# Datatype_hexBinary

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_hexBinary : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }
	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }

	// RVA: 0x62e09c8 VA: 0x75988f89c8
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62e09d4 VA: 0x75988f89d4
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e0a2c VA: 0x75988f8a2c
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e0a34 VA: 0x75988f8a34
	public override Type get_ValueType() { }
	// RVA: 0x62e0a8c VA: 0x75988f8a8c
	internal override Type get_ListValueType() { }
	// RVA: 0x62e0ae4 VA: 0x75988f8ae4
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62e0aec VA: 0x75988f8aec
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e0ba8 VA: 0x75988f8ba8
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e0d68 VA: 0x75988f8d68
	public Void .ctor() { }
	// RVA: 0x62e0dbc VA: 0x75988f8dbc
	private static Void .cctor() { }
}
```