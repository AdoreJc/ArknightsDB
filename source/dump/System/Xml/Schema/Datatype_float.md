# Datatype_float

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_float : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }
	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }

	// RVA: 0x62de544 VA: 0x75988f6544
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62de5ac VA: 0x75988f65ac
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62de604 VA: 0x75988f6604
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62de60c VA: 0x75988f660c
	public override Type get_ValueType() { }
	// RVA: 0x62de664 VA: 0x75988f6664
	internal override Type get_ListValueType() { }
	// RVA: 0x62de6bc VA: 0x75988f66bc
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62de6c4 VA: 0x75988f66c4
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62de758 VA: 0x75988f6758
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62de8ac VA: 0x75988f68ac
	public Void .ctor() { }
	// RVA: 0x62de900 VA: 0x75988f6900
	private static Void .cctor() { }
}
```