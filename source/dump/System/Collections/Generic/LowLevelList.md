# LowLevelList

**Namespace:** `System.Collections.Generic`


## Fields

- `Int32 _size`

- `Int32 _version`


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

- `Void EnsureCapacity(Int32)`

- `Void AddRange(IEnumerable`1)`

- `Void Clear()`

- `Boolean Contains(T)`

- `Void CopyTo(T[], Int32)`

- `Int32 IndexOf(T)`

- `Void Insert(Int32, T)`

- `Void InsertRange(Int32, IEnumerable`1)`

- `Boolean Remove(T)`

- `Int32 RemoveAll(Predicate`1)`

- `Void RemoveAt(Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections.Generic
internal class LowLevelList`1
{
	private const Int32 _defaultCapacity; // 0x0
	protected T[] _items; // 0x0
	protected Int32 _size; // 0x0
	protected Int32 _version; // 0x0
	private static readonly T[] s_emptyArray; // 0x0

	public Int32 Capacity { get; set; }
	public Int32 Count { get; }
	public T Item { get; set; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Capacity() { }
	// RVA: 0x VA: 0x0
	public Void set_Capacity(Int32 value) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public T get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(Int32 index, T value) { }
	// RVA: 0x VA: 0x0
	public Void Add(T item) { }
	// RVA: 0x VA: 0x0
	private Void EnsureCapacity(Int32 min) { }
	// RVA: 0x VA: 0x0
	public Void AddRange(IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T item) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(T item) { }
	// RVA: 0x VA: 0x0
	public Void Insert(Int32 index, T item) { }
	// RVA: 0x VA: 0x0
	public Void InsertRange(Int32 index, IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T item) { }
	// RVA: 0x VA: 0x0
	public Int32 RemoveAll(Predicate`1 match) { }
	// RVA: 0x VA: 0x0
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x VA: 0x0
	private static Void .cctor() { }
}
```