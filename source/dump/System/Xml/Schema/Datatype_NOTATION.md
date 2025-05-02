# Datatype_NOTATION

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_NOTATION : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override XmlTokenizedType TokenizedType { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }
	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }

	// RVA: 0x62e2078 VA: 0x75988fa078
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62e2084 VA: 0x75988fa084
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e20dc VA: 0x75988fa0dc
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e20e4 VA: 0x75988fa0e4
	public override XmlTokenizedType get_TokenizedType() { }
	// RVA: 0x62e20ec VA: 0x75988fa0ec
	public override Type get_ValueType() { }
	// RVA: 0x62e2144 VA: 0x75988fa144
	internal override Type get_ListValueType() { }
	// RVA: 0x62e219c VA: 0x75988fa19c
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62e21a4 VA: 0x75988fa1a4
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e23f4 VA: 0x75988fa3f4
	public Void .ctor() { }
	// RVA: 0x62e2448 VA: 0x75988fa448
	private static Void .cctor() { }
}
```