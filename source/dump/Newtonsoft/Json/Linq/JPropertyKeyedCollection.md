# JPropertyKeyedCollection

**Namespace:** `Newtonsoft.Json.Linq`


## Methods

- `Void AddKey(String, JToken)`

- `Boolean Contains(String)`

- `Void EnsureDictionary()`

- `String GetKeyForItem(JToken)`

- `Void RemoveKey(String)`

- `Boolean TryGetValue(String, out)`

- `Int32 IndexOfReference(JToken)`

- `Boolean Compare(JPropertyKeyedCollection)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq
internal class JPropertyKeyedCollection : Collection`1
{
	private static readonly IEqualityComparer`1 Comparer; // 0x0
	private Dictionary`2 _dictionary; // 0x18

	public ICollection`1 Keys { get; }

	// RVA: 0x6188984 VA: 0x75987a0984
	public Void .ctor() { }
	// RVA: 0x6188a14 VA: 0x75987a0a14
	private Void AddKey(String key, JToken item) { }
	// RVA: 0x6188b48 VA: 0x75987a0b48
	protected override Void ClearItems() { }
	// RVA: 0x6188bc0 VA: 0x75987a0bc0
	public Boolean Contains(String key) { }
	// RVA: 0x6188a84 VA: 0x75987a0a84
	private Void EnsureDictionary() { }
	// RVA: 0x6188c70 VA: 0x75987a0c70
	private String GetKeyForItem(JToken item) { }
	// RVA: 0x6188cf0 VA: 0x75987a0cf0
	protected override Void InsertItem(Int32 index, JToken item) { }
	// RVA: 0x6188d68 VA: 0x75987a0d68
	protected override Void RemoveItem(Int32 index) { }
	// RVA: 0x6188e5c VA: 0x75987a0e5c
	private Void RemoveKey(String key) { }
	// RVA: 0x6188ebc VA: 0x75987a0ebc
	protected override Void SetItem(Int32 index, JToken item) { }
	// RVA: 0x61890c4 VA: 0x75987a10c4
	public Boolean TryGetValue(String key, out JToken value) { }
	// RVA: 0x618914c VA: 0x75987a114c
	public ICollection`1 get_Keys() { }
	// RVA: 0x61891a4 VA: 0x75987a11a4
	public Int32 IndexOfReference(JToken t) { }
	// RVA: 0x6189248 VA: 0x75987a1248
	public Boolean Compare(JPropertyKeyedCollection other) { }
	// RVA: 0x61895b4 VA: 0x75987a15b4
	private static Void .cctor() { }
}
```