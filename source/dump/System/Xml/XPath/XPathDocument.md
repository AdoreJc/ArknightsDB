# XPathDocument

**Namespace:** `System.Xml.XPath`


## Fields

- `Int32 idxXmlNmsp`

- `XmlNameTable nameTable`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.XPath
public class XPathDocument
{
	private XPathNode[] pageXmlNmsp; // 0x10
	private Int32 idxXmlNmsp; // 0x18
	private XmlNameTable nameTable; // 0x20
	private Dictionary`2 mapNmsp; // 0x28

	internal XmlNameTable NameTable { get; }

	// RVA: 0x62d0590 VA: 0x75988e8590
	internal XmlNameTable get_NameTable() { }
	// RVA: 0x62d0598 VA: 0x75988e8598
	internal Int32 GetXmlNamespaceNode(out XPathNode[] pageXmlNmsp) { }
	// RVA: 0x62d05c0 VA: 0x75988e85c0
	internal Int32 LookupNamespaces(XPathNode[] pageElem, Int32 idxElem, out XPathNode[] pageNmsp) { }
}
```