# SortedDictionary

**Namespace:** `System.Collections.Generic`


## Fields

- `KeyCollection _keys`

- `ValueCollection _values`


## Properties

- `TValue Item`

- `Int32 Count`

- `KeyCollection Keys`

- `ValueCollection Values`


## Methods

- `TValue get_Item(TKey)`

- `Void set_Item(TKey, TValue)`

- `Int32 get_Count()`

- `KeyCollection get_Keys()`

- `ValueCollection get_Values()`

- `Void Add(TKey, TValue)`

- `Void Clear()`

- `Boolean ContainsKey(TKey)`

- `Boolean ContainsValue(TValue)`

- `Void CopyTo(KeyValuePair`2[], Int32)`

- `Enumerator GetEnumerator()`

- `Boolean Remove(TKey)`

- `Boolean TryGetValue(TKey, out)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Collections.Generic
public class SortedDictionary`2 : IDictionary`2, ICollection`1, IEnumerable`1, IEnumerable, IDictionary, ICollection, IReadOnlyDictionary`2, IReadOnlyCollection`1
{
	private KeyCollection _keys; // 0x0
	private ValueCollection _values; // 0x0
	private TreeSet`1 _set; // 0x0

	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.IsReadOnly { get; }
	public TValue Item { get; set; }
	public Int32 Count { get; }
	public KeyCollection Keys { get; }
	private ICollection`1 System.Collections.Generic.IDictionary<TKey,TValue>.Keys { get; }
	public ValueCollection Values { get; }
	private ICollection`1 System.Collections.Generic.IDictionary<TKey,TValue>.Values { get; }
	private Boolean System.Collections.IDictionary.IsFixedSize { get; }
	private Boolean System.Collections.IDictionary.IsReadOnly { get; }
	private ICollection System.Collections.IDictionary.Keys { get; }
	private ICollection System.Collections.IDictionary.Values { get; }
	private Object System.Collections.IDictionary.Item { get; set; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.Add(KeyValuePair`2 keyValuePair) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.Contains(KeyValuePair`2 keyValuePair) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.Remove(KeyValuePair`2 keyValuePair) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	public TValue get_Item(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public KeyCollection get_Keys() { }
	// RVA: 0x VA: 0x0
	private ICollection`1 System.Collections.Generic.IDictionary<TKey,TValue>.get_Keys() { }
	// RVA: 0x VA: 0x0
	public ValueCollection get_Values() { }
	// RVA: 0x VA: 0x0
	private ICollection`1 System.Collections.Generic.IDictionary<TKey,TValue>.get_Values() { }
	// RVA: 0x VA: 0x0
	public Void Add(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsKey(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsValue(TValue value) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(KeyValuePair`2[] array, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Enumerator GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator`1 System.Collections.Generic.IEnumerable<System.Collections.Generic.KeyValuePair<TKey,TValue>>.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.get_IsFixedSize() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private ICollection System.Collections.IDictionary.get_Keys() { }
	// RVA: 0x VA: 0x0
	private ICollection System.Collections.IDictionary.get_Values() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.IDictionary.get_Item(Object key) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.set_Item(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.Add(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.Contains(Object key) { }
	// RVA: 0x VA: 0x0
	private static Boolean IsCompatibleKey(Object key) { }
	// RVA: 0x VA: 0x0
	private IDictionaryEnumerator System.Collections.IDictionary.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.Remove(Object key) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```