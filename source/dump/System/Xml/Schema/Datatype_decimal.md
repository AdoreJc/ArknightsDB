# Datatype_decimal

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_decimal : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8
	private static readonly FacetsChecker numeric10FacetsChecker; // 0x10

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }
	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }

	// RVA: 0x62dee04 VA: 0x75988f6e04
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62dee6c VA: 0x75988f6e6c
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62deec4 VA: 0x75988f6ec4
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62deecc VA: 0x75988f6ecc
	public override Type get_ValueType() { }
	// RVA: 0x62def24 VA: 0x75988f6f24
	internal override Type get_ListValueType() { }
	// RVA: 0x62def7c VA: 0x75988f6f7c
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62def84 VA: 0x75988f6f84
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62df050 VA: 0x75988f7050
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62df1c8 VA: 0x75988f71c8
	public Void .ctor() { }
	// RVA: 0x62df21c VA: 0x75988f721c
	private static Void .cctor() { }
}
```