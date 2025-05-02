# NamespaceList

**Namespace:** `System.Xml.Schema`


## Fields

- `ListType type`

- `Hashtable set`

- `String targetNamespace`


## Properties

- `ListType Type`

- `String Excluded`

- `ICollection Enumerate`


## Methods

- `ListType get_Type()`

- `String get_Excluded()`

- `ICollection get_Enumerate()`

- `Boolean Allows(XmlQualifiedName)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class NamespaceList
{
	private ListType type; // 0x10
	private Hashtable set; // 0x18
	private String targetNamespace; // 0x20

	public ListType Type { get; }
	public String Excluded { get; }
	public ICollection Enumerate { get; }

	// RVA: 0x62ea684 VA: 0x7598902684
	public Void .ctor() { }
	// RVA: 0x62ea68c VA: 0x759890268c
	public Void .ctor(String namespaces, String targetNamespace) { }
	// RVA: 0x62ea944 VA: 0x7598902944
	public ListType get_Type() { }
	// RVA: 0x62ea94c VA: 0x759890294c
	public String get_Excluded() { }
	// RVA: 0x62ea954 VA: 0x7598902954
	public ICollection get_Enumerate() { }
	// RVA: 0x62ea9c0 VA: 0x75989029c0
	public virtual Boolean Allows(String ns) { }
	// RVA: 0x62eaa44 VA: 0x7598902a44
	public Boolean Allows(XmlQualifiedName qname) { }
	// RVA: 0x62eaa64 VA: 0x7598902a64
	public override String ToString() { }
}
```