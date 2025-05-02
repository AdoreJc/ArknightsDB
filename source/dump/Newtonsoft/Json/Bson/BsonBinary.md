# BsonBinary

**Namespace:** `Newtonsoft.Json.Bson`


## Fields

- `BsonBinaryType <BinaryType>k__BackingField`


## Properties

- `BsonBinaryType BinaryType`


## Methods

- `BsonBinaryType get_BinaryType()`

- `Void set_BinaryType(BsonBinaryType)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Bson
internal class BsonBinary : BsonValue
{
	private BsonBinaryType <BinaryType>k__BackingField; // 0x29

	public BsonBinaryType BinaryType { get; set; }

	// RVA: 0x61b9f64 VA: 0x75987d1f64
	public BsonBinaryType get_BinaryType() { }
	// RVA: 0x61b9f6c VA: 0x75987d1f6c
	public Void set_BinaryType(BsonBinaryType value) { }
	// RVA: 0x61b9f74 VA: 0x75987d1f74
	public Void .ctor(Byte[] value, BsonBinaryType binaryType) { }
}
```