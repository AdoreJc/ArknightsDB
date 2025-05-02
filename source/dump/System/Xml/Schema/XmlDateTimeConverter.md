# XmlDateTimeConverter

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class XmlDateTimeConverter : XmlBaseConverter
{


	// RVA: 0x62fc1fc VA: 0x75989141fc
	protected Void .ctor(XmlSchemaType schemaType) { }
	// RVA: 0x62dfe20 VA: 0x75988f7e20
	public static XmlValueConverter Create(XmlSchemaType schemaType) { }
	// RVA: 0x62fc260 VA: 0x7598914260
	public override DateTime ToDateTime(DateTimeOffset value) { }
	// RVA: 0x62fc2c4 VA: 0x75989142c4
	public override DateTime ToDateTime(String value) { }
	// RVA: 0x62fc474 VA: 0x7598914474
	public override DateTime ToDateTime(Object value) { }
	// RVA: 0x62fc7d0 VA: 0x75989147d0
	public override DateTimeOffset ToDateTimeOffset(DateTime value) { }
	// RVA: 0x62fc7f8 VA: 0x75989147f8
	public override DateTimeOffset ToDateTimeOffset(String value) { }
	// RVA: 0x62fc9a8 VA: 0x75989149a8
	public override DateTimeOffset ToDateTimeOffset(Object value) { }
	// RVA: 0x62fcd08 VA: 0x7598914d08
	public override String ToString(DateTime value) { }
	// RVA: 0x62fce68 VA: 0x7598914e68
	public override String ToString(DateTimeOffset value) { }
	// RVA: 0x62fd010 VA: 0x7598915010
	public override String ToString(Object value, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x62fd368 VA: 0x7598915368
	public override Object ChangeType(DateTime value, Type destinationType) { }
	// RVA: 0x62fd6fc VA: 0x75989156fc
	public override Object ChangeType(String value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x62fdaa8 VA: 0x7598915aa8
	public override Object ChangeType(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
}
```