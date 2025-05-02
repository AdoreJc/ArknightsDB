# BsonArray

**Namespace:** `Newtonsoft.Json.Bson`


## Methods

- `Void Add(BsonToken)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Bson
internal class BsonArray : BsonToken, IEnumerable`1, IEnumerable
{
	private readonly List`1 _children; // 0x20

	public override BsonType Type { get; }

	// RVA: 0x61b9d9c VA: 0x75987d1d9c
	public Void Add(BsonToken token) { }
	// RVA: 0x61b9e60 VA: 0x75987d1e60
	public override BsonType get_Type() { }
	// RVA: 0x61b7d8c VA: 0x75987cfd8c
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x61b9e68 VA: 0x75987d1e68
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x61b9e6c VA: 0x75987d1e6c
	public Void .ctor() { }
}
```