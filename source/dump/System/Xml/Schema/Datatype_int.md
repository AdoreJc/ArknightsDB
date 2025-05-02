# Datatype_int

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_int : Datatype_long
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8
	private static readonly FacetsChecker numeric10FacetsChecker; // 0x10

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }

	// RVA: 0x62e2eac VA: 0x75988faeac
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e2f04 VA: 0x75988faf04
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e2f0c VA: 0x75988faf0c
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e2fa0 VA: 0x75988fafa0
	public override Type get_ValueType() { }
	// RVA: 0x62e2ff8 VA: 0x75988faff8
	internal override Type get_ListValueType() { }
	// RVA: 0x62e3050 VA: 0x75988fb050
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e31a4 VA: 0x75988fb1a4
	public Void .ctor() { }
	// RVA: 0x62e31f8 VA: 0x75988fb1f8
	private static Void .cctor() { }
}
```