# LowLevelDictionary

**Namespace:** `System.Collections.Generic`


## Fields

- `Int32 _numEntries`

- `Int32 _version`


## Properties

- `TKey Item`


## Methods

- `Void set_Item(TKey, TValue)`

- `Void Clear(Int32)`

- `Boolean Remove(TKey)`

- `Entry Find(TKey)`

- `Entry UncheckedAdd(TKey, TValue)`

- `Void ExpandBuckets()`

- `Int32 GetBucket(TKey, Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections.Generic
internal class LowLevelDictionary`2
{
	private Entry[] _buckets; // 0x0
	private Int32 _numEntries; // 0x0
	private Int32 _version; // 0x0
	private IEqualityComparer`1 _comparer; // 0x0

	public TKey Item { set; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity, IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Void Clear(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(TKey key) { }
	// RVA: 0x VA: 0x0
	private Entry Find(TKey key) { }
	// RVA: 0x VA: 0x0
	private Entry UncheckedAdd(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	private Void ExpandBuckets() { }
	// RVA: 0x VA: 0x0
	private Int32 GetBucket(TKey key, Int32 numBuckets) { }
}
```