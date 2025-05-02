# RL03TotemListAdapter

**Namespace:** ` `


## Fields

- `RL03TotemBuffListView m_closure`


## Methods

- `Void RebuildList(RL03TotemListViewModel)`

- `Void UpdateSelectStatus(RL03TotemListViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RL03TotemListAdapter : UIRecycleLayoutAdapter
{
	private RL03TotemBuffListView m_closure; // 0x18
	private List`1 m_views; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x8
	private static DelegateBridge __Hotfix0_RebuildList; // 0x10
	private static DelegateBridge __Hotfix0_UpdateSelectStatus; // 0x18


	// RVA: 0x2ba852c VA: 0x75951c052c
	public Void .ctor(RL03TotemBuffListView closure) { }
	// RVA: 0x2ba86a4 VA: 0x75951c06a4
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x2ba7e10 VA: 0x75951bfe10
	public Void RebuildList(RL03TotemListViewModel viewModel) { }
	// RVA: 0x2ba8308 VA: 0x75951c0308
	public Void UpdateSelectStatus(RL03TotemListViewModel viewModel) { }
}
```