# ChaosListAdapter

**Namespace:** ` `


## Fields

- `RL03MenuVisionAndChaosWindow m_window`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ChaosListAdapter : SimpleLayoutAdapter
{
	private RL03MenuVisionAndChaosWindow m_window; // 0x20
	public List`1 items; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x2ba03c0 VA: 0x75951b83c0
	public Void .ctor(RL03MenuVisionAndChaosWindow win) { }
	// RVA: 0x2ba04f8 VA: 0x75951b84f8
	public override Int32 get_count() { }
	// RVA: 0x2ba0578 VA: 0x75951b8578
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```