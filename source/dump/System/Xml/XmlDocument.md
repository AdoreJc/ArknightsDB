# XmlDocument

**Namespace:** `System.Xml`


## Fields

- `XmlImplementation implementation`

- `DomNameTable domNameTable`

- `XmlLinkedNode lastChild`

- `XmlNamedNodeMap entities`

- `Hashtable htElementIdMap`

- `Hashtable htElementIDAttrDecl`

- `SchemaInfo schemaInfo`

- `XmlSchemaSet schemas`

- `Boolean reportValidity`

- `Boolean actualLoadingStatus`

- `XmlNodeChangedEventHandler onNodeInsertingDelegate`

- `XmlNodeChangedEventHandler onNodeInsertedDelegate`

- `XmlNodeChangedEventHandler onNodeRemovingDelegate`

- `XmlNodeChangedEventHandler onNodeRemovedDelegate`

- `XmlNodeChangedEventHandler onNodeChangingDelegate`

- `XmlNodeChangedEventHandler onNodeChangedDelegate`

- `Boolean preserveWhitespace`

- `Boolean isLoading`

- `XmlResolver resolver`


## Properties

- `XmlImplementation Implementation`

- `XmlElement DocumentElement`

- `XmlSchemaSet Schemas`

- `XmlNameTable NameTable`


## Methods

- `XmlName GetIDInfoByElement_(XmlName)`

- `WeakReference GetElement(ArrayList, XmlElement)`

- `XmlImplementation get_Implementation()`

- `XmlElement get_DocumentElement()`

- `Void set_Schemas(XmlSchemaSet)`

- `Boolean HasNodeTypeInPrevSiblings(XmlNodeType, XmlNode)`

- `Boolean HasNodeTypeInNextSiblings(XmlNodeType, XmlNode)`

- `XmlAttribute CreateAttribute(String)`

- `XmlElement CreateElement(String)`

- `SchemaElementDecl GetSchemaElementDecl(XmlElement)`

- `XmlAttribute PrepareDefaultAttribute(SchemaAttDef, String, String, String)`

- `XmlAttribute CreateAttribute(String, String)`

- `XmlElement CreateElement(String, String)`

- `XmlNode ImportNodeInternal(XmlNode, Boolean)`

- `Void ImportAttributes(XmlNode, XmlNode)`

- `Void ImportChildren(XmlNode, XmlNode, Boolean)`

- `XmlNameTable get_NameTable()`

- `XmlTextReader SetupReader(XmlTextReader)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlDocument : XmlNode
{
	private XmlImplementation implementation; // 0x18
	private DomNameTable domNameTable; // 0x20
	private XmlLinkedNode lastChild; // 0x28
	private XmlNamedNodeMap entities; // 0x30
	private Hashtable htElementIdMap; // 0x38
	private Hashtable htElementIDAttrDecl; // 0x40
	private SchemaInfo schemaInfo; // 0x48
	private XmlSchemaSet schemas; // 0x50
	private Boolean reportValidity; // 0x58
	private Boolean actualLoadingStatus; // 0x59
	private XmlNodeChangedEventHandler onNodeInsertingDelegate; // 0x60
	private XmlNodeChangedEventHandler onNodeInsertedDelegate; // 0x68
	private XmlNodeChangedEventHandler onNodeRemovingDelegate; // 0x70
	private XmlNodeChangedEventHandler onNodeRemovedDelegate; // 0x78
	private XmlNodeChangedEventHandler onNodeChangingDelegate; // 0x80
	private XmlNodeChangedEventHandler onNodeChangedDelegate; // 0x88
	internal Boolean fEntRefNodesPresent; // 0x90
	internal Boolean fCDataNodesPresent; // 0x91
	private Boolean preserveWhitespace; // 0x92
	private Boolean isLoading; // 0x93
	internal String strDocumentName; // 0x98
	internal String strDocumentFragmentName; // 0xa0
	internal String strCommentName; // 0xa8
	internal String strTextName; // 0xb0
	internal String strCDataSectionName; // 0xb8
	internal String strEntityName; // 0xc0
	internal String strID; // 0xc8
	internal String strXmlns; // 0xd0
	internal String strXml; // 0xd8
	internal String strSpace; // 0xe0
	internal String strLang; // 0xe8
	internal String strEmpty; // 0xf0
	internal String strNonSignificantWhitespaceName; // 0xf8
	internal String strSignificantWhitespaceName; // 0x100
	internal String strReservedXmlns; // 0x108
	internal String strReservedXml; // 0x110
	internal String baseURI; // 0x118
	private XmlResolver resolver; // 0x120
	internal Boolean bSetResolver; // 0x128
	internal Object objLock; // 0x130
	internal static EmptyEnumerator EmptyEnumerator; // 0x0
	internal static IXmlSchemaInfo NotKnownSchemaInfo; // 0x8
	internal static IXmlSchemaInfo ValidSchemaInfo; // 0x10
	internal static IXmlSchemaInfo InvalidSchemaInfo; // 0x18

	internal SchemaInfo DtdSchemaInfo { get; set; }
	public override XmlNodeType NodeType { get; }
	public override XmlNode ParentNode { get; }
	public virtual XmlDocumentType DocumentType { get; }
	internal virtual XmlDeclaration Declaration { get; }
	public XmlImplementation Implementation { get; }
	public override String Name { get; }
	public override String LocalName { get; }
	public XmlElement DocumentElement { get; }
	internal override Boolean IsContainer { get; }
	internal override XmlLinkedNode LastNode { get; set; }
	public override XmlDocument OwnerDocument { get; }
	public XmlSchemaSet Schemas { set; }
	internal Boolean CanReportValidity { get; }
	internal Boolean HasSetResolver { get; }
	public virtual XmlResolver XmlResolver { set; }
	public XmlNameTable NameTable { get; }
	public override Boolean IsReadOnly { get; }
	internal XmlNamedNodeMap Entities { get; set; }
	internal Boolean IsLoading { get; set; }
	internal Boolean ActualLoadingStatus { get; }
	public override String InnerText { set; }
	public override String InnerXml { set; }
	public override String BaseURI { get; }

	// RVA: 0x62a8dd0 VA: 0x75988c0dd0
	public Void .ctor() { }
	// RVA: 0x62a8e34 VA: 0x75988c0e34
	protected internal Void .ctor(XmlImplementation imp) { }
	// RVA: 0x62a92ec VA: 0x75988c12ec
	internal SchemaInfo get_DtdSchemaInfo() { }
	// RVA: 0x62a92f4 VA: 0x75988c12f4
	internal Void set_DtdSchemaInfo(SchemaInfo value) { }
	// RVA: 0x62a5ef8 VA: 0x75988bdef8
	internal static Void CheckName(String name) { }
	// RVA: 0x62a92fc VA: 0x75988c12fc
	internal XmlName AddXmlName(String prefix, String localName, String namespaceURI, IXmlSchemaInfo schemaInfo) { }
	// RVA: 0x62a9314 VA: 0x75988c1314
	internal XmlName GetXmlName(String prefix, String localName, String namespaceURI, IXmlSchemaInfo schemaInfo) { }
	// RVA: 0x62a600c VA: 0x75988be00c
	internal XmlName AddAttrXmlName(String prefix, String localName, String namespaceURI, IXmlSchemaInfo schemaInfo) { }
	// RVA: 0x62a932c VA: 0x75988c132c
	internal Boolean AddIdInfo(XmlName eleName, XmlName attrName) { }
	// RVA: 0x62a93fc VA: 0x75988c13fc
	private XmlName GetIDInfoByElement_(XmlName eleName) { }
	// RVA: 0x62a7bc0 VA: 0x75988bfbc0
	internal XmlName GetIDInfoByElement(XmlName eleName) { }
	// RVA: 0x62a94d0 VA: 0x75988c14d0
	private WeakReference GetElement(ArrayList elementList, XmlElement elem) { }
	// RVA: 0x62a7bd4 VA: 0x75988bfbd4
	internal Void AddElementWithId(String id, XmlElement elem) { }
	// RVA: 0x62a7dd4 VA: 0x75988bfdd4
	internal Void RemoveElementWithId(String id, XmlElement elem) { }
	// RVA: 0x62a9b20 VA: 0x75988c1b20
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62a9c24 VA: 0x75988c1c24
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62a9c2c VA: 0x75988c1c2c
	public override XmlNode get_ParentNode() { }
	// RVA: 0x62a9c34 VA: 0x75988c1c34
	public virtual XmlDocumentType get_DocumentType() { }
	// RVA: 0x62a9cc0 VA: 0x75988c1cc0
	internal virtual XmlDeclaration get_Declaration() { }
	// RVA: 0x62a9d64 VA: 0x75988c1d64
	public XmlImplementation get_Implementation() { }
	// RVA: 0x62a9d6c VA: 0x75988c1d6c
	public override String get_Name() { }
	// RVA: 0x62a9d74 VA: 0x75988c1d74
	public override String get_LocalName() { }
	// RVA: 0x62a9d7c VA: 0x75988c1d7c
	public XmlElement get_DocumentElement() { }
	// RVA: 0x62a9e08 VA: 0x75988c1e08
	internal override Boolean get_IsContainer() { }
	// RVA: 0x62a9e10 VA: 0x75988c1e10
	internal override XmlLinkedNode get_LastNode() { }
	// RVA: 0x62a9e18 VA: 0x75988c1e18
	internal override Void set_LastNode(XmlLinkedNode value) { }
	// RVA: 0x62a9e20 VA: 0x75988c1e20
	public override XmlDocument get_OwnerDocument() { }
	// RVA: 0x62a9e28 VA: 0x75988c1e28
	public Void set_Schemas(XmlSchemaSet value) { }
	// RVA: 0x62a9e30 VA: 0x75988c1e30
	internal Boolean get_CanReportValidity() { }
	// RVA: 0x62a9e38 VA: 0x75988c1e38
	internal Boolean get_HasSetResolver() { }
	// RVA: 0x62a9e40 VA: 0x75988c1e40
	internal XmlResolver GetResolver() { }
	// RVA: 0x62a9e48 VA: 0x75988c1e48
	public virtual Void set_XmlResolver(XmlResolver value) { }
	// RVA: 0x62a9fec VA: 0x75988c1fec
	internal override Boolean IsValidChildType(XmlNodeType type) { }
	// RVA: 0x62aa0dc VA: 0x75988c20dc
	private Boolean HasNodeTypeInPrevSiblings(XmlNodeType nt, XmlNode refNode) { }
	// RVA: 0x62aa18c VA: 0x75988c218c
	private Boolean HasNodeTypeInNextSiblings(XmlNodeType nt, XmlNode refNode) { }
	// RVA: 0x62aa1f0 VA: 0x75988c21f0
	internal override Boolean CanInsertAfter(XmlNode newChild, XmlNode refChild) { }
	// RVA: 0x62aa2e8 VA: 0x75988c22e8
	public XmlAttribute CreateAttribute(String name) { }
	// RVA: 0x62aa3a8 VA: 0x75988c23a8
	internal Void SetDefaultNamespace(String prefix, String localName, ref String namespaceURI) { }
	// RVA: 0x62aa44c VA: 0x75988c244c
	public virtual XmlCDataSection CreateCDataSection(String data) { }
	// RVA: 0x62aa4d4 VA: 0x75988c24d4
	public virtual XmlComment CreateComment(String data) { }
	// RVA: 0x62aa554 VA: 0x75988c2554
	public virtual XmlDocumentType CreateDocumentType(String name, String publicId, String systemId, String internalSubset) { }
	// RVA: 0x62aa5e8 VA: 0x75988c25e8
	public virtual XmlDocumentFragment CreateDocumentFragment() { }
	// RVA: 0x62aa64c VA: 0x75988c264c
	public XmlElement CreateElement(String name) { }
	// RVA: 0x62aa6fc VA: 0x75988c26fc
	internal Void AddDefaultAttributes(XmlElement elem) { }
	// RVA: 0x62aa984 VA: 0x75988c2984
	private SchemaElementDecl GetSchemaElementDecl(XmlElement elem) { }
	// RVA: 0x62aaa94 VA: 0x75988c2a94
	private XmlAttribute PrepareDefaultAttribute(SchemaAttDef attdef, String attrPrefix, String attrLocalname, String attrNamespaceURI) { }
	// RVA: 0x62aab90 VA: 0x75988c2b90
	public virtual XmlEntityReference CreateEntityReference(String name) { }
	// RVA: 0x62aac04 VA: 0x75988c2c04
	public virtual XmlProcessingInstruction CreateProcessingInstruction(String target, String data) { }
	// RVA: 0x62aac80 VA: 0x75988c2c80
	public virtual XmlDeclaration CreateXmlDeclaration(String version, String encoding, String standalone) { }
	// RVA: 0x62aad08 VA: 0x75988c2d08
	public virtual XmlText CreateTextNode(String text) { }
	// RVA: 0x62aad7c VA: 0x75988c2d7c
	public virtual XmlSignificantWhitespace CreateSignificantWhitespace(String text) { }
	// RVA: 0x62aadf0 VA: 0x75988c2df0
	public virtual XmlWhitespace CreateWhitespace(String text) { }
	// RVA: 0x62aae64 VA: 0x75988c2e64
	public XmlAttribute CreateAttribute(String qualifiedName, String namespaceURI) { }
	// RVA: 0x62aaf08 VA: 0x75988c2f08
	public XmlElement CreateElement(String qualifiedName, String namespaceURI) { }
	// RVA: 0x62aafac VA: 0x75988c2fac
	private XmlNode ImportNodeInternal(XmlNode node, Boolean deep) { }
	// RVA: 0x62ab45c VA: 0x75988c345c
	private Void ImportAttributes(XmlNode fromElem, XmlNode toElem) { }
	// RVA: 0x62a9b88 VA: 0x75988c1b88
	private Void ImportChildren(XmlNode fromNode, XmlNode toNode, Boolean deep) { }
	// RVA: 0x62a58a0 VA: 0x75988bd8a0
	public XmlNameTable get_NameTable() { }
	// RVA: 0x62ab570 VA: 0x75988c3570
	public virtual XmlAttribute CreateAttribute(String prefix, String localName, String namespaceURI) { }
	// RVA: 0x62ab610 VA: 0x75988c3610
	protected internal virtual XmlAttribute CreateDefaultAttribute(String prefix, String localName, String namespaceURI) { }
	// RVA: 0x62ab69c VA: 0x75988c369c
	public virtual XmlElement CreateElement(String prefix, String localName, String namespaceURI) { }
	// RVA: 0x62ab754 VA: 0x75988c3754
	public override Boolean get_IsReadOnly() { }
	// RVA: 0x62ab75c VA: 0x75988c375c
	internal XmlNamedNodeMap get_Entities() { }
	// RVA: 0x62ab7dc VA: 0x75988c37dc
	internal Void set_Entities(XmlNamedNodeMap value) { }
	// RVA: 0x62ab7e4 VA: 0x75988c37e4
	internal Boolean get_IsLoading() { }
	// RVA: 0x62ab7ec VA: 0x75988c37ec
	internal Void set_IsLoading(Boolean value) { }
	// RVA: 0x62ab7f8 VA: 0x75988c37f8
	internal Boolean get_ActualLoadingStatus() { }
	// RVA: 0x62ab800 VA: 0x75988c3800
	private XmlTextReader SetupReader(XmlTextReader tr) { }
	// RVA: 0x62ab86c VA: 0x75988c386c
	public virtual Void Load(XmlReader reader) { }
	// RVA: 0x62ab980 VA: 0x75988c3980
	public virtual Void LoadXml(String xml) { }
	// RVA: 0x62abacc VA: 0x75988c3acc
	public override Void set_InnerText(String value) { }
	// RVA: 0x62abb2c VA: 0x75988c3b2c
	public override Void set_InnerXml(String value) { }
	// RVA: 0x62abb3c VA: 0x75988c3b3c
	internal override XmlNodeChangedEventArgs GetEventArgs(XmlNode node, XmlNode oldParent, XmlNode newParent, String oldValue, String newValue, XmlNodeChangedAction action) { }
	// RVA: 0x62a67b8 VA: 0x75988be7b8
	internal XmlNodeChangedEventArgs GetInsertEventArgsForLoad(XmlNode node, XmlNode newParent) { }
	// RVA: 0x62abc3c VA: 0x75988c3c3c
	internal override Void BeforeEvent(XmlNodeChangedEventArgs args) { }
	// RVA: 0x62abc90 VA: 0x75988c3c90
	internal override Void AfterEvent(XmlNodeChangedEventArgs args) { }
	// RVA: 0x62a792c VA: 0x75988bf92c
	internal XmlAttribute GetDefaultAttribute(XmlElement elem, String attrPrefix, String attrLocalname, String attrNamespaceURI) { }
	// RVA: 0x62abce4 VA: 0x75988c3ce4
	internal XmlEntity GetEntityNode(String name) { }
	// RVA: 0x62abdac VA: 0x75988c3dac
	public override String get_BaseURI() { }
	// RVA: 0x62abdb4 VA: 0x75988c3db4
	internal Void SetBaseURI(String inBaseURI) { }
	// RVA: 0x62abdc4 VA: 0x75988c3dc4
	internal override XmlNode AppendChildForLoad(XmlNode newChild, XmlDocument doc) { }
	// RVA: 0x62abfc4 VA: 0x75988c3fc4
	private static Void .cctor() { }
}
```