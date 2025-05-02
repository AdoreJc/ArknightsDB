# JsonContainerContract

**Namespace:** `Newtonsoft.Json.Serialization`


## Fields

- `JsonContract _itemContract`

- `JsonContract _finalItemContract`

- `JsonConverter <ItemConverter>k__BackingField`


## Properties

- `JsonConverter ItemConverter`


## Methods

- `JsonConverter get_ItemConverter()`

- `Void set_ItemConverter(JsonConverter)`

- `Void set_ItemIsReference(Nullable`1)`

- `Void set_ItemReferenceLoopHandling(Nullable`1)`

- `Void set_ItemTypeNameHandling(Nullable`1)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
public class JsonContainerContract : JsonContract
{
	private JsonContract _itemContract; // 0x90
	private JsonContract _finalItemContract; // 0x98
	private JsonConverter <ItemConverter>k__BackingField; // 0xa0
	private Nullable`1 <ItemIsReference>k__BackingField; // 0xa8
	private Nullable`1 <ItemReferenceLoopHandling>k__BackingField; // 0xac
	private Nullable`1 <ItemTypeNameHandling>k__BackingField; // 0xb4

	internal JsonContract ItemContract { get; set; }
	internal JsonContract FinalItemContract { get; }
	public JsonConverter ItemConverter { get; set; }
	public Nullable`1 ItemIsReference { get; set; }
	public Nullable`1 ItemReferenceLoopHandling { get; set; }
	public Nullable`1 ItemTypeNameHandling { get; set; }

	// RVA: 0x61645cc VA: 0x759877c5cc
	internal JsonContract get_ItemContract() { }
	// RVA: 0x61645d4 VA: 0x759877c5d4
	internal Void set_ItemContract(JsonContract value) { }
	// RVA: 0x616463c VA: 0x759877c63c
	internal JsonContract get_FinalItemContract() { }
	// RVA: 0x6164644 VA: 0x759877c644
	public JsonConverter get_ItemConverter() { }
	// RVA: 0x616464c VA: 0x759877c64c
	public Void set_ItemConverter(JsonConverter value) { }
	// RVA: 0x6164654 VA: 0x759877c654
	public Nullable`1 get_ItemIsReference() { }
	// RVA: 0x616465c VA: 0x759877c65c
	public Void set_ItemIsReference(Nullable`1 value) { }
	// RVA: 0x6164664 VA: 0x759877c664
	public Nullable`1 get_ItemReferenceLoopHandling() { }
	// RVA: 0x616466c VA: 0x759877c66c
	public Void set_ItemReferenceLoopHandling(Nullable`1 value) { }
	// RVA: 0x6164674 VA: 0x759877c674
	public Nullable`1 get_ItemTypeNameHandling() { }
	// RVA: 0x616467c VA: 0x759877c67c
	public Void set_ItemTypeNameHandling(Nullable`1 value) { }
	// RVA: 0x6164684 VA: 0x759877c684
	internal Void .ctor(Type underlyingType) { }
}
```