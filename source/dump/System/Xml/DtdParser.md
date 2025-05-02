# DtdParser

**Namespace:** `System.Xml`


## Fields

- `IDtdParserAdapter readerAdapter`

- `IDtdParserAdapterWithValidation readerAdapterWithValidation`

- `XmlNameTable nameTable`

- `SchemaInfo schemaInfo`

- `XmlCharType xmlCharType`

- `String systemId`

- `String publicId`

- `Boolean normalize`

- `Boolean validate`

- `Boolean supportNamespaces`

- `Boolean v1Compat`

- `Int32 charsUsed`

- `Int32 curPos`

- `ScanningFunction scanningFunction`

- `ScanningFunction nextScaningFunction`

- `ScanningFunction savedScanningFunction`

- `Boolean whitespaceSeen`

- `Int32 tokenStartPos`

- `Int32 colonPos`

- `StringBuilder internalSubsetValueSb`

- `Int32 externalEntitiesDepth`

- `Int32 currentEntityId`

- `Boolean freeFloatingDtd`

- `Boolean hasFreeFloatingInternalSubset`

- `StringBuilder stringBuilder`

- `Int32 condSectionDepth`

- `LineInfo literalLineInfo`

- `Char literalQuoteChar`

- `String documentBaseUri`

- `String externalDtdBaseUri`


## Properties

- `Boolean ParsingInternalSubset`

- `Boolean IgnoreEntityReferences`

- `Boolean SaveInternalSubsetValue`

- `Boolean ParsingTopLevelMarkup`

- `Boolean SupportNamespaces`

- `Boolean Normalize`

- `Int32 LineNo`

- `Int32 LinePos`

- `String BaseUriStr`


## Methods

- `Void Initialize(IDtdParserAdapter)`

- `Void InitializeFreeFloatingDtd(String, String, String, String, String, IDtdParserAdapter)`

- `Boolean get_ParsingInternalSubset()`

- `Boolean get_IgnoreEntityReferences()`

- `Boolean get_SaveInternalSubsetValue()`

- `Boolean get_ParsingTopLevelMarkup()`

- `Boolean get_SupportNamespaces()`

- `Boolean get_Normalize()`

- `Void Parse(Boolean)`

- `Void ParseInDocumentDtd(Boolean)`

- `Void ParseFreeFloatingDtd()`

- `Void ParseInternalSubset()`

- `Void ParseExternalSubset()`

- `Void ParseSubset()`

- `Void ParseAttlistDecl()`

- `Void ParseAttlistType(SchemaAttDef, SchemaElementDecl, Boolean)`

- `Void ParseAttlistDefault(SchemaAttDef, Boolean)`

- `Void ParseElementDecl()`

- `Void ParseElementOnlyContent(ParticleContentValidator, Int32)`

- `Void ParseHowMany(ParticleContentValidator)`

- `Void ParseElementMixedContent(ParticleContentValidator, Int32)`

- `Void ParseEntityDecl()`

- `Void ParseNotationDecl()`

- `Void AddUndeclaredNotation(String)`

- `Void ParseComment()`

- `Void ParsePI()`

- `Void ParseCondSection()`

- `Void ParseExternalId(Token, Token, out, out)`

- `Token GetToken(Boolean)`

- `Token ScanSubsetContent()`

- `Token ScanNameExpected()`

- `Token ScanQNameExpected()`

- `Token ScanNmtokenExpected()`

- `Token ScanDoctype1()`

- `Token ScanDoctype2()`

- `Token ScanClosingTag()`

- `Token ScanElement1()`

- `Token ScanElement2()`

- `Token ScanElement3()`

- `Token ScanElement4()`

- `Token ScanElement5()`

- `Token ScanElement6()`

- `Token ScanElement7()`

- `Token ScanAttlist1()`

- `Token ScanAttlist2()`

- `Token ScanAttlist3()`

- `Token ScanAttlist4()`

- `Token ScanAttlist5()`

- `Token ScanAttlist6()`

- `Token ScanAttlist7()`

- `Token ScanLiteral(LiteralType)`

- `XmlQualifiedName ScanEntityName()`

- `Token ScanNotation1()`

- `Token ScanSystemId()`

- `Token ScanEntity1()`

- `Token ScanEntity2()`

- `Token ScanEntity3()`

- `Token ScanPublicId1()`

- `Token ScanPublicId2()`

- `Token ScanCondSection1()`

- `Token ScanCondSection2()`

- `Token ScanCondSection3()`

- `Void ScanName()`

- `Void ScanQName()`

- `Void ScanQName(Boolean)`

- `Boolean ReadDataInName()`

- `Void ScanNmtoken()`

- `Boolean EatPublicKeyword()`

- `Boolean EatSystemKeyword()`

- `XmlQualifiedName GetNameQualified(Boolean)`

- `String GetNameString()`

- `String GetNmtokenString()`

- `String GetValue()`

- `String GetValueWithStrippedSpaces()`

- `Int32 ReadData()`

- `Void LoadParsingBuffer()`

- `Void SaveParsingBuffer()`

- `Void SaveParsingBuffer(Int32)`

- `Boolean HandleEntityReference(Boolean, Boolean, Boolean)`

- `Boolean HandleEntityReference(XmlQualifiedName, Boolean, Boolean, Boolean)`

- `Boolean HandleEntityEnd(Boolean)`

- `SchemaEntity VerifyEntityReference(XmlQualifiedName, Boolean, Boolean, Boolean)`

- `Void SendValidationEvent(Int32, XmlSeverityType, String, String)`

- `Void SendValidationEvent(XmlSeverityType, String, String)`

- `Void SendValidationEvent(XmlSeverityType, XmlSchemaException)`

- `Boolean IsAttributeValueType(Token)`

- `Int32 get_LineNo()`

- `Int32 get_LinePos()`

- `String get_BaseUriStr()`

- `Void OnUnexpectedError()`

- `Void Throw(Int32, String)`

- `Void Throw(Int32, String, String)`

- `Void Throw(Int32, String, String[])`

- `Void Throw(String, String, Int32, Int32)`

- `Void ThrowInvalidChar(Int32, String, Int32)`

- `Void ThrowInvalidChar(Char[], Int32, Int32)`

- `Void ThrowUnexpectedToken(Int32, String)`

- `Void ThrowUnexpectedToken(Int32, String, String)`

- `String ParseUnexpectedToken(Int32)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class DtdParser : IDtdParser
{
	private IDtdParserAdapter readerAdapter; // 0x10
	private IDtdParserAdapterWithValidation readerAdapterWithValidation; // 0x18
	private XmlNameTable nameTable; // 0x20
	private SchemaInfo schemaInfo; // 0x28
	private XmlCharType xmlCharType; // 0x30
	private String systemId; // 0x38
	private String publicId; // 0x40
	private Boolean normalize; // 0x48
	private Boolean validate; // 0x49
	private Boolean supportNamespaces; // 0x4a
	private Boolean v1Compat; // 0x4b
	private Char[] chars; // 0x50
	private Int32 charsUsed; // 0x58
	private Int32 curPos; // 0x5c
	private ScanningFunction scanningFunction; // 0x60
	private ScanningFunction nextScaningFunction; // 0x64
	private ScanningFunction savedScanningFunction; // 0x68
	private Boolean whitespaceSeen; // 0x6c
	private Int32 tokenStartPos; // 0x70
	private Int32 colonPos; // 0x74
	private StringBuilder internalSubsetValueSb; // 0x78
	private Int32 externalEntitiesDepth; // 0x80
	private Int32 currentEntityId; // 0x84
	private Boolean freeFloatingDtd; // 0x88
	private Boolean hasFreeFloatingInternalSubset; // 0x89
	private StringBuilder stringBuilder; // 0x90
	private Int32 condSectionDepth; // 0x98
	private LineInfo literalLineInfo; // 0x9c
	private Char literalQuoteChar; // 0xa4
	private String documentBaseUri; // 0xa8
	private String externalDtdBaseUri; // 0xb0
	private Dictionary`2 undeclaredNotations; // 0xb8
	private Int32[] condSectionEntityIds; // 0xc0

	private Boolean ParsingInternalSubset { get; }
	private Boolean IgnoreEntityReferences { get; }
	private Boolean SaveInternalSubsetValue { get; }
	private Boolean ParsingTopLevelMarkup { get; }
	private Boolean SupportNamespaces { get; }
	private Boolean Normalize { get; }
	private Int32 LineNo { get; }
	private Int32 LinePos { get; }
	private String BaseUriStr { get; }

	// RVA: 0x62b87dc VA: 0x75988d07dc
	private Void .ctor() { }
	// RVA: 0x62b2c64 VA: 0x75988cac64
	internal static IDtdParser Create() { }
	// RVA: 0x62b88b8 VA: 0x75988d08b8
	private Void Initialize(IDtdParserAdapter readerAdapter) { }
	// RVA: 0x62b8ce0 VA: 0x75988d0ce0
	private Void InitializeFreeFloatingDtd(String baseUri, String docTypeName, String publicId, String systemId, String internalSubset, IDtdParserAdapter adapter) { }
	// RVA: 0x62b915c VA: 0x75988d115c
	private IDtdInfo System.Xml.IDtdParser.ParseInternalDtd(IDtdParserAdapter adapter, Boolean saveInternalSubset) { }
	// RVA: 0x62b93e8 VA: 0x75988d13e8
	private IDtdInfo System.Xml.IDtdParser.ParseFreeFloatingDtd(String baseUri, String docTypeName, String publicId, String systemId, String internalSubset, IDtdParserAdapter adapter) { }
	// RVA: 0x62b940c VA: 0x75988d140c
	private Boolean get_ParsingInternalSubset() { }
	// RVA: 0x62b941c VA: 0x75988d141c
	private Boolean get_IgnoreEntityReferences() { }
	// RVA: 0x62b942c VA: 0x75988d142c
	private Boolean get_SaveInternalSubsetValue() { }
	// RVA: 0x62b94ec VA: 0x75988d14ec
	private Boolean get_ParsingTopLevelMarkup() { }
	// RVA: 0x62b951c VA: 0x75988d151c
	private Boolean get_SupportNamespaces() { }
	// RVA: 0x62b9524 VA: 0x75988d1524
	private Boolean get_Normalize() { }
	// RVA: 0x62b918c VA: 0x75988d118c
	private Void Parse(Boolean saveInternalSubset) { }
	// RVA: 0x62b9580 VA: 0x75988d1580
	private Void ParseInDocumentDtd(Boolean saveInternalSubset) { }
	// RVA: 0x62b952c VA: 0x75988d152c
	private Void ParseFreeFloatingDtd() { }
	// RVA: 0x62baac8 VA: 0x75988d2ac8
	private Void ParseInternalSubset() { }
	// RVA: 0x62baacc VA: 0x75988d2acc
	private Void ParseExternalSubset() { }
	// RVA: 0x62bac7c VA: 0x75988d2c7c
	private Void ParseSubset() { }
	// RVA: 0x62baff4 VA: 0x75988d2ff4
	private Void ParseAttlistDecl() { }
	// RVA: 0x62bca80 VA: 0x75988d4a80
	private Void ParseAttlistType(SchemaAttDef attrDef, SchemaElementDecl elementDecl, Boolean ignoreErrors) { }
	// RVA: 0x62bcff4 VA: 0x75988d4ff4
	private Void ParseAttlistDefault(SchemaAttDef attrDef, Boolean ignoreErrors) { }
	// RVA: 0x62bb5bc VA: 0x75988d35bc
	private Void ParseElementDecl() { }
	// RVA: 0x62bd7a8 VA: 0x75988d57a8
	private Void ParseElementOnlyContent(ParticleContentValidator pcv, Int32 startParenEntityId) { }
	// RVA: 0x62bdaf8 VA: 0x75988d5af8
	private Void ParseHowMany(ParticleContentValidator pcv) { }
	// RVA: 0x62bd504 VA: 0x75988d5504
	private Void ParseElementMixedContent(ParticleContentValidator pcv, Int32 startParenEntityId) { }
	// RVA: 0x62bb958 VA: 0x75988d3958
	private Void ParseEntityDecl() { }
	// RVA: 0x62bbce0 VA: 0x75988d3ce0
	private Void ParseNotationDecl() { }
	// RVA: 0x62bd2a4 VA: 0x75988d52a4
	private Void AddUndeclaredNotation(String notationName) { }
	// RVA: 0x62bbee4 VA: 0x75988d3ee4
	private Void ParseComment() { }
	// RVA: 0x62bc128 VA: 0x75988d4128
	private Void ParsePI() { }
	// RVA: 0x62bc2f4 VA: 0x75988d42f4
	private Void ParseCondSection() { }
	// RVA: 0x62ba540 VA: 0x75988d2540
	private Void ParseExternalId(Token idTokenType, Token declType, out String publicId, out String systemId) { }
	// RVA: 0x62b9ad8 VA: 0x75988d1ad8
	private Token GetToken(Boolean needWhiteSpace) { }
	// RVA: 0x62be314 VA: 0x75988d6314
	private Token ScanSubsetContent() { }
	// RVA: 0x62be2ac VA: 0x75988d62ac
	private Token ScanNameExpected() { }
	// RVA: 0x62be2d0 VA: 0x75988d62d0
	private Token ScanQNameExpected() { }
	// RVA: 0x62be2f4 VA: 0x75988d62f4
	private Token ScanNmtokenExpected() { }
	// RVA: 0x62bea18 VA: 0x75988d6a18
	private Token ScanDoctype1() { }
	// RVA: 0x62beb34 VA: 0x75988d6b34
	private Token ScanDoctype2() { }
	// RVA: 0x62c0d68 VA: 0x75988d8d68
	private Token ScanClosingTag() { }
	// RVA: 0x62bebdc VA: 0x75988d6bdc
	private Token ScanElement1() { }
	// RVA: 0x62bedac VA: 0x75988d6dac
	private Token ScanElement2() { }
	// RVA: 0x62bef50 VA: 0x75988d6f50
	private Token ScanElement3() { }
	// RVA: 0x62befd0 VA: 0x75988d6fd0
	private Token ScanElement4() { }
	// RVA: 0x62bf09c VA: 0x75988d709c
	private Token ScanElement5() { }
	// RVA: 0x62bf188 VA: 0x75988d7188
	private Token ScanElement6() { }
	// RVA: 0x62bf258 VA: 0x75988d7258
	private Token ScanElement7() { }
	// RVA: 0x62bf2b8 VA: 0x75988d72b8
	private Token ScanAttlist1() { }
	// RVA: 0x62bf37c VA: 0x75988d737c
	private Token ScanAttlist2() { }
	// RVA: 0x62bf9fc VA: 0x75988d79fc
	private Token ScanAttlist3() { }
	// RVA: 0x62bfa9c VA: 0x75988d7a9c
	private Token ScanAttlist4() { }
	// RVA: 0x62bfb6c VA: 0x75988d7b6c
	private Token ScanAttlist5() { }
	// RVA: 0x62bfc3c VA: 0x75988d7c3c
	private Token ScanAttlist6() { }
	// RVA: 0x62bffb0 VA: 0x75988d7fb0
	private Token ScanAttlist7() { }
	// RVA: 0x62c13ac VA: 0x75988d93ac
	private Token ScanLiteral(LiteralType literalType) { }
	// RVA: 0x62c1e34 VA: 0x75988d9e34
	private XmlQualifiedName ScanEntityName() { }
	// RVA: 0x62c006c VA: 0x75988d806c
	private Token ScanNotation1() { }
	// RVA: 0x62c0164 VA: 0x75988d8164
	private Token ScanSystemId() { }
	// RVA: 0x62c0334 VA: 0x75988d8334
	private Token ScanEntity1() { }
	// RVA: 0x62c03a8 VA: 0x75988d83a8
	private Token ScanEntity2() { }
	// RVA: 0x62c04d4 VA: 0x75988d84d4
	private Token ScanEntity3() { }
	// RVA: 0x62c0218 VA: 0x75988d8218
	private Token ScanPublicId1() { }
	// RVA: 0x62c02cc VA: 0x75988d82cc
	private Token ScanPublicId2() { }
	// RVA: 0x62c05e8 VA: 0x75988d85e8
	private Token ScanCondSection1() { }
	// RVA: 0x62c0884 VA: 0x75988d8884
	private Token ScanCondSection2() { }
	// RVA: 0x62c091c VA: 0x75988d891c
	private Token ScanCondSection3() { }
	// RVA: 0x62c1068 VA: 0x75988d9068
	private Void ScanName() { }
	// RVA: 0x62c1070 VA: 0x75988d9070
	private Void ScanQName() { }
	// RVA: 0x62c2194 VA: 0x75988da194
	private Void ScanQName(Boolean isQName) { }
	// RVA: 0x62c2414 VA: 0x75988da414
	private Boolean ReadDataInName() { }
	// RVA: 0x62c1078 VA: 0x75988d9078
	private Void ScanNmtoken() { }
	// RVA: 0x62c11e4 VA: 0x75988d91e4
	private Boolean EatPublicKeyword() { }
	// RVA: 0x62c12c8 VA: 0x75988d92c8
	private Boolean EatSystemKeyword() { }
	// RVA: 0x62ba3d0 VA: 0x75988d23d0
	private XmlQualifiedName GetNameQualified(Boolean canHavePrefix) { }
	// RVA: 0x62bd288 VA: 0x75988d5288
	private String GetNameString() { }
	// RVA: 0x62bd42c VA: 0x75988d542c
	private String GetNmtokenString() { }
	// RVA: 0x62bd4a8 VA: 0x75988d54a8
	private String GetValue() { }
	// RVA: 0x62bd448 VA: 0x75988d5448
	private String GetValueWithStrippedSpaces() { }
	// RVA: 0x62c0dfc VA: 0x75988d8dfc
	private Int32 ReadData() { }
	// RVA: 0x62b994c VA: 0x75988d194c
	private Void LoadParsingBuffer() { }
	// RVA: 0x62baac0 VA: 0x75988d2ac0
	private Void SaveParsingBuffer() { }
	// RVA: 0x62bc608 VA: 0x75988d4608
	private Void SaveParsingBuffer(Int32 internalSubsetValueEndPos) { }
	// RVA: 0x62be1a0 VA: 0x75988d61a0
	private Boolean HandleEntityReference(Boolean paramEntity, Boolean inLiteral, Boolean inAttribute) { }
	// RVA: 0x62c2680 VA: 0x75988da680
	private Boolean HandleEntityReference(XmlQualifiedName entityName, Boolean paramEntity, Boolean inLiteral, Boolean inAttribute) { }
	// RVA: 0x62c0ec0 VA: 0x75988d8ec0
	private Boolean HandleEntityEnd(Boolean inLiteral) { }
	// RVA: 0x62c1f94 VA: 0x75988d9f94
	private SchemaEntity VerifyEntityReference(XmlQualifiedName entityName, Boolean paramEntity, Boolean mustBeDeclared, Boolean inAttribute) { }
	// RVA: 0x62bc52c VA: 0x75988d452c
	private Void SendValidationEvent(Int32 pos, XmlSeverityType severity, String code, String arg) { }
	// RVA: 0x62bd1c0 VA: 0x75988d51c0
	private Void SendValidationEvent(XmlSeverityType severity, String code, String arg) { }
	// RVA: 0x62b980c VA: 0x75988d180c
	private Void SendValidationEvent(XmlSeverityType severity, XmlSchemaException e) { }
	// RVA: 0x62bd1b4 VA: 0x75988d51b4
	private Boolean IsAttributeValueType(Token token) { }
	// RVA: 0x62bc75c VA: 0x75988d475c
	private Int32 get_LineNo() { }
	// RVA: 0x62bc800 VA: 0x75988d4800
	private Int32 get_LinePos() { }
	// RVA: 0x62b96e8 VA: 0x75988d16e8
	private String get_BaseUriStr() { }
	// RVA: 0x62ba384 VA: 0x75988d2384
	private Void OnUnexpectedError() { }
	// RVA: 0x62bc28c VA: 0x75988d428c
	private Void Throw(Int32 curPos, String res) { }
	// RVA: 0x62bdb68 VA: 0x75988d5b68
	private Void Throw(Int32 curPos, String res, String arg) { }
	// RVA: 0x62bdf38 VA: 0x75988d5f38
	private Void Throw(Int32 curPos, String res, String[] args) { }
	// RVA: 0x62bc8b0 VA: 0x75988d48b0
	private Void Throw(String res, String arg, Int32 lineNo, Int32 linePos) { }
	// RVA: 0x62b90e0 VA: 0x75988d10e0
	private Void ThrowInvalidChar(Int32 pos, String data, Int32 invCharPos) { }
	// RVA: 0x62be120 VA: 0x75988d6120
	private Void ThrowInvalidChar(Char[] data, Int32 length, Int32 invCharPos) { }
	// RVA: 0x62bc754 VA: 0x75988d4754
	private Void ThrowUnexpectedToken(Int32 pos, String expectedToken) { }
	// RVA: 0x62bdd50 VA: 0x75988d5d50
	private Void ThrowUnexpectedToken(Int32 pos, String expectedToken1, String expectedToken2) { }
	// RVA: 0x62be1f0 VA: 0x75988d61f0
	private String ParseUnexpectedToken(Int32 startPos) { }
	// RVA: 0x62c2458 VA: 0x75988da458
	internal static String StripSpaces(String value) { }
}
```