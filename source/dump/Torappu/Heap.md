# Heap

**Namespace:** `Torappu`


## Properties

- `Int32 count`

- `Boolean isEmpty`

- `T Item`


## Methods

- `Int32 get_count()`

- `Boolean get_isEmpty()`

- `T get_Item(Int32)`

- `Void Push(T)`

- `T Pop()`

- `T Peek()`

- `Boolean Update(T)`

- `Boolean Remove(T)`

- `Void Clear()`

- `Boolean Contains(T)`

- `Void _Up(Int32)`

- `Void _Down(Int32)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class Heap`1 : IEnumerable, IEnumerable`1
{
	private List`1 m_list; // 0x0
	private Dictionary`2 m_dataMap; // 0x0

	public Int32 count { get; }
	public Boolean isEmpty { get; }
	public T Item { get; }

	// RVA: 0x VA: 0x0
	public Int32 get_count() { }
	// RVA: 0x VA: 0x0
	public Boolean get_isEmpty() { }
	// RVA: 0x VA: 0x0
	public T get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public Void Push(T item) { }
	// RVA: 0x VA: 0x0
	public T Pop() { }
	// RVA: 0x VA: 0x0
	public T Peek() { }
	// RVA: 0x VA: 0x0
	public Boolean Update(T obj) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T obj) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T obj) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Void _Up(Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void _Down(Int32 index) { }
}
```