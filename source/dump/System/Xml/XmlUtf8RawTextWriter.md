# XmlUtf8RawTextWriter

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

- `Void FlushEncoder()`

- `Void WriteAttributeTextBlock(Char*, Char*)`

- `Void WriteElementTextBlock(Char*, Char*)`

- `Void RawText(String)`

- `Void RawText(Char*, Char*)`

- `Void WriteRawWithCharChecking(Char*, Char*)`

- `Void WriteCommentOrPi(String, Int32)`

- `Void WriteCDataSection(String)`

- `Void ValidateContentChars(String, String, Boolean)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class XmlUtf8RawTextWriter : XmlRawWriter
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
	protected NewLineHandling newLineHandling; // 0x64
	protected Boolean closeOutput; // 0x68
	protected Boolean omitXmlDeclaration; // 0x69
	protected String newLineChars; // 0x70
	protected Boolean checkCharacters; // 0x78
	protected XmlStandalone standalone; // 0x7c
	protected XmlOutputMethod outputMethod; // 0x80
	protected Boolean autoXmlDeclaration; // 0x84
	protected Boolean mergeCDataSections; // 0x85

	internal override Boolean SupportsNamespaceDeclarationInChunks { get; }

	// RVA: 0x6298f38 VA: 0x75988b0f38
	protected Void .ctor(XmlWriterSettings settings) { }
	// RVA: 0x62993a4 VA: 0x75988b13a4
	public Void .ctor(Stream stream, XmlWriterSettings settings) { }
	// RVA: 0x629950c VA: 0x75988b150c
	internal override Void WriteXmlDeclaration(XmlStandalone standalone) { }
	// RVA: 0x62996a8 VA: 0x75988b16a8
	internal override Void WriteXmlDeclaration(String xmldecl) { }
	// RVA: 0x6299720 VA: 0x75988b1720
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x6299910 VA: 0x75988b1910
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x62999b4 VA: 0x75988b19b4
	internal override Void StartElementContent() { }
	// RVA: 0x62999fc VA: 0x75988b19fc
	internal override Void WriteEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6299b54 VA: 0x75988b1b54
	internal override Void WriteFullEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6299c48 VA: 0x75988b1c48
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x6299d54 VA: 0x75988b1d54
	public override Void WriteEndAttribute() { }
	// RVA: 0x6299da0 VA: 0x75988b1da0
	internal override Void WriteNamespaceDeclaration(String prefix, String namespaceName) { }
	// RVA: 0x6299df4 VA: 0x75988b1df4
	internal override Boolean get_SupportsNamespaceDeclarationInChunks() { }
	// RVA: 0x6299dfc VA: 0x75988b1dfc
	internal override Void WriteStartNamespaceDeclaration(String prefix) { }
	// RVA: 0x6299ef0 VA: 0x75988b1ef0
	internal override Void WriteEndNamespaceDeclaration() { }
	// RVA: 0x6299f3c VA: 0x75988b1f3c
	public override Void WriteCData(String text) { }
	// RVA: 0x629a4b8 VA: 0x75988b24b8
	public override Void WriteComment(String text) { }
	// RVA: 0x629a944 VA: 0x75988b2944
	public override Void WriteProcessingInstruction(String name, String text) { }
	// RVA: 0x629aa6c VA: 0x75988b2a6c
	public override Void WriteEntityRef(String name) { }
	// RVA: 0x629ab0c VA: 0x75988b2b0c
	public override Void WriteCharEntity(Char ch) { }
	// RVA: 0x629acd8 VA: 0x75988b2cd8
	public override Void WriteWhitespace(String ws) { }
	// RVA: 0x629b2dc VA: 0x75988b32dc
	public override Void WriteString(String text) { }
	// RVA: 0x629b32c VA: 0x75988b332c
	public override Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x629b478 VA: 0x75988b3478
	public override Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x629b4b8 VA: 0x75988b34b8
	public override Void WriteRaw(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x629b744 VA: 0x75988b3744
	public override Void WriteRaw(String data) { }
	// RVA: 0x629b78c VA: 0x75988b378c
	public override Void Close() { }
	// RVA: 0x629b804 VA: 0x75988b3804
	public override Void Flush() { }
	// RVA: 0x629b840 VA: 0x75988b3840
	protected virtual Void FlushBuffer() { }
	// RVA: 0x629b800 VA: 0x75988b3800
	private Void FlushEncoder() { }
	// RVA: 0x629ad28 VA: 0x75988b2d28
	protected Void WriteAttributeTextBlock(Char* pSrc, Char* pSrcEnd) { }
	// RVA: 0x629b01c VA: 0x75988b301c
	protected Void WriteElementTextBlock(Char* pSrc, Char* pSrcEnd) { }
	// RVA: 0x629966c VA: 0x75988b166c
	protected Void RawText(String s) { }
	// RVA: 0x629bd5c VA: 0x75988b3d5c
	protected Void RawText(Char* pSrcBegin, Char* pSrcEnd) { }
	// RVA: 0x629b4f8 VA: 0x75988b34f8
	protected Void WriteRawWithCharChecking(Char* pSrcBegin, Char* pSrcEnd) { }
	// RVA: 0x629a610 VA: 0x75988b2610
	protected Void WriteCommentOrPi(String text, Int32 stopChar) { }
	// RVA: 0x629a198 VA: 0x75988b2198
	protected Void WriteCDataSection(String text) { }
	// RVA: 0x629bf2c VA: 0x75988b3f2c
	private static Boolean IsSurrogateByte(Byte b) { }
	// RVA: 0x629ba7c VA: 0x75988b3a7c
	private static Byte* EncodeSurrogate(Char* pSrc, Char* pSrcEnd, Byte* pDst) { }
	// RVA: 0x629bc14 VA: 0x75988b3c14
	private Byte* InvalidXmlChar(Int32 ch, Byte* pDst, Boolean entitize) { }
	// RVA: 0x629bfe8 VA: 0x75988b3fe8
	internal Void EncodeChar(ref Char* pSrc, Char* pSrcEnd, ref Byte* pDst) { }
	// RVA: 0x629bcc8 VA: 0x75988b3cc8
	internal static Byte* EncodeMultibyteUTF8(Int32 ch, Byte* pDst) { }
	// RVA: 0x629c0c4 VA: 0x75988b40c4
	internal static Void CharToUTF8(ref Char* pSrc, Char* pSrcEnd, ref Byte* pDst) { }
	// RVA: 0x629bd08 VA: 0x75988b3d08
	protected Byte* WriteNewLine(Byte* pDst) { }
	// RVA: 0x629b9dc VA: 0x75988b39dc
	protected static Byte* LtEntity(Byte* pDst) { }
	// RVA: 0x629b9ec VA: 0x75988b39ec
	protected static Byte* GtEntity(Byte* pDst) { }
	// RVA: 0x629b9bc VA: 0x75988b39bc
	protected static Byte* AmpEntity(Byte* pDst) { }
	// RVA: 0x629b9fc VA: 0x75988b39fc
	protected static Byte* QuoteEntity(Byte* pDst) { }
	// RVA: 0x629ba1c VA: 0x75988b3a1c
	protected static Byte* TabEntity(Byte* pDst) { }
	// RVA: 0x629ba5c VA: 0x75988b3a5c
	protected static Byte* LineFeedEntity(Byte* pDst) { }
	// RVA: 0x629ba3c VA: 0x75988b3a3c
	protected static Byte* CarriageReturnEntity(Byte* pDst) { }
	// RVA: 0x629bf3c VA: 0x75988b3f3c
	private static Byte* CharEntity(Byte* pDst, Char ch) { }
	// RVA: 0x629bf04 VA: 0x75988b3f04
	protected static Byte* RawStartCData(Byte* pDst) { }
	// RVA: 0x629bee8 VA: 0x75988b3ee8
	protected static Byte* RawEndCData(Byte* pDst) { }
	// RVA: 0x6299038 VA: 0x75988b1038
	protected Void ValidateContentChars(String chars, String propertyName, Boolean allowOnlyWhitespace) { }
}
```