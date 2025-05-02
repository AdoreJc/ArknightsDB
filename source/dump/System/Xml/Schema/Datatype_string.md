# Datatype_string

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_string : Datatype_anySimpleType
{

	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }
	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override XmlTokenizedType TokenizedType { get; }

	// RVA: 0x62ddf20 VA: 0x75988f5f20
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62ddf2c VA: 0x75988f5f2c
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62ddf34 VA: 0x75988f5f34
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62ddf8c VA: 0x75988f5f8c
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62ddf94 VA: 0x75988f5f94
	public override XmlTokenizedType get_TokenizedType() { }
	// RVA: 0x62ddf9c VA: 0x75988f5f9c
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62de088 VA: 0x75988f6088
	public Void .ctor() { }
}
```