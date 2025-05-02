# ClimbTowerSquadMultiEditAdapter

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSquadMultiEditView m_closure`


## Methods

- `Void RefreshList(ClimbTowerSquadMultiEditModel, Boolean)`

- `Void RebuildList(ClimbTowerSquadMultiEditModel, Boolean)`

- `Int32 GetProfessionIndex(ProfessionCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadMultiEditAdapter : UIRecycleLayoutAdapter
{
	private ClimbTowerSquadMultiEditView m_closure; // 0x18
	private List`1 m_viewList; // 0x20
	private Dictionary`2 m_professionIndex; // 0x28
	private Dictionary`2 m_groupDict; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x8
	private static DelegateBridge __Hotfix0_RefreshList; // 0x10
	private static DelegateBridge __Hotfix0_RebuildList; // 0x18
	private static DelegateBridge __Hotfix0_GetProfessionIndex; // 0x20


	// RVA: 0x2cc132c VA: 0x75952d932c
	public Void .ctor(ClimbTowerSquadMultiEditView closure) { }
	// RVA: 0x2cc14b4 VA: 0x75952d94b4
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x2cc1654 VA: 0x75952d9654
	public Void RefreshList(ClimbTowerSquadMultiEditModel editModel, Boolean needRebuild) { }
	// RVA: 0x2cc1874 VA: 0x75952d9874
	public Void RebuildList(ClimbTowerSquadMultiEditModel editModel, Boolean needRebuild) { }
	// RVA: 0x2cc1fac VA: 0x75952d9fac
	public Int32 GetProfessionIndex(ProfessionCategory profession) { }
}
```