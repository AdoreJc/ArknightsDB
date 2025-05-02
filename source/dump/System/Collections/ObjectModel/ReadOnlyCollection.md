# ReadOnlyCollection

**Namespace:** `System.Collections.ObjectModel`


## Fields

- `Object _syncRoot`


## Properties

- `Int32 Count`

- `T Item`


## Methods

- `Int32 get_Count()`

- `T get_Item(Int32)`

- `Boolean Contains(T)`

- `Void CopyTo(T[], Int32)`

- `Int32 IndexOf(T)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections.ObjectModel
public class ReadOnlyCollection`1 : IList`1, ICollection`1, IEnumerable`1, IEnumerable, IList, ICollection, IReadOnlyList`1, IReadOnlyCollection`1
{
	private IList`1 list; // 0x0
	private Object _syncRoot; // 0x0

	public Int32 Count { get; }
	public T Item { get; }
	private Boolean System.Collections.Generic.ICollection<T>.IsReadOnly { get; }
	private T System.Collections.Generic.IList<T>.Item { get; set; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	private Boolean System.Collections.IList.IsFixedSize { get; }
	private Boolean System.Collections.IList.IsReadOnly { get; }
	private Object System.Collections.IList.Item { get; set; }

	// RVA: 0x VA: 0x0
	public Void .ctor(IList`1 list) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public T get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T value) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array, Int32 index) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(T value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<T>.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private T System.Collections.Generic.IList<T>.get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.IList<T>.set_Item(Int32 index, T value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<T>.Add(T value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<T>.Clear() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.IList<T>.Insert(Int32 index, T value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<T>.Remove(T value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.IList<T>.RemoveAt(Int32 index) { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IList.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x VA: 0x0
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.Clear() { }
	// RVA: 0x VA: 0x0
	private static Boolean IsCompatibleObject(Object value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IList.Contains(Object value) { }
	// RVA: 0x VA: 0x0
	private Int32 System.Collections.IList.IndexOf(Object value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.Insert(Int32 index, Object value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.RemoveAt(Int32 index) { }
}
```