# ArrayDict

**Namespace:** `Torappu`


## Properties

- `Int32 Count`

- `Boolean IsReadOnly`

- `TValue Item`


## Methods

- `Int32 get_Count()`

- `Boolean get_IsReadOnly()`

- `TValue get_Item(TKey)`

- `Void set_Item(TKey, TValue)`

- `Void set_Item(Int32, KeyValuePair`2)`

- `Boolean Contains(KeyValuePair`2)`

- `Void Clear()`

- `Boolean TryGetValue(TKey, out)`

- `Int32 IndexOf(TKey)`

- `Void CopyTo(KeyValuePair`2[], Int32)`

- `Void Add(TKey, TValue)`

- `Void Add(KeyValuePair`2)`

- `Boolean ContainsKey(TKey)`

- `Boolean Remove(TKey)`

- `Boolean Remove(KeyValuePair`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ArrayDict`2 : IDictionary`2, ICollection`1, IEnumerable`1, IEnumerable
{
	private SerializableKV[] _items; // 0x0
	private TValue[] _test; // 0x0

	public Int32 Count { get; }
	public Boolean IsReadOnly { get; }
	public TValue Item { get; set; }
	public KeyValuePair`2 Item { get; set; }
	public ICollection`1 Keys { get; }
	public ICollection`1 Values { get; }

	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public Boolean get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	public TValue get_Item(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public KeyValuePair`2 get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(Int32 index, KeyValuePair`2 value) { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Keys() { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Values() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(KeyValuePair`2 kv) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(TKey key) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(KeyValuePair`2[] target, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void Add(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Void Add(KeyValuePair`2 kv) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsKey(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(KeyValuePair`2 kv) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```