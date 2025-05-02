# Act24sideBattleTrapSquadHomePluginView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `GameObject _objNew`

- `String m_groupId`

- `Boolean m_canEdit`


## Methods

- `Boolean _TryShowNewTag()`

- `Boolean _CheckIfStageCanUseTool(Act24SideData, String)`

- `Void _RefreshTrapItems(PluginInputParams)`

- `Void OnClick()`

- `Boolean <>xLuaBaseProxy_ShowSquadLeftArrow()`

- `SquadHomeStartBattleServicePluginBase <>xLuaBaseProxy_CreateStartBattlePlugin()`

- `SquadHomeFinishBattleServicePluginBase <>xLuaBaseProxy_CreateFinishBattlePlugin()`

- `BattleActivityMeta <>xLuaBaseProxy_OverrideActMeta(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleTrapSquadHomePluginView : SquadHomePluginView
{
	private List`1 _itemViewList; // 0x30
	private GameObject _objNew; // 0x38
	private String m_groupId; // 0x40
	private Boolean m_canEdit; // 0x48
	private ListDict`2 m_toolDataList; // 0x50
	private static DelegateBridge __Hotfix0_ShowSquadLeftArrow; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0__TryShowNewTag; // 0x10
	private static DelegateBridge __Hotfix0__CheckIfStageCanUseTool; // 0x18
	private static DelegateBridge __Hotfix0__GetSelectTrapToolIconIdsList; // 0x20
	private static DelegateBridge __Hotfix0__GetSelectTrapToolIdsListFromPlayerData; // 0x28
	private static DelegateBridge __Hotfix0__GetSelectTrapToolIdsListFromMem; // 0x30
	private static DelegateBridge __Hotfix0__RefreshTrapItems; // 0x38
	private static DelegateBridge __Hotfix0_CreateStartBattlePlugin; // 0x40
	private static DelegateBridge __Hotfix0_CreateFinishBattlePlugin; // 0x48
	private static DelegateBridge __Hotfix0_OverrideActMeta; // 0x50
	private static DelegateBridge __Hotfix0_OnClick; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x3294508 VA: 0x75958ac508
	public override Boolean ShowSquadLeftArrow() { }
	// RVA: 0x329456c VA: 0x75958ac56c
	public override Void Show(PluginInputParams param) { }
	// RVA: 0x329491c VA: 0x75958ac91c
	private Boolean _TryShowNewTag() { }
	// RVA: 0x32946a4 VA: 0x75958ac6a4
	private Boolean _CheckIfStageCanUseTool(Act24SideData act24SideData, String stageId) { }
	// RVA: 0x3294a50 VA: 0x75958aca50
	private List`1 _GetSelectTrapToolIconIdsList(PluginInputParams param) { }
	// RVA: 0x3294df4 VA: 0x75958acdf4
	private List`1 _GetSelectTrapToolIdsListFromPlayerData() { }
	// RVA: 0x3294aec VA: 0x75958acaec
	private List`1 _GetSelectTrapToolIdsListFromMem(String stageId) { }
	// RVA: 0x3294798 VA: 0x75958ac798
	private Void _RefreshTrapItems(PluginInputParams param) { }
	// RVA: 0x3295088 VA: 0x75958ad088
	public override SquadHomeStartBattleServicePluginBase CreateStartBattlePlugin() { }
	// RVA: 0x329511c VA: 0x75958ad11c
	public override SquadHomeFinishBattleServicePluginBase CreateFinishBattlePlugin() { }
	// RVA: 0x32951b0 VA: 0x75958ad1b0
	public override BattleActivityMeta OverrideActMeta(String activityId) { }
	// RVA: 0x3295264 VA: 0x75958ad264
	public Void OnClick() { }
	// RVA: 0x3295398 VA: 0x75958ad398
	public Void .ctor() { }
	// RVA: 0x3295408 VA: 0x75958ad408
	private Boolean <>xLuaBaseProxy_ShowSquadLeftArrow() { }
	// RVA: 0x3295410 VA: 0x75958ad410
	private SquadHomeStartBattleServicePluginBase <>xLuaBaseProxy_CreateStartBattlePlugin() { }
	// RVA: 0x3295418 VA: 0x75958ad418
	private SquadHomeFinishBattleServicePluginBase <>xLuaBaseProxy_CreateFinishBattlePlugin() { }
	// RVA: 0x3295420 VA: 0x75958ad420
	private BattleActivityMeta <>xLuaBaseProxy_OverrideActMeta(String P0) { }
}
```