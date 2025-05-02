# EnumerableSorter

**Namespace:** `System.Linq`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Linq
internal class EnumerableSorter`2 : EnumerableSorter`1
{
	internal Func`2 keySelector; // 0x0
	internal IComparer`1 comparer; // 0x0
	internal Boolean descending; // 0x0
	internal EnumerableSorter`1 next; // 0x0
	internal TKey[] keys; // 0x0


	// RVA: 0x VA: 0x0
	internal Void .ctor(Func`2 keySelector, IComparer`1 comparer, Boolean descending, EnumerableSorter`1 next) { }
	// RVA: 0x VA: 0x0
	internal override Void ComputeKeys(TElement[] elements, Int32 count) { }
	// RVA: 0x VA: 0x0
	internal override Int32 CompareKeys(Int32 index1, Int32 index2) { }
}
```