# ValueTypeList

**Namespace:** `Torappu`


## Properties

- `T Item`


## Methods

- `T get_Item(Int32)`

- `Void set_Item(Int32, T)`

- `Void Add(T)`

- `Boolean Contains(T)`

- `Enumerator GetEnumerator()`

- `Int32 IndexOf(T)`

- `Void Insert(Int32, T)`

- `Boolean Remove(T)`

- `Void Sort(Comparison`1)`

- `Int32 <CreateComparison>b__12_0(StructWrapper`1, StructWrapper`1)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class ValueTypeList`1 : BaseValueTypeList`1
{
	private Comparison`1 m_comparison; // 0x0

	public T Item { get; set; }

	// RVA: 0x VA: 0x0
	public T get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(Int32 index, T value) { }
	// RVA: 0x VA: 0x0
	public Void Add(T item) { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T item) { }
	// RVA: 0x VA: 0x0
	public Enumerator GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Int32 IndexOf(T item) { }
	// RVA: 0x VA: 0x0
	public Void Insert(Int32 index, T item) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T item) { }
	// RVA: 0x VA: 0x0
	public Void Sort(Comparison`1 comparison) { }
	// RVA: 0x VA: 0x0
	protected override Comparison`1 CreateComparison() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	private Int32 <CreateComparison>b__12_0(StructWrapper`1 lhs, StructWrapper`1 rhs) { }
}
```