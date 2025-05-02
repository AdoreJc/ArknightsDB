# XmlUntypedConverter

**Namespace:** `System.Xml.Schema`


## Fields

- `Boolean allowListToList`


## Methods

- `Object ChangeTypeWildcardDestination(Object, Type, IXmlNamespaceResolver)`

- `Object ChangeTypeWildcardSource(Object, Type, IXmlNamespaceResolver)`

- `Boolean SupportsType(Type)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class XmlUntypedConverter : XmlListConverter
{
	private Boolean allowListToList; // 0x30
	public static readonly XmlValueConverter Untyped; // 0x0
	public static readonly XmlValueConverter UntypedList; // 0x8


	// RVA: 0x6302940 VA: 0x759891a940
	protected Void .ctor() { }
	// RVA: 0x6302a38 VA: 0x759891aa38
	protected Void .ctor(XmlUntypedConverter atomicConverter, Boolean allowListToList) { }
	// RVA: 0x6302b50 VA: 0x759891ab50
	public override Boolean ToBoolean(String value) { }
	// RVA: 0x6302bf8 VA: 0x759891abf8
	public override Boolean ToBoolean(Object value) { }
	// RVA: 0x6302f04 VA: 0x759891af04
	public override DateTime ToDateTime(String value) { }
	// RVA: 0x6302fac VA: 0x759891afac
	public override DateTime ToDateTime(Object value) { }
	// RVA: 0x6303164 VA: 0x759891b164
	public override DateTimeOffset ToDateTimeOffset(String value) { }
	// RVA: 0x630320c VA: 0x759891b20c
	public override DateTimeOffset ToDateTimeOffset(Object value) { }
	// RVA: 0x63033c4 VA: 0x759891b3c4
	public override Decimal ToDecimal(String value) { }
	// RVA: 0x630346c VA: 0x759891b46c
	public override Decimal ToDecimal(Object value) { }
	// RVA: 0x630363c VA: 0x759891b63c
	public override Double ToDouble(String value) { }
	// RVA: 0x63036e4 VA: 0x759891b6e4
	public override Double ToDouble(Object value) { }
	// RVA: 0x63038b4 VA: 0x759891b8b4
	public override Int32 ToInt32(String value) { }
	// RVA: 0x630395c VA: 0x759891b95c
	public override Int32 ToInt32(Object value) { }
	// RVA: 0x6303b2c VA: 0x759891bb2c
	public override Int64 ToInt64(String value) { }
	// RVA: 0x6303bd4 VA: 0x759891bbd4
	public override Int64 ToInt64(Object value) { }
	// RVA: 0x6303da4 VA: 0x759891bda4
	public override Single ToSingle(String value) { }
	// RVA: 0x6303e4c VA: 0x759891be4c
	public override Single ToSingle(Object value) { }
	// RVA: 0x630401c VA: 0x759891c01c
	public override String ToString(Boolean value) { }
	// RVA: 0x6304074 VA: 0x759891c074
	public override String ToString(DateTime value) { }
	// RVA: 0x63040cc VA: 0x759891c0cc
	public override String ToString(DateTimeOffset value) { }
	// RVA: 0x6304134 VA: 0x759891c134
	public override String ToString(Decimal value) { }
	// RVA: 0x630419c VA: 0x759891c19c
	public override String ToString(Double value) { }
	// RVA: 0x63041fc VA: 0x759891c1fc
	public override String ToString(Int32 value) { }
	// RVA: 0x6304254 VA: 0x759891c254
	public override String ToString(Int64 value) { }
	// RVA: 0x63042ac VA: 0x759891c2ac
	public override String ToString(Single value) { }
	// RVA: 0x630430c VA: 0x759891c30c
	public override String ToString(Object value, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x63050b4 VA: 0x759891d0b4
	public override Object ChangeType(Boolean value, Type destinationType) { }
	// RVA: 0x6305430 VA: 0x759891d430
	public override Object ChangeType(DateTime value, Type destinationType) { }
	// RVA: 0x63055fc VA: 0x759891d5fc
	public override Object ChangeType(Decimal value, Type destinationType) { }
	// RVA: 0x6305808 VA: 0x759891d808
	public override Object ChangeType(Double value, Type destinationType) { }
	// RVA: 0x63059e8 VA: 0x759891d9e8
	public override Object ChangeType(Int32 value, Type destinationType) { }
	// RVA: 0x6305bc8 VA: 0x759891dbc8
	public override Object ChangeType(Int64 value, Type destinationType) { }
	// RVA: 0x6305da8 VA: 0x759891dda8
	public override Object ChangeType(String value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x63069b0 VA: 0x759891e9b0
	public override Object ChangeType(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x6302dc8 VA: 0x759891adc8
	private Object ChangeTypeWildcardDestination(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x6305298 VA: 0x759891d298
	private Object ChangeTypeWildcardSource(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x6307eac VA: 0x759891feac
	protected override Object ChangeListType(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x63081b4 VA: 0x75989201b4
	private Boolean SupportsType(Type clrType) { }
	// RVA: 0x63094dc VA: 0x75989214dc
	private static Void .cctor() { }
}
```