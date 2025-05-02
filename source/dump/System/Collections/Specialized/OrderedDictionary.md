# OrderedDictionary

**Namespace:** `System.Collections.Specialized`


## Fields

- `ArrayList _objectsArray`

- `Hashtable _objectsTable`

- `Int32 _initialCapacity`

- `IEqualityComparer _comparer`

- `Boolean _readOnly`

- `Object _syncRoot`

- `SerializationInfo _siInfo`


## Properties

- `Int32 Count`

- `Boolean IsReadOnly`

- `ICollection Keys`

- `ArrayList objectsArray`

- `Hashtable objectsTable`

- `Object Item`

- `ICollection Values`


## Methods

- `Int32 get_Count()`

- `Boolean get_IsReadOnly()`

- `ICollection get_Keys()`

- `ArrayList get_objectsArray()`

- `Hashtable get_objectsTable()`

- `Object get_Item(Object)`

- `Void set_Item(Object, Object)`

- `ICollection get_Values()`

- `Void Add(Object, Object)`

- `Void Clear()`

- `Boolean Contains(Object)`

- `Void CopyTo(Array, Int32)`

- `Int32 IndexOfKey(Object)`

- `Void Remove(Object)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Collections.Specialized
public class OrderedDictionary : IDictionary, ICollection, IEnumerable, ISerializable, IDeserializationCallback
{
	private ArrayList _objectsArray; // 0x10
	private Hashtable _objectsTable; // 0x18
	private Int32 _initialCapacity; // 0x20
	private IEqualityComparer _comparer; // 0x28
	private Boolean _readOnly; // 0x30
	private Object _syncRoot; // 0x38
	private SerializationInfo _siInfo; // 0x40

	public Int32 Count { get; }
	private Boolean System.Collections.IDictionary.IsFixedSize { get; }
	public Boolean IsReadOnly { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	public ICollection Keys { get; }
	private ArrayList objectsArray { get; }
	private Hashtable objectsTable { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	public Object Item { get; set; }
	public ICollection Values { get; }

	// RVA: 0x640b624 VA: 0x7598a23624
	public Void .ctor() { }
	// RVA: 0x63f06a8 VA: 0x7598a086a8
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x640b64c VA: 0x7598a2364c
	public Void .ctor(Int32 capacity, IEqualityComparer comparer) { }
	// RVA: 0x640b684 VA: 0x7598a23684
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x63f0888 VA: 0x7598a08888
	public Int32 get_Count() { }
	// RVA: 0x640b738 VA: 0x7598a23738
	private Boolean System.Collections.IDictionary.get_IsFixedSize() { }
	// RVA: 0x640b740 VA: 0x7598a23740
	public Boolean get_IsReadOnly() { }
	// RVA: 0x640b748 VA: 0x7598a23748
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x640b750 VA: 0x7598a23750
	public ICollection get_Keys() { }
	// RVA: 0x640b6b4 VA: 0x7598a236b4
	private ArrayList get_objectsArray() { }
	// RVA: 0x640b814 VA: 0x7598a23814
	private Hashtable get_objectsTable() { }
	// RVA: 0x640b8a8 VA: 0x7598a238a8
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x63ffce0 VA: 0x7598a17ce0
	public Object get_Item(Object key) { }
	// RVA: 0x63f0708 VA: 0x7598a08708
	public Void set_Item(Object key, Object value) { }
	// RVA: 0x63f08ac VA: 0x7598a088ac
	public ICollection get_Values() { }
	// RVA: 0x640baa4 VA: 0x7598a23aa4
	public Void Add(Object key, Object value) { }
	// RVA: 0x640bbcc VA: 0x7598a23bcc
	public Void Clear() { }
	// RVA: 0x63f06dc VA: 0x7598a086dc
	public Boolean Contains(Object key) { }
	// RVA: 0x640bc64 VA: 0x7598a23c64
	public Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x640b924 VA: 0x7598a23924
	private Int32 IndexOfKey(Object key) { }
	// RVA: 0x63ffd0c VA: 0x7598a17d0c
	public Void Remove(Object key) { }
	// RVA: 0x640bca0 VA: 0x7598a23ca0
	public virtual IDictionaryEnumerator GetEnumerator() { }
	// RVA: 0x640bd6c VA: 0x7598a23d6c
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x640bde0 VA: 0x7598a23de0
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x640bfb8 VA: 0x7598a23fb8
	private Void System.Runtime.Serialization.IDeserializationCallback.OnDeserialization(Object sender) { }
	// RVA: 0x640bfc8 VA: 0x7598a23fc8
	protected virtual Void OnDeserialization(Object sender) { }
}
```