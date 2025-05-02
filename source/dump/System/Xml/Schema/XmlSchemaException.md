# XmlSchemaException

**Namespace:** `System.Xml.Schema`


## Fields

- `String res`

- `String sourceUri`

- `Int32 lineNumber`

- `Int32 linePosition`

- `XmlSchemaObject sourceSchemaObject`

- `String message`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
public class XmlSchemaException : SystemException
{
	private String res; // 0x90
	private String[] args; // 0x98
	private String sourceUri; // 0xa0
	private Int32 lineNumber; // 0xa8
	private Int32 linePosition; // 0xac
	private XmlSchemaObject sourceSchemaObject; // 0xb0
	private String message; // 0xb8

	public override String Message { get; }

	// RVA: 0x62ef1e4 VA: 0x75989071e4
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x62ef6a8 VA: 0x75989076a8
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x62ef818 VA: 0x7598907818
	public Void .ctor() { }
	// RVA: 0x62ef82c VA: 0x759890782c
	public Void .ctor(String message) { }
	// RVA: 0x62e570c VA: 0x75988fd70c
	public Void .ctor(String message, Exception innerException) { }
	// RVA: 0x62ef83c VA: 0x759890783c
	public Void .ctor(String message, Exception innerException, Int32 lineNumber, Int32 linePosition) { }
	// RVA: 0x62df7ac VA: 0x75988f77ac
	internal Void .ctor(String res, String arg) { }
	// RVA: 0x62efa14 VA: 0x7598907a14
	internal Void .ctor(String res, String arg, String sourceUri, Int32 lineNumber, Int32 linePosition) { }
	// RVA: 0x62ef95c VA: 0x759890795c
	internal Void .ctor(String res, String[] args, Exception innerException, String sourceUri, Int32 lineNumber, Int32 linePosition, XmlSchemaObject source) { }
	// RVA: 0x62ef5e4 VA: 0x75989075e4
	internal static String CreateMessage(String res, String[] args) { }
	// RVA: 0x62efb04 VA: 0x7598907b04
	public override String get_Message() { }
}
```