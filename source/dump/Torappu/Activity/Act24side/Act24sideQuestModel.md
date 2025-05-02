# Act24sideQuestModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String m_actId`

- `String m_selectStageId`


## Properties

- `String actId`

- `String selectStageId`


## Methods

- `String get_actId()`

- `String get_selectStageId()`

- `Void set_selectStageId(String)`

- `Act24sideQuestStageItemModel FindSelectedQuestItemModel()`

- `Act24sideQuestStageItemModel FindNormalStageModel(String)`

- `Void LoadData(String, String)`

- `Void SaveLastSelectQuest()`

- `Act24sideQuestStageItemModel _FindQuestItemModel(String)`

- `String _GetSelectStageFromLocalCache(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideQuestModel : IHotfixable
{
	private String m_actId; // 0x10
	private List`1 m_displayQuestGroupList; // 0x18
	private String m_selectStageId; // 0x20
	private static DelegateBridge __Hotfix0_get_displayQuestGroupList; // 0x0
	private static DelegateBridge __Hotfix0_get_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_selectStageId; // 0x10
	private static DelegateBridge __Hotfix0_set_selectStageId; // 0x18
	private static DelegateBridge __Hotfix0_FindSelectedQuestItemModel; // 0x20
	private static DelegateBridge __Hotfix0_FindNormalStageModel; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_SaveLastSelectQuest; // 0x38
	private static DelegateBridge __Hotfix0__FindQuestItemModel; // 0x40
	private static DelegateBridge __Hotfix0__GetSelectStageFromLocalCache; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public List`1 displayQuestGroupList { get; }
	public String actId { get; }
	public String selectStageId { get; set; }

	// RVA: 0x32df61c VA: 0x75958f761c
	public List`1 get_displayQuestGroupList() { }
	// RVA: 0x32df684 VA: 0x75958f7684
	public String get_actId() { }
	// RVA: 0x32df6ec VA: 0x75958f76ec
	public String get_selectStageId() { }
	// RVA: 0x32df754 VA: 0x75958f7754
	public Void set_selectStageId(String value) { }
	// RVA: 0x32df7d8 VA: 0x75958f77d8
	public Act24sideQuestStageItemModel FindSelectedQuestItemModel() { }
	// RVA: 0x32dfa0c VA: 0x75958f7a0c
	public Act24sideQuestStageItemModel FindNormalStageModel(String hardStageId) { }
	// RVA: 0x32dfbe0 VA: 0x75958f7be0
	public Void LoadData(String actId, String selectStageId) { }
	// RVA: 0x32e0484 VA: 0x75958f8484
	public Void SaveLastSelectQuest() { }
	// RVA: 0x32df844 VA: 0x75958f7844
	private Act24sideQuestStageItemModel _FindQuestItemModel(String questId) { }
	// RVA: 0x32e035c VA: 0x75958f835c
	private String _GetSelectStageFromLocalCache(String cacheStageIdFromBattle) { }
	// RVA: 0x32e0520 VA: 0x75958f8520
	public Void .ctor() { }
}
```