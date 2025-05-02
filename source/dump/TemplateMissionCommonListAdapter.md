# TemplateMissionCommonListAdapter

**Namespace:** ` `


## Fields

- `TemplateMissionCommonListView m_closure`


## Methods

- `Void RebuildList(TemplateMissionViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TemplateMissionCommonListAdapter : UIRecycleLayoutAdapter
{
	private TemplateMissionCommonListView m_closure; // 0x18
	private List`1 m_views; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x8
	private static DelegateBridge __Hotfix0_RebuildList; // 0x10


	// RVA: 0x236adcc VA: 0x7594982dcc
	public Void .ctor(TemplateMissionCommonListView closure) { }
	// RVA: 0x236af90 VA: 0x7594982f90
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x236a8fc VA: 0x75949828fc
	public Void RebuildList(TemplateMissionViewModel viewModel) { }
}
```