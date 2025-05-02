# ActionDict

**Namespace:** `Torappu`


## Properties

- `Int32 Count`

- `Boolean IsReadOnly`

- `Object Item`

- `Boolean IsSynchronized`

- `Object SyncRoot`

- `Boolean IsFixedSize`

- `ActionArray Item`


## Methods

- `Int32 get_Count()`

- `Boolean get_IsReadOnly()`

- `Object get_Item(Object)`

- `Void set_Item(Object, Object)`

- `Void CopyTo(Array, Int32)`

- `Boolean get_IsSynchronized()`

- `Object get_SyncRoot()`

- `Boolean Contains(Object)`

- `Void Remove(Object)`

- `Void Add(Object, Object)`

- `Boolean get_IsFixedSize()`

- `ActionArray get_Item(TKey)`

- `Void set_Item(TKey, ActionArray)`

- `Void set_Item(Int32, KeyValuePair`2)`

- `Boolean Contains(KeyValuePair`2)`

- `Void Clear()`

- `Boolean TryGetValue(TKey, out)`

- `Int32 IndexOf(TKey)`

- `IEnumerator GetEnumerator()`

- `Void CopyTo(KeyValuePair`2[], Int32)`

- `Void Add(TKey, ActionArray)`

- `Void Add(KeyValuePair`2)`

- `Boolean ContainsKey(TKey)`

- `Boolean Remove(TKey)`

- `Boolean Remove(KeyValuePair`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ActionDict`2 : IDictionary`2, ICollection`1, IEnumerable`1, IEnumerable
{
	private List`1 _items; // 0x0

	public Int32 Count { get; }
	public Boolean IsReadOnly { get; }
	public Object Item { get; set; }
	public Boolean IsSynchronized { get; }
	public Object SyncRoot { get; }
	public Boolean IsFixedSize { get; }
	public ActionArray Item { get; set; }
	public KeyValuePair`2 Item { get; set; }
	public ICollection`1 Keys { get; }
	public ICollection`1 Values { get; }

	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public Boolean get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	public Object get_Item(Object key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Boolean get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	public Object get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(Object key) { }
	// RVA: 0x VA: 0x0
	public Void Remove(Object key) { }
	// RVA: 0x VA: 0x0
	public Void Add(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	public Boolean get_IsFixedSize() { }
	// RVA: 0x VA: 0x0
	public ActionArray get_Item(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, ActionArray value) { }
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
	public Boolean TryGetValue(TKey key, out ActionArray value) { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(TKey key) { }
	// RVA: 0x VA: 0x0
	private IEnumerator`1 System.Collections.Generic.IEnumerable<System.Collections.Generic.KeyValuePair<TKey,ActionArray>>.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public IEnumerator GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(KeyValuePair`2[] target, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void Add(TKey key, ActionArray value) { }
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