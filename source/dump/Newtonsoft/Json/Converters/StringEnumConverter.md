# StringEnumConverter

**Namespace:** `Newtonsoft.Json.Converters`


## Fields

- `Boolean <CamelCaseText>k__BackingField`

- `Boolean <AllowIntegerValues>k__BackingField`


## Properties

- `Boolean CamelCaseText`

- `Boolean AllowIntegerValues`


## Methods

- `Boolean get_CamelCaseText()`

- `Boolean get_AllowIntegerValues()`

- `Void set_AllowIntegerValues(Boolean)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
public class StringEnumConverter : JsonConverter
{
	private Boolean <CamelCaseText>k__BackingField; // 0x10
	private Boolean <AllowIntegerValues>k__BackingField; // 0x11

	public Boolean CamelCaseText { get; }
	public Boolean AllowIntegerValues { get; set; }

	// RVA: 0x61a8d58 VA: 0x75987c0d58
	public Boolean get_CamelCaseText() { }
	// RVA: 0x61a8d60 VA: 0x75987c0d60
	public Boolean get_AllowIntegerValues() { }
	// RVA: 0x61a8d68 VA: 0x75987c0d68
	public Void set_AllowIntegerValues(Boolean value) { }
	// RVA: 0x61a8d74 VA: 0x75987c0d74
	public Void .ctor() { }
	// RVA: 0x61a8d94 VA: 0x75987c0d94
	public override Void WriteJson(JsonWriter writer, Object value, JsonSerializer serializer) { }
	// RVA: 0x61a8f5c VA: 0x75987c0f5c
	public override Object ReadJson(JsonReader reader, Type objectType, Object existingValue, JsonSerializer serializer) { }
	// RVA: 0x61a93a0 VA: 0x75987c13a0
	public override Boolean CanConvert(Type objectType) { }
}
```