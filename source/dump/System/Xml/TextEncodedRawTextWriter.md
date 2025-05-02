# TextEncodedRawTextWriter

**Namespace:** `System.Xml`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class TextEncodedRawTextWriter : XmlEncodedRawTextWriter
{

	internal override Boolean SupportsNamespaceDeclarationInChunks { get; }

	// RVA: 0x6278a40 VA: 0x7598890a40
	public Void .ctor(TextWriter writer, XmlWriterSettings settings) { }
	// RVA: 0x6278a44 VA: 0x7598890a44
	public Void .ctor(Stream stream, XmlWriterSettings settings) { }
	// RVA: 0x6278a48 VA: 0x7598890a48
	internal override Void WriteXmlDeclaration(XmlStandalone standalone) { }
	// RVA: 0x6278a4c VA: 0x7598890a4c
	internal override Void WriteXmlDeclaration(String xmldecl) { }
	// RVA: 0x6278a50 VA: 0x7598890a50
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x6278a54 VA: 0x7598890a54
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x6278a58 VA: 0x7598890a58
	internal override Void WriteEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6278a5c VA: 0x7598890a5c
	internal override Void WriteFullEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6278a60 VA: 0x7598890a60
	internal override Void StartElementContent() { }
	// RVA: 0x6278a64 VA: 0x7598890a64
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x6278a70 VA: 0x7598890a70
	public override Void WriteEndAttribute() { }
	// RVA: 0x6278a78 VA: 0x7598890a78
	internal override Void WriteNamespaceDeclaration(String prefix, String ns) { }
	// RVA: 0x6278a7c VA: 0x7598890a7c
	internal override Boolean get_SupportsNamespaceDeclarationInChunks() { }
	// RVA: 0x6278a84 VA: 0x7598890a84
	public override Void WriteCData(String text) { }
	// RVA: 0x6278aec VA: 0x7598890aec
	public override Void WriteComment(String text) { }
	// RVA: 0x6278af0 VA: 0x7598890af0
	public override Void WriteProcessingInstruction(String name, String text) { }
	// RVA: 0x6278af4 VA: 0x7598890af4
	public override Void WriteEntityRef(String name) { }
	// RVA: 0x6278af8 VA: 0x7598890af8
	public override Void WriteCharEntity(Char ch) { }
	// RVA: 0x6278afc VA: 0x7598890afc
	public override Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x6278b00 VA: 0x7598890b00
	public override Void WriteWhitespace(String ws) { }
	// RVA: 0x6278b10 VA: 0x7598890b10
	public override Void WriteString(String textBlock) { }
	// RVA: 0x6278b20 VA: 0x7598890b20
	public override Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6278bac VA: 0x7598890bac
	public override Void WriteRaw(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6278bbc VA: 0x7598890bbc
	public override Void WriteRaw(String data) { }
}
```