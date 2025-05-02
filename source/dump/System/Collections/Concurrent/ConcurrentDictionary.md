# ConcurrentDictionary

**Namespace:** `System.Collections.Concurrent`


## Fields

- `Tables _tables`

- `Int32 _budget`

- `Int32 _serializationConcurrencyLevel`

- `Int32 _serializationCapacity`


## Properties

- `TValue Item`

- `Int32 Count`


## Methods

- `Void InitializeFromCollection(IEnumerable`1)`

- `Boolean TryAdd(TKey, TValue)`

- `Boolean ContainsKey(TKey)`

- `Boolean TryRemove(TKey, out)`

- `Boolean TryRemoveInternal(TKey, out, Boolean, TValue)`

- `Boolean TryGetValue(TKey, out)`

- `Boolean TryGetValueInternal(TKey, Int32, out)`

- `Void Clear()`

- `Void CopyToPairs(KeyValuePair`2[], Int32)`

- `Void CopyToEntries(DictionaryEntry[], Int32)`

- `Void CopyToObjects(Object[], Int32)`

- `Boolean TryAddInternal(TKey, Int32, TValue, Boolean, Boolean, out)`

- `TValue get_Item(TKey)`

- `Void set_Item(TKey, TValue)`

- `Int32 get_Count()`

- `Int32 GetCountInternal()`

- `TValue GetOrAdd(TKey, Func`2)`

- `TValue GetOrAdd(TKey, TValue)`

- `Void GrowTable(Tables)`

- `Void AcquireAllLocks(ref)`

- `Void AcquireLocks(Int32, Int32, ref)`

- `Void ReleaseLocks(Int32, Int32)`

- `Void OnSerializing(StreamingContext)`

- `Void OnSerialized(StreamingContext)`

- `Void OnDeserialized(StreamingContext)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections.Concurrent
public class ConcurrentDictionary`2 : IDictionary`2, ICollection`1, IEnumerable`1, IEnumerable, IDictionary, ICollection, IReadOnlyDictionary`2, IReadOnlyCollection`1
{
	private Tables _tables; // 0x0
	private IEqualityComparer`1 _comparer; // 0x0
	private readonly Boolean _growLockArray; // 0x0
	private Int32 _budget; // 0x0
	private KeyValuePair`2[] _serializationArray; // 0x0
	private Int32 _serializationConcurrencyLevel; // 0x0
	private Int32 _serializationCapacity; // 0x0
	private static readonly Boolean s_isValueWriteAtomic; // 0x0

	public TValue Item { get; set; }
	public Int32 Count { get; }
	public ICollection`1 Keys { get; }
	public ICollection`1 Values { get; }
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.IsReadOnly { get; }
	private Boolean System.Collections.IDictionary.IsFixedSize { get; }
	private Boolean System.Collections.IDictionary.IsReadOnly { get; }
	private ICollection System.Collections.IDictionary.Keys { get; }
	private ICollection System.Collections.IDictionary.Values { get; }
	private Object System.Collections.IDictionary.Item { get; set; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	private static Int32 DefaultConcurrencyLevel { get; }

	// RVA: 0x VA: 0x0
	private static Boolean IsValueWriteAtomic() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	private Void InitializeFromCollection(IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	internal Void .ctor(Int32 concurrencyLevel, Int32 capacity, Boolean growLockArray, IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Boolean TryAdd(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsKey(TKey key) { }
	// RVA: 0x VA: 0x0
	public Boolean TryRemove(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	private Boolean TryRemoveInternal(TKey key, out TValue value, Boolean matchValue, TValue oldValue) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	private Boolean TryGetValueInternal(TKey key, Int32 hashcode, out TValue value) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.CopyTo(KeyValuePair`2[] array, Int32 index) { }
	// RVA: 0x VA: 0x0
	public KeyValuePair`2[] ToArray() { }
	// RVA: 0x VA: 0x0
	private Void CopyToPairs(KeyValuePair`2[] array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void CopyToEntries(DictionaryEntry[] array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void CopyToObjects(Object[] array, Int32 index) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Boolean TryAddInternal(TKey key, Int32 hashcode, TValue value, Boolean updateIfExists, Boolean acquireLock, out TValue resultingValue) { }
	// RVA: 0x VA: 0x0
	public TValue get_Item(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	private static Void ThrowKeyNotFoundException(Object key) { }
	// RVA: 0x VA: 0x0
	private static Void ThrowKeyNullException() { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	private Int32 GetCountInternal() { }
	// RVA: 0x VA: 0x0
	public TValue GetOrAdd(TKey key, Func`2 valueFactory) { }
	// RVA: 0x VA: 0x0
	public TValue GetOrAdd(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.IDictionary<TKey,TValue>.Add(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.IDictionary<TKey,TValue>.Remove(TKey key) { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Keys() { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Values() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.Add(KeyValuePair`2 keyValuePair) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.Contains(KeyValuePair`2 keyValuePair) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.Remove(KeyValuePair`2 keyValuePair) { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.Add(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.Contains(Object key) { }
	// RVA: 0x VA: 0x0
	private IDictionaryEnumerator System.Collections.IDictionary.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.get_IsFixedSize() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private ICollection System.Collections.IDictionary.get_Keys() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.Remove(Object key) { }
	// RVA: 0x VA: 0x0
	private ICollection System.Collections.IDictionary.get_Values() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.IDictionary.get_Item(Object key) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.set_Item(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	private Void GrowTable(Tables tables) { }
	// RVA: 0x VA: 0x0
	private static Int32 GetBucket(Int32 hashcode, Int32 bucketCount) { }
	// RVA: 0x VA: 0x0
	private static Void GetBucketAndLockNo(Int32 hashcode, out Int32 bucketNo, out Int32 lockNo, Int32 bucketCount, Int32 lockCount) { }
	// RVA: 0x VA: 0x0
	private static Int32 get_DefaultConcurrencyLevel() { }
	// RVA: 0x VA: 0x0
	private Void AcquireAllLocks(ref Int32 locksAcquired) { }
	// RVA: 0x VA: 0x0
	private Void AcquireLocks(Int32 fromInclusive, Int32 toExclusive, ref Int32 locksAcquired) { }
	// RVA: 0x VA: 0x0
	private Void ReleaseLocks(Int32 fromInclusive, Int32 toExclusive) { }
	// RVA: 0x VA: 0x0
	private ReadOnlyCollection`1 GetKeys() { }
	// RVA: 0x VA: 0x0
	private ReadOnlyCollection`1 GetValues() { }
	// RVA: 0x VA: 0x0
	private Void OnSerializing(StreamingContext context) { }
	// RVA: 0x VA: 0x0
	private Void OnSerialized(StreamingContext context) { }
	// RVA: 0x VA: 0x0
	private Void OnDeserialized(StreamingContext context) { }
	// RVA: 0x VA: 0x0
	private static Void .cctor() { }
}
```