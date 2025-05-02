# Act24sideQuestStageItemModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String m_actId`

- `QuestStageData m_questData`

- `StageData m_stageData`

- `PlayerStage m_playerStageData`

- `StageRewardViewModel m_completeReward`


## Properties

- `Boolean isUrgent`

- `String actId`

- `Int32 completeRankCount`

- `StageData stageData`

- `String stageId`

- `Int32 sortId`

- `Boolean isHardStage`

- `Boolean isDragonStage`

- `String stageName`

- `Int32 practiceCost`

- `Int32 apCost`

- `String stageDesc`

- `String dangerLv`

- `Boolean isStageComplete`

- `StageRewardViewModel completeRewardModel`


## Methods

- `Boolean get_isUrgent()`

- `String get_actId()`

- `Int32 get_completeRankCount()`

- `StageData get_stageData()`

- `String get_stageId()`

- `Int32 get_sortId()`

- `Boolean get_isHardStage()`

- `Boolean get_isDragonStage()`

- `String get_stageName()`

- `Int32 get_practiceCost()`

- `Int32 get_apCost()`

- `String get_stageDesc()`

- `String get_dangerLv()`

- `Boolean get_isStageComplete()`

- `StageRewardViewModel get_completeRewardModel()`

- `Int32 GetTotalRankCount(Boolean)`

- `Void LoadData(String, QuestStageData, StageData, PlayerStage)`

- `Void _FetchCompleteReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideQuestStageItemModel : IHotfixable
{
	private String m_actId; // 0x10
	private QuestStageData m_questData; // 0x18
	private StageData m_stageData; // 0x20
	private PlayerStage m_playerStageData; // 0x28
	private StageRewardViewModel m_completeReward; // 0x30
	private List`1 m_meldingDropItemList; // 0x38
	private static DelegateBridge __Hotfix0_get_isUrgent; // 0x0
	private static DelegateBridge __Hotfix0_get_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_completeRankCount; // 0x10
	private static DelegateBridge __Hotfix0_get_stageData; // 0x18
	private static DelegateBridge __Hotfix0_get_stageId; // 0x20
	private static DelegateBridge __Hotfix0_get_sortId; // 0x28
	private static DelegateBridge __Hotfix0_get_isHardStage; // 0x30
	private static DelegateBridge __Hotfix0_get_isDragonStage; // 0x38
	private static DelegateBridge __Hotfix0_get_stageName; // 0x40
	private static DelegateBridge __Hotfix0_get_practiceCost; // 0x48
	private static DelegateBridge __Hotfix0_get_apCost; // 0x50
	private static DelegateBridge __Hotfix0_get_stageDesc; // 0x58
	private static DelegateBridge __Hotfix0_get_dangerLv; // 0x60
	private static DelegateBridge __Hotfix0_get_isStageComplete; // 0x68
	private static DelegateBridge __Hotfix0_get_meldingDropList; // 0x70
	private static DelegateBridge __Hotfix0_get_completeRewardModel; // 0x78
	private static DelegateBridge __Hotfix0_GetTotalRankCount; // 0x80
	private static DelegateBridge __Hotfix0_LoadData; // 0x88
	private static DelegateBridge __Hotfix0__FetchCompleteReward; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public Boolean isUrgent { get; }
	public String actId { get; }
	public Int32 completeRankCount { get; }
	public StageData stageData { get; }
	public String stageId { get; }
	public Int32 sortId { get; }
	public Boolean isHardStage { get; }
	public Boolean isDragonStage { get; }
	public String stageName { get; }
	public Int32 practiceCost { get; }
	public Int32 apCost { get; }
	public String stageDesc { get; }
	public String dangerLv { get; }
	public Boolean isStageComplete { get; }
	public List`1 meldingDropList { get; }
	public StageRewardViewModel completeRewardModel { get; }

	// RVA: 0x32de658 VA: 0x75958f6658
	public Boolean get_isUrgent() { }
	// RVA: 0x32de6d8 VA: 0x75958f66d8
	public String get_actId() { }
	// RVA: 0x32de740 VA: 0x75958f6740
	public Int32 get_completeRankCount() { }
	// RVA: 0x32de880 VA: 0x75958f6880
	public StageData get_stageData() { }
	// RVA: 0x32de8e8 VA: 0x75958f68e8
	public String get_stageId() { }
	// RVA: 0x32de960 VA: 0x75958f6960
	public Int32 get_sortId() { }
	// RVA: 0x32de800 VA: 0x75958f6800
	public Boolean get_isHardStage() { }
	// RVA: 0x32de9d8 VA: 0x75958f69d8
	public Boolean get_isDragonStage() { }
	// RVA: 0x32dea58 VA: 0x75958f6a58
	public String get_stageName() { }
	// RVA: 0x32deb38 VA: 0x75958f6b38
	public Int32 get_practiceCost() { }
	// RVA: 0x32debb0 VA: 0x75958f6bb0
	public Int32 get_apCost() { }
	// RVA: 0x32dec28 VA: 0x75958f6c28
	public String get_stageDesc() { }
	// RVA: 0x32decbc VA: 0x75958f6cbc
	public String get_dangerLv() { }
	// RVA: 0x32ded50 VA: 0x75958f6d50
	public Boolean get_isStageComplete() { }
	// RVA: 0x32dedd0 VA: 0x75958f6dd0
	public List`1 get_meldingDropList() { }
	// RVA: 0x32dee38 VA: 0x75958f6e38
	public StageRewardViewModel get_completeRewardModel() { }
	// RVA: 0x32deea0 VA: 0x75958f6ea0
	public Int32 GetTotalRankCount(Boolean displayWhenUnlocked) { }
	// RVA: 0x32def4c VA: 0x75958f6f4c
	public Void LoadData(String actId, QuestStageData questStageData, StageData stageData, PlayerStage playerStageData) { }
	// RVA: 0x32df054 VA: 0x75958f7054
	private Void _FetchCompleteReward() { }
	// RVA: 0x32df1f0 VA: 0x75958f71f0
	public Void .ctor() { }
}
```