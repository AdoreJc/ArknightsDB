# XmlTextReaderImpl

**Namespace:** `System.Xml`


## Fields

- `LaterInitParam laterInitParam`

- `XmlCharType xmlCharType`

- `ParsingState ps`

- `ParsingFunction parsingFunction`

- `ParsingFunction nextParsingFunction`

- `ParsingFunction nextNextParsingFunction`

- `NodeData curNode`

- `Int32 index`

- `Int32 curAttrIndex`

- `Int32 attrCount`

- `Int32 attrHashtable`

- `Int32 attrDuplWalkCount`

- `Boolean attrNeedNamespaceLookup`

- `Boolean fullAttrCleanup`

- `XmlNameTable nameTable`

- `Boolean nameTableFromSettings`

- `XmlResolver xmlResolver`

- `String url`

- `Boolean normalize`

- `Boolean supportNamespaces`

- `WhitespaceHandling whitespaceHandling`

- `DtdProcessing dtdProcessing`

- `EntityHandling entityHandling`

- `Boolean ignorePIs`

- `Boolean ignoreComments`

- `Boolean checkCharacters`

- `Int32 lineNumberOffset`

- `Int32 linePositionOffset`

- `Boolean closeInput`

- `Int64 maxCharactersInDocument`

- `Int64 maxCharactersFromEntities`

- `Boolean v1Compat`

- `XmlNamespaceManager namespaceManager`

- `String lastPrefix`

- `XmlContext xmlContext`

- `Int32 parsingStatesStackTop`

- `String reportedBaseUri`

- `Encoding reportedEncoding`

- `IDtdInfo dtdInfo`

- `XmlNodeType fragmentType`

- `XmlParserContext fragmentParserContext`

- `Boolean fragment`

- `IncrementalReadDecoder incReadDecoder`

- `IncrementalReadState incReadState`

- `LineInfo incReadLineInfo`

- `Int32 incReadDepth`

- `Int32 incReadLeftStartPos`

- `Int32 incReadLeftEndPos`

- `Int32 attributeValueBaseEntityId`

- `Boolean emptyEntityInAttributeResolved`

- `IValidationEventHandling validationEventHandling`

- `OnDefaultAttributeUseDelegate onDefaultAttributeUse`

- `Boolean validatingReaderCompatFlag`

- `Boolean addDefaultAttributesAndNormalize`

- `StringBuilder stringBuilder`

- `Boolean rootElementParsed`

- `Boolean standalone`

- `Int32 nextEntityId`

- `ParsingMode parsingMode`

- `ReadState readState`

- `IDtdEntityInfo lastEntity`

- `Boolean afterResetState`

- `Int32 documentStartBytePos`

- `Int32 readValueOffset`

- `Int64 charactersInDocument`

- `Int64 charactersFromEntities`

- `Boolean disableUndeclaredEntityCheck`

- `XmlReader outerReader`

- `Boolean xmlResolverIsSet`

- `String Xml`

- `String XmlNs`


## Properties

- `Boolean IsResolverNull`

- `Boolean InAttributeValueIterator`

- `Boolean DtdValidation`

- `Boolean InEntity`


## Methods

- `Void FinishInitUriString()`

- `Void FinishInitStream()`

- `Void FinishInitTextReader()`

- `Void FinishInit()`

- `Boolean get_IsResolverNull()`

- `XmlResolver GetTempResolver()`

- `Void Throw(Int32, String, String)`

- `Void Throw(Int32, String, String[])`

- `Void Throw(Int32, String)`

- `Void Throw(String)`

- `Void Throw(String, Int32, Int32)`

- `Void Throw(String, String)`

- `Void Throw(String, String, Int32, Int32)`

- `Void Throw(String, String[])`

- `Void Throw(String, String, Exception)`

- `Void Throw(String, String[], Exception)`

- `Void Throw(Exception)`

- `Void ReThrow(Exception, Int32, Int32)`

- `Void ThrowWithoutLineInfo(String)`

- `Void ThrowWithoutLineInfo(String, String)`

- `Void ThrowWithoutLineInfo(String, String[], Exception)`

- `Void ThrowInvalidChar(Char[], Int32, Int32)`

- `Void SetErrorState()`

- `Void SendValidationEvent(XmlSeverityType, String, String, Int32, Int32)`

- `Void SendValidationEvent(XmlSeverityType, XmlSchemaException)`

- `Boolean get_InAttributeValueIterator()`

- `Void FinishAttributeValueIterator()`

- `Boolean get_DtdValidation()`

- `Void InitStreamInput(Uri, Stream, Encoding)`

- `Void InitStreamInput(Uri, String, Stream, Encoding)`

- `Void InitStreamInput(Uri, String, Stream, Byte[], Int32, Encoding)`

- `Void InitTextReaderInput(String, TextReader)`

- `Void InitTextReaderInput(String, Uri, TextReader)`

- `Void InitStringInput(String, Encoding, String)`

- `Void InitFragmentReader(XmlNodeType, XmlParserContext, Boolean)`

- `Void ProcessDtdFromParserContext(XmlParserContext)`

- `Void OpenUrl()`

- `Void OpenUrlDelegate(Object)`

- `Encoding DetectEncoding()`

- `Void SetupEncoding(Encoding)`

- `Void SwitchEncoding(Encoding)`

- `Encoding CheckEncoding(String)`

- `Void UnDecodeChars()`

- `Void SwitchEncodingToUTF8()`

- `Int32 ReadData()`

- `Int32 GetChars(Int32)`

- `Void InvalidCharRecovery(ref, out)`

- `Void ShiftBuffer(Int32, Int32, Int32)`

- `Boolean ParseXmlDeclaration(Boolean)`

- `Boolean ParseDocumentContent()`

- `Boolean ParseElementContent()`

- `Void ThrowUnclosedElements()`

- `Void ParseElement()`

- `Void AddDefaultAttributesAndNormalize()`

- `Void ParseEndElement()`

- `Void ThrowTagMismatch(NodeData)`

- `Void ParseAttributes()`

- `Void ElementNamespaceLookup()`

- `Void AttributeNamespaceLookup()`

- `Void AttributeDuplCheck()`

- `Void OnDefaultNamespaceDecl(NodeData)`

- `Void OnNamespaceDecl(NodeData)`

- `Void OnXmlReservedAttribute(NodeData)`

- `Void ParseAttributeValueSlow(Int32, Char, NodeData)`

- `Void AddAttributeChunkToList(NodeData, NodeData, ref)`

- `Boolean ParseText()`

- `Boolean ParseText(out, out, ref)`

- `Void FinishPartialValue()`

- `Void FinishOtherValueIterator()`

- `Void SkipPartialTextValue()`

- `Void FinishReadValueChunk()`

- `Void FinishReadContentAsBinary()`

- `Void FinishReadElementContentAsBinary()`

- `Boolean ParseRootLevelWhitespace()`

- `Void ParseEntityReference()`

- `EntityType HandleEntityReference(Boolean, EntityExpandType, out)`

- `EntityType HandleGeneralEntityReference(String, Boolean, Boolean, Int32)`

- `Boolean get_InEntity()`

- `Boolean HandleEntityEnd(Boolean)`

- `Void SetupEndEntityNodeInContent()`

- `Void SetupEndEntityNodeInAttribute()`

- `Boolean ParsePI()`

- `Boolean ParsePI(StringBuilder)`

- `Boolean ParsePIValue(out, out)`

- `Boolean ParseComment()`

- `Void ParseCData()`

- `Void ParseCDataOrComment(XmlNodeType)`

- `Boolean ParseCDataOrComment(XmlNodeType, out, out)`

- `Boolean ParseDoctypeDecl()`

- `Void ParseDtd()`

- `Void SkipDtd()`

- `Void SkipPublicOrSystemIdLiteral()`

- `Void SkipUntil(Char, Boolean)`

- `Int32 EatWhitespaces(StringBuilder)`

- `Int32 ParseCharRefInline(Int32, out, out)`

- `Int32 ParseNumericCharRef(Boolean, StringBuilder, out)`

- `Int32 ParseNumericCharRefInline(Int32, Boolean, StringBuilder, out, out)`

- `Int32 ParseNamedCharRef(Boolean, StringBuilder)`

- `Int32 ParseNamedCharRefInline(Int32, Boolean, StringBuilder)`

- `Int32 ParseName()`

- `Int32 ParseQName(out)`

- `Int32 ParseQName(Boolean, Int32, out)`

- `Boolean ReadDataInName(ref)`

- `String ParseEntityName()`

- `NodeData AddNode(Int32, Int32)`

- `NodeData AllocNode(Int32, Int32)`

- `NodeData AddAttributeNoChecks(String, Int32)`

- `NodeData AddAttribute(Int32, Int32)`

- `NodeData AddAttribute(String, String, String)`

- `Void PopElementContext()`

- `Void OnNewLine(Int32)`

- `Void OnEof()`

- `String LookupNamespace(NodeData)`

- `Void AddNamespace(String, String, NodeData)`

- `Void ResetAttributes()`

- `Void FullAttributeCleanup()`

- `Void PushXmlContext()`

- `Void PopXmlContext()`

- `XmlNodeType GetWhitespaceType()`

- `XmlNodeType GetTextNodeType(Int32)`

- `Void PushExternalEntityOrSubset(String, String, Uri, String)`

- `Boolean OpenAndPush(Uri)`

- `Boolean PushExternalEntity(IDtdEntityInfo)`

- `Void PushInternalEntity(IDtdEntityInfo)`

- `Void PopEntity()`

- `Void RegisterEntity(IDtdEntityInfo)`

- `Void UnregisterEntity()`

- `Void PushParsingState()`

- `Void PopParsingState()`

- `Int32 IncrementalRead()`

- `Void FinishIncrementalRead()`

- `Boolean ParseFragmentAttribute()`

- `Boolean ParseAttributeValueChunk()`

- `Void ParseXmlDeclarationFragment()`

- `Void ThrowUnexpectedToken(Int32, String)`

- `Void ThrowUnexpectedToken(String)`

- `Void ThrowUnexpectedToken(Int32, String, String)`

- `Void ThrowUnexpectedToken(String, String)`

- `String ParseUnexpectedToken(Int32)`

- `String ParseUnexpectedToken()`

- `Void ThrowExpectingWhitespace(Int32)`

- `Int32 GetIndexOfAttributeWithoutPrefix(String)`

- `Int32 GetIndexOfAttributeWithPrefix(String)`

- `Boolean ZeroEndingStream(Int32)`

- `Void ParseDtdFromParserContext()`

- `Boolean MoveToNextContentNode(Boolean)`

- `Boolean AddDefaultAttributeDtd(IDtdDefaultAttributeInfo, Boolean, NodeData[])`

- `NodeData AddDefaultAttributeInternal(String, String, String, String, Int32, Int32, Int32, Int32, Boolean)`

- `Void RegisterConsumedCharacters(Int64, Boolean)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class XmlTextReaderImpl : XmlReader, IXmlNamespaceResolver
{
	private LaterInitParam laterInitParam; // 0x10
	private XmlCharType xmlCharType; // 0x18
	private ParsingState ps; // 0x20
	private ParsingFunction parsingFunction; // 0x98
	private ParsingFunction nextParsingFunction; // 0x9c
	private ParsingFunction nextNextParsingFunction; // 0xa0
	private NodeData[] nodes; // 0xa8
	private NodeData curNode; // 0xb0
	private Int32 index; // 0xb8
	private Int32 curAttrIndex; // 0xbc
	private Int32 attrCount; // 0xc0
	private Int32 attrHashtable; // 0xc4
	private Int32 attrDuplWalkCount; // 0xc8
	private Boolean attrNeedNamespaceLookup; // 0xcc
	private Boolean fullAttrCleanup; // 0xcd
	private NodeData[] attrDuplSortingArray; // 0xd0
	private XmlNameTable nameTable; // 0xd8
	private Boolean nameTableFromSettings; // 0xe0
	private XmlResolver xmlResolver; // 0xe8
	private String url; // 0xf0
	private Boolean normalize; // 0xf8
	private Boolean supportNamespaces; // 0xf9
	private WhitespaceHandling whitespaceHandling; // 0xfc
	private DtdProcessing dtdProcessing; // 0x100
	private EntityHandling entityHandling; // 0x104
	private Boolean ignorePIs; // 0x108
	private Boolean ignoreComments; // 0x109
	private Boolean checkCharacters; // 0x10a
	private Int32 lineNumberOffset; // 0x10c
	private Int32 linePositionOffset; // 0x110
	private Boolean closeInput; // 0x114
	private Int64 maxCharactersInDocument; // 0x118
	private Int64 maxCharactersFromEntities; // 0x120
	private Boolean v1Compat; // 0x128
	private XmlNamespaceManager namespaceManager; // 0x130
	private String lastPrefix; // 0x138
	private XmlContext xmlContext; // 0x140
	private ParsingState[] parsingStatesStack; // 0x148
	private Int32 parsingStatesStackTop; // 0x150
	private String reportedBaseUri; // 0x158
	private Encoding reportedEncoding; // 0x160
	private IDtdInfo dtdInfo; // 0x168
	private XmlNodeType fragmentType; // 0x170
	private XmlParserContext fragmentParserContext; // 0x178
	private Boolean fragment; // 0x180
	private IncrementalReadDecoder incReadDecoder; // 0x188
	private IncrementalReadState incReadState; // 0x190
	private LineInfo incReadLineInfo; // 0x194
	private Int32 incReadDepth; // 0x19c
	private Int32 incReadLeftStartPos; // 0x1a0
	private Int32 incReadLeftEndPos; // 0x1a4
	private Int32 attributeValueBaseEntityId; // 0x1a8
	private Boolean emptyEntityInAttributeResolved; // 0x1ac
	private IValidationEventHandling validationEventHandling; // 0x1b0
	private OnDefaultAttributeUseDelegate onDefaultAttributeUse; // 0x1b8
	private Boolean validatingReaderCompatFlag; // 0x1c0
	private Boolean addDefaultAttributesAndNormalize; // 0x1c1
	private StringBuilder stringBuilder; // 0x1c8
	private Boolean rootElementParsed; // 0x1d0
	private Boolean standalone; // 0x1d1
	private Int32 nextEntityId; // 0x1d4
	private ParsingMode parsingMode; // 0x1d8
	private ReadState readState; // 0x1dc
	private IDtdEntityInfo lastEntity; // 0x1e0
	private Boolean afterResetState; // 0x1e8
	private Int32 documentStartBytePos; // 0x1ec
	private Int32 readValueOffset; // 0x1f0
	private Int64 charactersInDocument; // 0x1f8
	private Int64 charactersFromEntities; // 0x200
	private Dictionary`2 currentEntities; // 0x208
	private Boolean disableUndeclaredEntityCheck; // 0x210
	private XmlReader outerReader; // 0x218
	private Boolean xmlResolverIsSet; // 0x220
	private String Xml; // 0x228
	private String XmlNs; // 0x230
	private Task`1 parseText_dummyTask; // 0x238

	public override XmlReaderSettings Settings { get; }
	public override XmlNodeType NodeType { get; }
	public override String Name { get; }
	public override String LocalName { get; }
	public override String NamespaceURI { get; }
	public override String Prefix { get; }
	public override String Value { get; }
	public override String BaseURI { get; }
	public override Boolean IsEmptyElement { get; }
	public override Boolean IsDefault { get; }
	public override ReadState ReadState { get; }
	public override XmlNameTable NameTable { get; }
	public override Boolean CanResolveEntity { get; }
	internal XmlReader OuterReader { set; }
	internal Boolean Namespaces { set; }
	internal EntityHandling EntityHandling { set; }
	internal XmlResolver XmlResolver { set; }
	internal XmlNameTable DtdParserProxy_NameTable { get; }
	internal IXmlNamespaceResolver DtdParserProxy_NamespaceResolver { get; }
	internal Boolean DtdParserProxy_DtdValidation { get; }
	internal Boolean DtdParserProxy_Normalization { get; }
	internal Boolean DtdParserProxy_Namespaces { get; }
	internal Boolean DtdParserProxy_V1CompatibilityMode { get; }
	internal Uri DtdParserProxy_BaseUri { get; }
	internal Boolean DtdParserProxy_IsEof { get; }
	internal Char[] DtdParserProxy_ParsingBuffer { get; }
	internal Int32 DtdParserProxy_ParsingBufferLength { get; }
	internal Int32 DtdParserProxy_CurrentPosition { get; set; }
	internal Int32 DtdParserProxy_EntityStackLength { get; }
	internal Boolean DtdParserProxy_IsEntityEolNormalized { get; }
	internal IValidationEventHandling DtdParserProxy_ValidationEventHandling { get; }
	internal Int32 DtdParserProxy_LineNo { get; }
	internal Int32 DtdParserProxy_LineStartPosition { get; }
	private Boolean IsResolverNull { get; }
	private Boolean InAttributeValueIterator { get; }
	private Boolean DtdValidation { get; }
	private Boolean InEntity { get; }
	internal override IDtdInfo DtdInfo { get; }
	internal Boolean XmlValidatingReaderCompatibilityMode { set; }
	internal Boolean DisableUndeclaredEntityCheck { set; }

	// RVA: 0x6285c98 VA: 0x759889dc98
	internal Void .ctor(XmlNameTable nt) { }
	// RVA: 0x62860c8 VA: 0x759889e0c8
	internal Void .ctor(TextReader input, XmlNameTable nt) { }
	// RVA: 0x6286130 VA: 0x759889e130
	internal Void .ctor(String url, TextReader input, XmlNameTable nt) { }
	// RVA: 0x6286228 VA: 0x759889e228
	internal Void .ctor(String xmlFragment, XmlNodeType fragType, XmlParserContext context) { }
	// RVA: 0x62866c0 VA: 0x759889e6c0
	internal Void .ctor(String xmlFragment, XmlParserContext context) { }
	// RVA: 0x62867f8 VA: 0x759889e7f8
	private Void FinishInitUriString() { }
	// RVA: 0x6286e38 VA: 0x759889ee38
	private Void FinishInitStream() { }
	// RVA: 0x6286ed4 VA: 0x759889eed4
	private Void FinishInitTextReader() { }
	// RVA: 0x6286f54 VA: 0x759889ef54
	public override XmlReaderSettings get_Settings() { }
	// RVA: 0x62870ac VA: 0x759889f0ac
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62870c8 VA: 0x759889f0c8
	public override String get_Name() { }
	// RVA: 0x62870ec VA: 0x759889f0ec
	public override String get_LocalName() { }
	// RVA: 0x6287108 VA: 0x759889f108
	public override String get_NamespaceURI() { }
	// RVA: 0x6287124 VA: 0x759889f124
	public override String get_Prefix() { }
	// RVA: 0x6287140 VA: 0x759889f140
	public override String get_Value() { }
	// RVA: 0x6287354 VA: 0x759889f354
	public override String get_BaseURI() { }
	// RVA: 0x628735c VA: 0x759889f35c
	public override Boolean get_IsEmptyElement() { }
	// RVA: 0x6287378 VA: 0x759889f378
	public override Boolean get_IsDefault() { }
	// RVA: 0x6287394 VA: 0x759889f394
	public override ReadState get_ReadState() { }
	// RVA: 0x628739c VA: 0x759889f39c
	public override XmlNameTable get_NameTable() { }
	// RVA: 0x62873a4 VA: 0x759889f3a4
	public override Boolean get_CanResolveEntity() { }
	// RVA: 0x62873ac VA: 0x759889f3ac
	public override Boolean MoveToAttribute(String name) { }
	// RVA: 0x62876d8 VA: 0x759889f6d8
	public override Boolean MoveToFirstAttribute() { }
	// RVA: 0x6287754 VA: 0x759889f754
	public override Boolean MoveToNextAttribute() { }
	// RVA: 0x62877e4 VA: 0x759889f7e4
	public override Boolean MoveToElement() { }
	// RVA: 0x6287874 VA: 0x759889f874
	private Void FinishInit() { }
	// RVA: 0x62878bc VA: 0x759889f8bc
	public override Boolean Read() { }
	// RVA: 0x6289b64 VA: 0x75988a1b64
	public override Void Close() { }
	// RVA: 0x6289c5c VA: 0x75988a1c5c
	public override String LookupNamespace(String prefix) { }
	// RVA: 0x6289c94 VA: 0x75988a1c94
	public override Boolean ReadAttributeValue() { }
	// RVA: 0x628a3d0 VA: 0x75988a23d0
	public override Void ResolveEntity() { }
	// RVA: 0x628aac8 VA: 0x75988a2ac8
	internal Void set_OuterReader(XmlReader value) { }
	// RVA: 0x628aad8 VA: 0x75988a2ad8
	private String System.Xml.IXmlNamespaceResolver.LookupNamespace(String prefix) { }
	// RVA: 0x628aae8 VA: 0x75988a2ae8
	private String System.Xml.IXmlNamespaceResolver.LookupPrefix(String namespaceName) { }
	// RVA: 0x628ab0c VA: 0x75988a2b0c
	internal String LookupPrefix(String namespaceName) { }
	// RVA: 0x628ab30 VA: 0x75988a2b30
	internal Void set_Namespaces(Boolean value) { }
	// RVA: 0x628ad24 VA: 0x75988a2d24
	internal Void set_EntityHandling(EntityHandling value) { }
	// RVA: 0x628adac VA: 0x75988a2dac
	internal Void set_XmlResolver(XmlResolver value) { }
	// RVA: 0x628ae34 VA: 0x75988a2e34
	internal XmlNameTable get_DtdParserProxy_NameTable() { }
	// RVA: 0x628ae3c VA: 0x75988a2e3c
	internal IXmlNamespaceResolver get_DtdParserProxy_NamespaceResolver() { }
	// RVA: 0x628ae44 VA: 0x75988a2e44
	internal Boolean get_DtdParserProxy_DtdValidation() { }
	// RVA: 0x628ae64 VA: 0x75988a2e64
	internal Boolean get_DtdParserProxy_Normalization() { }
	// RVA: 0x628ae6c VA: 0x75988a2e6c
	internal Boolean get_DtdParserProxy_Namespaces() { }
	// RVA: 0x628ae74 VA: 0x75988a2e74
	internal Boolean get_DtdParserProxy_V1CompatibilityMode() { }
	// RVA: 0x628ae7c VA: 0x75988a2e7c
	internal Uri get_DtdParserProxy_BaseUri() { }
	// RVA: 0x628af30 VA: 0x75988a2f30
	internal Boolean get_DtdParserProxy_IsEof() { }
	// RVA: 0x628af38 VA: 0x75988a2f38
	internal Char[] get_DtdParserProxy_ParsingBuffer() { }
	// RVA: 0x628af40 VA: 0x75988a2f40
	internal Int32 get_DtdParserProxy_ParsingBufferLength() { }
	// RVA: 0x628af48 VA: 0x75988a2f48
	internal Int32 get_DtdParserProxy_CurrentPosition() { }
	// RVA: 0x628af50 VA: 0x75988a2f50
	internal Void set_DtdParserProxy_CurrentPosition(Int32 value) { }
	// RVA: 0x628af58 VA: 0x75988a2f58
	internal Int32 get_DtdParserProxy_EntityStackLength() { }
	// RVA: 0x628af64 VA: 0x75988a2f64
	internal Boolean get_DtdParserProxy_IsEntityEolNormalized() { }
	// RVA: 0x628af6c VA: 0x75988a2f6c
	internal IValidationEventHandling get_DtdParserProxy_ValidationEventHandling() { }
	// RVA: 0x628af74 VA: 0x75988a2f74
	internal Void DtdParserProxy_OnNewLine(Int32 pos) { }
	// RVA: 0x628af9c VA: 0x75988a2f9c
	internal Int32 get_DtdParserProxy_LineNo() { }
	// RVA: 0x628afa4 VA: 0x75988a2fa4
	internal Int32 get_DtdParserProxy_LineStartPosition() { }
	// RVA: 0x628afac VA: 0x75988a2fac
	internal Int32 DtdParserProxy_ReadData() { }
	// RVA: 0x628b408 VA: 0x75988a3408
	internal Int32 DtdParserProxy_ParseNumericCharRef(StringBuilder internalSubsetBuilder) { }
	// RVA: 0x628b4d4 VA: 0x75988a34d4
	internal Int32 DtdParserProxy_ParseNamedCharRef(Boolean expand, StringBuilder internalSubsetBuilder) { }
	// RVA: 0x628b540 VA: 0x75988a3540
	internal Void DtdParserProxy_ParsePI(StringBuilder sb) { }
	// RVA: 0x628b8f4 VA: 0x75988a38f4
	internal Void DtdParserProxy_ParseComment(StringBuilder sb) { }
	// RVA: 0x628bca8 VA: 0x75988a3ca8
	private Boolean get_IsResolverNull() { }
	// RVA: 0x628bce8 VA: 0x75988a3ce8
	private XmlResolver GetTempResolver() { }
	// RVA: 0x628bd50 VA: 0x75988a3d50
	internal Boolean DtdParserProxy_PushEntity(IDtdEntityInfo entity, out Int32 entityId) { }
	// RVA: 0x628c50c VA: 0x75988a450c
	internal Boolean DtdParserProxy_PopEntity(out IDtdEntityInfo oldEntity, out Int32 newEntityId) { }
	// RVA: 0x628c5bc VA: 0x75988a45bc
	internal Boolean DtdParserProxy_PushExternalSubset(String systemId, String publicId) { }
	// RVA: 0x628cd24 VA: 0x75988a4d24
	internal Void DtdParserProxy_PushInternalDtd(String baseUri, String internalDtd) { }
	// RVA: 0x628cfb8 VA: 0x75988a4fb8
	internal Void DtdParserProxy_Throw(Exception e) { }
	// RVA: 0x628d050 VA: 0x75988a5050
	internal Void DtdParserProxy_OnSystemId(String systemId, LineInfo keywordLineInfo, LineInfo systemLiteralLineInfo) { }
	// RVA: 0x628d158 VA: 0x75988a5158
	internal Void DtdParserProxy_OnPublicId(String publicId, LineInfo keywordLineInfo, LineInfo publicLiteralLineInfo) { }
	// RVA: 0x628d1e4 VA: 0x75988a51e4
	private Void Throw(Int32 pos, String res, String arg) { }
	// RVA: 0x628d294 VA: 0x75988a5294
	private Void Throw(Int32 pos, String res, String[] args) { }
	// RVA: 0x628d344 VA: 0x75988a5344
	private Void Throw(Int32 pos, String res) { }
	// RVA: 0x628d3a0 VA: 0x75988a53a0
	private Void Throw(String res) { }
	// RVA: 0x628d3f4 VA: 0x75988a53f4
	private Void Throw(String res, Int32 lineNo, Int32 linePos) { }
	// RVA: 0x628d1f8 VA: 0x75988a51f8
	private Void Throw(String res, String arg) { }
	// RVA: 0x628d49c VA: 0x75988a549c
	private Void Throw(String res, String arg, Int32 lineNo, Int32 linePos) { }
	// RVA: 0x628d2a8 VA: 0x75988a52a8
	private Void Throw(String res, String[] args) { }
	// RVA: 0x628d528 VA: 0x75988a5528
	private Void Throw(String res, String arg, Exception innerException) { }
	// RVA: 0x628d5b4 VA: 0x75988a55b4
	private Void Throw(String res, String[] args, Exception innerException) { }
	// RVA: 0x628cfc0 VA: 0x75988a4fc0
	private Void Throw(Exception e) { }
	// RVA: 0x628d670 VA: 0x75988a5670
	private Void ReThrow(Exception e, Int32 lineNo, Int32 linePos) { }
	// RVA: 0x6289950 VA: 0x75988a1950
	private Void ThrowWithoutLineInfo(String res) { }
	// RVA: 0x628d718 VA: 0x75988a5718
	private Void ThrowWithoutLineInfo(String res, String arg) { }
	// RVA: 0x628d790 VA: 0x75988a5790
	private Void ThrowWithoutLineInfo(String res, String[] args, Exception innerException) { }
	// RVA: 0x628d81c VA: 0x75988a581c
	private Void ThrowInvalidChar(Char[] data, Int32 length, Int32 invCharPos) { }
	// RVA: 0x628d65c VA: 0x75988a565c
	private Void SetErrorState() { }
	// RVA: 0x628bbfc VA: 0x75988a3bfc
	private Void SendValidationEvent(XmlSeverityType severity, String code, String arg, Int32 lineNo, Int32 linePos) { }
	// RVA: 0x628d88c VA: 0x75988a588c
	private Void SendValidationEvent(XmlSeverityType severity, XmlSchemaException exception) { }
	// RVA: 0x6287610 VA: 0x759889f610
	private Boolean get_InAttributeValueIterator() { }
	// RVA: 0x6287634 VA: 0x759889f634
	private Void FinishAttributeValueIterator() { }
	// RVA: 0x628ae54 VA: 0x75988a2e54
	private Boolean get_DtdValidation() { }
	// RVA: 0x628da94 VA: 0x75988a5a94
	private Void InitStreamInput(Uri baseUri, Stream stream, Encoding encoding) { }
	// RVA: 0x628daf4 VA: 0x75988a5af4
	private Void InitStreamInput(Uri baseUri, String baseUriStr, Stream stream, Encoding encoding) { }
	// RVA: 0x6286afc VA: 0x759889eafc
	private Void InitStreamInput(Uri baseUri, String baseUriStr, Stream stream, Byte[] bytes, Int32 byteCount, Encoding encoding) { }
	// RVA: 0x628621c VA: 0x759889e21c
	private Void InitTextReaderInput(String baseUriStr, TextReader input) { }
	// RVA: 0x628dea8 VA: 0x75988a5ea8
	private Void InitTextReaderInput(String baseUriStr, Uri baseUri, TextReader input) { }
	// RVA: 0x6286344 VA: 0x759889e344
	private Void InitStringInput(String baseUriStr, Encoding originalEncoding, String str) { }
	// RVA: 0x628644c VA: 0x759889e44c
	private Void InitFragmentReader(XmlNodeType fragmentType, XmlParserContext parserContext, Boolean allowXmlDeclFragment) { }
	// RVA: 0x6286dcc VA: 0x759889edcc
	private Void ProcessDtdFromParserContext(XmlParserContext context) { }
	// RVA: 0x6288530 VA: 0x75988a0530
	private Void OpenUrl() { }
	// RVA: 0x628e1d4 VA: 0x75988a61d4
	private Void OpenUrlDelegate(Object xmlResolver) { }
	// RVA: 0x628db04 VA: 0x75988a5b04
	private Encoding DetectEncoding() { }
	// RVA: 0x628dd30 VA: 0x75988a5d30
	private Void SetupEncoding(Encoding encoding) { }
	// RVA: 0x628e308 VA: 0x75988a6308
	private Void SwitchEncoding(Encoding newEncoding) { }
	// RVA: 0x628e4a4 VA: 0x75988a64a4
	private Encoding CheckEncoding(String newEncodingName) { }
	// RVA: 0x628e3f8 VA: 0x75988a63f8
	private Void UnDecodeChars() { }
	// RVA: 0x628e7e4 VA: 0x75988a67e4
	private Void SwitchEncodingToUTF8() { }
	// RVA: 0x628afb0 VA: 0x75988a2fb0
	private Int32 ReadData() { }
	// RVA: 0x628e86c VA: 0x75988a686c
	private Int32 GetChars(Int32 maxCharsCount) { }
	// RVA: 0x628e984 VA: 0x75988a6984
	private Void InvalidCharRecovery(ref Int32 bytesCount, out Int32 charsCount) { }
	// RVA: 0x6289b6c VA: 0x75988a1b6c
	internal Void Close(Boolean closeInput) { }
	// RVA: 0x628eb74 VA: 0x75988a6b74
	private Void ShiftBuffer(Int32 sourcePos, Int32 destPos, Int32 count) { }
	// RVA: 0x62886e8 VA: 0x75988a06e8
	private Boolean ParseXmlDeclaration(Boolean isTextDecl) { }
	// RVA: 0x6288040 VA: 0x75988a0040
	private Boolean ParseDocumentContent() { }
	// RVA: 0x6287d08 VA: 0x759889fd08
	private Boolean ParseElementContent() { }
	// RVA: 0x6290140 VA: 0x75988a8140
	private Void ThrowUnclosedElements() { }
	// RVA: 0x628f058 VA: 0x75988a7058
	private Void ParseElement() { }
	// RVA: 0x6290928 VA: 0x75988a8928
	private Void AddDefaultAttributesAndNormalize() { }
	// RVA: 0x628fd48 VA: 0x75988a7d48
	private Void ParseEndElement() { }
	// RVA: 0x6291ab0 VA: 0x75988a9ab0
	private Void ThrowTagMismatch(NodeData startTag) { }
	// RVA: 0x62902ec VA: 0x75988a82ec
	private Void ParseAttributes() { }
	// RVA: 0x629133c VA: 0x75988a933c
	private Void ElementNamespaceLookup() { }
	// RVA: 0x6291a00 VA: 0x75988a9a00
	private Void AttributeNamespaceLookup() { }
	// RVA: 0x6292bf4 VA: 0x75988aabf4
	private Void AttributeDuplCheck() { }
	// RVA: 0x62927fc VA: 0x75988aa7fc
	private Void OnDefaultNamespaceDecl(NodeData attr) { }
	// RVA: 0x6292918 VA: 0x75988aa918
	private Void OnNamespaceDecl(NodeData attr) { }
	// RVA: 0x62929f4 VA: 0x75988aa9f4
	private Void OnXmlReservedAttribute(NodeData attr) { }
	// RVA: 0x6291edc VA: 0x75988a9edc
	private Void ParseAttributeValueSlow(Int32 curPos, Char quoteChar, NodeData attr) { }
	// RVA: 0x6293328 VA: 0x75988ab328
	private Void AddAttributeChunkToList(NodeData attr, NodeData chunk, ref NodeData lastChunk) { }
	// RVA: 0x628f7d8 VA: 0x75988a77d8
	private Boolean ParseText() { }
	// RVA: 0x62934c8 VA: 0x75988ab4c8
	private Boolean ParseText(out Int32 startPos, out Int32 endPos, ref Int32 outOrChars) { }
	// RVA: 0x6287188 VA: 0x759889f188
	private Void FinishPartialValue() { }
	// RVA: 0x6287244 VA: 0x759889f244
	private Void FinishOtherValueIterator() { }
	// RVA: 0x62899e4 VA: 0x75988a19e4
	private Void SkipPartialTextValue() { }
	// RVA: 0x6289a24 VA: 0x75988a1a24
	private Void FinishReadValueChunk() { }
	// RVA: 0x6289a44 VA: 0x75988a1a44
	private Void FinishReadContentAsBinary() { }
	// RVA: 0x6289a94 VA: 0x75988a1a94
	private Void FinishReadElementContentAsBinary() { }
	// RVA: 0x628fb4c VA: 0x75988a7b4c
	private Boolean ParseRootLevelWhitespace() { }
	// RVA: 0x6289518 VA: 0x75988a1518
	private Void ParseEntityReference() { }
	// RVA: 0x628f510 VA: 0x75988a7510
	private EntityType HandleEntityReference(Boolean isInAttributeValue, EntityExpandType expandType, out Int32 charRefEndPos) { }
	// RVA: 0x628a624 VA: 0x75988a2624
	private EntityType HandleGeneralEntityReference(String name, Boolean isInAttributeValue, Boolean pushFakeEntityIfNullResolver, Int32 entityStartLinePos) { }
	// RVA: 0x628e7d4 VA: 0x75988a67d4
	private Boolean get_InEntity() { }
	// RVA: 0x628d950 VA: 0x75988a5950
	private Boolean HandleEntityEnd(Boolean checkEntityNesting) { }
	// RVA: 0x628958c VA: 0x75988a158c
	private Void SetupEndEntityNodeInContent() { }
	// RVA: 0x6293dc4 VA: 0x75988abdc4
	private Void SetupEndEntityNodeInAttribute() { }
	// RVA: 0x628ed44 VA: 0x75988a6d44
	private Boolean ParsePI() { }
	// RVA: 0x628b584 VA: 0x75988a3584
	private Boolean ParsePI(StringBuilder piInDtdStringBuilder) { }
	// RVA: 0x6293e3c VA: 0x75988abe3c
	private Boolean ParsePIValue(out Int32 outStartPos, out Int32 outEndPos) { }
	// RVA: 0x628ed4c VA: 0x75988a6d4c
	private Boolean ParseComment() { }
	// RVA: 0x628edb0 VA: 0x75988a6db0
	private Void ParseCData() { }
	// RVA: 0x628baa4 VA: 0x75988a3aa4
	private Void ParseCDataOrComment(XmlNodeType type) { }
	// RVA: 0x62941d0 VA: 0x75988ac1d0
	private Boolean ParseCDataOrComment(XmlNodeType type, out Int32 outStartPos, out Int32 outEndPos) { }
	// RVA: 0x628edb8 VA: 0x75988a6db8
	private Boolean ParseDoctypeDecl() { }
	// RVA: 0x629460c VA: 0x75988ac60c
	private Void ParseDtd() { }
	// RVA: 0x6294938 VA: 0x75988ac938
	private Void SkipDtd() { }
	// RVA: 0x6294c90 VA: 0x75988acc90
	private Void SkipPublicOrSystemIdLiteral() { }
	// RVA: 0x6294d48 VA: 0x75988acd48
	private Void SkipUntil(Char stopChar, Boolean recognizeLiterals) { }
	// RVA: 0x628cad0 VA: 0x75988a4ad0
	private Int32 EatWhitespaces(StringBuilder sb) { }
	// RVA: 0x6293bec VA: 0x75988abbec
	private Int32 ParseCharRefInline(Int32 startPos, out Int32 charCount, out EntityType entityType) { }
	// RVA: 0x628b428 VA: 0x75988a3428
	private Int32 ParseNumericCharRef(Boolean expand, StringBuilder internalSubsetBuilder, out EntityType entityType) { }
	// RVA: 0x6295184 VA: 0x75988ad184
	private Int32 ParseNumericCharRefInline(Int32 startPos, Boolean expand, StringBuilder internalSubsetBuilder, out Int32 charCount, out EntityType entityType) { }
	// RVA: 0x628b4dc VA: 0x75988a34dc
	private Int32 ParseNamedCharRef(Boolean expand, StringBuilder internalSubsetBuilder) { }
	// RVA: 0x62957e4 VA: 0x75988ad7e4
	private Int32 ParseNamedCharRefInline(Int32 startPos, Boolean expand, StringBuilder internalSubsetBuilder) { }
	// RVA: 0x628eb9c VA: 0x75988a6b9c
	private Int32 ParseName() { }
	// RVA: 0x62902dc VA: 0x75988a82dc
	private Int32 ParseQName(out Int32 colonPos) { }
	// RVA: 0x6295ac0 VA: 0x75988adac0
	private Int32 ParseQName(Boolean isQName, Int32 startOffset, out Int32 colonPos) { }
	// RVA: 0x6295d48 VA: 0x75988add48
	private Boolean ReadDataInName(ref Int32 pos) { }
	// RVA: 0x629338c VA: 0x75988ab38c
	private String ParseEntityName() { }
	// RVA: 0x6289490 VA: 0x75988a1490
	private NodeData AddNode(Int32 nodeIndex, Int32 nodeDepth) { }
	// RVA: 0x6295d88 VA: 0x75988add88
	private NodeData AllocNode(Int32 nodeIndex, Int32 nodeDepth) { }
	// RVA: 0x628d0dc VA: 0x75988a50dc
	private NodeData AddAttributeNoChecks(String name, Int32 attrDepth) { }
	// RVA: 0x6291d2c VA: 0x75988a9d2c
	private NodeData AddAttribute(Int32 endNamePos, Int32 colonPos) { }
	// RVA: 0x6295ed8 VA: 0x75988aded8
	private NodeData AddAttribute(String localName, String prefix, String nameWPrefix) { }
	// RVA: 0x62894d4 VA: 0x75988a14d4
	private Void PopElementContext() { }
	// RVA: 0x628af88 VA: 0x75988a2f88
	private Void OnNewLine(Int32 pos) { }
	// RVA: 0x62898b0 VA: 0x75988a18b0
	private Void OnEof() { }
	// RVA: 0x6292f78 VA: 0x75988aaf78
	private String LookupNamespace(NodeData node) { }
	// RVA: 0x62930cc VA: 0x75988ab0cc
	private Void AddNamespace(String prefix, String uri, NodeData attr) { }
	// RVA: 0x6289464 VA: 0x75988a1464
	private Void ResetAttributes() { }
	// RVA: 0x6296044 VA: 0x75988ae044
	private Void FullAttributeCleanup() { }
	// RVA: 0x629303c VA: 0x75988ab03c
	private Void PushXmlContext() { }
	// RVA: 0x629600c VA: 0x75988ae00c
	private Void PopXmlContext() { }
	// RVA: 0x6293d7c VA: 0x75988abd7c
	private XmlNodeType GetWhitespaceType() { }
	// RVA: 0x6293b94 VA: 0x75988abb94
	private XmlNodeType GetTextNodeType(Int32 orChars) { }
	// RVA: 0x628c704 VA: 0x75988a4704
	private Void PushExternalEntityOrSubset(String publicId, String systemId, Uri baseUri, String entityName) { }
	// RVA: 0x62960cc VA: 0x75988ae0cc
	private Boolean OpenAndPush(Uri uri) { }
	// RVA: 0x628be5c VA: 0x75988a3e5c
	private Boolean PushExternalEntity(IDtdEntityInfo entity) { }
	// RVA: 0x628c1ec VA: 0x75988a41ec
	private Void PushInternalEntity(IDtdEntityInfo entity) { }
	// RVA: 0x628c570 VA: 0x75988a4570
	private Void PopEntity() { }
	// RVA: 0x6296300 VA: 0x75988ae300
	private Void RegisterEntity(IDtdEntityInfo entity) { }
	// RVA: 0x6296514 VA: 0x75988ae514
	private Void UnregisterEntity() { }
	// RVA: 0x628cd94 VA: 0x75988a4d94
	private Void PushParsingState() { }
	// RVA: 0x628eb00 VA: 0x75988a6b00
	private Void PopParsingState() { }
	// RVA: 0x6296578 VA: 0x75988ae578
	private Int32 IncrementalRead() { }
	// RVA: 0x62896f0 VA: 0x75988a16f0
	private Void FinishIncrementalRead() { }
	// RVA: 0x6289774 VA: 0x75988a1774
	private Boolean ParseFragmentAttribute() { }
	// RVA: 0x6289f24 VA: 0x75988a1f24
	private Boolean ParseAttributeValueChunk() { }
	// RVA: 0x62897f4 VA: 0x75988a17f4
	private Void ParseXmlDeclarationFragment() { }
	// RVA: 0x628eda0 VA: 0x75988a6da0
	private Void ThrowUnexpectedToken(Int32 pos, String expectedToken) { }
	// RVA: 0x628eb94 VA: 0x75988a6b94
	private Void ThrowUnexpectedToken(String expectedToken1) { }
	// RVA: 0x628f048 VA: 0x75988a7048
	private Void ThrowUnexpectedToken(Int32 pos, String expectedToken1, String expectedToken2) { }
	// RVA: 0x628ebbc VA: 0x75988a6bbc
	private Void ThrowUnexpectedToken(String expectedToken1, String expectedToken2) { }
	// RVA: 0x628f040 VA: 0x75988a7040
	private String ParseUnexpectedToken(Int32 pos) { }
	// RVA: 0x6296eac VA: 0x75988aeeac
	private String ParseUnexpectedToken() { }
	// RVA: 0x6291cac VA: 0x75988a9cac
	private Void ThrowExpectingWhitespace(Int32 pos) { }
	// RVA: 0x6287474 VA: 0x759889f474
	private Int32 GetIndexOfAttributeWithoutPrefix(String name) { }
	// RVA: 0x628755c VA: 0x759889f55c
	private Int32 GetIndexOfAttributeWithPrefix(String name) { }
	// RVA: 0x6293c58 VA: 0x75988abc58
	private Boolean ZeroEndingStream(Int32 pos) { }
	// RVA: 0x628df9c VA: 0x75988a5f9c
	private Void ParseDtdFromParserContext() { }
	// RVA: 0x6293cd4 VA: 0x75988abcd4
	private Boolean MoveToNextContentNode(Boolean moveIfOnContentNode) { }
	// RVA: 0x6296f74 VA: 0x75988aef74
	internal override IDtdInfo get_DtdInfo() { }
	// RVA: 0x6296f7c VA: 0x75988aef7c
	internal Void SetDtdInfo(IDtdInfo newDtdInfo) { }
	// RVA: 0x62970cc VA: 0x75988af0cc
	internal Void set_XmlValidatingReaderCompatibilityMode(Boolean value) { }
	// RVA: 0x6291388 VA: 0x75988a9388
	private Boolean AddDefaultAttributeDtd(IDtdDefaultAttributeInfo defAttrInfo, Boolean definedInDtd, NodeData[] nameSortedNodeData) { }
	// RVA: 0x62971a4 VA: 0x75988af1a4
	private NodeData AddDefaultAttributeInternal(String localName, String ns, String prefix, String value, Int32 lineNo, Int32 linePos, Int32 valueLineNo, Int32 valueLinePos, Boolean isXmlAttribute) { }
	// RVA: 0x6297404 VA: 0x75988af404
	internal Void set_DisableUndeclaredEntityCheck(Boolean value) { }
	// RVA: 0x628cedc VA: 0x75988a4edc
	private Void RegisterConsumedCharacters(Int64 characters, Boolean inEntityReference) { }
	// RVA: 0x6297410 VA: 0x75988af410
	internal static String StripSpaces(String value) { }
	// RVA: 0x6297638 VA: 0x75988af638
	internal static Void StripSpaces(Char[] value, Int32 index, ref Int32 len) { }
	// RVA: 0x628e850 VA: 0x75988a6850
	internal static Void BlockCopyChars(Char[] src, Int32 srcOffset, Char[] dst, Int32 dstOffset, Int32 count) { }
	// RVA: 0x628e864 VA: 0x75988a6864
	internal static Void BlockCopy(Byte[] src, Int32 srcOffset, Byte[] dst, Int32 dstOffset, Int32 count) { }
}
```