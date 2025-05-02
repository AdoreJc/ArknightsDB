# XDocumentWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Properties

- `XDocument Document`

- `IXmlElement DocumentElement`


## Methods

- `XDocument get_Document()`

- `IXmlNode CreateComment(String)`

- `IXmlNode CreateTextNode(String)`

- `IXmlNode CreateCDataSection(String)`

- `IXmlNode CreateWhitespace(String)`

- `IXmlNode CreateSignificantWhitespace(String)`

- `IXmlNode CreateXmlDeclaration(String, String, String)`

- `IXmlNode CreateXmlDocumentType(String, String, String, String)`

- `IXmlNode CreateProcessingInstruction(String, String)`

- `IXmlElement CreateElement(String)`

- `IXmlElement CreateElement(String, String)`

- `IXmlNode CreateAttribute(String, String)`

- `IXmlNode CreateAttribute(String, String, String)`

- `IXmlElement get_DocumentElement()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
internal class XDocumentWrapper : XContainerWrapper, IXmlDocument, IXmlNode
{

	private XDocument Document { get; }
	public override List`1 ChildNodes { get; }
	public IXmlElement DocumentElement { get; }

	// RVA: 0x61acb7c VA: 0x75987c4b7c
	private XDocument get_Document() { }
	// RVA: 0x61acbf4 VA: 0x75987c4bf4
	public Void .ctor(XDocument document) { }
	// RVA: 0x61acc6c VA: 0x75987c4c6c
	public override List`1 get_ChildNodes() { }
	// RVA: 0x61ad19c VA: 0x75987c519c
	public IXmlNode CreateComment(String text) { }
	// RVA: 0x61ad23c VA: 0x75987c523c
	public IXmlNode CreateTextNode(String text) { }
	// RVA: 0x61ad2dc VA: 0x75987c52dc
	public IXmlNode CreateCDataSection(String data) { }
	// RVA: 0x61ad37c VA: 0x75987c537c
	public IXmlNode CreateWhitespace(String text) { }
	// RVA: 0x61ad41c VA: 0x75987c541c
	public IXmlNode CreateSignificantWhitespace(String text) { }
	// RVA: 0x61ad4bc VA: 0x75987c54bc
	public IXmlNode CreateXmlDeclaration(String version, String encoding, String standalone) { }
	// RVA: 0x61ad564 VA: 0x75987c5564
	public IXmlNode CreateXmlDocumentType(String name, String publicId, String systemId, String internalSubset) { }
	// RVA: 0x61ad61c VA: 0x75987c561c
	public IXmlNode CreateProcessingInstruction(String target, String data) { }
	// RVA: 0x61ad730 VA: 0x75987c5730
	public IXmlElement CreateElement(String elementName) { }
	// RVA: 0x61ad7d8 VA: 0x75987c57d8
	public IXmlElement CreateElement(String qualifiedName, String namespaceUri) { }
	// RVA: 0x61ad894 VA: 0x75987c5894
	public IXmlNode CreateAttribute(String name, String value) { }
	// RVA: 0x61ad9bc VA: 0x75987c59bc
	public IXmlNode CreateAttribute(String qualifiedName, String namespaceUri, String value) { }
	// RVA: 0x61ada80 VA: 0x75987c5a80
	public IXmlElement get_DocumentElement() { }
	// RVA: 0x61adb1c VA: 0x75987c5b1c
	public override IXmlNode AppendChild(IXmlNode newChild) { }
}
```