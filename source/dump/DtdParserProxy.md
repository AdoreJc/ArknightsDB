# DtdParserProxy

**Namespace:** ` `


## Fields

- `XmlTextReaderImpl reader`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : 
internal class DtdParserProxy : IDtdParserAdapterV1, IDtdParserAdapterWithValidation, IDtdParserAdapter
{
	private XmlTextReaderImpl reader; // 0x10

	private XmlNameTable System.Xml.IDtdParserAdapter.NameTable { get; }
	private IXmlNamespaceResolver System.Xml.IDtdParserAdapter.NamespaceResolver { get; }
	private Uri System.Xml.IDtdParserAdapter.BaseUri { get; }
	private Boolean System.Xml.IDtdParserAdapter.IsEof { get; }
	private Char[] System.Xml.IDtdParserAdapter.ParsingBuffer { get; }
	private Int32 System.Xml.IDtdParserAdapter.ParsingBufferLength { get; }
	private Int32 System.Xml.IDtdParserAdapter.CurrentPosition { get; set; }
	private Int32 System.Xml.IDtdParserAdapter.EntityStackLength { get; }
	private Boolean System.Xml.IDtdParserAdapter.IsEntityEolNormalized { get; }
	private Int32 System.Xml.IDtdParserAdapter.LineNo { get; }
	private Int32 System.Xml.IDtdParserAdapter.LineStartPosition { get; }
	private Boolean System.Xml.IDtdParserAdapterWithValidation.DtdValidation { get; }
	private IValidationEventHandling System.Xml.IDtdParserAdapterWithValidation.ValidationEventHandling { get; }
	private Boolean System.Xml.IDtdParserAdapterV1.Normalization { get; }
	private Boolean System.Xml.IDtdParserAdapterV1.Namespaces { get; }
	private Boolean System.Xml.IDtdParserAdapterV1.V1CompatibilityMode { get; }

	// RVA: 0x6297e88 VA: 0x75988afe88
	internal Void .ctor(XmlTextReaderImpl reader) { }
	// RVA: 0x6297eb8 VA: 0x75988afeb8
	private XmlNameTable System.Xml.IDtdParserAdapter.get_NameTable() { }
	// RVA: 0x6297ed4 VA: 0x75988afed4
	private IXmlNamespaceResolver System.Xml.IDtdParserAdapter.get_NamespaceResolver() { }
	// RVA: 0x6297ef0 VA: 0x75988afef0
	private Uri System.Xml.IDtdParserAdapter.get_BaseUri() { }
	// RVA: 0x6297f0c VA: 0x75988aff0c
	private Boolean System.Xml.IDtdParserAdapter.get_IsEof() { }
	// RVA: 0x6297f28 VA: 0x75988aff28
	private Char[] System.Xml.IDtdParserAdapter.get_ParsingBuffer() { }
	// RVA: 0x6297f44 VA: 0x75988aff44
	private Int32 System.Xml.IDtdParserAdapter.get_ParsingBufferLength() { }
	// RVA: 0x6297f60 VA: 0x75988aff60
	private Int32 System.Xml.IDtdParserAdapter.get_CurrentPosition() { }
	// RVA: 0x6297f7c VA: 0x75988aff7c
	private Void System.Xml.IDtdParserAdapter.set_CurrentPosition(Int32 value) { }
	// RVA: 0x6297f98 VA: 0x75988aff98
	private Int32 System.Xml.IDtdParserAdapter.get_EntityStackLength() { }
	// RVA: 0x6297fb4 VA: 0x75988affb4
	private Boolean System.Xml.IDtdParserAdapter.get_IsEntityEolNormalized() { }
	// RVA: 0x6297fd0 VA: 0x75988affd0
	private Void System.Xml.IDtdParserAdapter.OnNewLine(Int32 pos) { }
	// RVA: 0x6297fec VA: 0x75988affec
	private Int32 System.Xml.IDtdParserAdapter.get_LineNo() { }
	// RVA: 0x6298008 VA: 0x75988b0008
	private Int32 System.Xml.IDtdParserAdapter.get_LineStartPosition() { }
	// RVA: 0x6298024 VA: 0x75988b0024
	private Int32 System.Xml.IDtdParserAdapter.ReadData() { }
	// RVA: 0x6298040 VA: 0x75988b0040
	private Int32 System.Xml.IDtdParserAdapter.ParseNumericCharRef(StringBuilder internalSubsetBuilder) { }
	// RVA: 0x629805c VA: 0x75988b005c
	private Int32 System.Xml.IDtdParserAdapter.ParseNamedCharRef(Boolean expand, StringBuilder internalSubsetBuilder) { }
	// RVA: 0x629807c VA: 0x75988b007c
	private Void System.Xml.IDtdParserAdapter.ParsePI(StringBuilder sb) { }
	// RVA: 0x6298098 VA: 0x75988b0098
	private Void System.Xml.IDtdParserAdapter.ParseComment(StringBuilder sb) { }
	// RVA: 0x62980b4 VA: 0x75988b00b4
	private Boolean System.Xml.IDtdParserAdapter.PushEntity(IDtdEntityInfo entity, out Int32 entityId) { }
	// RVA: 0x62980d0 VA: 0x75988b00d0
	private Boolean System.Xml.IDtdParserAdapter.PopEntity(out IDtdEntityInfo oldEntity, out Int32 newEntityId) { }
	// RVA: 0x62980ec VA: 0x75988b00ec
	private Boolean System.Xml.IDtdParserAdapter.PushExternalSubset(String systemId, String publicId) { }
	// RVA: 0x6298108 VA: 0x75988b0108
	private Void System.Xml.IDtdParserAdapter.PushInternalDtd(String baseUri, String internalDtd) { }
	// RVA: 0x6298124 VA: 0x75988b0124
	private Void System.Xml.IDtdParserAdapter.Throw(Exception e) { }
	// RVA: 0x6298140 VA: 0x75988b0140
	private Void System.Xml.IDtdParserAdapter.OnSystemId(String systemId, LineInfo keywordLineInfo, LineInfo systemLiteralLineInfo) { }
	// RVA: 0x629815c VA: 0x75988b015c
	private Void System.Xml.IDtdParserAdapter.OnPublicId(String publicId, LineInfo keywordLineInfo, LineInfo publicLiteralLineInfo) { }
	// RVA: 0x6298178 VA: 0x75988b0178
	private Boolean System.Xml.IDtdParserAdapterWithValidation.get_DtdValidation() { }
	// RVA: 0x6298194 VA: 0x75988b0194
	private IValidationEventHandling System.Xml.IDtdParserAdapterWithValidation.get_ValidationEventHandling() { }
	// RVA: 0x62981b0 VA: 0x75988b01b0
	private Boolean System.Xml.IDtdParserAdapterV1.get_Normalization() { }
	// RVA: 0x62981cc VA: 0x75988b01cc
	private Boolean System.Xml.IDtdParserAdapterV1.get_Namespaces() { }
	// RVA: 0x62981e8 VA: 0x75988b01e8
	private Boolean System.Xml.IDtdParserAdapterV1.get_V1CompatibilityMode() { }
}
```