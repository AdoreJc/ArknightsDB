# XmlMiscConverter

**Namespace:** `System.Xml.Schema`


## Methods

- `Object ChangeTypeWildcardDestination(Object, Type, IXmlNamespaceResolver)`

- `Object ChangeTypeWildcardSource(Object, Type, IXmlNamespaceResolver)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class XmlMiscConverter : XmlBaseConverter
{


	// RVA: 0x63004c4 VA: 0x75989184c4
	protected Void .ctor(XmlSchemaType schemaType) { }
	// RVA: 0x630052c VA: 0x759891852c
	public static XmlValueConverter Create(XmlSchemaType schemaType) { }
	// RVA: 0x630058c VA: 0x759891858c
	public override String ToString(Object value, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x6300c14 VA: 0x7598918c14
	public override Object ChangeType(String value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x630128c VA: 0x759891928c
	public override Object ChangeType(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x6300ad8 VA: 0x7598918ad8
	private Object ChangeTypeWildcardDestination(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x6301128 VA: 0x7598919128
	private Object ChangeTypeWildcardSource(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
}
```