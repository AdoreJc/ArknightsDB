# OrderedEnumerable

**Namespace:** `System.Linq`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq
internal class OrderedEnumerable`2 : OrderedEnumerable`1
{
	internal OrderedEnumerable`1 parent; // 0x0
	internal Func`2 keySelector; // 0x0
	internal IComparer`1 comparer; // 0x0
	internal Boolean descending; // 0x0


	// RVA: 0x VA: 0x0
	internal Void .ctor(IEnumerable`1 source, Func`2 keySelector, IComparer`1 comparer, Boolean descending) { }
	// RVA: 0x VA: 0x0
	internal override EnumerableSorter`1 GetEnumerableSorter(EnumerableSorter`1 next) { }
}
```