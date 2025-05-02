# Datatype_QNameXdr

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Datatype_QNameXdr : Datatype_anySimpleType
{
	private static readonly Type atomicValueType; // 0x0
	private static readonly Type listValueType; // 0x8

	public override XmlTokenizedType TokenizedType { get; }
	public override Type ValueType { get; }
	internal override Type ListValueType { get; }

	// RVA: 0x62e5a3c VA: 0x75988fda3c
	public override XmlTokenizedType get_TokenizedType() { }
	// RVA: 0x62e5a44 VA: 0x75988fda44
	public override Object ParseValue(String s, XmlNameTable nameTable, IXmlNamespaceResolver nsmgr) { }
	// RVA: 0x62e5cb8 VA: 0x75988fdcb8
	public override Type get_ValueType() { }
	// RVA: 0x62e5d10 VA: 0x75988fdd10
	internal override Type get_ListValueType() { }
	// RVA: 0x62e5d68 VA: 0x75988fdd68
	public Void .ctor() { }
	// RVA: 0x62e5dbc VA: 0x75988fddbc
	private static Void .cctor() { }
}
```