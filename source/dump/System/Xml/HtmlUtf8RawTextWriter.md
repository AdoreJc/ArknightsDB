# HtmlUtf8RawTextWriter

**Namespace:** `System.Xml`


## Fields

- `ByteStack elementScope`

- `ElementProperties currentElementProperties`

- `AttributeProperties currentAttributeProperties`

- `Boolean endsWithAmpersand`

- `String mediaType`

- `Boolean doNotEscapeUriAttributes`


## Methods

- `Void Init(XmlWriterSettings)`

- `Void WriteMetaElement()`

- `Void WriteHtmlElementTextBlock(Char*, Char*)`

- `Void WriteHtmlAttributeTextBlock(Char*, Char*)`

- `Void WriteHtmlAttributeText(Char*, Char*)`

- `Void WriteUriAttributeText(Char*, Char*)`

- `Void OutputRestAmps()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class HtmlUtf8RawTextWriter : XmlUtf8RawTextWriter
{
	protected ByteStack elementScope; // 0x88
	protected ElementProperties currentElementProperties; // 0x90
	private AttributeProperties currentAttributeProperties; // 0x94
	private Boolean endsWithAmpersand; // 0x98
	private Byte[] uriEscapingBuffer; // 0xa0
	private String mediaType; // 0xa8
	private Boolean doNotEscapeUriAttributes; // 0xb0
	protected static TernaryTreeReadOnly elementPropertySearch; // 0x0
	protected static TernaryTreeReadOnly attributePropertySearch; // 0x8


	// RVA: 0x62760d4 VA: 0x759888e0d4
	public Void .ctor(Stream stream, XmlWriterSettings settings) { }
	// RVA: 0x62762c8 VA: 0x759888e2c8
	internal override Void WriteXmlDeclaration(XmlStandalone standalone) { }
	// RVA: 0x62762cc VA: 0x759888e2cc
	internal override Void WriteXmlDeclaration(String xmldecl) { }
	// RVA: 0x62762d0 VA: 0x759888e2d0
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x6276518 VA: 0x759888e518
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x6276620 VA: 0x759888e620
	internal override Void StartElementContent() { }
	// RVA: 0x6276794 VA: 0x759888e794
	internal override Void WriteEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6276878 VA: 0x759888e878
	internal override Void WriteFullEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x627695c VA: 0x759888e95c
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x6276acc VA: 0x759888eacc
	public override Void WriteEndAttribute() { }
	// RVA: 0x6276c08 VA: 0x759888ec08
	public override Void WriteProcessingInstruction(String target, String text) { }
	// RVA: 0x6276d28 VA: 0x759888ed28
	public override Void WriteString(String text) { }
	// RVA: 0x6276dd4 VA: 0x759888edd4
	public override Void WriteEntityRef(String name) { }
	// RVA: 0x6276e34 VA: 0x759888ee34
	public override Void WriteCharEntity(Char ch) { }
	// RVA: 0x6276e94 VA: 0x759888ee94
	public override Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x6276ef4 VA: 0x759888eef4
	public override Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6276100 VA: 0x759888e100
	private Void Init(XmlWriterSettings settings) { }
	// RVA: 0x6276678 VA: 0x759888e678
	protected Void WriteMetaElement() { }
	// RVA: 0x6276dbc VA: 0x759888edbc
	protected Void WriteHtmlElementTextBlock(Char* pSrc, Char* pSrcEnd) { }
	// RVA: 0x6276d78 VA: 0x759888ed78
	protected Void WriteHtmlAttributeTextBlock(Char* pSrc, Char* pSrcEnd) { }
	// RVA: 0x6277274 VA: 0x759888f274
	private Void WriteHtmlAttributeText(Char* pSrc, Char* pSrcEnd) { }
	// RVA: 0x6276f38 VA: 0x759888ef38
	private Void WriteUriAttributeText(Char* pSrc, Char* pSrcEnd) { }
	// RVA: 0x6276b44 VA: 0x759888eb44
	private Void OutputRestAmps() { }
}
```