# Datatype_duration

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_duration : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }
	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }

	// RVA: 0x62df408 VA: 0x75988f7408
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62df414 VA: 0x75988f7414
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62df46c VA: 0x75988f746c
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62df474 VA: 0x75988f7474
	public override Type get_ValueType() { }
	// RVA: 0x62df4cc VA: 0x75988f74cc
	internal override Type get_ListValueType() { }
	// RVA: 0x62df524 VA: 0x75988f7524
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62df52c VA: 0x75988f752c
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62df5d0 VA: 0x75988f75d0
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62df880 VA: 0x75988f7880
	public Void .ctor() { }
	// RVA: 0x62df8d4 VA: 0x75988f78d4
	private static Void .cctor() { }
}
```