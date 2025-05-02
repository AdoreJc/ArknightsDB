# XmlNamespaceManager

**Namespace:** `System.Xml`


## Fields

- `Int32 lastDecl`

- `XmlNameTable nameTable`

- `Int32 scopeId`

- `Boolean useHashtable`

- `String xml`

- `String xmlNs`


## Methods

- `Int32 LookupNamespaceDecl(String)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlNamespaceManager : IXmlNamespaceResolver, IEnumerable
{
	private NamespaceDeclaration[] nsdecls; // 0x10
	private Int32 lastDecl; // 0x18
	private XmlNameTable nameTable; // 0x20
	private Int32 scopeId; // 0x28
	private Dictionary`2 hashTable; // 0x30
	private Boolean useHashtable; // 0x38
	private String xml; // 0x40
	private String xmlNs; // 0x48

	public virtual XmlNameTable NameTable { get; }
	public virtual String DefaultNamespace { get; }

	// RVA: 0x62ce2d0 VA: 0x75988e62d0
	internal Void .ctor() { }
	// RVA: 0x62ce2d8 VA: 0x75988e62d8
	public Void .ctor(XmlNameTable nameTable) { }
	// RVA: 0x62ce588 VA: 0x75988e6588
	public virtual XmlNameTable get_NameTable() { }
	// RVA: 0x62ce590 VA: 0x75988e6590
	public virtual String get_DefaultNamespace() { }
	// RVA: 0x62ce600 VA: 0x75988e6600
	public virtual Void PushScope() { }
	// RVA: 0x62ce610 VA: 0x75988e6610
	public virtual Boolean PopScope() { }
	// RVA: 0x62ce6e8 VA: 0x75988e66e8
	public virtual Void AddNamespace(String prefix, String uri) { }
	// RVA: 0x62cec78 VA: 0x75988e6c78
	public virtual Void RemoveNamespace(String prefix, String uri) { }
	// RVA: 0x62cedbc VA: 0x75988e6dbc
	public virtual IEnumerator GetEnumerator() { }
	// RVA: 0x62cef2c VA: 0x75988e6f2c
	public virtual String LookupNamespace(String prefix) { }
	// RVA: 0x62ceaec VA: 0x75988e6aec
	private Int32 LookupNamespaceDecl(String prefix) { }
	// RVA: 0x62cef78 VA: 0x75988e6f78
	public virtual String LookupPrefix(String uri) { }
}
```