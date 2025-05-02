# XmlNumeric10Converter

**Namespace:** `System.Xml.Schema`


## Methods

- `Object ChangeTypeWildcardDestination(Object, Type, IXmlNamespaceResolver)`

- `Object ChangeTypeWildcardSource(Object, Type, IXmlNamespaceResolver)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class XmlNumeric10Converter : XmlBaseConverter
{


	// RVA: 0x62f69ec VA: 0x759890e9ec
	protected Void .ctor(XmlSchemaType schemaType) { }
	// RVA: 0x62dee0c VA: 0x75988f6e0c
	public static XmlValueConverter Create(XmlSchemaType schemaType) { }
	// RVA: 0x62f6a50 VA: 0x759890ea50
	public override Decimal ToDecimal(String value) { }
	// RVA: 0x62f6b18 VA: 0x759890eb18
	public override Decimal ToDecimal(Object value) { }
	// RVA: 0x62f735c VA: 0x759890f35c
	public override Int32 ToInt32(Int64 value) { }
	// RVA: 0x62f73b0 VA: 0x759890f3b0
	public override Int32 ToInt32(String value) { }
	// RVA: 0x62f74b4 VA: 0x759890f4b4
	public override Int32 ToInt32(Object value) { }
	// RVA: 0x62f7898 VA: 0x759890f898
	public override Int64 ToInt64(Int32 value) { }
	// RVA: 0x62f78a0 VA: 0x759890f8a0
	public override Int64 ToInt64(String value) { }
	// RVA: 0x62f79a4 VA: 0x759890f9a4
	public override Int64 ToInt64(Object value) { }
	// RVA: 0x62f7d70 VA: 0x759890fd70
	public override String ToString(Decimal value) { }
	// RVA: 0x62f7e2c VA: 0x759890fe2c
	public override String ToString(Int32 value) { }
	// RVA: 0x62f7e84 VA: 0x759890fe84
	public override String ToString(Int64 value) { }
	// RVA: 0x62f7edc VA: 0x759890fedc
	public override String ToString(Object value, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x62f82e8 VA: 0x75989102e8
	public override Object ChangeType(Decimal value, Type destinationType) { }
	// RVA: 0x62f8b70 VA: 0x7598910b70
	public override Object ChangeType(Int32 value, Type destinationType) { }
	// RVA: 0x62f8f94 VA: 0x7598910f94
	public override Object ChangeType(Int64 value, Type destinationType) { }
	// RVA: 0x62f93c4 VA: 0x75989113c4
	public override Object ChangeType(String value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x62f97f8 VA: 0x75989117f8
	public override Object ChangeType(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x62f6efc VA: 0x759890eefc
	private Object ChangeTypeWildcardDestination(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x62f8724 VA: 0x7598910724
	private Object ChangeTypeWildcardSource(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
}
```