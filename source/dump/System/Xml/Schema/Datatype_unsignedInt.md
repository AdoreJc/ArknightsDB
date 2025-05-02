# Datatype_unsignedInt

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_unsignedInt : Datatype_unsignedLong
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8
	private static readonly FacetsChecker numeric10FacetsChecker; // 0x10

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }

	// RVA: 0x62e43ec VA: 0x75988fc3ec
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e4444 VA: 0x75988fc444
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e444c VA: 0x75988fc44c
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e44e0 VA: 0x75988fc4e0
	public override Type get_ValueType() { }
	// RVA: 0x62e4538 VA: 0x75988fc538
	internal override Type get_ListValueType() { }
	// RVA: 0x62e4590 VA: 0x75988fc590
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e46e4 VA: 0x75988fc6e4
	public Void .ctor() { }
	// RVA: 0x62e4738 VA: 0x75988fc738
	private static Void .cctor() { }
}
```