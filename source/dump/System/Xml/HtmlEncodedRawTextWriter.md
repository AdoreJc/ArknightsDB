# HtmlEncodedRawTextWriter

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
internal class HtmlEncodedRawTextWriter : XmlEncodedRawTextWriter
{
	protected ByteStack elementScope; // 0xb8
	protected ElementProperties currentElementProperties; // 0xc0
	private AttributeProperties currentAttributeProperties; // 0xc4
	private Boolean endsWithAmpersand; // 0xc8
	private Byte[] uriEscapingBuffer; // 0xd0
	private String mediaType; // 0xd8
	private Boolean doNotEscapeUriAttributes; // 0xe0
	protected static TernaryTreeReadOnly elementPropertySearch; // 0x0
	protected static TernaryTreeReadOnly attributePropertySearch; // 0x8


	// RVA: 0x6272e7c VA: 0x759888ae7c
	public Void .ctor(TextWriter writer, XmlWriterSettings settings) { }
	// RVA: 0x6273168 VA: 0x759888b168
	public Void .ctor(Stream stream, XmlWriterSettings settings) { }
	// RVA: 0x627349c VA: 0x759888b49c
	internal override Void WriteXmlDeclaration(XmlStandalone standalone) { }
	// RVA: 0x62734a0 VA: 0x759888b4a0
	internal override Void WriteXmlDeclaration(String xmldecl) { }
	// RVA: 0x62734a4 VA: 0x759888b4a4
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x627377c VA: 0x759888b77c
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x6273a88 VA: 0x759888ba88
	internal override Void StartElementContent() { }
	// RVA: 0x6273be0 VA: 0x759888bbe0
	internal override Void WriteEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6273e48 VA: 0x759888be48
	internal override Void WriteFullEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6274048 VA: 0x759888c048
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x62742d8 VA: 0x759888c2d8
	public override Void WriteEndAttribute() { }
	// RVA: 0x62743fc VA: 0x759888c3fc
	public override Void WriteProcessingInstruction(String target, String text) { }
	// RVA: 0x6274838 VA: 0x759888c838
	public override Void WriteString(String text) { }
	// RVA: 0x62748f4 VA: 0x759888c8f4
	public override Void WriteEntityRef(String name) { }
	// RVA: 0x6274954 VA: 0x759888c954
	public override Void WriteCharEntity(Char ch) { }
	// RVA: 0x62749b4 VA: 0x759888c9b4
	public override Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x6274a14 VA: 0x759888ca14
	public override Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6272fa0 VA: 0x759888afa0
	private Void Init(XmlWriterSettings settings) { }
	// RVA: 0x6273adc VA: 0x759888badc
	protected Void WriteMetaElement() { }
	// RVA: 0x62748e4 VA: 0x759888c8e4
	protected Void WriteHtmlElementTextBlock(Char* pSrc, Char* pSrcEnd) { }
	// RVA: 0x62748a4 VA: 0x759888c8a4
	protected Void WriteHtmlAttributeTextBlock(Char* pSrc, Char* pSrcEnd) { }
	// RVA: 0x627555c VA: 0x759888d55c
	private Void WriteHtmlAttributeText(Char* pSrc, Char* pSrcEnd) { }
	// RVA: 0x62751e4 VA: 0x759888d1e4
	private Void WriteUriAttributeText(Char* pSrc, Char* pSrcEnd) { }
	// RVA: 0x6274368 VA: 0x759888c368
	private Void OutputRestAmps() { }
}
```