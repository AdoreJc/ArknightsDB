# ListDict

**Namespace:** `Torappu`


## Fields

- `Equality m_equals`


## Properties

- `TValue Item`


## Methods

- `TValue get_Item(TKey)`

- `Void set_Item(TKey, TValue)`

- `Void Set(Int32, KeyValuePair`2)`

- `Void Add(KeyValuePair`2)`

- `Void Add(TKey, TValue)`

- `Boolean ContainsKey(TKey)`

- `Boolean Remove(TKey)`

- `Boolean TryGetValue(TKey, out)`

- `Int32 IndexOf(TKey)`

- `Boolean TryGetAndRemove(TKey, out)`

- `Void _SetEquals(Equality)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class ListDict`2 : List`1, IDictionary`2, ICollection`1, IEnumerable`1, IEnumerable, IListDict, IHotfixable
{
	private Equality m_equals; // 0x0

	public TValue Item { get; set; }
	public ICollection`1 Keys { get; }
	public ICollection`1 Values { get; }

	// RVA: 0x VA: 0x0
	public TValue get_Item(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public KeyValuePair`2 Get(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void Set(Int32 index, KeyValuePair`2 value) { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Keys() { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Values() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Equality equals) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(ListDict`2 another, Equality equals) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEnumerable`1 collection, Equality equals) { }
	// RVA: 0x VA: 0x0
	public Void Add(KeyValuePair`2 pair) { }
	// RVA: 0x VA: 0x0
	public Void Add(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsKey(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetAndRemove(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	private KeyValuePair`2 _MakePair(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	private Void _SetEquals(Equality equals) { }
}
```