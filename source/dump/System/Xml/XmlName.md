# XmlName

**Namespace:** `System.Xml`


## Fields

- `String prefix`

- `String localName`

- `String ns`

- `String name`

- `Int32 hashCode`


## Properties

- `String LocalName`

- `String NamespaceURI`

- `String Prefix`

- `Int32 HashCode`

- `XmlDocument OwnerDocument`

- `String Name`


## Methods

- `String get_LocalName()`

- `String get_NamespaceURI()`

- `String get_Prefix()`

- `Int32 get_HashCode()`

- `XmlDocument get_OwnerDocument()`

- `String get_Name()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class XmlName : IXmlSchemaInfo
{
	private String prefix; // 0x10
	private String localName; // 0x18
	private String ns; // 0x20
	private String name; // 0x28
	private Int32 hashCode; // 0x30
	internal XmlDocument ownerDoc; // 0x38
	internal XmlName next; // 0x40

	public String LocalName { get; }
	public String NamespaceURI { get; }
	public String Prefix { get; }
	public Int32 HashCode { get; }
	public XmlDocument OwnerDocument { get; }
	public String Name { get; }
	public virtual XmlSchemaValidity Validity { get; }
	public virtual Boolean IsDefault { get; }
	public virtual Boolean IsNil { get; }
	public virtual XmlSchemaSimpleType MemberType { get; }
	public virtual XmlSchemaType SchemaType { get; }
	public virtual XmlSchemaElement SchemaElement { get; }
	public virtual XmlSchemaAttribute SchemaAttribute { get; }

	// RVA: 0x62b3bbc VA: 0x75988cbbbc
	public static XmlName Create(String prefix, String localName, String ns, Int32 hashCode, XmlDocument ownerDoc, XmlName next, IXmlSchemaInfo schemaInfo) { }
	// RVA: 0x62b3cb4 VA: 0x75988cbcb4
	internal Void .ctor(String prefix, String localName, String ns, Int32 hashCode, XmlDocument ownerDoc, XmlName next) { }
	// RVA: 0x62b4150 VA: 0x75988cc150
	public String get_LocalName() { }
	// RVA: 0x62b4158 VA: 0x75988cc158
	public String get_NamespaceURI() { }
	// RVA: 0x62b4160 VA: 0x75988cc160
	public String get_Prefix() { }
	// RVA: 0x62b4168 VA: 0x75988cc168
	public Int32 get_HashCode() { }
	// RVA: 0x62b4170 VA: 0x75988cc170
	public XmlDocument get_OwnerDocument() { }
	// RVA: 0x62ae198 VA: 0x75988c6198
	public String get_Name() { }
	// RVA: 0x62b4178 VA: 0x75988cc178
	public virtual XmlSchemaValidity get_Validity() { }
	// RVA: 0x62b4180 VA: 0x75988cc180
	public virtual Boolean get_IsDefault() { }
	// RVA: 0x62b4188 VA: 0x75988cc188
	public virtual Boolean get_IsNil() { }
	// RVA: 0x62b4190 VA: 0x75988cc190
	public virtual XmlSchemaSimpleType get_MemberType() { }
	// RVA: 0x62b4198 VA: 0x75988cc198
	public virtual XmlSchemaType get_SchemaType() { }
	// RVA: 0x62b41a0 VA: 0x75988cc1a0
	public virtual XmlSchemaElement get_SchemaElement() { }
	// RVA: 0x62b41a8 VA: 0x75988cc1a8
	public virtual XmlSchemaAttribute get_SchemaAttribute() { }
	// RVA: 0x62b41b0 VA: 0x75988cc1b0
	public virtual Boolean Equals(IXmlSchemaInfo schemaInfo) { }
	// RVA: 0x62b41bc VA: 0x75988cc1bc
	public static Int32 GetHashCode(String name) { }
}
```