# Datatype_unsignedLong

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_unsignedLong : Datatype_nonNegativeInteger
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8
	private static readonly FacetsChecker numeric10FacetsChecker; // 0x10

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }

	// RVA: 0x62e3eb8 VA: 0x75988fbeb8
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e3f10 VA: 0x75988fbf10
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e3f18 VA: 0x75988fbf18
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e3fac VA: 0x75988fbfac
	public override Type get_ValueType() { }
	// RVA: 0x62e4004 VA: 0x75988fc004
	internal override Type get_ListValueType() { }
	// RVA: 0x62e405c VA: 0x75988fc05c
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e41f4 VA: 0x75988fc1f4
	public Void .ctor() { }
	// RVA: 0x62e4248 VA: 0x75988fc248
	private static Void .cctor() { }
}
```