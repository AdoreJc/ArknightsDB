# EventDescriptorCollection

**Namespace:** `System.ComponentModel`


## Fields

- `Boolean _eventsOwned`

- `Boolean _needSort`

- `Int32 <Count>k__BackingField`


## Properties

- `Int32 Count`


## Methods

- `Int32 get_Count()`

- `Void set_Count(Int32)`

- `Int32 Add(EventDescriptor)`

- `Void Clear()`

- `Boolean Contains(EventDescriptor)`

- `Void EnsureEventsOwned()`

- `Void EnsureSize(Int32)`

- `Int32 IndexOf(EventDescriptor)`

- `Void Insert(Int32, EventDescriptor)`

- `Void Remove(EventDescriptor)`

- `Void RemoveAt(Int32)`

- `IEnumerator GetEnumerator()`

- `Void InternalSort(String[])`

- `Void InternalSort(IComparer)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class EventDescriptorCollection : ICollection, IEnumerable, IList
{
	private EventDescriptor[] _events; // 0x10
	private String[] _namedSort; // 0x18
	private readonly IComparer _comparer; // 0x20
	private Boolean _eventsOwned; // 0x28
	private Boolean _needSort; // 0x29
	private readonly Boolean _readOnly; // 0x2a
	public static readonly EventDescriptorCollection Empty; // 0x0
	private Int32 <Count>k__BackingField; // 0x2c

	public Int32 Count { get; set; }
	public virtual EventDescriptor Item { get; }
	public virtual EventDescriptor Item { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	private Int32 System.Collections.ICollection.Count { get; }
	private Object System.Collections.IList.Item { get; set; }
	private Boolean System.Collections.IList.IsReadOnly { get; }
	private Boolean System.Collections.IList.IsFixedSize { get; }

	// RVA: 0x63c1f84 VA: 0x75989d9f84
	public Void .ctor(EventDescriptor[] events) { }
	// RVA: 0x63c204c VA: 0x75989da04c
	public Void .ctor(EventDescriptor[] events, Boolean readOnly) { }
	// RVA: 0x63c2070 VA: 0x75989da070
	private Void .ctor(EventDescriptor[] events, Int32 eventCount, String[] namedSort, IComparer comparer) { }
	// RVA: 0x63c2184 VA: 0x75989da184
	public Int32 get_Count() { }
	// RVA: 0x63c218c VA: 0x75989da18c
	private Void set_Count(Int32 value) { }
	// RVA: 0x63c2194 VA: 0x75989da194
	public virtual EventDescriptor get_Item(Int32 index) { }
	// RVA: 0x63c22dc VA: 0x75989da2dc
	public virtual EventDescriptor get_Item(String name) { }
	// RVA: 0x63c22f0 VA: 0x75989da2f0
	public Int32 Add(EventDescriptor value) { }
	// RVA: 0x63c24e8 VA: 0x75989da4e8
	public Void Clear() { }
	// RVA: 0x63c253c VA: 0x75989da53c
	public Boolean Contains(EventDescriptor value) { }
	// RVA: 0x63c25b4 VA: 0x75989da5b4
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x63c2220 VA: 0x75989da220
	private Void EnsureEventsOwned() { }
	// RVA: 0x63c23c8 VA: 0x75989da3c8
	private Void EnsureSize(Int32 sizeNeeded) { }
	// RVA: 0x63c2864 VA: 0x75989da864
	public virtual EventDescriptor Find(String name, Boolean ignoreCase) { }
	// RVA: 0x63c2554 VA: 0x75989da554
	public Int32 IndexOf(EventDescriptor value) { }
	// RVA: 0x63c2978 VA: 0x75989da978
	public Void Insert(Int32 index, EventDescriptor value) { }
	// RVA: 0x63c2a70 VA: 0x75989daa70
	public Void Remove(EventDescriptor value) { }
	// RVA: 0x63c2ae0 VA: 0x75989daae0
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x63c2ba4 VA: 0x75989daba4
	public IEnumerator GetEnumerator() { }
	// RVA: 0x63c2c88 VA: 0x75989dac88
	public virtual EventDescriptorCollection Sort() { }
	// RVA: 0x63c2d08 VA: 0x75989dad08
	public virtual EventDescriptorCollection Sort(String[] names) { }
	// RVA: 0x63c2d8c VA: 0x75989dad8c
	public virtual EventDescriptorCollection Sort(String[] names, IComparer comparer) { }
	// RVA: 0x63c2e10 VA: 0x75989dae10
	public virtual EventDescriptorCollection Sort(IComparer comparer) { }
	// RVA: 0x63c25f0 VA: 0x75989da5f0
	protected Void InternalSort(String[] names) { }
	// RVA: 0x63c2e94 VA: 0x75989dae94
	protected Void InternalSort(IComparer sorter) { }
	// RVA: 0x63c2f0c VA: 0x75989daf0c
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x63c2f14 VA: 0x75989daf14
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x63c2f1c VA: 0x75989daf1c
	private Int32 System.Collections.ICollection.get_Count() { }
	// RVA: 0x63c2f24 VA: 0x75989daf24
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x63c2f28 VA: 0x75989daf28
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x63c2f38 VA: 0x75989daf38
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x63c30b4 VA: 0x75989db0b4
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x63c3138 VA: 0x75989db138
	private Boolean System.Collections.IList.Contains(Object value) { }
	// RVA: 0x63c31c8 VA: 0x75989db1c8
	private Void System.Collections.IList.Clear() { }
	// RVA: 0x63c31cc VA: 0x75989db1cc
	private Int32 System.Collections.IList.IndexOf(Object value) { }
	// RVA: 0x63c3250 VA: 0x75989db250
	private Void System.Collections.IList.Insert(Int32 index, Object value) { }
	// RVA: 0x63c32e4 VA: 0x75989db2e4
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x63c3368 VA: 0x75989db368
	private Void System.Collections.IList.RemoveAt(Int32 index) { }
	// RVA: 0x63c336c VA: 0x75989db36c
	private Boolean System.Collections.IList.get_IsReadOnly() { }
	// RVA: 0x63c3374 VA: 0x75989db374
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x63c337c VA: 0x75989db37c
	private static Void .cctor() { }
}
```