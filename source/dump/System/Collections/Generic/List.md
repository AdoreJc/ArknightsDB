# List

**Namespace:** `System.Collections.Generic`


## Fields

- `Int32 _size`

- `Int32 _version`

- `Object _syncRoot`


## Properties

- `Int32 Capacity`

- `Int32 Count`

- `T Item`


## Methods

- `Int32 get_Capacity()`

- `Void set_Capacity(Int32)`

- `Int32 get_Count()`

- `T get_Item(Int32)`

- `Void set_Item(Int32, T)`

- `Void Add(T)`

- `Void AddWithResize(T)`

- `Void AddRange(IEnumerable`1)`

- `Int32 BinarySearch(Int32, Int32, T, IComparer`1)`

- `Int32 BinarySearch(T)`

- `Int32 BinarySearch(T, IComparer`1)`

- `Void Clear()`

- `Boolean Contains(T)`

- `Void CopyTo(T[])`

- `Void CopyTo(Int32, T[], Int32, Int32)`

- `Void CopyTo(T[], Int32)`

- `Void EnsureCapacity(Int32)`

- `Boolean Exists(Predicate`1)`

- `T Find(Predicate`1)`

- `Int32 FindIndex(Predicate`1)`

- `Int32 FindIndex(Int32, Predicate`1)`

- `Int32 FindIndex(Int32, Int32, Predicate`1)`

- `T FindLast(Predicate`1)`

- `Int32 FindLastIndex(Predicate`1)`

- `Int32 FindLastIndex(Int32, Predicate`1)`

- `Int32 FindLastIndex(Int32, Int32, Predicate`1)`

- `Void ForEach(Action`1)`

- `Enumerator GetEnumerator()`

- `Int32 IndexOf(T)`

- `Int32 IndexOf(T, Int32)`

- `Int32 IndexOf(T, Int32, Int32)`

- `Void Insert(Int32, T)`

- `Void InsertRange(Int32, IEnumerable`1)`

- `Int32 LastIndexOf(T)`

- `Int32 LastIndexOf(T, Int32)`

- `Int32 LastIndexOf(T, Int32, Int32)`

- `Boolean Remove(T)`

- `Int32 RemoveAll(Predicate`1)`

- `Void RemoveAt(Int32)`

- `Void RemoveRange(Int32, Int32)`

- `Void Reverse()`

- `Void Reverse(Int32, Int32)`

- `Void Sort()`

- `Void Sort(IComparer`1)`

- `Void Sort(Int32, Int32, IComparer`1)`

- `Void Sort(Comparison`1)`

- `Void TrimExcess()`

- `Boolean TrueForAll(Predicate`1)`

- `Void AddEnumerable(IEnumerable`1)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections.Generic
public class List`1 : IList`1, ICollection`1, IEnumerable`1, IEnumerable, IList, ICollection, IReadOnlyList`1, IReadOnlyCollection`1
{
	private const Int32 DefaultCapacity; // 0x0
	private T[] _items; // 0x0
	private Int32 _size; // 0x0
	private Int32 _version; // 0x0
	private Object _syncRoot; // 0x0
	private static readonly T[] s_emptyArray; // 0x0

	public Int32 Capacity { get; set; }
	public Int32 Count { get; }
	private Boolean System.Collections.IList.IsFixedSize { get; }
	private Boolean System.Collections.Generic.ICollection<T>.IsReadOnly { get; }
	private Boolean System.Collections.IList.IsReadOnly { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	public T Item { get; set; }
	private Object System.Collections.IList.Item { get; set; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Capacity() { }
	// RVA: 0x VA: 0x0
	public Void set_Capacity(Int32 value) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<T>.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IList.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	public T get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(Int32 index, T value) { }
	// RVA: 0x VA: 0x0
	private static Boolean IsCompatibleObject(Object value) { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x VA: 0x0
	public Void Add(T item) { }
	// RVA: 0x VA: 0x0
	private Void AddWithResize(T item) { }
	// RVA: 0x VA: 0x0
	private Int32 System.Collections.IList.Add(Object item) { }
	// RVA: 0x VA: 0x0
	public Void AddRange(IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	public ReadOnlyCollection`1 AsReadOnly() { }
	// RVA: 0x VA: 0x0
	public Int32 BinarySearch(Int32 index, Int32 count, T item, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Int32 BinarySearch(T item) { }
	// RVA: 0x VA: 0x0
	public Int32 BinarySearch(T item, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T item) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IList.Contains(Object item) { }
	// RVA: 0x VA: 0x0
	public List`1 ConvertAll(Converter`2 converter) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(Int32 index, T[] array, Int32 arrayIndex, Int32 count) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	private Void EnsureCapacity(Int32 min) { }
	// RVA: 0x VA: 0x0
	public Boolean Exists(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public T Find(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public List`1 FindAll(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 FindIndex(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 FindIndex(Int32 startIndex, Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 FindIndex(Int32 startIndex, Int32 count, Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public T FindLast(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 FindLastIndex(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 FindLastIndex(Int32 startIndex, Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 FindLastIndex(Int32 startIndex, Int32 count, Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Void ForEach(Action`1 action) { }
	// RVA: 0x VA: 0x0
	public Enumerator GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator`1 System.Collections.Generic.IEnumerable<T>.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public List`1 GetRange(Int32 index, Int32 count) { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(T item) { }
	// RVA: 0x VA: 0x0
	private Int32 System.Collections.IList.IndexOf(Object item) { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(T item, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(T item, Int32 index, Int32 count) { }
	// RVA: 0x VA: 0x0
	public Void Insert(Int32 index, T item) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.Insert(Int32 index, Object item) { }
	// RVA: 0x VA: 0x0
	public Void InsertRange(Int32 index, IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	public Int32 LastIndexOf(T item) { }
	// RVA: 0x VA: 0x0
	public Int32 LastIndexOf(T item, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Int32 LastIndexOf(T item, Int32 index, Int32 count) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T item) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.Remove(Object item) { }
	// RVA: 0x VA: 0x0
	public Int32 RemoveAll(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void RemoveRange(Int32 index, Int32 count) { }
	// RVA: 0x VA: 0x0
	public Void Reverse() { }
	// RVA: 0x VA: 0x0
	public Void Reverse(Int32 index, Int32 count) { }
	// RVA: 0x VA: 0x0
	public Void Sort() { }
	// RVA: 0x VA: 0x0
	public Void Sort(IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void Sort(Int32 index, Int32 count, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void Sort(Comparison`1 comparison) { }
	// RVA: 0x VA: 0x0
	public T[] ToArray() { }
	// RVA: 0x VA: 0x0
	public Void TrimExcess() { }
	// RVA: 0x VA: 0x0
	public Boolean TrueForAll(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	private Void AddEnumerable(IEnumerable`1 enumerable) { }
	// RVA: 0x VA: 0x0
	private static Void .cctor() { }
}
```