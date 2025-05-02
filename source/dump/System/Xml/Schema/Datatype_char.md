# Datatype_char

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_char : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	public override Type ValueType { get; }
	internal override Type ListValueType { get; }

	// RVA: 0x62e5e9c VA: 0x75988fde9c
	public override Type get_ValueType() { }
	// RVA: 0x62e5ef4 VA: 0x75988fdef4
	internal override Type get_ListValueType() { }
	// RVA: 0x62e5f4c VA: 0x75988fdf4c
	internal override Int32 Compare(Object value1, Object value2) { }
	// RVA: 0x62e5ff0 VA: 0x75988fdff0
	public override Object ParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr) { }
	// RVA: 0x62e61c4 VA: 0x75988fe1c4
	internal override Exception TryParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr, out Object typedValue) { }
	// RVA: 0x62e6288 VA: 0x75988fe288
	public Void .ctor() { }
	// RVA: 0x62e62dc VA: 0x75988fe2dc
	private static Void .cctor() { }
}
```