# XmlLoader

**Namespace:** `System.Xml`


## Fields

- `XmlDocument doc`

- `XmlReader reader`

- `Boolean preserveWhitespace`


## Methods

- `Void LoadDocSequence(XmlDocument)`

- `XmlNode LoadNode(Boolean)`

- `XmlAttribute LoadAttributeNode()`

- `XmlAttribute LoadDefaultAttribute()`

- `Void LoadAttributeValue(XmlNode, Boolean)`

- `XmlEntityReference LoadEntityReferenceNode(Boolean)`

- `XmlDeclaration LoadDeclarationNode()`

- `XmlDocumentType LoadDocumentTypeNode()`

- `XmlNode LoadNodeDirect()`

- `XmlAttribute LoadAttributeNodeDirect()`

- `Void ParseDocumentType(XmlDocumentType, Boolean, XmlResolver)`

- `Void LoadDocumentType(IDtdInfo, XmlDocumentType)`

- `XmlParserContext GetContext(XmlNode)`

- `Void RemoveDuplicateNamespace(XmlElement, XmlNamespaceManager, Boolean)`

- `String EntitizeName(String)`

- `XmlReader CreateInnerXmlReader(String, XmlNodeType, XmlParserContext, XmlDocument)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class XmlLoader
{
	private XmlDocument doc; // 0x10
	private XmlReader reader; // 0x18
	private Boolean preserveWhitespace; // 0x20


	// RVA: 0x62ad2e4 VA: 0x75988c52e4
	public Void .ctor() { }
	// RVA: 0x62afd80 VA: 0x75988c7d80
	internal Void Load(XmlDocument doc, XmlReader reader, Boolean preserveWhitespace) { }
	// RVA: 0x62afff4 VA: 0x75988c7ff4
	private Void LoadDocSequence(XmlDocument parentDoc) { }
	// RVA: 0x62b0060 VA: 0x75988c8060
	private XmlNode LoadNode(Boolean skipOverWhitespace) { }
	// RVA: 0x62b05ec VA: 0x75988c85ec
	private XmlAttribute LoadAttributeNode() { }
	// RVA: 0x62b0f84 VA: 0x75988c8f84
	private XmlAttribute LoadDefaultAttribute() { }
	// RVA: 0x62b112c VA: 0x75988c912c
	private Void LoadAttributeValue(XmlNode parent, Boolean direct) { }
	// RVA: 0x62b0928 VA: 0x75988c8928
	private XmlEntityReference LoadEntityReferenceNode(Boolean direct) { }
	// RVA: 0x62b0b1c VA: 0x75988c8b1c
	private XmlDeclaration LoadDeclarationNode() { }
	// RVA: 0x62b0cc0 VA: 0x75988c8cc0
	private XmlDocumentType LoadDocumentTypeNode() { }
	// RVA: 0x62b145c VA: 0x75988c945c
	private XmlNode LoadNodeDirect() { }
	// RVA: 0x62b2694 VA: 0x75988ca694
	private XmlAttribute LoadAttributeNodeDirect() { }
	// RVA: 0x62ad7ac VA: 0x75988c57ac
	internal Void ParseDocumentType(XmlDocumentType dtNode) { }
	// RVA: 0x62b2980 VA: 0x75988ca980
	private Void ParseDocumentType(XmlDocumentType dtNode, Boolean bUseResolver, XmlResolver resolver) { }
	// RVA: 0x62b1b28 VA: 0x75988c9b28
	private Void LoadDocumentType(IDtdInfo dtdInfo, XmlDocumentType dtNode) { }
	// RVA: 0x62b2d48 VA: 0x75988cad48
	private XmlParserContext GetContext(XmlNode node) { }
	// RVA: 0x62ad2ec VA: 0x75988c52ec
	internal XmlNamespaceManager ParsePartialContent(XmlNode parentNode, String innerxmltext, XmlNodeType nt) { }
	// RVA: 0x62ae9dc VA: 0x75988c69dc
	internal Void LoadInnerXmlElement(XmlElement node, String innerxmltext) { }
	// RVA: 0x62b3b3c VA: 0x75988cbb3c
	internal Void LoadInnerXmlAttribute(XmlAttribute node, String innerxmltext) { }
	// RVA: 0x62b38ac VA: 0x75988cb8ac
	private Void RemoveDuplicateNamespace(XmlElement elem, XmlNamespaceManager mgr, Boolean fCheckElemAttrs) { }
	// RVA: 0x62b3b44 VA: 0x75988cbb44
	private String EntitizeName(String name) { }
	// RVA: 0x62aef18 VA: 0x75988c6f18
	internal Void ExpandEntity(XmlEntity ent) { }
	// RVA: 0x62af2e8 VA: 0x75988c72e8
	internal Void ExpandEntityReference(XmlEntityReference eref) { }
	// RVA: 0x62b3620 VA: 0x75988cb620
	private XmlReader CreateInnerXmlReader(String xmlFragment, XmlNodeType nt, XmlParserContext context, XmlDocument doc) { }
	// RVA: 0x62b18e0 VA: 0x75988c98e0
	internal static Void ParseXmlDeclarationValue(String strValue, out String version, out String encoding, out String standalone) { }
	// RVA: 0x62b0e6c VA: 0x75988c8e6c
	internal static Exception UnexpectedNodeType(XmlNodeType nodetype) { }
}
```