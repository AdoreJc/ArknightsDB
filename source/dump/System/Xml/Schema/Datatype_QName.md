# Datatype_QName

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_QName : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override XmlTokenizedType TokenizedType { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }
	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }

	// RVA: 0x62e1a10 VA: 0x75988f9a10
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62e1a1c VA: 0x75988f9a1c
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e1a74 VA: 0x75988f9a74
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e1a7c VA: 0x75988f9a7c
	public override XmlTokenizedType get_TokenizedType() { }
	// RVA: 0x62e1a84 VA: 0x75988f9a84
	public override Type get_ValueType() { }
	// RVA: 0x62e1adc VA: 0x75988f9adc
	internal override Type get_ListValueType() { }
	// RVA: 0x62e1b34 VA: 0x75988f9b34
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62e1b3c VA: 0x75988f9b3c
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e1d8c VA: 0x75988f9d8c
	public Void .ctor() { }
	// RVA: 0x62e1de0 VA: 0x75988f9de0
	private static Void .cctor() { }
}
```