# Dictionary

**Namespace:** `System.Collections.Generic`


## Fields

- `Int32 _count`

- `Int32 _freeList`

- `Int32 _freeCount`

- `Int32 _version`

- `KeyCollection _keys`

- `ValueCollection _values`

- `Object _syncRoot`


## Properties

- `Int32 Count`

- `KeyCollection Keys`

- `ValueCollection Values`

- `TValue Item`


## Methods

- `Int32 get_Count()`

- `KeyCollection get_Keys()`

- `ValueCollection get_Values()`

- `TValue get_Item(TKey)`

- `Void set_Item(TKey, TValue)`

- `Void Add(TKey, TValue)`

- `Void Clear()`

- `Boolean ContainsKey(TKey)`

- `Boolean ContainsValue(TValue)`

- `Void CopyTo(KeyValuePair`2[], Int32)`

- `Enumerator GetEnumerator()`

- `Int32 FindEntry(TKey)`

- `Int32 Initialize(Int32)`

- `Boolean TryInsert(TKey, TValue, InsertionBehavior)`

- `Void Resize()`

- `Void Resize(Int32, Boolean)`

- `Boolean Remove(TKey)`

- `Boolean TryGetValue(TKey, out)`

- `Boolean TryAdd(TKey, TValue)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections.Generic
public class Dictionary`2 : IDictionary`2, ICollection`1, IEnumerable`1, IEnumerable, IDictionary, ICollection, IReadOnlyDictionary`2, IReadOnlyCollection`1, ISerializable, IDeserializationCallback
{
	private Int32[] _buckets; // 0x0
	private Entry[] _entries; // 0x0
	private Int32 _count; // 0x0
	private Int32 _freeList; // 0x0
	private Int32 _freeCount; // 0x0
	private Int32 _version; // 0x0
	private IEqualityComparer`1 _comparer; // 0x0
	private KeyCollection _keys; // 0x0
	private ValueCollection _values; // 0x0
	private Object _syncRoot; // 0x0
	private const String VersionName; // 0x0
	private const String HashSizeName; // 0x0
	private const String KeyValuePairsName; // 0x0
	private const String ComparerName; // 0x0

	public IEqualityComparer`1 Comparer { get; }
	public Int32 Count { get; }
	public KeyCollection Keys { get; }
	private ICollection`1 System.Collections.Generic.IDictionary<TKey,TValue>.Keys { get; }
	public ValueCollection Values { get; }
	private ICollection`1 System.Collections.Generic.IDictionary<TKey,TValue>.Values { get; }
	public TValue Item { get; set; }
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.IsReadOnly { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	private Boolean System.Collections.IDictionary.IsFixedSize { get; }
	private Boolean System.Collections.IDictionary.IsReadOnly { get; }
	private ICollection System.Collections.IDictionary.Keys { get; }
	private ICollection System.Collections.IDictionary.Values { get; }
	private Object System.Collections.IDictionary.Item { get; set; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity, IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IDictionary`2 dictionary) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IDictionary`2 dictionary, IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x VA: 0x0
	public IEqualityComparer`1 get_Comparer() { }
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
	public TValue get_Item(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Void Add(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.Add(KeyValuePair`2 keyValuePair) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.Contains(KeyValuePair`2 keyValuePair) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.Remove(KeyValuePair`2 keyValuePair) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsKey(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsValue(TValue value) { }
	// RVA: 0x VA: 0x0
	private Void CopyTo(KeyValuePair`2[] array, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Enumerator GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator`1 System.Collections.Generic.IEnumerable<System.Collections.Generic.KeyValuePair<TKey,TValue>>.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x VA: 0x0
	private Int32 FindEntry(TKey key) { }
	// RVA: 0x VA: 0x0
	private Int32 Initialize(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	private Boolean TryInsert(TKey key, TValue value, InsertionBehavior behavior) { }
	// RVA: 0x VA: 0x0
	public virtual Void OnDeserialization(Object sender) { }
	// RVA: 0x VA: 0x0
	private Void Resize() { }
	// RVA: 0x VA: 0x0
	private Void Resize(Int32 newSize, Boolean forceNewHashCodes) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	public Boolean TryAdd(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.CopyTo(KeyValuePair`2[] array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
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
	private static Boolean IsCompatibleKey(Object key) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.Add(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.Contains(Object key) { }
	// RVA: 0x VA: 0x0
	private IDictionaryEnumerator System.Collections.IDictionary.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.Remove(Object key) { }
}
```