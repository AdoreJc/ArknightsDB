# GroupedEnumerable

**Namespace:** `System.Linq`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq
internal class GroupedEnumerable`3 : IEnumerable`1, IEnumerable
{
	private IEnumerable`1 source; // 0x0
	private Func`2 keySelector; // 0x0
	private Func`2 elementSelector; // 0x0
	private IEqualityComparer`1 comparer; // 0x0


	// RVA: 0x VA: 0x0
	public Void .ctor(IEnumerable`1 source, Func`2 keySelector, Func`2 elementSelector, IEqualityComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```