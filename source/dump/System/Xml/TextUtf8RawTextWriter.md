# TextUtf8RawTextWriter

**Namespace:** `System.Xml`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class TextUtf8RawTextWriter : XmlUtf8RawTextWriter
{

	internal override Boolean SupportsNamespaceDeclarationInChunks { get; }

	// RVA: 0x6278bcc VA: 0x7598890bcc
	public Void .ctor(Stream stream, XmlWriterSettings settings) { }
	// RVA: 0x6278bd4 VA: 0x7598890bd4
	internal override Void WriteXmlDeclaration(XmlStandalone standalone) { }
	// RVA: 0x6278bd8 VA: 0x7598890bd8
	internal override Void WriteXmlDeclaration(String xmldecl) { }
	// RVA: 0x6278bdc VA: 0x7598890bdc
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x6278be0 VA: 0x7598890be0
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x6278be4 VA: 0x7598890be4
	internal override Void WriteEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6278be8 VA: 0x7598890be8
	internal override Void WriteFullEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6278bec VA: 0x7598890bec
	internal override Void StartElementContent() { }
	// RVA: 0x6278bf0 VA: 0x7598890bf0
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x6278bfc VA: 0x7598890bfc
	public override Void WriteEndAttribute() { }
	// RVA: 0x6278c04 VA: 0x7598890c04
	internal override Void WriteNamespaceDeclaration(String prefix, String ns) { }
	// RVA: 0x6278c08 VA: 0x7598890c08
	internal override Boolean get_SupportsNamespaceDeclarationInChunks() { }
	// RVA: 0x6278c10 VA: 0x7598890c10
	public override Void WriteCData(String text) { }
	// RVA: 0x6278c18 VA: 0x7598890c18
	public override Void WriteComment(String text) { }
	// RVA: 0x6278c1c VA: 0x7598890c1c
	public override Void WriteProcessingInstruction(String name, String text) { }
	// RVA: 0x6278c20 VA: 0x7598890c20
	public override Void WriteEntityRef(String name) { }
	// RVA: 0x6278c24 VA: 0x7598890c24
	public override Void WriteCharEntity(Char ch) { }
	// RVA: 0x6278c28 VA: 0x7598890c28
	public override Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x6278c2c VA: 0x7598890c2c
	public override Void WriteWhitespace(String ws) { }
	// RVA: 0x6278c40 VA: 0x7598890c40
	public override Void WriteString(String textBlock) { }
	// RVA: 0x6278c54 VA: 0x7598890c54
	public override Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6278c68 VA: 0x7598890c68
	public override Void WriteRaw(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6278c7c VA: 0x7598890c7c
	public override Void WriteRaw(String data) { }
}
```