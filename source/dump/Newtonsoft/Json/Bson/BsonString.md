# BsonString

**Namespace:** `Newtonsoft.Json.Bson`


## Fields

- `Int32 <ByteCount>k__BackingField`

- `Boolean <IncludeLength>k__BackingField`


## Properties

- `Int32 ByteCount`

- `Boolean IncludeLength`


## Methods

- `Int32 get_ByteCount()`

- `Void set_ByteCount(Int32)`

- `Boolean get_IncludeLength()`

- `Void set_IncludeLength(Boolean)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Bson
internal class BsonString : BsonValue
{
	private Int32 <ByteCount>k__BackingField; // 0x2c
	private Boolean <IncludeLength>k__BackingField; // 0x30

	public Int32 ByteCount { get; set; }
	public Boolean IncludeLength { get; set; }

	// RVA: 0x61b9f40 VA: 0x75987d1f40
	public Int32 get_ByteCount() { }
	// RVA: 0x61b9f48 VA: 0x75987d1f48
	public Void set_ByteCount(Int32 value) { }
	// RVA: 0x61b9f50 VA: 0x75987d1f50
	public Boolean get_IncludeLength() { }
	// RVA: 0x61b9f58 VA: 0x75987d1f58
	public Void set_IncludeLength(Boolean value) { }
	// RVA: 0x61b9cc0 VA: 0x75987d1cc0
	public Void .ctor(Object value, Boolean includeLength) { }
}
```