# SortedList

**Namespace:** `System.Collections.Generic`


## Fields

- `Int32 _size`

- `Int32 version`

- `KeyList keyList`

- `ValueList valueList`

- `Object _syncRoot`


## Properties

- `Int32 Capacity`

- `Int32 Count`

- `TValue Item`


## Methods

- `Void Add(TKey, TValue)`

- `Void set_Capacity(Int32)`

- `Int32 get_Count()`

- `KeyList GetKeyListHelper()`

- `ValueList GetValueListHelper()`

- `Void Clear()`

- `Boolean ContainsKey(TKey)`

- `Boolean ContainsValue(TValue)`

- `Void EnsureCapacity(Int32)`

- `TValue GetByIndex(Int32)`

- `TKey GetKey(Int32)`

- `TValue get_Item(TKey)`

- `Void set_Item(TKey, TValue)`

- `Int32 IndexOfKey(TKey)`

- `Int32 IndexOfValue(TValue)`

- `Void Insert(Int32, TKey, TValue)`

- `Boolean TryGetValue(TKey, out)`

- `Void RemoveAt(Int32)`

- `Boolean Remove(TKey)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Collections.Generic
public class SortedList`2 : IDictionary`2, ICollection`1, IEnumerable`1, IEnumerable, IDictionary, ICollection, IReadOnlyDictionary`2, IReadOnlyCollection`1
{
	private TKey[] keys; // 0x0
	private TValue[] values; // 0x0
	private Int32 _size; // 0x0
	private Int32 version; // 0x0
	private IComparer`1 comparer; // 0x0
	private KeyList keyList; // 0x0
	private ValueList valueList; // 0x0
	private Object _syncRoot; // 0x0

	public Int32 Capacity { set; }
	public IComparer`1 Comparer { get; }
	public Int32 Count { get; }
	private ICollection`1 System.Collections.Generic.IDictionary<TKey,TValue>.Keys { get; }
	private ICollection System.Collections.IDictionary.Keys { get; }
	private ICollection`1 System.Collections.Generic.IDictionary<TKey,TValue>.Values { get; }
	private ICollection System.Collections.IDictionary.Values { get; }
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.IsReadOnly { get; }
	private Boolean System.Collections.IDictionary.IsReadOnly { get; }
	private Boolean System.Collections.IDictionary.IsFixedSize { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	public TValue Item { get; set; }
	private Object System.Collections.IDictionary.Item { get; set; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void Add(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.Add(KeyValuePair`2 keyValuePair) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.Contains(KeyValuePair`2 keyValuePair) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.Remove(KeyValuePair`2 keyValuePair) { }
	// RVA: 0x VA: 0x0
	public Void set_Capacity(Int32 value) { }
	// RVA: 0x VA: 0x0
	public IComparer`1 get_Comparer() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.Add(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	private ICollection`1 System.Collections.Generic.IDictionary<TKey,TValue>.get_Keys() { }
	// RVA: 0x VA: 0x0
	private ICollection System.Collections.IDictionary.get_Keys() { }
	// RVA: 0x VA: 0x0
	private ICollection`1 System.Collections.Generic.IDictionary<TKey,TValue>.get_Values() { }
	// RVA: 0x VA: 0x0
	private ICollection System.Collections.IDictionary.get_Values() { }
	// RVA: 0x VA: 0x0
	private KeyList GetKeyListHelper() { }
	// RVA: 0x VA: 0x0
	private ValueList GetValueListHelper() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.get_IsFixedSize() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.Contains(Object key) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsKey(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsValue(TValue value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.CopyTo(KeyValuePair`2[] array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void EnsureCapacity(Int32 min) { }
	// RVA: 0x VA: 0x0
	private TValue GetByIndex(Int32 index) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator`1 System.Collections.Generic.IEnumerable<System.Collections.Generic.KeyValuePair<TKey,TValue>>.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IDictionaryEnumerator System.Collections.IDictionary.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private TKey GetKey(Int32 index) { }
	// RVA: 0x VA: 0x0
	public TValue get_Item(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.IDictionary.get_Item(Object key) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.set_Item(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOfKey(TKey key) { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOfValue(TValue value) { }
	// RVA: 0x VA: 0x0
	private Void Insert(Int32 index, TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(TKey key) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.Remove(Object key) { }
	// RVA: 0x VA: 0x0
	private static Boolean IsCompatibleKey(Object key) { }
}
```