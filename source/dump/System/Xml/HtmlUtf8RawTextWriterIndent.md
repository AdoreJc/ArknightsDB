# HtmlUtf8RawTextWriterIndent

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
internal class HtmlUtf8RawTextWriterIndent : HtmlUtf8RawTextWriter
{
	private Int32 indentLevel; // 0xb4
	private Int32 endBlockPos; // 0xb8
	private String indentChars; // 0xc0
	private Boolean newLineOnAttributes; // 0xc8


	// RVA: 0x62774d4 VA: 0x759888f4d4
	public Void .ctor(Stream stream, XmlWriterSettings settings) { }
	// RVA: 0x627754c VA: 0x759888f54c
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x6277568 VA: 0x759888f568
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x627775c VA: 0x759888f75c
	internal override Void StartElementContent() { }
	// RVA: 0x62777d0 VA: 0x759888f7d0
	internal override Void WriteEndElement(String prefix, String localName, String ns) { }
	// RVA: 0x6277870 VA: 0x759888f870
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x62778e4 VA: 0x759888f8e4
	protected override Void FlushBuffer() { }
	// RVA: 0x627750c VA: 0x759888f50c
	private Void Init(XmlWriterSettings settings) { }
	// RVA: 0x627770c VA: 0x759888f70c
	private Void WriteIndent() { }
}
```