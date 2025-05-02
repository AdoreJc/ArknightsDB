# XmlAnyConverter

**Namespace:** `System.Xml.Schema`


## Methods

- `Object ChangeTypeWildcardDestination(Object, Type, IXmlNamespaceResolver)`

- `Object ChangeTypeWildcardSource(Object, Type, IXmlNamespaceResolver)`

- `XPathNavigator ToNavigator(XPathNavigator)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class XmlAnyConverter : XmlBaseConverter
{
	public static readonly XmlValueConverter Item; // 0x0
	public static readonly XmlValueConverter AnyAtomic; // 0x8


	// RVA: 0x63095a8 VA: 0x75989215a8
	protected Void .ctor(XmlTypeCode typeCode) { }
	// RVA: 0x6309610 VA: 0x7598921610
	public override Boolean ToBoolean(Object value) { }
	// RVA: 0x6309900 VA: 0x7598921900
	public override DateTime ToDateTime(Object value) { }
	// RVA: 0x6309ab4 VA: 0x7598921ab4
	public override DateTimeOffset ToDateTimeOffset(Object value) { }
	// RVA: 0x6309c78 VA: 0x7598921c78
	public override Decimal ToDecimal(Object value) { }
	// RVA: 0x6309e3c VA: 0x7598921e3c
	public override Double ToDouble(Object value) { }
	// RVA: 0x6309ff0 VA: 0x7598921ff0
	public override Int32 ToInt32(Object value) { }
	// RVA: 0x630a1a4 VA: 0x75989221a4
	public override Int64 ToInt64(Object value) { }
	// RVA: 0x630a358 VA: 0x7598922358
	public override Single ToSingle(Object value) { }
	// RVA: 0x630a518 VA: 0x7598922518
	public override Object ChangeType(Boolean value, Type destinationType) { }
	// RVA: 0x630a878 VA: 0x7598922878
	public override Object ChangeType(DateTime value, Type destinationType) { }
	// RVA: 0x630aa70 VA: 0x7598922a70
	public override Object ChangeType(Decimal value, Type destinationType) { }
	// RVA: 0x630acb0 VA: 0x7598922cb0
	public override Object ChangeType(Double value, Type destinationType) { }
	// RVA: 0x630aea8 VA: 0x7598922ea8
	public override Object ChangeType(Int32 value, Type destinationType) { }
	// RVA: 0x630b0a0 VA: 0x75989230a0
	public override Object ChangeType(Int64 value, Type destinationType) { }
	// RVA: 0x630b298 VA: 0x7598923298
	public override Object ChangeType(String value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x630b4a0 VA: 0x75989234a0
	public override Object ChangeType(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x63097c4 VA: 0x75989217c4
	private Object ChangeTypeWildcardDestination(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x630a714 VA: 0x7598922714
	private Object ChangeTypeWildcardSource(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x630c994 VA: 0x7598924994
	private XPathNavigator ToNavigator(XPathNavigator nav) { }
	// RVA: 0x630ca1c VA: 0x7598924a1c
	private static Void .cctor() { }
}
```