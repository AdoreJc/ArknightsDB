# UDictionary

**Namespace:** `AdvancedInspector`


## Properties

- `Boolean IsFixedSize`

- `TValue Item`

- `Int32 Count`

- `Boolean IsReadOnly`

- `Boolean IsSynchronized`

- `Object SyncRoot`


## Methods

- `Void OnAfterDeserialize()`

- `Void OnBeforeSerialize()`

- `Void GetObjectData(SerializationInfo, StreamingContext)`

- `Void OnDeserialization(Object)`

- `Boolean get_IsFixedSize()`

- `TValue get_Item(TKey)`

- `Void set_Item(TKey, TValue)`

- `Void Add(TKey, TValue)`

- `Boolean ContainsKey(TKey)`

- `Boolean Remove(TKey)`

- `Boolean TryGetValue(TKey, out)`

- `Int32 get_Count()`

- `Boolean get_IsReadOnly()`

- `Boolean get_IsSynchronized()`

- `Object get_SyncRoot()`

- `Void Add(KeyValuePair`2)`

- `Void Clear()`

- `Boolean Contains(KeyValuePair`2)`

- `Boolean Remove(KeyValuePair`2)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class UDictionary`2 : IDictionary`2, ICollection`1, IEnumerable`1, IEnumerable, IDictionary, ICollection, ISerializable, IDeserializationCallback, ISerializationCallbackReceiver
{
	private List`1 keys; // 0x0
	private List`1 values; // 0x0
	private Dictionary`2 dictionary; // 0x0

	public Boolean IsFixedSize { get; }
	public ICollection`1 Keys { get; }
	private ICollection System.Collections.IDictionary.Keys { get; }
	public ICollection`1 Values { get; }
	private ICollection System.Collections.IDictionary.Values { get; }
	public TValue Item { get; set; }
	private Object System.Collections.IDictionary.Item { get; set; }
	public Int32 Count { get; }
	public Boolean IsReadOnly { get; }
	public Boolean IsSynchronized { get; }
	public Object SyncRoot { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IDictionary`2 dictionary) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IDictionary`2 dictionary, IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity, IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void OnAfterDeserialize() { }
	// RVA: 0x VA: 0x0
	public Void OnBeforeSerialize() { }
	// RVA: 0x VA: 0x0
	public Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x VA: 0x0
	public Void OnDeserialization(Object sender) { }
	// RVA: 0x VA: 0x0
	public Boolean get_IsFixedSize() { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Keys() { }
	// RVA: 0x VA: 0x0
	private ICollection System.Collections.IDictionary.get_Keys() { }
	// RVA: 0x VA: 0x0
	public ICollection`1 get_Values() { }
	// RVA: 0x VA: 0x0
	private ICollection System.Collections.IDictionary.get_Values() { }
	// RVA: 0x VA: 0x0
	public TValue get_Item(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.IDictionary.get_Item(Object key) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.set_Item(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	public Void Add(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.Add(Object key, Object value) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsKey(TKey key) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IDictionary.Contains(Object key) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(TKey key) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IDictionary.Remove(Object key) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	private IDictionaryEnumerator System.Collections.IDictionary.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public Boolean get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	public Boolean get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	public Object get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	public Void Add(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<System.Collections.Generic.KeyValuePair<TKey,TValue>>.CopyTo(KeyValuePair`2[] array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(KeyValuePair`2 item) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```