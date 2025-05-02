# PicAdapter

**Namespace:** ` `


## Fields

- `Act25sideResearchUnlockView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PicAdapter : SimpleLayoutAdapter, IHotfixable
{
	private Act25sideResearchUnlockView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x3285604 VA: 0x759589d604
	public Void .ctor(Act25sideResearchUnlockView closure) { }
	// RVA: 0x32859c8 VA: 0x759589d9c8
	public override Int32 get_count() { }
	// RVA: 0x3285aa0 VA: 0x759589daa0
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```