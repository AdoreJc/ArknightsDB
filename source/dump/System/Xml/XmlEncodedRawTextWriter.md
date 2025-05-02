# XmlEncodedRawTextWriter

**Namespace:** `System.Xml`


## Fields

- `Stream stream`

- `Encoding encoding`

- `XmlCharType xmlCharType`

- `Int32 bufPos`

- `Int32 textPos`

- `Int32 contentPos`

- `Int32 cdataPos`

- `Int32 attrEndPos`

- `Int32 bufLen`

- `Boolean writeToNull`

- `Boolean hadDoubleBracket`

- `Boolean inAttributeValue`

- `Int32 bufBytesUsed`

- `Encoder encoder`

- `TextWriter writer`

- `Boolean trackTextContent`

- `Boolean inTextContent`

- `Int32 lastMarkPos`

- `CharEntityEncoderFallback charEntityFallback`

- `NewLineHandling newLineHandling`

- `Boolean closeOutput`

- `Boolean omitXmlDeclaration`

- `String newLineChars`

- `Boolean checkCharacters`

- `XmlStandalone standalone`

- `XmlOutputMethod outputMethod`

- `Boolean autoXmlDeclaration`

- `Boolean mergeCDataSections`


## Methods

- `Void EncodeChars(Int32, Int32, Boolean)`

- `Void FlushEncoder()`

- `Void WriteAttributeTextBlock(Char*, Char*)`

- `Void WriteElementTextBlock(Char*, Char*)`

- `Void RawText(String)`

- `Void RawText(Char*, Char*)`

- `Void WriteRawWithCharChecking(Char*, Char*)`

- `Void WriteCommentOrPi(String, Int32)`

- `Void WriteCDataSection(String)`

- `Void ChangeTextContentMark(Boolean)`

- `Void GrowTextContentMarks()`

- `Void ValidateContentChars(String, String, Boolean)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class XmlEncodedRawTextWriter : XmlRawWriter
{
	private readonly Boolean useAsync; // 0x20
	protected Byte[] bufBytes; // 0x28
	protected Stream stream; // 0x30
	protected Encoding encoding; // 0x38
	protected XmlCharType xmlCharType; // 0x40
	protected Int32 bufPos; // 0x48
	protected Int32 textPos; // 0x4c
	protected Int32 contentPos; // 0x50
	protected Int32 cdataPos; // 0x54
	protected Int32 attrEndPos; // 0x58
	protected Int32 bufLen; // 0x5c
	protected Boolean writeToNull; // 0x60
	protected Boolean hadDoubleBracket; // 0x61
	protected Boolean inAttributeValue; // 0x62
	protected Int32 bufBytesUsed; // 0x64
	protected Char[] bufChars; // 0x68
	protected Encoder encoder; // 0x70
	protected TextWriter writer; // 0x78
	protected Boolean trackTextContent; // 0x80
	protected Boolean inTextContent; // 0x81
	private Int32 lastMarkPos; // 0x84
	private Int32[] textContentMarks; // 0x88
	private CharEntityEncoderFallback charEntityFallback; // 0x90
	protected NewLineHandling newLineHandling; // 0x98
	protected Boolean closeOutput; // 0x9c
	protected Boolean omitXmlDeclaration; // 0x9d
	protected String newLineChars; // 0xa0
	protected Boolean checkCharacters; // 0xa8
	protected XmlStandalone standalone; // 0xac
	protected XmlOutputMethod outputMethod; // 0xb0
	protected Boolean autoXmlDeclaration; // 0xb4
	protected Boolean mergeCDataSections; // 0xb5

	internal override Boolean SupportsNamespaceDeclarationInChunks { get; }

	// RVA: 0x627a778 VA: 0x7598892778
	protected Void .ctor(XmlWriterSettings settings) { }
	// RVA: 0x6272ea4 VA: 0x759888aea4
	public Void .ctor(TextWriter writer, XmlWriterSettings settings) { }
	// RVA: 0x6273190 VA: 0x759888b190
	public Void .ctor(Stream stream, XmlWriterSettings settings) { }
	// RVA: 0x627abe4 VA: 0x7598892be4
	internal override Void WriteXmlDeclaration(XmlStandalone standalone) { }
	// RVA: 0x627ad60 VA: 0x7598892d60
	internal override Void WriteXmlDeclaration(String xmldecl) { }
	// RVA: 0x627add8 VA: 0x7598892dd8
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x62739c0 VA: 0x759888b9c0
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x627afc4 VA: 0x7598892fc4
	internal override Void StartElementContent() { }
	// RVA: 0x6273cd8 VA: 0x759888bcd8
	internal override Void WriteEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6273f40 VA: 0x759888bf40
	internal override Void WriteFullEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x62741b8 VA: 0x759888c1b8
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x627b008 VA: 0x7598893008
	public override Void WriteEndAttribute() { }
	// RVA: 0x627b070 VA: 0x7598893070
	internal override Void WriteNamespaceDeclaration(String prefix, String namespaceName) { }
	// RVA: 0x627b0c4 VA: 0x75988930c4
	internal override Boolean get_SupportsNamespaceDeclarationInChunks() { }
	// RVA: 0x627b0cc VA: 0x75988930cc
	internal override Void WriteStartNamespaceDeclaration(String prefix) { }
	// RVA: 0x627b1f0 VA: 0x75988931f0
	internal override Void WriteEndNamespaceDeclaration() { }
	// RVA: 0x627b258 VA: 0x7598893258
	public override Void WriteCData(String text) { }
	// RVA: 0x627b748 VA: 0x7598893748
	public override Void WriteComment(String text) { }
	// RVA: 0x627b874 VA: 0x7598893874
	public override Void WriteProcessingInstruction(String name, String text) { }
	// RVA: 0x627b9a0 VA: 0x75988939a0
	public override Void WriteEntityRef(String name) { }
	// RVA: 0x627ba6c VA: 0x7598893a6c
	public override Void WriteCharEntity(Char ch) { }
	// RVA: 0x627bc30 VA: 0x7598893c30
	public override Void WriteWhitespace(String ws) { }
	// RVA: 0x627bc9c VA: 0x7598893c9c
	public override Void WriteString(String text) { }
	// RVA: 0x627bd08 VA: 0x7598893d08
	public override Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x627be50 VA: 0x7598893e50
	public override Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6278b30 VA: 0x7598890b30
	public override Void WriteRaw(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6278a88 VA: 0x7598890a88
	public override Void WriteRaw(String data) { }
	// RVA: 0x627c0fc VA: 0x75988940fc
	public override Void Close() { }
	// RVA: 0x627c214 VA: 0x7598894214
	public override Void Flush() { }
	// RVA: 0x6275de4 VA: 0x759888dde4
	protected virtual Void FlushBuffer() { }
	// RVA: 0x627c26c VA: 0x759889426c
	private Void EncodeChars(Int32 startOffset, Int32 endOffset, Boolean writeAllToStream) { }
	// RVA: 0x627c178 VA: 0x7598894178
	private Void FlushEncoder() { }
	// RVA: 0x6274a9c VA: 0x759888ca9c
	protected Void WriteAttributeTextBlock(Char* pSrc, Char* pSrcEnd) { }
	// RVA: 0x6274d90 VA: 0x759888cd90
	protected Void WriteElementTextBlock(Char* pSrc, Char* pSrcEnd) { }
	// RVA: 0x6273740 VA: 0x759888b740
	protected Void RawText(String s) { }
	// RVA: 0x6275070 VA: 0x759888d070
	protected Void RawText(Char* pSrcBegin, Char* pSrcEnd) { }
	// RVA: 0x627bed8 VA: 0x7598893ed8
	protected Void WriteRawWithCharChecking(Char* pSrcBegin, Char* pSrcEnd) { }
	// RVA: 0x6274524 VA: 0x759888c524
	protected Void WriteCommentOrPi(String text, Int32 stopChar) { }
	// RVA: 0x627b438 VA: 0x7598893438
	protected Void WriteCDataSection(String text) { }
	// RVA: 0x627c3f8 VA: 0x75988943f8
	private static Char* EncodeSurrogate(Char* pSrc, Char* pSrcEnd, Char* pDst) { }
	// RVA: 0x627c558 VA: 0x7598894558
	private Char* InvalidXmlChar(Int32 ch, Char* pDst, Boolean entitize) { }
	// RVA: 0x62758d8 VA: 0x759888d8d8
	internal Void EncodeChar(ref Char* pSrc, Char* pSrcEnd, ref Char* pDst) { }
	// RVA: 0x62736cc VA: 0x759888b6cc
	protected Void ChangeTextContentMark(Boolean value) { }
	// RVA: 0x627c728 VA: 0x7598894728
	private Void GrowTextContentMarks() { }
	// RVA: 0x627c5c4 VA: 0x75988945c4
	protected Char* WriteNewLine(Char* pDst) { }
	// RVA: 0x627c3a0 VA: 0x75988943a0
	protected static Char* LtEntity(Char* pDst) { }
	// RVA: 0x627c3b8 VA: 0x75988943b8
	protected static Char* GtEntity(Char* pDst) { }
	// RVA: 0x6275834 VA: 0x759888d834
	protected static Char* AmpEntity(Char* pDst) { }
	// RVA: 0x627585c VA: 0x759888d85c
	protected static Char* QuoteEntity(Char* pDst) { }
	// RVA: 0x627c3d0 VA: 0x75988943d0
	protected static Char* TabEntity(Char* pDst) { }
	// RVA: 0x62758b0 VA: 0x759888d8b0
	protected static Char* LineFeedEntity(Char* pDst) { }
	// RVA: 0x6275888 VA: 0x759888d888
	protected static Char* CarriageReturnEntity(Char* pDst) { }
	// RVA: 0x627c678 VA: 0x7598894678
	private static Char* CharEntity(Char* pDst, Char ch) { }
	// RVA: 0x627c640 VA: 0x7598894640
	protected static Char* RawStartCData(Char* pDst) { }
	// RVA: 0x627c620 VA: 0x7598894620
	protected static Char* RawEndCData(Char* pDst) { }
	// RVA: 0x627a878 VA: 0x7598892878
	protected Void ValidateContentChars(String chars, String propertyName, Boolean allowOnlyWhitespace) { }
}
```