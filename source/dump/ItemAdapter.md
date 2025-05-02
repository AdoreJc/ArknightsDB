# ItemAdapter

**Namespace:** ` `


## Fields

- `Single m_delayPerItem`

- `Act24sideBattleFinishMeldingDropInfoItemView m_closure`


## Methods

- `Void <>xLuaBaseProxy_RecycleViews(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ItemAdapter : SimpleLayoutAdapter
{
	private List`1 m_viewModel; // 0x20
	private Single m_delayPerItem; // 0x28
	private Act24sideBattleFinishMeldingDropInfoItemView m_closure; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RecycleViews; // 0x8
	private static DelegateBridge __Hotfix0_get_count; // 0x10
	private static DelegateBridge __Hotfix0_RenderView; // 0x18

	public override Int32 count { get; }

	// RVA: 0x3290b08 VA: 0x75958a8b08
	public Void .ctor(Act24sideBattleFinishMeldingDropInfoItemView closure, List`1 dropList, Single delayPerItem) { }
	// RVA: 0x3290ec4 VA: 0x75958a8ec4
	protected override Void RecycleViews(List`1 views) { }
	// RVA: 0x3290ff0 VA: 0x75958a8ff0
	public override Int32 get_count() { }
	// RVA: 0x329109c VA: 0x75958a909c
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x3291298 VA: 0x75958a9298
	private Void <>xLuaBaseProxy_RecycleViews(List`1 P0) { }
}
```