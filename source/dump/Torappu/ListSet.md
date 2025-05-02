# ListSet

**Namespace:** `Torappu`


## Properties

- `Int32 count`

- `Boolean isEmpty`

- `TItem Item`


## Methods

- `Int32 get_count()`

- `Boolean get_isEmpty()`

- `TItem get_Item(Int32)`

- `Void Clear()`

- `Boolean Contains(TItem)`

- `Boolean Add(TItem)`

- `Void AddRange(IList`1)`

- `Void RemoveRange(IEnumerable`1)`

- `Boolean Remove(TItem)`

- `Void RemoveAt(Int32)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class ListSet`1 : IEnumerable, IEnumerable`1
{
	private List`1 m_items; // 0x0

	public Int32 count { get; }
	public Boolean isEmpty { get; }
	public TItem Item { get; }

	// RVA: 0x VA: 0x0
	public Int32 get_count() { }
	// RVA: 0x VA: 0x0
	public Boolean get_isEmpty() { }
	// RVA: 0x VA: 0x0
	public TItem get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(TItem item) { }
	// RVA: 0x VA: 0x0
	public Boolean Add(TItem item) { }
	// RVA: 0x VA: 0x0
	public Void AddRange(IList`1 items) { }
	// RVA: 0x VA: 0x0
	public Void RemoveRange(IEnumerable`1 items) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(TItem item) { }
	// RVA: 0x VA: 0x0
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public TItem[] ToArray() { }
	// RVA: 0x VA: 0x0
	public List`1 GetInternalList() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```