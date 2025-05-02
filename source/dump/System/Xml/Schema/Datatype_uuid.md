# Datatype_uuid

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_uuid : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	public override Type ValueType { get; }
	internal override Type ListValueType { get; }

	// RVA: 0x62e6ac0 VA: 0x75988feac0
	public override Type get_ValueType() { }
	// RVA: 0x62e6b18 VA: 0x75988feb18
	internal override Type get_ListValueType() { }
	// RVA: 0x62e6b70 VA: 0x75988feb70
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e6c0c VA: 0x75988fec0c
	public override Object ParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr) { }
	// RVA: 0x62e6de0 VA: 0x75988fede0
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e6eac VA: 0x75988feeac
	public Void .ctor() { }
	// RVA: 0x62e6f00 VA: 0x75988fef00
	private static Void .cctor() { }
}
```