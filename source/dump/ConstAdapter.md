# ConstAdapter

**Namespace:** ` `


## Fields

- `Int32 constCount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ConstAdapter : SimpleLayoutAdapter
{
	public Int32 constCount; // 0x20
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x2aa1dfc VA: 0x75950b9dfc
	public override Int32 get_count() { }
	// RVA: 0x2aa1e64 VA: 0x75950b9e64
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2aa1984 VA: 0x75950b9984
	public Void .ctor() { }
}
```