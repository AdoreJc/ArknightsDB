# XmlAutoDetectWriter

**Namespace:** `System.Xml`


## Fields

- `XmlRawWriter wrapped`

- `OnRemoveWriter onRemove`

- `XmlWriterSettings writerSettings`

- `XmlEventCache eventCache`

- `TextWriter textWriter`

- `Stream strm`


## Methods

- `Void EnsureWrappedWriter(XmlOutputMethod)`

- `Boolean TextBlockCreatesWriter(String)`

- `Void CreateWrappedWriter(XmlOutputMethod)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class XmlAutoDetectWriter : XmlRawWriter
{
	private XmlRawWriter wrapped; // 0x20
	private OnRemoveWriter onRemove; // 0x28
	private XmlWriterSettings writerSettings; // 0x30
	private XmlEventCache eventCache; // 0x38
	private TextWriter textWriter; // 0x40
	private Stream strm; // 0x48

	internal override IXmlNamespaceResolver NamespaceResolver { set; }
	internal override Boolean SupportsNamespaceDeclarationInChunks { get; }

	// RVA: 0x6279438 VA: 0x7598891438
	private Void .ctor(XmlWriterSettings writerSettings) { }
	// RVA: 0x627955c VA: 0x759889155c
	public Void .ctor(TextWriter textWriter, XmlWriterSettings writerSettings) { }
	// RVA: 0x627958c VA: 0x759889158c
	public Void .ctor(Stream strm, XmlWriterSettings writerSettings) { }
	// RVA: 0x62795bc VA: 0x75988915bc
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x6279634 VA: 0x7598891634
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x6279910 VA: 0x7598891910
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x6279970 VA: 0x7598891970
	public override Void WriteEndAttribute() { }
	// RVA: 0x6279994 VA: 0x7598891994
	public override Void WriteCData(String text) { }
	// RVA: 0x6279a3c VA: 0x7598891a3c
	public override Void WriteComment(String text) { }
	// RVA: 0x6279a6c VA: 0x7598891a6c
	public override Void WriteProcessingInstruction(String name, String text) { }
	// RVA: 0x6279a9c VA: 0x7598891a9c
	public override Void WriteWhitespace(String ws) { }
	// RVA: 0x6279acc VA: 0x7598891acc
	public override Void WriteString(String text) { }
	// RVA: 0x6279b14 VA: 0x7598891b14
	public override Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6279b44 VA: 0x7598891b44
	public override Void WriteRaw(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6279b74 VA: 0x7598891b74
	public override Void WriteRaw(String data) { }
	// RVA: 0x6279bbc VA: 0x7598891bbc
	public override Void WriteEntityRef(String name) { }
	// RVA: 0x6279c08 VA: 0x7598891c08
	public override Void WriteCharEntity(Char ch) { }
	// RVA: 0x6279c54 VA: 0x7598891c54
	public override Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x6279ca8 VA: 0x7598891ca8
	public override Void WriteBase64(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6279d0c VA: 0x7598891d0c
	public override Void WriteBinHex(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6279d70 VA: 0x7598891d70
	public override Void Close() { }
	// RVA: 0x6279dac VA: 0x7598891dac
	public override Void Flush() { }
	// RVA: 0x6279de8 VA: 0x7598891de8
	public override Void WriteValue(String value) { }
	// RVA: 0x6279e34 VA: 0x7598891e34
	internal override Void set_NamespaceResolver(IXmlNamespaceResolver value) { }
	// RVA: 0x6279e84 VA: 0x7598891e84
	internal override Void WriteXmlDeclaration(XmlStandalone standalone) { }
	// RVA: 0x6279ed0 VA: 0x7598891ed0
	internal override Void WriteXmlDeclaration(String xmldecl) { }
	// RVA: 0x6279f1c VA: 0x7598891f1c
	internal override Void StartElementContent() { }
	// RVA: 0x6279f40 VA: 0x7598891f40
	internal override Void WriteEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6279f64 VA: 0x7598891f64
	internal override Void WriteFullEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6279f88 VA: 0x7598891f88
	internal override Void WriteNamespaceDeclaration(String prefix, String ns) { }
	// RVA: 0x6279fdc VA: 0x7598891fdc
	internal override Boolean get_SupportsNamespaceDeclarationInChunks() { }
	// RVA: 0x627a000 VA: 0x7598892000
	internal override Void WriteStartNamespaceDeclaration(String prefix) { }
	// RVA: 0x627a04c VA: 0x759889204c
	internal override Void WriteEndNamespaceDeclaration() { }
	// RVA: 0x62796b4 VA: 0x75988916b4
	private static Boolean IsHtmlTag(String tagName) { }
	// RVA: 0x6279624 VA: 0x7598891624
	private Void EnsureWrappedWriter(XmlOutputMethod outMethod) { }
	// RVA: 0x62799dc VA: 0x75988919dc
	private Boolean TextBlockCreatesWriter(String textBlock) { }
	// RVA: 0x62797c8 VA: 0x75988917c8
	private Void CreateWrappedWriter(XmlOutputMethod outMethod) { }
}
```