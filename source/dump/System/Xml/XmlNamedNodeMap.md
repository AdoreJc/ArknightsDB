# XmlNamedNodeMap

**Namespace:** `System.Xml`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlNamedNodeMap : IEnumerable
{
	internal XmlNode parent; // 0x10
	internal SmallXmlNodeList nodes; // 0x18

	public virtual Int32 Count { get; }

	// RVA: 0x62ad8fc VA: 0x75988c58fc
	internal Void .ctor(XmlNode parent) { }
	// RVA: 0x62b4790 VA: 0x75988cc790
	public virtual XmlNode GetNamedItem(String name) { }
	// RVA: 0x62b49ec VA: 0x75988cc9ec
	public virtual XmlNode SetNamedItem(XmlNode node) { }
	// RVA: 0x62b4c20 VA: 0x75988ccc20
	public virtual Int32 get_Count() { }
	// RVA: 0x62b4ccc VA: 0x75988ccccc
	public virtual IEnumerator GetEnumerator() { }
	// RVA: 0x62b4828 VA: 0x75988cc828
	internal Int32 FindNodeOffset(String name) { }
	// RVA: 0x62b4aa8 VA: 0x75988ccaa8
	internal Int32 FindNodeOffset(String localName, String namespaceURI) { }
	// RVA: 0x62b4de0 VA: 0x75988ccde0
	internal virtual XmlNode AddNode(XmlNode node) { }
	// RVA: 0x62b5084 VA: 0x75988cd084
	internal virtual XmlNode AddNodeForLoad(XmlNode node, XmlDocument doc) { }
	// RVA: 0x62b512c VA: 0x75988cd12c
	internal virtual XmlNode RemoveNodeAt(Int32 i) { }
	// RVA: 0x62b4bcc VA: 0x75988ccbcc
	internal XmlNode ReplaceNodeAt(Int32 i, XmlNode node) { }
	// RVA: 0x62b5380 VA: 0x75988cd380
	internal virtual XmlNode InsertNodeAt(Int32 i, XmlNode node) { }
}
```