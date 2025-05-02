# Lookup

**Namespace:** `System.Linq`


## Fields

- `Grouping lastGrouping`

- `Int32 count`


## Methods

- `Void Resize()`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq
public class Lookup`2 : IEnumerable`1, IEnumerable
{
	private IEqualityComparer`1 comparer; // 0x0
	private Grouping[] groupings; // 0x0
	private Grouping lastGrouping; // 0x0
	private Int32 count; // 0x0


	// RVA: 0x VA: 0x0
	internal static Lookup`2 Create(IEnumerable`1 source, Func`2 keySelector, Func`2 elementSelector, IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	internal static Lookup`2 CreateForJoin(IEnumerable`1 source, Func`2 keySelector, IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	private Void .ctor(IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	internal Int32 InternalGetHashCode(TKey key) { }
	// RVA: 0x VA: 0x0
	internal Grouping GetGrouping(TKey key, Boolean create) { }
	// RVA: 0x VA: 0x0
	private Void Resize() { }
}
```