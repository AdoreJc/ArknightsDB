# Set

**Namespace:** `System.Linq`


## Fields

- `Int32 count`

- `Int32 freeList`


## Methods

- `Boolean Add(TElement)`

- `Boolean Find(TElement, Boolean)`

- `Void Resize()`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq
internal class Set`1
{
	private Int32[] buckets; // 0x0
	private Slot[] slots; // 0x0
	private Int32 count; // 0x0
	private Int32 freeList; // 0x0
	private IEqualityComparer`1 comparer; // 0x0


	// RVA: 0x VA: 0x0
	public Void .ctor(IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public Boolean Add(TElement value) { }
	// RVA: 0x VA: 0x0
	private Boolean Find(TElement value, Boolean add) { }
	// RVA: 0x VA: 0x0
	private Void Resize() { }
	// RVA: 0x VA: 0x0
	internal Int32 InternalGetHashCode(TElement value) { }
}
```