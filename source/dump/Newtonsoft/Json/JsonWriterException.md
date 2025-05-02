# JsonWriterException

**Namespace:** `Newtonsoft.Json`


## Fields

- `String <Path>k__BackingField`


## Properties

- `String Path`


## Methods

- `Void set_Path(String)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json
public class JsonWriterException : JsonException
{
	private String <Path>k__BackingField; // 0x90

	private String Path { set; }

	// RVA: 0x6147de4 VA: 0x759875fde4
	private Void set_Path(String value) { }
	// RVA: 0x6147dec VA: 0x759875fdec
	public Void .ctor() { }
	// RVA: 0x6147df0 VA: 0x759875fdf0
	public Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x6147df4 VA: 0x759875fdf4
	internal Void .ctor(String message, Exception innerException, String path) { }
	// RVA: 0x61460e8 VA: 0x759875e0e8
	internal static JsonWriterException Create(JsonWriter writer, String message, Exception ex) { }
	// RVA: 0x6147ec8 VA: 0x759875fec8
	internal static JsonWriterException Create(String path, String message, Exception ex) { }
}
```