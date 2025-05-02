# Datatype_boolean

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_boolean : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }
	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }

	// RVA: 0x62de0dc VA: 0x75988f60dc
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62de144 VA: 0x75988f6144
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62de19c VA: 0x75988f619c
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62de1a4 VA: 0x75988f61a4
	public override Type get_ValueType() { }
	// RVA: 0x62de1fc VA: 0x75988f61fc
	internal override Type get_ListValueType() { }
	// RVA: 0x62de254 VA: 0x75988f6254
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62de25c VA: 0x75988f625c
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62de300 VA: 0x75988f6300
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62de41c VA: 0x75988f641c
	public Void .ctor() { }
	// RVA: 0x62de470 VA: 0x75988f6470
	private static Void .cctor() { }
}
```