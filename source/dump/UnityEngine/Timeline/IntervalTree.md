# IntervalTree

**Namespace:** `UnityEngine.Timeline`


## Fields

- `Boolean <dirty>k__BackingField`


## Properties

- `Boolean dirty`


## Methods

- `Boolean get_dirty()`

- `Void Add(T)`

- `Void IntersectsWith(Int64, List`1)`

- `Void Query(IntervalTreeNode, Int64, List`1)`

- `Void Rebuild()`

- `Int32 Rebuild(Int32, Int32)`


## Dump
```C#
// Dll : Unity.Timeline.dll
// Namespace : UnityEngine.Timeline
internal class IntervalTree`1
{
	private readonly List`1 m_Entries; // 0x0
	private readonly List`1 m_Nodes; // 0x0
	private Boolean <dirty>k__BackingField; // 0x0

	public Boolean dirty { get; set; }

	// RVA: 0x VA: 0x0
	public Boolean get_dirty() { }
	// RVA: 0x VA: 0x0
	internal Void set_dirty(Boolean value) { }
	// RVA: 0x VA: 0x0
	public Void Add(T item) { }
	// RVA: 0x VA: 0x0
	public Void IntersectsWith(Int64 value, List`1 results) { }
	// RVA: 0x VA: 0x0
	private Void Query(IntervalTreeNode intervalTreeNode, Int64 value, List`1 results) { }
	// RVA: 0x VA: 0x0
	private Void Rebuild() { }
	// RVA: 0x VA: 0x0
	private Int32 Rebuild(Int32 start, Int32 end) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```