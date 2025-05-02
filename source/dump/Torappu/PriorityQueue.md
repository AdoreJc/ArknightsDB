# PriorityQueue

**Namespace:** `Torappu`


## Properties

- `Int32 count`

- `Boolean isEmpty`

- `T Item`


## Methods

- `Int32 get_count()`

- `Boolean get_isEmpty()`

- `T get_Item(Int32)`

- `Void set_Item(Int32, T)`

- `Void Add(T)`

- `Boolean Remove(T)`

- `Void RemoveLast()`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PriorityQueue`1 : IEnumerable, IEnumerable`1
{
	private List`1 m_list; // 0x0

	public Int32 count { get; }
	public Boolean isEmpty { get; }
	public T Item { get; set; }

	// RVA: 0x VA: 0x0
	public Int32 get_count() { }
	// RVA: 0x VA: 0x0
	public Boolean get_isEmpty() { }
	// RVA: 0x VA: 0x0
	public T get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(Int32 index, T value) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IList`1 items) { }
	// RVA: 0x VA: 0x0
	public Void Add(T item) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T item) { }
	// RVA: 0x VA: 0x0
	public Void RemoveLast() { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```