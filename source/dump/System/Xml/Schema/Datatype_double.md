# Datatype_double

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_double : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }
	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }

	// RVA: 0x62de9d4 VA: 0x75988f69d4
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62de9dc VA: 0x75988f69dc
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62dea34 VA: 0x75988f6a34
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62dea3c VA: 0x75988f6a3c
	public override Type get_ValueType() { }
	// RVA: 0x62dea94 VA: 0x75988f6a94
	internal override Type get_ListValueType() { }
	// RVA: 0x62deaec VA: 0x75988f6aec
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62deaf4 VA: 0x75988f6af4
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62deb88 VA: 0x75988f6b88
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62decdc VA: 0x75988f6cdc
	public Void .ctor() { }
	// RVA: 0x62ded30 VA: 0x75988f6d30
	private static Void .cctor() { }
}
```