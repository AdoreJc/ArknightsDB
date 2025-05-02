# KeyValuePairConverter

**Namespace:** `Newtonsoft.Json.Converters`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
public class KeyValuePairConverter : JsonConverter
{
	private static readonly ThreadSafeStore`2 ReflectionObjectPerType; // 0x0


	// RVA: 0x61a7404 VA: 0x75987bf404
	private static ReflectionObject InitializeReflectionObject(Type t) { }
	// RVA: 0x61a76d4 VA: 0x75987bf6d4
	public override Void WriteJson(JsonWriter writer, Object value, JsonSerializer serializer) { }
	// RVA: 0x61a7914 VA: 0x75987bf914
	public override Object ReadJson(JsonReader reader, Type objectType, Object existingValue, JsonSerializer serializer) { }
	// RVA: 0x61a7ca8 VA: 0x75987bfca8
	public override Boolean CanConvert(Type objectType) { }
	// RVA: 0x61a7db4 VA: 0x75987bfdb4
	public Void .ctor() { }
	// RVA: 0x61a7dbc VA: 0x75987bfdbc
	private static Void .cctor() { }
}
```