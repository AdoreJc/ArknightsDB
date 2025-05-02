# NamespacePrefixForQName

**Namespace:** ` `


## Fields

- `String prefix`

- `String ns`


## Methods

- `String LookupNamespace(String)`

- `String LookupPrefix(String)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : 
private class NamespacePrefixForQName : IXmlNamespaceResolver
{
	public String prefix; // 0x10
	public String ns; // 0x18


	// RVA: 0x62ed1dc VA: 0x75989051dc
	public Void .ctor(String prefix, String ns) { }
	// RVA: 0x62edee8 VA: 0x7598905ee8
	public String LookupNamespace(String prefix) { }
	// RVA: 0x62edf1c VA: 0x7598905f1c
	public String LookupPrefix(String namespaceName) { }
}
```