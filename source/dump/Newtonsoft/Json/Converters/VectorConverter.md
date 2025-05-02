# VectorConverter

**Namespace:** `Newtonsoft.Json.Converters`


## Fields

- `Boolean <EnableVector2>k__BackingField`

- `Boolean <EnableVector3>k__BackingField`

- `Boolean <EnableVector4>k__BackingField`


## Properties

- `Boolean EnableVector2`

- `Boolean EnableVector3`

- `Boolean EnableVector4`


## Methods

- `Boolean get_EnableVector2()`

- `Void set_EnableVector2(Boolean)`

- `Boolean get_EnableVector3()`

- `Void set_EnableVector3(Boolean)`

- `Boolean get_EnableVector4()`

- `Void set_EnableVector4(Boolean)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
public class VectorConverter : JsonConverter
{
	private static readonly Type V2; // 0x0
	private static readonly Type V3; // 0x8
	private static readonly Type V4; // 0x10
	private Boolean <EnableVector2>k__BackingField; // 0x10
	private Boolean <EnableVector3>k__BackingField; // 0x11
	private Boolean <EnableVector4>k__BackingField; // 0x12

	public Boolean EnableVector2 { get; set; }
	public Boolean EnableVector3 { get; set; }
	public Boolean EnableVector4 { get; set; }

	// RVA: 0x61a9418 VA: 0x75987c1418
	public Boolean get_EnableVector2() { }
	// RVA: 0x61a9420 VA: 0x75987c1420
	public Void set_EnableVector2(Boolean value) { }
	// RVA: 0x61a942c VA: 0x75987c142c
	public Boolean get_EnableVector3() { }
	// RVA: 0x61a9434 VA: 0x75987c1434
	public Void set_EnableVector3(Boolean value) { }
	// RVA: 0x61a9440 VA: 0x75987c1440
	public Boolean get_EnableVector4() { }
	// RVA: 0x61a9448 VA: 0x75987c1448
	public Void set_EnableVector4(Boolean value) { }
	// RVA: 0x61a9454 VA: 0x75987c1454
	public Void .ctor() { }
	// RVA: 0x61a947c VA: 0x75987c147c
	public override Void WriteJson(JsonWriter writer, Object value, JsonSerializer serializer) { }
	// RVA: 0x61a972c VA: 0x75987c172c
	private static Void WriteVector(JsonWriter writer, Single x, Single y, Nullable`1 z, Nullable`1 w) { }
	// RVA: 0x61a98fc VA: 0x75987c18fc
	public override Object ReadJson(JsonReader reader, Type objectType, Object existingValue, JsonSerializer serializer) { }
	// RVA: 0x61a9da0 VA: 0x75987c1da0
	public override Boolean CanConvert(Type objectType) { }
	// RVA: 0x61a9a34 VA: 0x75987c1a34
	private static Vector2 PopulateVector2(JsonReader reader) { }
	// RVA: 0x61a9b18 VA: 0x75987c1b18
	private static Vector3 PopulateVector3(JsonReader reader) { }
	// RVA: 0x61a9c3c VA: 0x75987c1c3c
	private static Vector4 PopulateVector4(JsonReader reader) { }
	// RVA: 0x61a9e78 VA: 0x75987c1e78
	private static Void .cctor() { }
}
```