# ClimbTowerSquadSingleEditAdapter

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSquadSingleEditView m_closure`


## Methods

- `Void RefreshList(ClimbTowerSquadSingleEditModel)`

- `Void RebuildList(ClimbTowerSquadSingleEditModel)`

- `Int32 GetProfessionIndex(ProfessionCategory)`

- `Single GetCharCardOffset(ProfessionCategory, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadSingleEditAdapter : UIRecycleLayoutAdapter
{
	private ListDict`2 m_viewList; // 0x18
	private ClimbTowerSquadSingleEditView m_closure; // 0x20
	private Dictionary`2 m_professionIndex; // 0x28
	private Dictionary`2 m_groupDict; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x8
	private static DelegateBridge __Hotfix0_RefreshList; // 0x10
	private static DelegateBridge __Hotfix0_RebuildList; // 0x18
	private static DelegateBridge __Hotfix0_GetProfessionIndex; // 0x20
	private static DelegateBridge __Hotfix0_GetCharCardOffset; // 0x28


	// RVA: 0x2cc7c00 VA: 0x75952dfc00
	public Void .ctor(ClimbTowerSquadSingleEditView closure) { }
	// RVA: 0x2cc7d88 VA: 0x75952dfd88
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x2cc7f30 VA: 0x75952dff30
	public Void RefreshList(ClimbTowerSquadSingleEditModel editModel) { }
	// RVA: 0x2cc8140 VA: 0x75952e0140
	public Void RebuildList(ClimbTowerSquadSingleEditModel editModel) { }
	// RVA: 0x2cc88dc VA: 0x75952e08dc
	public Int32 GetProfessionIndex(ProfessionCategory profession) { }
	// RVA: 0x2cc8978 VA: 0x75952e0978
	public Single GetCharCardOffset(ProfessionCategory profession, Int32 cardId) { }
}
```