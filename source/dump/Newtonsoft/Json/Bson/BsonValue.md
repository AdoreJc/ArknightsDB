# BsonValue

**Namespace:** `Newtonsoft.Json.Bson`


## Properties

- `Object Value`


## Methods

- `Object get_Value()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Bson
internal class BsonValue : BsonToken
{
	private readonly Object _value; // 0x20
	private readonly BsonType _type; // 0x28

	public Object Value { get; }
	public override BsonType Type { get; }

	// RVA: 0x61b9ef4 VA: 0x75987d1ef4
	public Void .ctor(Object value, BsonType type) { }
	// RVA: 0x61b9f30 VA: 0x75987d1f30
	public Object get_Value() { }
	// RVA: 0x61b9f38 VA: 0x75987d1f38
	public override BsonType get_Type() { }
}
```