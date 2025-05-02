# XmlDocumentWrapper

**Namespace:** `Newtonsoft.Json.Converters`


## Properties

- `IXmlElement DocumentElement`


## Methods

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
internal class XmlDocumentWrapper : XmlNodeWrapper, IXmlDocument, IXmlNode
{
	private readonly XmlDocument _document; // 0x28

	public IXmlElement DocumentElement { get; }

	// RVA: 0x61ab19c VA: 0x75987c319c
	public Void .ctor(XmlDocument document) { }
	// RVA: 0x61ab20c VA: 0x75987c320c
	public IXmlNode CreateComment(String data) { }
	// RVA: 0x61ab2a4 VA: 0x75987c32a4
	public IXmlNode CreateTextNode(String text) { }
	// RVA: 0x61ab33c VA: 0x75987c333c
	public IXmlNode CreateCDataSection(String data) { }
	// RVA: 0x61ab3d4 VA: 0x75987c33d4
	public IXmlNode CreateWhitespace(String text) { }
	// RVA: 0x61ab46c VA: 0x75987c346c
	public IXmlNode CreateSignificantWhitespace(String text) { }
	// RVA: 0x61ab504 VA: 0x75987c3504
	public IXmlNode CreateXmlDeclaration(String version, String encoding, String standalone) { }
	// RVA: 0x61ab5e4 VA: 0x75987c35e4
	public IXmlNode CreateXmlDocumentType(String name, String publicId, String systemId, String internalSubset) { }
	// RVA: 0x61ab6c8 VA: 0x75987c36c8
	public IXmlNode CreateProcessingInstruction(String target, String data) { }
	// RVA: 0x61ab770 VA: 0x75987c3770
	public IXmlElement CreateElement(String elementName) { }
	// RVA: 0x61ab830 VA: 0x75987c3830
	public IXmlElement CreateElement(String qualifiedName, String namespaceUri) { }
	// RVA: 0x61ab8c0 VA: 0x75987c38c0
	public IXmlNode CreateAttribute(String name, String value) { }
	// RVA: 0x61ab998 VA: 0x75987c3998
	public IXmlNode CreateAttribute(String qualifiedName, String namespaceUri, String value) { }
	// RVA: 0x61aba58 VA: 0x75987c3a58
	public IXmlElement get_DocumentElement() { }
}
```