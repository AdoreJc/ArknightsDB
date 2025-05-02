# Datatype_anySimpleType

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_anySimpleType : DatatypeImplementation
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	internal override FacetsChecker FacetsChecker { get; }
	public override Type ValueType { get; }
	public override XmlTypeCode TypeCode { get; }
	internal override Type ListValueType { get; }
	public override XmlTokenizedType TokenizedType { get; }
	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }

	// RVA: 0x62ddacc VA: 0x75988f5acc
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62ddb24 VA: 0x75988f5b24
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62ddb7c VA: 0x75988f5b7c
	public override Type get_ValueType() { }
	// RVA: 0x62ddbd4 VA: 0x75988f5bd4
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62ddbdc VA: 0x75988f5bdc
	internal override Type get_ListValueType() { }
	// RVA: 0x62ddc34 VA: 0x75988f5c34
	public override XmlTokenizedType get_TokenizedType() { }
	// RVA: 0x62ddc3c VA: 0x75988f5c3c
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62ddc44 VA: 0x75988f5c44
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62ddc9c VA: 0x75988f5c9c
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62ddccc VA: 0x75988f5ccc
	public Void .ctor() { }
	// RVA: 0x62ddd24 VA: 0x75988f5d24
	private static Void .cctor() { }
}
```