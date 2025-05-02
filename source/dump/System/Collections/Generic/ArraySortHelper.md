# ArraySortHelper

**Namespace:** `System.Collections.Generic`


## Methods

- `Void Sort(TKey[], TValue[], Int32, Int32, IComparer`1)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections.Generic
internal class ArraySortHelper`2
{
	private static readonly ArraySortHelper`2 s_defaultArraySortHelper; // 0x0

	public static ArraySortHelper`2 Default { get; }

	// RVA: 0x VA: 0x0
	public Void Sort(TKey[] keys, TValue[] values, Int32 index, Int32 length, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	private static Void SwapIfGreaterWithItems(TKey[] keys, TValue[] values, IComparer`1 comparer, Int32 a, Int32 b) { }
	// RVA: 0x VA: 0x0
	private static Void Swap(TKey[] keys, TValue[] values, Int32 i, Int32 j) { }
	// RVA: 0x VA: 0x0
	internal static Void IntrospectiveSort(TKey[] keys, TValue[] values, Int32 left, Int32 length, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	private static Void IntroSort(TKey[] keys, TValue[] values, Int32 lo, Int32 hi, Int32 depthLimit, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	private static Int32 PickPivotAndPartition(TKey[] keys, TValue[] values, Int32 lo, Int32 hi, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	private static Void Heapsort(TKey[] keys, TValue[] values, Int32 lo, Int32 hi, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	private static Void DownHeap(TKey[] keys, TValue[] values, Int32 i, Int32 n, Int32 lo, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	private static Void InsertionSort(TKey[] keys, TValue[] values, Int32 lo, Int32 hi, IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	public static ArraySortHelper`2 get_Default() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	private static Void .cctor() { }
}
```