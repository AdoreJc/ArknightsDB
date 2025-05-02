# Datatype_unsignedByte

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_unsignedByte : Datatype_unsignedShort
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8
	private static readonly FacetsChecker numeric10FacetsChecker; // 0x10

	internal override FacetsChecker FacetsChecker { get; }
	public override XmlTypeCode TypeCode { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }

	// RVA: 0x62e4dcc VA: 0x75988fcdcc
	internal override FacetsChecker get_FacetsChecker() { }
	// RVA: 0x62e4e24 VA: 0x75988fce24
	public override XmlTypeCode get_TypeCode() { }
	// RVA: 0x62e4e2c VA: 0x75988fce2c
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e4ec0 VA: 0x75988fcec0
	public override Type get_ValueType() { }
	// RVA: 0x62e4f18 VA: 0x75988fcf18
	internal override Type get_ListValueType() { }
	// RVA: 0x62e4f70 VA: 0x75988fcf70
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e50c4 VA: 0x75988fd0c4
	public Void .ctor() { }
	// RVA: 0x62e5118 VA: 0x75988fd118
	private static Void .cctor() { }
}
```