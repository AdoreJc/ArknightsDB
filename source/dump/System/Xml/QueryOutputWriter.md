# QueryOutputWriter

**Namespace:** `System.Xml`


## Fields

- `XmlRawWriter wrapped`

- `Boolean inCDataSection`

- `BitStack bitsCData`

- `XmlQualifiedName qnameCData`

- `Boolean outputDocType`

- `Boolean checkWellFormedDoc`

- `Boolean hasDocElem`

- `Boolean inAttr`

- `String systemId`

- `String publicId`

- `Int32 depth`


## Methods

- `Boolean StartCDataSection()`

- `Void EndCDataSection()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class QueryOutputWriter : XmlRawWriter
{
	private XmlRawWriter wrapped; // 0x20
	private Boolean inCDataSection; // 0x28
	private Dictionary`2 lookupCDataElems; // 0x30
	private BitStack bitsCData; // 0x38
	private XmlQualifiedName qnameCData; // 0x40
	private Boolean outputDocType; // 0x48
	private Boolean checkWellFormedDoc; // 0x49
	private Boolean hasDocElem; // 0x4a
	private Boolean inAttr; // 0x4b
	private String systemId; // 0x50
	private String publicId; // 0x58
	private Int32 depth; // 0x60

	internal override IXmlNamespaceResolver NamespaceResolver { set; }
	internal override Boolean SupportsNamespaceDeclarationInChunks { get; }

	// RVA: 0x6277a80 VA: 0x759888fa80
	public Void .ctor(XmlRawWriter writer, XmlWriterSettings settings) { }
	// RVA: 0x6277db0 VA: 0x759888fdb0
	internal override Void set_NamespaceResolver(IXmlNamespaceResolver value) { }
	// RVA: 0x6277df4 VA: 0x759888fdf4
	internal override Void WriteXmlDeclaration(XmlStandalone standalone) { }
	// RVA: 0x6277e18 VA: 0x759888fe18
	internal override Void WriteXmlDeclaration(String xmldecl) { }
	// RVA: 0x6277e3c VA: 0x759888fe3c
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x6277e74 VA: 0x759888fe74
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x6278044 VA: 0x7598890044
	internal override Void WriteEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x62780b4 VA: 0x75988900b4
	internal override Void WriteFullEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6278124 VA: 0x7598890124
	internal override Void StartElementContent() { }
	// RVA: 0x6278148 VA: 0x7598890148
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x6278174 VA: 0x7598890174
	public override Void WriteEndAttribute() { }
	// RVA: 0x62781a0 VA: 0x75988901a0
	internal override Void WriteNamespaceDeclaration(String prefix, String ns) { }
	// RVA: 0x62781c4 VA: 0x75988901c4
	internal override Boolean get_SupportsNamespaceDeclarationInChunks() { }
	// RVA: 0x62781e8 VA: 0x75988901e8
	internal override Void WriteStartNamespaceDeclaration(String prefix) { }
	// RVA: 0x627820c VA: 0x759889020c
	internal override Void WriteEndNamespaceDeclaration() { }
	// RVA: 0x6278230 VA: 0x7598890230
	public override Void WriteCData(String text) { }
	// RVA: 0x6278254 VA: 0x7598890254
	public override Void WriteComment(String text) { }
	// RVA: 0x6278280 VA: 0x7598890280
	public override Void WriteProcessingInstruction(String name, String text) { }
	// RVA: 0x62782ac VA: 0x75988902ac
	public override Void WriteWhitespace(String ws) { }
	// RVA: 0x6278358 VA: 0x7598890358
	public override Void WriteString(String text) { }
	// RVA: 0x62783c8 VA: 0x75988903c8
	public override Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6278450 VA: 0x7598890450
	public override Void WriteEntityRef(String name) { }
	// RVA: 0x627847c VA: 0x759889047c
	public override Void WriteCharEntity(Char ch) { }
	// RVA: 0x62784a8 VA: 0x75988904a8
	public override Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x62784d4 VA: 0x75988904d4
	public override Void WriteRaw(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x627855c VA: 0x759889055c
	public override Void WriteRaw(String data) { }
	// RVA: 0x62785cc VA: 0x75988905cc
	public override Void Close() { }
	// RVA: 0x6278674 VA: 0x7598890674
	public override Void Flush() { }
	// RVA: 0x627831c VA: 0x759889031c
	private Boolean StartCDataSection() { }
	// RVA: 0x627803c VA: 0x759889003c
	private Void EndCDataSection() { }
}
```