# EnumIntDictionary

**Namespace:** `Torappu`


## Properties

- `TValue Item`

- `Int32 Count`


## Methods

- `TValue get_Item(TKey)`

- `Void set_Item(TKey, TValue)`

- `Int32 get_Count()`

- `Void Add(TKey, TValue)`

- `Void Add(KeyValuePair`2)`

- `Void Clear()`

- `Boolean Contains(KeyValuePair`2)`

- `Boolean ContainsKey(TKey)`

- `KeyValueEnumerator GetEnumerator()`

- `Boolean Remove(TKey)`

- `Boolean Remove(KeyValuePair`2)`

- `Boolean TryGetValue(TKey, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class EnumIntDictionary`2
{
	private Dictionary`2 m_impl; // 0x0

	public TValue Item { get; set; }
	public ICollection`1 Keys { get; }
	public ICollection`1 Values { get; }
	public Int32 Count { get; }

	// RVA: 0x VA: 0x0
	public TValue get_Item(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Keys() { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Values() { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public Void Add(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Void Add(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsKey(TKey key) { }
	// RVA: 0x VA: 0x0
	public KeyValueEnumerator GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```