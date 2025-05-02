# DictionaryWrapper

**Namespace:** `Newtonsoft.Json.Utilities`


## Fields

- `Object _syncRoot`


## Properties

- `TValue Item`

- `Int32 Count`

- `Boolean IsReadOnly`

- `Object UnderlyingDictionary`


## Methods

- `Void Add(TKey, TValue)`

- `Boolean ContainsKey(TKey)`

- `Boolean Remove(TKey)`

- `Boolean TryGetValue(TKey, out)`

- `TValue get_Item(TKey)`

- `Void set_Item(TKey, TValue)`

- `Void Add(KeyValuePair`2)`

- `Void Clear()`

- `Boolean Contains(KeyValuePair`2)`

- `Void CopyTo(KeyValuePair`2[], Int32)`

- `Int32 get_Count()`

- `Boolean get_IsReadOnly()`

- `Boolean Remove(KeyValuePair`2)`

- `Void Remove(Object)`

- `Object get_UnderlyingDictionary()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Utilities
internal class DictionaryWrapper`2 : IDictionary`2, ICollection`1, IEnumerable`1, IEnumerable, IWrappedDictionary, IDictionary, ICollection
{
	private readonly IDictionary _dictionary; // 0x0
	private readonly IDictionary`2 _genericDictionary; // 0x0
	private Object _syncRoot; // 0x0

	public ICollection`1 Keys { get; }
	public ICollection`1 Values { get; }
	public TValue Item { get; set; }
	public Int32 Count { get; }
	public Boolean IsReadOnly { get; }
	private Object System.Collections.IDictionary.Item { get; set; }
	private Boolean System.Collections.IDictionary.IsFixedSize { get; }
	private ICollection System.Collections.IDictionary.Keys { get; }
	private ICollection System.Collections.IDictionary.Values { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	public Object UnderlyingDictionary { get; }

	// RVA: 0x VA: 0x0
	public Void Add(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsKey(TKey key) { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Keys() { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Values() { }
	// RVA: 0x VA: 0x0
	public TValue get_Item(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Void Add(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(KeyValuePair`2[] array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public Boolean get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.Add(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.IDictionary.get_Item(Object key) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.set_Item(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	private IDictionaryEnumerator System.Collections.IDictionary.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.Contains(Object key) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.get_IsFixedSize() { }
	// RVA: 0x VA: 0x0
	private ICollection System.Collections.IDictionary.get_Keys() { }
	// RVA: 0x VA: 0x0
	public Void Remove(Object key) { }
	// RVA: 0x VA: 0x0
	private ICollection System.Collections.IDictionary.get_Values() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	public Object get_UnderlyingDictionary() { }
}
```