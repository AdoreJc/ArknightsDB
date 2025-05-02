# RegexConverter

**Namespace:** `Newtonsoft.Json.Converters`


## Methods

- `Boolean HasFlag(RegexOptions, RegexOptions)`

- `Void WriteBson(BsonWriter, Regex)`

- `Void WriteJson(JsonWriter, Regex, JsonSerializer)`

- `Object ReadRegexString(JsonReader)`

- `Regex ReadRegexObject(JsonReader, JsonSerializer)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
public class RegexConverter : JsonConverter
{


	// RVA: 0x61a8370 VA: 0x75987c0370
	public override Void WriteJson(JsonWriter writer, Object value, JsonSerializer serializer) { }
	// RVA: 0x61a8758 VA: 0x75987c0758
	private Boolean HasFlag(RegexOptions options, RegexOptions flag) { }
	// RVA: 0x61a8468 VA: 0x75987c0468
	private Void WriteBson(BsonWriter writer, Regex regex) { }
	// RVA: 0x61a859c VA: 0x75987c059c
	private Void WriteJson(JsonWriter writer, Regex regex, JsonSerializer serializer) { }
	// RVA: 0x61a8824 VA: 0x75987c0824
	public override Object ReadJson(JsonReader reader, Type objectType, Object existingValue, JsonSerializer serializer) { }
	// RVA: 0x61a8b4c VA: 0x75987c0b4c
	private Object ReadRegexString(JsonReader reader) { }
	// RVA: 0x61a88c8 VA: 0x75987c08c8
	private Regex ReadRegexObject(JsonReader reader, JsonSerializer serializer) { }
	// RVA: 0x61a8ccc VA: 0x75987c0ccc
	public override Boolean CanConvert(Type objectType) { }
	// RVA: 0x61a8d50 VA: 0x75987c0d50
	public Void .ctor() { }
}
```