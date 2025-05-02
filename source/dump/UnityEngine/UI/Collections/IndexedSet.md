# IndexedSet

**Namespace:** `UnityEngine.UI.Collections`


## Fields

- `Int32 m_EnabledObjectCount`


## Properties

- `Int32 Count`

- `Int32 Capacity`

- `Boolean IsReadOnly`

- `T Item`


## Methods

- `Void Add(T)`

- `Void Add(T, Boolean)`

- `Boolean AddUnique(T, Boolean)`

- `Boolean EnableItem(T)`

- `Boolean DisableItem(T)`

- `Boolean Remove(T)`

- `Void Clear()`

- `Boolean Contains(T)`

- `Void CopyTo(T[], Int32)`

- `Int32 get_Count()`

- `Int32 get_Capacity()`

- `Boolean get_IsReadOnly()`

- `Int32 IndexOf(T)`

- `Void Insert(Int32, T)`

- `Void RemoveAt(Int32)`

- `Void Swap(Int32, Int32)`

- `T get_Item(Int32)`

- `Void set_Item(Int32, T)`

- `Void RemoveAll(Predicate`1)`

- `Void Sort(Comparison`1)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI.Collections
internal class IndexedSet`1 : IList`1, ICollection`1, IEnumerable`1, IEnumerable
{
	private readonly List`1 m_List; // 0x0
	private Dictionary`2 m_Dictionary; // 0x0
	private Int32 m_EnabledObjectCount; // 0x0

	public Int32 Count { get; }
	public Int32 Capacity { get; }
	public Boolean IsReadOnly { get; }
	public T Item { get; set; }

	// RVA: 0x VA: 0x0
	public Void Add(T item) { }
	// RVA: 0x VA: 0x0
	public Void Add(T item, Boolean isActive) { }
	// RVA: 0x VA: 0x0
	public Boolean AddUnique(T item, Boolean isActive) { }
	// RVA: 0x VA: 0x0
	public Boolean EnableItem(T item) { }
	// RVA: 0x VA: 0x0
	public Boolean DisableItem(T item) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T item) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T item) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public Int32 get_Capacity() { }
	// RVA: 0x VA: 0x0
	public Boolean get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(T item) { }
	// RVA: 0x VA: 0x0
	public Void Insert(Int32 index, T item) { }
	// RVA: 0x VA: 0x0
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void Swap(Int32 index1, Int32 index2) { }
	// RVA: 0x VA: 0x0
	public T get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(Int32 index, T value) { }
	// RVA: 0x VA: 0x0
	public Void RemoveAll(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Void Sort(Comparison`1 sortLayoutFunction) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```