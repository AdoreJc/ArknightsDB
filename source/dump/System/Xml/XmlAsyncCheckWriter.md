# XmlAsyncCheckWriter

**Namespace:** `System.Xml`


## Fields

- `Task lastTask`


## Methods

- `Void CheckAsync()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class XmlAsyncCheckWriter : XmlWriter
{
	private readonly XmlWriter coreWriter; // 0x10
	private Task lastTask; // 0x18

	public override WriteState WriteState { get; }

	// RVA: 0x6278c90 VA: 0x7598890c90
	public Void .ctor(XmlWriter writer) { }
	// RVA: 0x6278d1c VA: 0x7598890d1c
	private Void CheckAsync() { }
	// RVA: 0x6278da0 VA: 0x7598890da0
	public override Void WriteStartDocument() { }
	// RVA: 0x6278dc8 VA: 0x7598890dc8
	public override Void WriteStartDocument(Boolean standalone) { }
	// RVA: 0x6278e00 VA: 0x7598890e00
	public override Void WriteEndDocument() { }
	// RVA: 0x6278e28 VA: 0x7598890e28
	public override Void WriteDocType(String name, String pubid, String sysid, String subset) { }
	// RVA: 0x6278e80 VA: 0x7598890e80
	public override Void WriteStartElement(String prefix, String localName, String ns) { }
	// RVA: 0x6278ed0 VA: 0x7598890ed0
	public override Void WriteEndElement() { }
	// RVA: 0x6278ef8 VA: 0x7598890ef8
	public override Void WriteFullEndElement() { }
	// RVA: 0x6278f20 VA: 0x7598890f20
	public override Void WriteStartAttribute(String prefix, String localName, String ns) { }
	// RVA: 0x6278f70 VA: 0x7598890f70
	public override Void WriteEndAttribute() { }
	// RVA: 0x6278f9c VA: 0x7598890f9c
	public override Void WriteCData(String text) { }
	// RVA: 0x6278fd8 VA: 0x7598890fd8
	public override Void WriteComment(String text) { }
	// RVA: 0x6279014 VA: 0x7598891014
	public override Void WriteProcessingInstruction(String name, String text) { }
	// RVA: 0x6279058 VA: 0x7598891058
	public override Void WriteEntityRef(String name) { }
	// RVA: 0x6279094 VA: 0x7598891094
	public override Void WriteCharEntity(Char ch) { }
	// RVA: 0x62790d0 VA: 0x75988910d0
	public override Void WriteWhitespace(String ws) { }
	// RVA: 0x627910c VA: 0x759889110c
	public override Void WriteString(String text) { }
	// RVA: 0x6279148 VA: 0x7598891148
	public override Void WriteSurrogateCharEntity(Char lowChar, Char highChar) { }
	// RVA: 0x627918c VA: 0x759889118c
	public override Void WriteChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x62791e0 VA: 0x75988911e0
	public override Void WriteRaw(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6279234 VA: 0x7598891234
	public override Void WriteRaw(String data) { }
	// RVA: 0x6279270 VA: 0x7598891270
	public override Void WriteBase64(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x62792c4 VA: 0x75988912c4
	public override Void WriteBinHex(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6279318 VA: 0x7598891318
	public override WriteState get_WriteState() { }
	// RVA: 0x6279344 VA: 0x7598891344
	public override Void Close() { }
	// RVA: 0x6279370 VA: 0x7598891370
	public override Void Flush() { }
	// RVA: 0x627939c VA: 0x759889139c
	public override String LookupPrefix(String ns) { }
	// RVA: 0x62793d8 VA: 0x75988913d8
	public override Void WriteValue(String value) { }
	// RVA: 0x6279414 VA: 0x7598891414
	protected override Void Dispose(Boolean disposing) { }
}
```