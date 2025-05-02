# NamespaceResolverProxy

**Namespace:** ` `


## Fields

- `XmlWellFormedWriter wfWriter`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : 
private class NamespaceResolverProxy : IXmlNamespaceResolver
{
	private XmlWellFormedWriter wfWriter; // 0x10


	// RVA: 0x629cbd8 VA: 0x75988b4bd8
	internal Void .ctor(XmlWellFormedWriter wfWriter) { }
	// RVA: 0x62a455c VA: 0x75988bc55c
	private String System.Xml.IXmlNamespaceResolver.LookupNamespace(String prefix) { }
	// RVA: 0x62a4574 VA: 0x75988bc574
	private String System.Xml.IXmlNamespaceResolver.LookupPrefix(String namespaceName) { }
}
```