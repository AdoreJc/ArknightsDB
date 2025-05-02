# Datatype_dateTimeBase

**Namespace:** `System.Xml.Schema`


## Fields

- `XsdDateTimeFlags dateTimeFlags`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_dateTimeBase : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8
	private XsdDateTimeFlags dateTimeFlags; // 0x38

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }
	internal override XmlSchemaWhiteSpace BuiltInWhitespaceFacet { get; }

	// RVA: 0x62dfe18 VA: 0x75988f7e18
	internal override XmlValueConverter CreateValueConverter(XmlSchemaType schemaType) { }
	// RVA: 0x62dfe80 VA: 0x75988f7e80
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62dfed8 VA: 0x75988f7ed8
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62dfee0 VA: 0x75988f7ee0
	internal Void .ctor(XsdDateTimeFlags dateTimeFlags) { }
	// RVA: 0x62dff48 VA: 0x75988f7f48
	public override Type get_ValueType() { }
	// RVA: 0x62dffa0 VA: 0x75988f7fa0
	internal override Type get_ListValueType() { }
	// RVA: 0x62dfff8 VA: 0x75988f7ff8
	internal override XmlSchemaWhiteSpace get_BuiltInWhitespaceFacet() { }
	// RVA: 0x62e0000 VA: 0x75988f8000
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e0148 VA: 0x75988f8148
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e049c VA: 0x75988f849c
	private static Void .cctor() { }
}
```