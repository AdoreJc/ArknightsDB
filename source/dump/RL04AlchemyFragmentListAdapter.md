# RL04AlchemyFragmentListAdapter

**Namespace:** ` `


## Fields

- `RL04AlchemyFragmentStorageView m_closure`


## Methods

- `Void RebuildList(RL04AlchemyFragmentListViewModel)`

- `Void TryUpdateSelectStatus(RL04AlchemyFragmentListViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RL04AlchemyFragmentListAdapter : UIRecycleLayoutAdapter
{
	private RL04AlchemyFragmentStorageView m_closure; // 0x18
	private List`1 m_views; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x8
	private static DelegateBridge __Hotfix0_RebuildList; // 0x10
	private static DelegateBridge __Hotfix0_TryUpdateSelectStatus; // 0x18


	// RVA: 0x2b09cbc VA: 0x7595121cbc
	public Void .ctor(RL04AlchemyFragmentStorageView closure) { }
	// RVA: 0x2b09e14 VA: 0x7595121e14
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x2b09570 VA: 0x7595121570
	public Void RebuildList(RL04AlchemyFragmentListViewModel viewModel) { }
	// RVA: 0x2b09a20 VA: 0x7595121a20
	public Void TryUpdateSelectStatus(RL04AlchemyFragmentListViewModel viewModel) { }
}
```