# BsonRegex

**Namespace:** `Newtonsoft.Json.Bson`


## Fields

- `BsonString <Pattern>k__BackingField`

- `BsonString <Options>k__BackingField`


## Properties

- `BsonString Pattern`

- `BsonString Options`


## Methods

- `BsonString get_Pattern()`

- `Void set_Pattern(BsonString)`

- `BsonString get_Options()`

- `Void set_Options(BsonString)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Bson
internal class BsonRegex : BsonToken
{
	private BsonString <Pattern>k__BackingField; // 0x20
	private BsonString <Options>k__BackingField; // 0x28

	public BsonString Pattern { get; set; }
	public BsonString Options { get; set; }
	public override BsonType Type { get; }

	// RVA: 0x61b9fb8 VA: 0x75987d1fb8
	public BsonString get_Pattern() { }
	// RVA: 0x61b9fc0 VA: 0x75987d1fc0
	public Void set_Pattern(BsonString value) { }
	// RVA: 0x61b9fc8 VA: 0x75987d1fc8
	public BsonString get_Options() { }
	// RVA: 0x61b9fd0 VA: 0x75987d1fd0
	public Void set_Options(BsonString value) { }
	// RVA: 0x61b9fd8 VA: 0x75987d1fd8
	public Void .ctor(String pattern, String options) { }
	// RVA: 0x61ba0c0 VA: 0x75987d20c0
	public override BsonType get_Type() { }
}
```