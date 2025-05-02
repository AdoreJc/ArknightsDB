# UnorderedArray

**Namespace:** `Torappu`


## Fields

- `Int32 <count>k__BackingField`


## Properties

- `Int32 count`

- `T Item`


## Methods

- `Int32 get_count()`

- `Void set_count(Int32)`

- `T get_Item(Int32)`

- `Void Add(T)`

- `Boolean Remove(T)`

- `Boolean Contains(T)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class UnorderedArray`1 : IEnumerable`1, IEnumerable
{
	private T[] m_items; // 0x0
	private Dictionary`2 m_itemMap; // 0x0
	private Int32 <count>k__BackingField; // 0x0

	public Int32 count { get; set; }
	public T Item { get; }

	// RVA: 0x VA: 0x0
	public Int32 get_count() { }
	// RVA: 0x VA: 0x0
	private Void set_count(Int32 value) { }
	// RVA: 0x VA: 0x0
	public T get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public Void Add(T item) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T item) { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T item) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```