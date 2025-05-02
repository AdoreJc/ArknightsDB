# Collection

**Namespace:** `System.Collections.ObjectModel`


## Properties

- `Int32 Count`

- `T Item`


## Methods

- `Int32 get_Count()`

- `T get_Item(Int32)`

- `Void set_Item(Int32, T)`

- `Void Add(T)`

- `Void Clear()`

- `Void CopyTo(T[], Int32)`

- `Boolean Contains(T)`

- `Int32 IndexOf(T)`

- `Void Insert(Int32, T)`

- `Boolean Remove(T)`

- `Void RemoveAt(Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections.ObjectModel
public class Collection`1 : IList`1, ICollection`1, IEnumerable`1, IEnumerable, IList, ICollection, IReadOnlyList`1, IReadOnlyCollection`1
{
	private IList`1 items; // 0x0

	public Int32 Count { get; }
	protected IList`1 Items { get; }
	public T Item { get; set; }
	private Boolean System.Collections.Generic.ICollection<T>.IsReadOnly { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	private Object System.Collections.IList.Item { get; set; }
	private Boolean System.Collections.IList.IsReadOnly { get; }
	private Boolean System.Collections.IList.IsFixedSize { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IList`1 list) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	protected IList`1 get_Items() { }
	// RVA: 0x VA: 0x0
	public T get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(Int32 index, T value) { }
	// RVA: 0x VA: 0x0
	public Void Add(T item) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T item) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(T item) { }
	// RVA: 0x VA: 0x0
	public Void Insert(Int32 index, T item) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T item) { }
	// RVA: 0x VA: 0x0
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x VA: 0x0
	protected virtual Void ClearItems() { }
	// RVA: 0x VA: 0x0
	protected virtual Void InsertItem(Int32 index, T item) { }
	// RVA: 0x VA: 0x0
	protected virtual Void RemoveItem(Int32 index) { }
	// RVA: 0x VA: 0x0
	protected virtual Void SetItem(Int32 index, T item) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<T>.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IList.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x VA: 0x0
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IList.Contains(Object value) { }
	// RVA: 0x VA: 0x0
	private Int32 System.Collections.IList.IndexOf(Object value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.Insert(Int32 index, Object value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x VA: 0x0
	private static Boolean IsCompatibleObject(Object value) { }
}
```