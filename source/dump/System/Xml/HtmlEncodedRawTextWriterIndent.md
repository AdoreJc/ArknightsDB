# HtmlEncodedRawTextWriterIndent

**Namespace:** `System.Xml`


## Fields

- `Int32 indentLevel`

- `Int32 endBlockPos`

- `String indentChars`

- `Boolean newLineOnAttributes`


## Methods

- `Void Init(XmlWriterSettings)`

- `Void WriteIndent()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class HtmlEncodedRawTextWriterIndent : HtmlEncodedRawTextWriter
{
	private Int32 indentLevel; // 0xe4
	private Int32 endBlockPos; // 0xe8
	private String indentChars; // 0xf0
	private Boolean newLineOnAttributes; // 0xf8


	// RVA: 0x627597c VA: 0x759888d97c
	public Void .ctor(TextWriter writer, XmlWriterSettings settings) { }
	// RVA: 0x62759f0 VA: 0x759888d9f0
	public Void .ctor(Stream stream, XmlWriterSettings settings) { }
	// RVA: 0x6275a24 VA: 0x759888da24
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x6275a40 VA: 0x759888da40
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x6275c3c VA: 0x759888dc3c
	internal override Void StartElementContent() { }
	// RVA: 0x6275cac VA: 0x759888dcac
	internal override Void WriteEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6275d4c VA: 0x759888dd4c
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x6275dbc VA: 0x759888ddbc
	protected override Void FlushBuffer() { }
	// RVA: 0x62759b0 VA: 0x759888d9b0
	private Void Init(XmlWriterSettings settings) { }
	// RVA: 0x6275bf4 VA: 0x759888dbf4
	private Void WriteIndent() { }
}
```