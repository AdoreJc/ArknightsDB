# ReusableList

**Namespace:** `Torappu`


## Methods

- `Void Dispose()`

- `Void OnAllocate()`

- `Void OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ReusableList`1 : List`1, IReusable, IDisposable
{
	private ListPool`1 m_parentPool; // 0x0


	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity, ListPool`1 pool) { }
	// RVA: 0x VA: 0x0
	private Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void Dispose() { }
	// RVA: 0x VA: 0x0
	public Void OnAllocate() { }
	// RVA: 0x VA: 0x0
	public Void OnRecycle() { }
	// RVA: 0x VA: 0x0
	public static ReusableList`1 FlagOnly_CreateFakeReusableList() { }
}
```