# ClimbTowerSquadEditRecylceAdapter

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSquadEditView m_closure`


## Methods

- `Void RebuildList(List`1)`

- `Int32 GetProfessionIndex(ProfessionCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadEditRecylceAdapter : UIRecycleLayoutAdapter
{
	private ClimbTowerSquadEditView m_closure; // 0x18
	private ListDict`2 m_viewList; // 0x20
	private Dictionary`2 m_professionIndex; // 0x28
	private Dictionary`2 m_groupDict; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x8
	private static DelegateBridge __Hotfix0_RebuildList; // 0x10
	private static DelegateBridge __Hotfix0_GetProfessionIndex; // 0x18
	private static DelegateBridge __Hotfix0_GetCharCardBounds; // 0x20


	// RVA: 0x2cb93a0 VA: 0x75952d13a0
	public Void .ctor(ClimbTowerSquadEditView closure) { }
	// RVA: 0x2cb9528 VA: 0x75952d1528
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x2cb96d0 VA: 0x75952d16d0
	public Void RebuildList(List`1 charList) { }
	// RVA: 0x2cb9eb8 VA: 0x75952d1eb8
	public Int32 GetProfessionIndex(ProfessionCategory profession) { }
	// RVA: 0x2cb9f54 VA: 0x75952d1f54
	public KeyValuePair`2 GetCharCardBounds(ProfessionCategory profession, String charId) { }
}
```