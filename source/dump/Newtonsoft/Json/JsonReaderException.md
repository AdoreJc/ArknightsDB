# JsonReaderException

**Namespace:** `Newtonsoft.Json`


## Fields

- `Int32 <LineNumber>k__BackingField`

- `Int32 <LinePosition>k__BackingField`

- `String <Path>k__BackingField`


## Properties

- `Int32 LineNumber`

- `Int32 LinePosition`

- `String Path`


## Methods

- `Void set_LineNumber(Int32)`

- `Void set_LinePosition(Int32)`

- `Void set_Path(String)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json
public class JsonReaderException : JsonException
{
	private Int32 <LineNumber>k__BackingField; // 0x8c
	private Int32 <LinePosition>k__BackingField; // 0x90
	private String <Path>k__BackingField; // 0x98

	private Int32 LineNumber { set; }
	private Int32 LinePosition { set; }
	private String Path { set; }

	// RVA: 0x6147f88 VA: 0x759875ff88
	private Void set_LineNumber(Int32 value) { }
	// RVA: 0x6147f90 VA: 0x759875ff90
	private Void set_LinePosition(Int32 value) { }
	// RVA: 0x6147f98 VA: 0x759875ff98
	private Void set_Path(String value) { }
	// RVA: 0x6147fa0 VA: 0x759875ffa0
	public Void .ctor() { }
	// RVA: 0x6147fa4 VA: 0x759875ffa4
	public Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x6147fa8 VA: 0x759875ffa8
	internal Void .ctor(String message, Exception innerException, String path, Int32 lineNumber, Int32 linePosition) { }
	// RVA: 0x61408f0 VA: 0x75987588f0
	internal static JsonReaderException Create(JsonReader reader, String message) { }
	// RVA: 0x61456ac VA: 0x759875d6ac
	internal static JsonReaderException Create(JsonReader reader, String message, Exception ex) { }
	// RVA: 0x6147fec VA: 0x759875ffec
	internal static JsonReaderException Create(IJsonLineInfo lineInfo, String path, String message, Exception ex) { }
}
```