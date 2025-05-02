# Datatype_byte

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_byte : Datatype_short
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8
	private static readonly FacetsChecker numeric10FacetsChecker; // 0x10

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }

	// RVA: 0x62e385c VA: 0x75988fb85c
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e38b4 VA: 0x75988fb8b4
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e38bc VA: 0x75988fb8bc
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e3950 VA: 0x75988fb950
	public override Type get_ValueType() { }
	// RVA: 0x62e39a8 VA: 0x75988fb9a8
	internal override Type get_ListValueType() { }
	// RVA: 0x62e3a00 VA: 0x75988fba00
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e3b54 VA: 0x75988fbb54
	public Void .ctor() { }
	// RVA: 0x62e3ba8 VA: 0x75988fbba8
	private static Void .cctor() { }
}
```