# JsonSerializationException

**Namespace:** `Newtonsoft.Json`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json
public class JsonSerializationException : JsonException
{


	// RVA: 0x614ba18 VA: 0x7598763a18
	public Void .ctor() { }
	// RVA: 0x614ba14 VA: 0x7598763a14
	public Void .ctor(String message) { }
	// RVA: 0x614ba1c VA: 0x7598763a1c
	public Void .ctor(String message, Exception innerException) { }
	// RVA: 0x614ba20 VA: 0x7598763a20
	public Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x614a558 VA: 0x7598762558
	internal static JsonSerializationException Create(JsonReader reader, String message) { }
	// RVA: 0x614ba24 VA: 0x7598763a24
	internal static JsonSerializationException Create(JsonReader reader, String message, Exception ex) { }
	// RVA: 0x614baa8 VA: 0x7598763aa8
	internal static JsonSerializationException Create(IJsonLineInfo lineInfo, String path, String message, Exception ex) { }
}
```