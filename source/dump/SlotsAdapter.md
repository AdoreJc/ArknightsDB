# SlotsAdapter

**Namespace:** ` `


## Fields

- `RecruitBuildSlotGroupView m_closure`

- `Boolean m_AVGIsEmptySlotRegistered`


## Methods

- `Void <>xLuaBaseProxy_NotifyDataSetChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SlotsAdapter : SimpleLayoutAdapter
{
	private RecruitBuildSlotGroupView m_closure; // 0x20
	private Boolean m_AVGIsEmptySlotRegistered; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0_NotifyDataSetChanged; // 0x18

	public override Int32 count { get; }

	// RVA: 0x2705a1c VA: 0x7594d1da1c
	public Void .ctor(RecruitBuildSlotGroupView closure) { }
	// RVA: 0x2705c0c VA: 0x7594d1dc0c
	public override Int32 get_count() { }
	// RVA: 0x2705cc8 VA: 0x7594d1dcc8
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2706418 VA: 0x7594d1e418
	public override Void NotifyDataSetChanged() { }
	// RVA: 0x2706488 VA: 0x7594d1e488
	private Void <>xLuaBaseProxy_NotifyDataSetChanged() { }
}
```