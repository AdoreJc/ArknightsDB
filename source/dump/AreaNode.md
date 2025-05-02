# AreaNode

**Namespace:** ` `


## Fields

- `RectInt rect`

- `AreaNode previous`

- `AreaNode next`


## Methods

- `Void Release()`

- `Void RemoveFromChain()`

- `Void AddAfter(AreaNode)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : 
private class AreaNode
{
	private static ObjectPool`1 s_Pool; // 0x0
	public RectInt rect; // 0x10
	public AreaNode previous; // 0x20
	public AreaNode next; // 0x28


	// RVA: 0x6a044a0 VA: 0x759901c4a0
	public static AreaNode Acquire(RectInt rect) { }
	// RVA: 0x6a0410c VA: 0x759901c10c
	public Void Release() { }
	// RVA: 0x6a04cfc VA: 0x759901ccfc
	public Void RemoveFromChain() { }
	// RVA: 0x6a04d5c VA: 0x759901cd5c
	public Void AddAfter(AreaNode previous) { }
	// RVA: 0x6a04f94 VA: 0x759901cf94
	public Void .ctor() { }
	// RVA: 0x6a04f9c VA: 0x759901cf9c
	private static Void .cctor() { }
}
```