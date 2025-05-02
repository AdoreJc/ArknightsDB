# MedalAdapter

**Namespace:** ` `


## Fields

- `SandboxV2RacerInventoryDetailView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MedalAdapter : SimpleLayoutAdapter, IHotfixable
{
	private SandboxV2RacerInventoryDetailView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x25dff7c VA: 0x7594bf7f7c
	public Void .ctor(SandboxV2RacerInventoryDetailView closure) { }
	// RVA: 0x25e01a8 VA: 0x7594bf81a8
	public override Int32 get_count() { }
	// RVA: 0x25e0234 VA: 0x7594bf8234
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```