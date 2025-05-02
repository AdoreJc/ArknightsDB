# SortedList

**Namespace:** `System.Collections`


## Fields

- `Int32 _size`

- `Int32 version`

- `IComparer comparer`

- `KeyList keyList`

- `ValueList valueList`

- `Object _syncRoot`


## Methods

- `Void Init()`

- `Void EnsureCapacity(Int32)`

- `Void Insert(Int32, Object, Object)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections
public class SortedList : IDictionary, ICollection, IEnumerable, ICloneable
{
	private Object[] keys; // 0x10
	private Object[] values; // 0x18
	private Int32 _size; // 0x20
	private Int32 version; // 0x24
	private IComparer comparer; // 0x28
	private KeyList keyList; // 0x30
	private ValueList valueList; // 0x38
	private Object _syncRoot; // 0x40

	public virtual Int32 Capacity { set; }
	public virtual Int32 Count { get; }
	public virtual ICollection Keys { get; }
	public virtual ICollection Values { get; }
	public virtual Boolean IsReadOnly { get; }
	public virtual Boolean IsFixedSize { get; }
	public virtual Boolean IsSynchronized { get; }
	public virtual Object SyncRoot { get; }
	public virtual Object Item { get; set; }

	// RVA: 0x607f7bc VA: 0x75986977bc
	public Void .ctor() { }
	// RVA: 0x607f7d8 VA: 0x75986977d8
	private Void Init() { }
	// RVA: 0x607f930 VA: 0x7598697930
	public Void .ctor(Int32 initialCapacity) { }
	// RVA: 0x607fa94 VA: 0x7598697a94
	public Void .ctor(IComparer comparer) { }
	// RVA: 0x607fadc VA: 0x7598697adc
	public virtual Void Add(Object key, Object value) { }
	// RVA: 0x607fd4c VA: 0x7598697d4c
	public virtual Void set_Capacity(Int32 value) { }
	// RVA: 0x607ff74 VA: 0x7598697f74
	public virtual Int32 get_Count() { }
	// RVA: 0x607ff7c VA: 0x7598697f7c
	public virtual ICollection get_Keys() { }
	// RVA: 0x607ff8c VA: 0x7598697f8c
	public virtual ICollection get_Values() { }
	// RVA: 0x607ff9c VA: 0x7598697f9c
	public virtual Boolean get_IsReadOnly() { }
	// RVA: 0x607ffa4 VA: 0x7598697fa4
	public virtual Boolean get_IsFixedSize() { }
	// RVA: 0x607ffac VA: 0x7598697fac
	public virtual Boolean get_IsSynchronized() { }
	// RVA: 0x607ffb4 VA: 0x7598697fb4
	public virtual Object get_SyncRoot() { }
	// RVA: 0x608002c VA: 0x759869802c
	public virtual Void Clear() { }
	// RVA: 0x6080070 VA: 0x7598698070
	public virtual Object Clone() { }
	// RVA: 0x6080124 VA: 0x7598698124
	public virtual Boolean Contains(Object key) { }
	// RVA: 0x6080148 VA: 0x7598698148
	public virtual Boolean ContainsValue(Object value) { }
	// RVA: 0x608016c VA: 0x759869816c
	public virtual Void CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x6080420 VA: 0x7598698420
	private Void EnsureCapacity(Int32 min) { }
	// RVA: 0x608046c VA: 0x759869846c
	public virtual Object GetByIndex(Int32 index) { }
	// RVA: 0x6080528 VA: 0x7598698528
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x6080610 VA: 0x7598698610
	public virtual IDictionaryEnumerator GetEnumerator() { }
	// RVA: 0x6080680 VA: 0x7598698680
	public virtual Object GetKey(Int32 index) { }
	// RVA: 0x608073c VA: 0x759869873c
	public virtual IList GetKeyList() { }
	// RVA: 0x60807f8 VA: 0x75986987f8
	public virtual IList GetValueList() { }
	// RVA: 0x60808b4 VA: 0x75986988b4
	public virtual Object get_Item(Object key) { }
	// RVA: 0x6080904 VA: 0x7598698904
	public virtual Void set_Item(Object key, Object value) { }
	// RVA: 0x6080a30 VA: 0x7598698a30
	public virtual Int32 IndexOfKey(Object key) { }
	// RVA: 0x6080ad0 VA: 0x7598698ad0
	public virtual Int32 IndexOfValue(Object value) { }
	// RVA: 0x607fc0c VA: 0x7598697c0c
	private Void Insert(Int32 index, Object key, Object value) { }
	// RVA: 0x6080b30 VA: 0x7598698b30
	public virtual Void RemoveAt(Int32 index) { }
	// RVA: 0x6080c7c VA: 0x7598698c7c
	public virtual Void Remove(Object key) { }
	// RVA: 0x6080cbc VA: 0x7598698cbc
	public static SortedList Synchronized(SortedList list) { }
}
```