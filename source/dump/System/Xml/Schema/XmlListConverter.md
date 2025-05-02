# XmlListConverter

**Namespace:** `System.Xml.Schema`


## Fields

- `XmlValueConverter atomicConverter`


## Methods

- `Boolean IsListType(Type)`

- `IList ToList(Object, IXmlNamespaceResolver)`

- `String ListAsString(IEnumerable, IXmlNamespaceResolver)`

- `Exception CreateInvalidClrMappingException(Type, Type)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class XmlListConverter : XmlBaseConverter
{
	protected XmlValueConverter atomicConverter; // 0x28


	// RVA: 0x630cabc VA: 0x7598924abc
	protected Void .ctor(XmlBaseConverter atomicConverter) { }
	// RVA: 0x6302ad0 VA: 0x759891aad0
	protected Void .ctor(XmlBaseConverter atomicConverter, Type clrTypeDefault) { }
	// RVA: 0x63029d0 VA: 0x759891a9d0
	protected Void .ctor(XmlSchemaType schemaType) { }
	// RVA: 0x630cf04 VA: 0x7598924f04
	public static XmlValueConverter Create(XmlValueConverter atomicConverter) { }
	// RVA: 0x630d0b0 VA: 0x75989250b0
	public override Object ChangeType(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x63086e4 VA: 0x75989206e4
	protected override Object ChangeListType(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x630d1b8 VA: 0x75989251b8
	private Boolean IsListType(Type type) { }
	// RVA: 0x VA: 0x0
	private T[] ToArray(Object list, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x630da50 VA: 0x7598925a50
	private IList ToList(Object list, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x630d9a0 VA: 0x75989259a0
	private List`1 StringAsList(String value) { }
	// RVA: 0x630d5f4 VA: 0x75989255f4
	private String ListAsString(IEnumerable list, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x630d348 VA: 0x7598925348
	private Exception CreateInvalidClrMappingException(Type sourceType, Type destinationType) { }
}
```