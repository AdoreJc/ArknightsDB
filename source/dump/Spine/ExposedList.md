# ExposedList

**Namespace:** `Spine`


## Fields

- `Int32 Count`

- `Int32 version`


## Properties

- `Int32 Capacity`


## Methods

- `Void Add(T)`

- `Void GrowIfNeeded(Int32)`

- `Void EnsureCapacity(Int32)`

- `Void CheckRange(Int32, Int32)`

- `Void AddCollection(ICollection`1)`

- `Void AddEnumerable(IEnumerable`1)`

- `Void AddRange(ExposedList`1)`

- `Void AddRange(IEnumerable`1)`

- `Int32 BinarySearch(T)`

- `Int32 BinarySearch(T, IComparer`1)`

- `Int32 BinarySearch(Int32, Int32, T, IComparer`1)`

- `Void Clear(Boolean)`

- `Boolean Contains(T)`

- `Void CopyTo(T[])`

- `Void CopyTo(T[], Int32)`

- `Void CopyTo(Int32, T[], Int32, Int32)`

- `Boolean Exists(Predicate`1)`

- `T Find(Predicate`1)`

- `Int32 FindIndex(Predicate`1)`

- `Int32 FindIndex(Int32, Predicate`1)`

- `Int32 FindIndex(Int32, Int32, Predicate`1)`

- `Int32 GetIndex(Int32, Int32, Predicate`1)`

- `T FindLast(Predicate`1)`

- `Int32 FindLastIndex(Predicate`1)`

- `Int32 FindLastIndex(Int32, Predicate`1)`

- `Int32 FindLastIndex(Int32, Int32, Predicate`1)`

- `Int32 GetLastIndex(Int32, Int32, Predicate`1)`

- `Void ForEach(Action`1)`

- `Enumerator GetEnumerator()`

- `Int32 IndexOf(T)`

- `Int32 IndexOf(T, Int32)`

- `Int32 IndexOf(T, Int32, Int32)`

- `Void Shift(Int32, Int32)`

- `Void CheckIndex(Int32)`

- `Void Insert(Int32, T)`

- `Void CheckCollection(IEnumerable`1)`

- `Void InsertRange(Int32, IEnumerable`1)`

- `Void InsertCollection(Int32, ICollection`1)`

- `Void InsertEnumeration(Int32, IEnumerable`1)`

- `Int32 LastIndexOf(T)`

- `Int32 LastIndexOf(T, Int32)`

- `Int32 LastIndexOf(T, Int32, Int32)`

- `Boolean Remove(T)`

- `Int32 RemoveAll(Predicate`1)`

- `Void RemoveAt(Int32)`

- `T Pop()`

- `Void RemoveRange(Int32, Int32)`

- `Void Reverse()`

- `Void Reverse(Int32, Int32)`

- `Void Sort()`

- `Void Sort(IComparer`1)`

- `Void Sort(Comparison`1)`

- `Void Sort(Int32, Int32, IComparer`1)`

- `Void TrimExcess()`

- `Boolean TrueForAll(Predicate`1)`

- `Int32 get_Capacity()`

- `Void set_Capacity(Int32)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class ExposedList`1 : IEnumerable`1, IEnumerable
{
	public T[] Items; // 0x0
	public Int32 Count; // 0x0
	private const Int32 DefaultCapacity; // 0x0
	private static readonly T[] EmptyArray; // 0x0
	private Int32 version; // 0x0

	public Int32 Capacity { get; set; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	internal Void .ctor(T[] data, Int32 size) { }
	// RVA: 0x VA: 0x0
	public Void Add(T item) { }
	// RVA: 0x VA: 0x0
	public Void GrowIfNeeded(Int32 addedCount) { }
	// RVA: 0x VA: 0x0
	public ExposedList`1 Resize(Int32 newSize) { }
	// RVA: 0x VA: 0x0
	public Void EnsureCapacity(Int32 min) { }
	// RVA: 0x VA: 0x0
	private Void CheckRange(Int32 index, Int32 count) { }
	// RVA: 0x VA: 0x0
	private Void AddCollection(ICollection`1 collection) { }
	// RVA: 0x VA: 0x0
	private Void AddEnumerable(IEnumerable`1 enumerable) { }
	// RVA: 0x VA: 0x0
	public Void AddRange(ExposedList`1 list) { }
	// RVA: 0x VA: 0x0
	public Void AddRange(IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	public Int32 BinarySearch(T item) { }
	// RVA: 0x VA: 0x0
	public Int32 BinarySearch(T item, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Int32 BinarySearch(Int32 index, Int32 count, T item, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Void Clear(Boolean clearArray) { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T item) { }
	// RVA: 0x VA: 0x0
	public ExposedList`1 ConvertAll(Converter`2 converter) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(Int32 index, T[] array, Int32 arrayIndex, Int32 count) { }
	// RVA: 0x VA: 0x0
	public Boolean Exists(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public T Find(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	private static Void CheckMatch(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public ExposedList`1 FindAll(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	private ExposedList`1 FindAllList(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 FindIndex(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 FindIndex(Int32 startIndex, Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 FindIndex(Int32 startIndex, Int32 count, Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	private Int32 GetIndex(Int32 startIndex, Int32 count, Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public T FindLast(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 FindLastIndex(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 FindLastIndex(Int32 startIndex, Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 FindLastIndex(Int32 startIndex, Int32 count, Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	private Int32 GetLastIndex(Int32 startIndex, Int32 count, Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Void ForEach(Action`1 action) { }
	// RVA: 0x VA: 0x0
	public Enumerator GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public ExposedList`1 GetRange(Int32 index, Int32 count) { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(T item) { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(T item, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(T item, Int32 index, Int32 count) { }
	// RVA: 0x VA: 0x0
	private Void Shift(Int32 start, Int32 delta) { }
	// RVA: 0x VA: 0x0
	private Void CheckIndex(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void Insert(Int32 index, T item) { }
	// RVA: 0x VA: 0x0
	private Void CheckCollection(IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	public Void InsertRange(Int32 index, IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	private Void InsertCollection(Int32 index, ICollection`1 collection) { }
	// RVA: 0x VA: 0x0
	private Void InsertEnumeration(Int32 index, IEnumerable`1 enumerable) { }
	// RVA: 0x VA: 0x0
	public Int32 LastIndexOf(T item) { }
	// RVA: 0x VA: 0x0
	public Int32 LastIndexOf(T item, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Int32 LastIndexOf(T item, Int32 index, Int32 count) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T item) { }
	// RVA: 0x VA: 0x0
	public Int32 RemoveAll(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x VA: 0x0
	public T Pop() { }
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
	public Void Sort(Comparison`1 comparison) { }
	// RVA: 0x VA: 0x0
	public Void Sort(Int32 index, Int32 count, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public T[] ToArray() { }
	// RVA: 0x VA: 0x0
	public Void TrimExcess() { }
	// RVA: 0x VA: 0x0
	public Boolean TrueForAll(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Capacity() { }
	// RVA: 0x VA: 0x0
	public Void set_Capacity(Int32 value) { }
	// RVA: 0x VA: 0x0
	private IEnumerator`1 System.Collections.Generic.IEnumerable<T>.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private static Void .cctor() { }
}
```