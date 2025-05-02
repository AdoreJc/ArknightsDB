# XmlEncodedRawTextWriterIndent

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
internal class XmlEncodedRawTextWriterIndent : XmlEncodedRawTextWriter
{
	protected Int32 indentLevel; // 0xb8
	protected Boolean newLineOnAttributes; // 0xbc
	protected String indentChars; // 0xc0
	protected Boolean mixedContent; // 0xc8
	private BitStack mixedContentStack; // 0xd0
	protected ConformanceLevel conformanceLevel; // 0xd8


	// RVA: 0x627c7b0 VA: 0x75988947b0
	public Void .ctor(TextWriter writer, XmlWriterSettings settings) { }
	// RVA: 0x627c914 VA: 0x7598894914
	public Void .ctor(Stream stream, XmlWriterSettings settings) { }
	// RVA: 0x627c93c VA: 0x759889493c
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x627c9e4 VA: 0x75988949e4
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x627ca7c VA: 0x7598894a7c
	internal override Void StartElementContent() { }
	// RVA: 0x627cac0 VA: 0x7598894ac0
	internal override Void OnRootElement(ConformanceLevel currentConformanceLevel) { }
	// RVA: 0x627cac8 VA: 0x7598894ac8
	internal override Void WriteEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x627cb60 VA: 0x7598894b60
	internal override Void WriteFullEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x627cbf8 VA: 0x7598894bf8
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x627cc34 VA: 0x7598894c34
	public override Void WriteCData(String text) { }
	// RVA: 0x627cc40 VA: 0x7598894c40
	public override Void WriteComment(String text) { }
	// RVA: 0x627cc80 VA: 0x7598894c80
	public override Void WriteProcessingInstruction(String target, String text) { }
	// RVA: 0x627ccc8 VA: 0x7598894cc8
	public override Void WriteEntityRef(String name) { }
	// RVA: 0x627ccd4 VA: 0x7598894cd4
	public override Void WriteCharEntity(Char ch) { }
	// RVA: 0x627cce0 VA: 0x7598894ce0
	public override Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x627ccec VA: 0x7598894cec
	public override Void WriteWhitespace(String ws) { }
	// RVA: 0x627ccf8 VA: 0x7598894cf8
	public override Void WriteString(String text) { }
	// RVA: 0x627cd04 VA: 0x7598894d04
	public override Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x627cd10 VA: 0x7598894d10
	public override Void WriteRaw(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x627cd1c VA: 0x7598894d1c
	public override Void WriteRaw(String data) { }
	// RVA: 0x627cd28 VA: 0x7598894d28
	public override Void WriteBase64(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x627c7d8 VA: 0x75988947d8
	private Void Init(XmlWriterSettings settings) { }
	// RVA: 0x627c99c VA: 0x759889499c
	private Void WriteIndent() { }
}
```