# BinaryConverter

**Namespace:** `Newtonsoft.Json.Converters`


## Fields

- `ReflectionObject _reflectionObject`


## Methods

- `Void EnsureReflectionObject(Type)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
public class BinaryConverter : JsonConverter
{
	private ReflectionObject _reflectionObject; // 0x10


	// RVA: 0x61a6650 VA: 0x75987be650
	public override Void WriteJson(JsonWriter writer, Object value, JsonSerializer serializer) { }
	// RVA: 0x61a66a4 VA: 0x75987be6a4
	private Byte[] GetByteArray(Object value) { }
	// RVA: 0x61a681c VA: 0x75987be81c
	private Void EnsureReflectionObject(Type t) { }
	// RVA: 0x61a69e4 VA: 0x75987be9e4
	public override Object ReadJson(JsonReader reader, Type objectType, Object existingValue, JsonSerializer serializer) { }
	// RVA: 0x61a6d10 VA: 0x75987bed10
	private Byte[] ReadByteArray(JsonReader reader) { }
	// RVA: 0x61a6f9c VA: 0x75987bef9c
	public override Boolean CanConvert(Type objectType) { }
	// RVA: 0x61a6fe8 VA: 0x75987befe8
	public Void .ctor() { }
}
```