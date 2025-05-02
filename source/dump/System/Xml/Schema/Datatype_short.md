# Datatype_short

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_short : Datatype_int
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8
	private static readonly FacetsChecker numeric10FacetsChecker; // 0x10

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }

	// RVA: 0x62e3384 VA: 0x75988fb384
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e33dc VA: 0x75988fb3dc
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e33e4 VA: 0x75988fb3e4
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e3478 VA: 0x75988fb478
	public override Type get_ValueType() { }
	// RVA: 0x62e34d0 VA: 0x75988fb4d0
	internal override Type get_ListValueType() { }
	// RVA: 0x62e3528 VA: 0x75988fb528
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e367c VA: 0x75988fb67c
	public Void .ctor() { }
	// RVA: 0x62e36d0 VA: 0x75988fb6d0
	private static Void .cctor() { }
}
```