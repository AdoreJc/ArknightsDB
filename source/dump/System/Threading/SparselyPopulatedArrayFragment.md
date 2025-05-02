# SparselyPopulatedArrayFragment

**Namespace:** `System.Threading`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading
internal class SparselyPopulatedArrayFragment`1
{
	internal readonly T[] _elements; // 0x0
	internal Int32 _freeCount; // 0x0
	internal SparselyPopulatedArrayFragment`1 _next; // 0x0
	internal SparselyPopulatedArrayFragment`1 _prev; // 0x0

	internal T Item { get; }
	internal Int32 Length { get; }
	internal SparselyPopulatedArrayFragment`1 Prev { get; }

	// RVA: 0x VA: 0x0
	internal Void .ctor(Int32 size) { }
	// RVA: 0x VA: 0x0
	internal Void .ctor(Int32 size, SparselyPopulatedArrayFragment`1 prev) { }
	// RVA: 0x VA: 0x0
	internal T get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	internal Int32 get_Length() { }
	// RVA: 0x VA: 0x0
	internal SparselyPopulatedArrayFragment`1 get_Prev() { }
	// RVA: 0x VA: 0x0
	internal T SafeAtomicRemove(Int32 index, T expectedElement) { }
}
```