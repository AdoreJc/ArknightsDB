# Datatype_long

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_long : Datatype_integer
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8
	private static readonly FacetsChecker numeric10FacetsChecker; // 0x10

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }

	// RVA: 0x62e2a24 VA: 0x75988faa24
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e2a7c VA: 0x75988faa7c
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e2a84 VA: 0x75988faa84
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e2b18 VA: 0x75988fab18
	public override Type get_ValueType() { }
	// RVA: 0x62e2b70 VA: 0x75988fab70
	internal override Type get_ListValueType() { }
	// RVA: 0x62e2bc8 VA: 0x75988fabc8
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e2d1c VA: 0x75988fad1c
	public Void .ctor() { }
	// RVA: 0x62e2d20 VA: 0x75988fad20
	private static Void .cctor() { }
}
```