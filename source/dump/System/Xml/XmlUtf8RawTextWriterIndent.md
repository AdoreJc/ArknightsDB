# XmlUtf8RawTextWriterIndent

**Namespace:** `System.Xml`


## Fields

- `Int32 indentLevel`

- `Boolean newLineOnAttributes`

- `String indentChars`

- `Boolean mixedContent`

- `BitStack mixedContentStack`

- `ConformanceLevel conformanceLevel`


## Methods

- `Void Init(XmlWriterSettings)`

- `Void WriteIndent()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class XmlUtf8RawTextWriterIndent : XmlUtf8RawTextWriter
{
	protected Int32 indentLevel; // 0x88
	protected Boolean newLineOnAttributes; // 0x8c
	protected String indentChars; // 0x90
	protected Boolean mixedContent; // 0x98
	private BitStack mixedContentStack; // 0xa0
	protected ConformanceLevel conformanceLevel; // 0xa8


	// RVA: 0x629c194 VA: 0x75988b4194
	public Void .ctor(Stream stream, XmlWriterSettings settings) { }
	// RVA: 0x629c2f0 VA: 0x75988b42f0
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x629c398 VA: 0x75988b4398
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x629c404 VA: 0x75988b4404
	internal override Void StartElementContent() { }
	// RVA: 0x629c454 VA: 0x75988b4454
	internal override Void OnRootElement(ConformanceLevel currentConformanceLevel) { }
	// RVA: 0x629c45c VA: 0x75988b445c
	internal override Void WriteEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x629c4dc VA: 0x75988b44dc
	internal override Void WriteFullEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x629c55c VA: 0x75988b455c
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x629c598 VA: 0x75988b4598
	public override Void WriteCData(String text) { }
	// RVA: 0x629c5a4 VA: 0x75988b45a4
	public override Void WriteComment(String text) { }
	// RVA: 0x629c5e4 VA: 0x75988b45e4
	public override Void WriteProcessingInstruction(String target, String text) { }
	// RVA: 0x629c62c VA: 0x75988b462c
	public override Void WriteEntityRef(String name) { }
	// RVA: 0x629c638 VA: 0x75988b4638
	public override Void WriteCharEntity(Char ch) { }
	// RVA: 0x629c644 VA: 0x75988b4644
	public override Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x629c650 VA: 0x75988b4650
	public override Void WriteWhitespace(String ws) { }
	// RVA: 0x629c65c VA: 0x75988b465c
	public override Void WriteString(String text) { }
	// RVA: 0x629c668 VA: 0x75988b4668
	public override Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x629c674 VA: 0x75988b4674
	public override Void WriteRaw(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x629c680 VA: 0x75988b4680
	public override Void WriteRaw(String data) { }
	// RVA: 0x629c68c VA: 0x75988b468c
	public override Void WriteBase64(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x629c1bc VA: 0x75988b41bc
	private Void Init(XmlWriterSettings settings) { }
	// RVA: 0x629c350 VA: 0x75988b4350
	private Void WriteIndent() { }
}
```