# BsonObject

**Namespace:** `Newtonsoft.Json.Bson`


## Methods

- `Void Add(String, BsonToken)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Bson
internal class BsonObject : BsonToken, IEnumerable`1, IEnumerable
{
	private readonly List`1 _children; // 0x20

	public override BsonType Type { get; }

	// RVA: 0x61b9b4c VA: 0x75987d1b4c
	public Void Add(String name, BsonToken token) { }
	// RVA: 0x61b9d08 VA: 0x75987d1d08
	public override BsonType get_Type() { }
	// RVA: 0x61b7c58 VA: 0x75987cfc58
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x61b9d10 VA: 0x75987d1d10
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x61b9d14 VA: 0x75987d1d14
	public Void .ctor() { }
}
```