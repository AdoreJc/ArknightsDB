# Datatype_unsignedShort

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_unsignedShort : Datatype_unsignedInt
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8
	private static readonly FacetsChecker numeric10FacetsChecker; // 0x10

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }

	// RVA: 0x62e48dc VA: 0x75988fc8dc
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e4934 VA: 0x75988fc934
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e493c VA: 0x75988fc93c
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e49d0 VA: 0x75988fc9d0
	public override Type get_ValueType() { }
	// RVA: 0x62e4a28 VA: 0x75988fca28
	internal override Type get_ListValueType() { }
	// RVA: 0x62e4a80 VA: 0x75988fca80
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e4bd4 VA: 0x75988fcbd4
	public Void .ctor() { }
	// RVA: 0x62e4c28 VA: 0x75988fcc28
	private static Void .cctor() { }
}
```