# XmlWellFormedWriter

**Namespace:** `System.Xml`


## Fields

- `XmlWriter writer`

- `XmlRawWriter rawWriter`

- `IXmlNamespaceResolver predefinedNamespaces`

- `Int32 nsTop`

- `Boolean useNsHashtable`

- `Int32 elemTop`

- `Int32 attrCount`

- `SpecialAttribute specAttr`

- `AttributeValueCache attrValueCache`

- `String curDeclPrefix`

- `State currentState`

- `Boolean checkCharacters`

- `Boolean omitDuplNamespaces`

- `Boolean writeEndDocumentOnClose`

- `ConformanceLevel conformanceLevel`

- `Boolean dtdWritten`

- `Boolean xmlDeclFollows`

- `XmlCharType xmlCharType`

- `SecureStringHasher hasher`


## Properties

- `Boolean SaveAttrValue`

- `Boolean InBase64`

- `Boolean IsClosedOrErrorState`


## Methods

- `Boolean get_SaveAttrValue()`

- `Boolean get_InBase64()`

- `Void SetSpecialAttribute(SpecialAttribute)`

- `Void WriteStartDocumentImpl(XmlStandalone)`

- `Void StartFragment()`

- `Void PushNamespaceImplicit(String, String)`

- `Boolean PushNamespaceExplicit(String, String)`

- `Void AddNamespace(String, String, NamespaceKind)`

- `Void AddToNamespaceHashtable(Int32)`

- `Int32 LookupNamespaceIndex(String)`

- `Void PopNamespaces(Int32, Int32)`

- `Void AdvanceState(Token)`

- `Void StartElementContent()`

- `String LookupLocalNamespace(String)`

- `String GeneratePrefix()`

- `Void CheckNCName(String)`

- `Void ThrowInvalidStateTransition(Token, State)`

- `Boolean get_IsClosedOrErrorState()`

- `Void AddAttribute(String, String, String)`

- `Void AddToAttrHashTable(Int32)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class XmlWellFormedWriter : XmlWriter
{
	private XmlWriter writer; // 0x10
	private XmlRawWriter rawWriter; // 0x18
	private IXmlNamespaceResolver predefinedNamespaces; // 0x20
	private Namespace[] nsStack; // 0x28
	private Int32 nsTop; // 0x30
	private Dictionary`2 nsHashtable; // 0x38
	private Boolean useNsHashtable; // 0x40
	private ElementScope[] elemScopeStack; // 0x48
	private Int32 elemTop; // 0x50
	private AttrName[] attrStack; // 0x58
	private Int32 attrCount; // 0x60
	private Dictionary`2 attrHashTable; // 0x68
	private SpecialAttribute specAttr; // 0x70
	private AttributeValueCache attrValueCache; // 0x78
	private String curDeclPrefix; // 0x80
	private State[] stateTable; // 0x88
	private State currentState; // 0x90
	private Boolean checkCharacters; // 0x94
	private Boolean omitDuplNamespaces; // 0x95
	private Boolean writeEndDocumentOnClose; // 0x96
	private ConformanceLevel conformanceLevel; // 0x98
	private Boolean dtdWritten; // 0x9c
	private Boolean xmlDeclFollows; // 0x9d
	private XmlCharType xmlCharType; // 0xa0
	private SecureStringHasher hasher; // 0xa8
	internal static readonly String[] stateName; // 0x0
	internal static readonly String[] tokenName; // 0x8
	private static WriteState[] state2WriteState; // 0x10
	private static readonly State[] StateTableDocument; // 0x18
	private static readonly State[] StateTableAuto; // 0x20

	public override WriteState WriteState { get; }
	internal XmlRawWriter RawWriter { get; }
	private Boolean SaveAttrValue { get; }
	private Boolean InBase64 { get; }
	private Boolean IsClosedOrErrorState { get; }

	// RVA: 0x629c69c VA: 0x75988b469c
	internal Void .ctor(XmlWriter writer, XmlWriterSettings settings) { }
	// RVA: 0x629cca8 VA: 0x75988b4ca8
	public override WriteState get_WriteState() { }
	// RVA: 0x629cd3c VA: 0x75988b4d3c
	public override Void WriteStartDocument() { }
	// RVA: 0x629cf04 VA: 0x75988b4f04
	public override Void WriteStartDocument(Boolean standalone) { }
	// RVA: 0x629cf20 VA: 0x75988b4f20
	public override Void WriteEndDocument() { }
	// RVA: 0x629d388 VA: 0x75988b5388
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x629d880 VA: 0x75988b5880
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x629e2ac VA: 0x75988b62ac
	public override Void WriteEndElement() { }
	// RVA: 0x629e59c VA: 0x75988b659c
	public override Void WriteFullEndElement() { }
	// RVA: 0x629e7b8 VA: 0x75988b67b8
	public override Void WriteStartAttribute(String prefix, String localName, String namespaceName) { }
	// RVA: 0x629f3ec VA: 0x75988b73ec
	public override Void WriteEndAttribute() { }
	// RVA: 0x62a0958 VA: 0x75988b8958
	public override Void WriteCData(String text) { }
	// RVA: 0x62a0a5c VA: 0x75988b8a5c
	public override Void WriteComment(String text) { }
	// RVA: 0x62a0b60 VA: 0x75988b8b60
	public override Void WriteProcessingInstruction(String name, String text) { }
	// RVA: 0x62a0e1c VA: 0x75988b8e1c
	public override Void WriteEntityRef(String name) { }
	// RVA: 0x62a1134 VA: 0x75988b9134
	public override Void WriteCharEntity(Char ch) { }
	// RVA: 0x62a1374 VA: 0x75988b9374
	public override Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x62a15dc VA: 0x75988b95dc
	public override Void WriteWhitespace(String ws) { }
	// RVA: 0x62a17ec VA: 0x75988b97ec
	public override Void WriteString(String text) { }
	// RVA: 0x62a1950 VA: 0x75988b9950
	public override Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x62a1c88 VA: 0x75988b9c88
	public override Void WriteRaw(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x62a1fc0 VA: 0x75988b9fc0
	public override Void WriteRaw(String data) { }
	// RVA: 0x62a2100 VA: 0x75988ba100
	public override Void WriteBase64(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x62a2350 VA: 0x75988ba350
	public override Void Close() { }
	// RVA: 0x62a2538 VA: 0x75988ba538
	public override Void Flush() { }
	// RVA: 0x62a25ec VA: 0x75988ba5ec
	public override String LookupPrefix(String ns) { }
	// RVA: 0x62a286c VA: 0x75988ba86c
	public override Void WriteValue(String value) { }
	// RVA: 0x62a29bc VA: 0x75988ba9bc
	public override Void WriteBinHex(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x62a2b1c VA: 0x75988bab1c
	internal XmlRawWriter get_RawWriter() { }
	// RVA: 0x62a0f88 VA: 0x75988b8f88
	private Boolean get_SaveAttrValue() { }
	// RVA: 0x62a250c VA: 0x75988ba50c
	private Boolean get_InBase64() { }
	// RVA: 0x629eea0 VA: 0x75988b6ea0
	private Void SetSpecialAttribute(SpecialAttribute special) { }
	// RVA: 0x629cd44 VA: 0x75988b4d44
	private Void WriteStartDocumentImpl(XmlStandalone standalone) { }
	// RVA: 0x62a2ba0 VA: 0x75988baba0
	private Void StartFragment() { }
	// RVA: 0x629de80 VA: 0x75988b5e80
	private Void PushNamespaceImplicit(String prefix, String ns) { }
	// RVA: 0x629fc80 VA: 0x75988b7c80
	private Boolean PushNamespaceExplicit(String prefix, String ns) { }
	// RVA: 0x62a2c88 VA: 0x75988bac88
	private Void AddNamespace(String prefix, String ns, NamespaceKind kind) { }
	// RVA: 0x62a2f50 VA: 0x75988baf50
	private Void AddToNamespaceHashtable(Int32 namespaceIndex) { }
	// RVA: 0x62a2bac VA: 0x75988babac
	private Int32 LookupNamespaceIndex(String prefix) { }
	// RVA: 0x629e4c8 VA: 0x75988b64c8
	private Void PopNamespaces(Int32 indexFrom, Int32 indexTo) { }
	// RVA: 0x62a2e44 VA: 0x75988bae44
	private static XmlException DupAttrException(String prefix, String localName) { }
	// RVA: 0x629d07c VA: 0x75988b507c
	private Void AdvanceState(Token token) { }
	// RVA: 0x62a32c4 VA: 0x75988bb2c4
	private Void StartElementContent() { }
	// RVA: 0x62a3038 VA: 0x75988bb038
	private static String GetStateName(State state) { }
	// RVA: 0x629dd4c VA: 0x75988b5d4c
	internal String LookupNamespace(String prefix) { }
	// RVA: 0x629f078 VA: 0x75988b7078
	private String LookupLocalNamespace(String prefix) { }
	// RVA: 0x629ef44 VA: 0x75988b6f44
	private String GeneratePrefix() { }
	// RVA: 0x629dc4c VA: 0x75988b5c4c
	private Void CheckNCName(String ncname) { }
	// RVA: 0x62a34b8 VA: 0x75988bb4b8
	private static Exception InvalidCharsException(String name, Int32 badCharIndex) { }
	// RVA: 0x62a30d8 VA: 0x75988bb0d8
	private Void ThrowInvalidStateTransition(Token token, State currentState) { }
	// RVA: 0x62a2af0 VA: 0x75988baaf0
	private Boolean get_IsClosedOrErrorState() { }
	// RVA: 0x629f148 VA: 0x75988b7148
	private Void AddAttribute(String prefix, String localName, String namespaceName) { }
	// RVA: 0x62a3714 VA: 0x75988bb714
	private Void AddToAttrHashTable(Int32 attributeIndex) { }
	// RVA: 0x62a3850 VA: 0x75988bb850
	private static Void .cctor() { }
}
```