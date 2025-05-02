# DimensionListAdapter

**Namespace:** ` `


## Fields

- `CrisisV2MapButtonView m_closure`


## Methods

- `Void SetScoreList(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DimensionListAdapter : SimpleLayoutAdapter
{
	private CrisisV2MapButtonView m_closure; // 0x20
	private List`1 m_currentScoreList; // 0x28
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0_SetScoreList; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 count { get; }

	// RVA: 0x2c04984 VA: 0x759521c984
	public override Int32 get_count() { }
	// RVA: 0x2c049ec VA: 0x759521c9ec
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2c04410 VA: 0x759521c410
	public Void SetScoreList(List`1 currentScoreList) { }
	// RVA: 0x2c04494 VA: 0x759521c494
	public Void .ctor() { }
}
```