# TemplateActivityMissionGroupViewModel

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `TemplateActivityMissionViewModelPlugin plugin`

- `DataBundle meta`

- `Boolean haveMissionToGet`

- `Int32 <completedMissionCount>k__BackingField`


## Properties

- `Int32 completedMissionCount`

- `Int32 missionCount`


## Methods

- `Int32 get_completedMissionCount()`

- `Void set_completedMissionCount(Int32)`

- `Int32 get_missionCount()`

- `Void SortMissionList()`

- `Void RefreshMissionState()`

- `Boolean CheckMissionPlayerDataChanged(PlayerDataModel, PlayerDataModel)`

- `Int32 <SortMissionList>b__12_0(TemplateMissionViewModel, TemplateMissionViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityMissionGroupViewModel : TemplateActivityViewModel
{
	public List`1 missionList; // 0x20
	public TemplateActivityMissionViewModelPlugin plugin; // 0x28
	public DataBundle meta; // 0x30
	public Boolean haveMissionToGet; // 0x38
	private Int32 <completedMissionCount>k__BackingField; // 0x3c
	private static DelegateBridge __Hotfix0_get_completedMissionCount; // 0x0
	private static DelegateBridge __Hotfix0_set_completedMissionCount; // 0x8
	private static DelegateBridge __Hotfix0_get_missionCount; // 0x10
	private static DelegateBridge __Hotfix0_SortMissionList; // 0x18
	private static DelegateBridge __Hotfix0_GetMissionList; // 0x20
	private static DelegateBridge __Hotfix0_RefreshMissionState; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30
	private static DelegateBridge __Hotfix0_CheckMissionPlayerDataChanged; // 0x38

	public Int32 completedMissionCount { get; set; }
	public Int32 missionCount { get; }

	// RVA: 0x30af010 VA: 0x75956c7010
	public Int32 get_completedMissionCount() { }
	// RVA: 0x30af078 VA: 0x75956c7078
	private Void set_completedMissionCount(Int32 value) { }
	// RVA: 0x30af0f4 VA: 0x75956c70f4
	public Int32 get_missionCount() { }
	// RVA: 0x30af174 VA: 0x75956c7174
	public Void SortMissionList() { }
	// RVA: 0x30af24c VA: 0x75956c724c
	public List`1 GetMissionList() { }
	// RVA: 0x30af464 VA: 0x75956c7464
	public Void RefreshMissionState() { }
	// RVA: 0x30af778 VA: 0x75956c7778
	public Void .ctor(Object param) { }
	// RVA: 0x30afe50 VA: 0x75956c7e50
	public Boolean CheckMissionPlayerDataChanged(PlayerDataModel prevData, PlayerDataModel curData) { }
	// RVA: 0x30b0368 VA: 0x75956c8368
	private Int32 <SortMissionList>b__12_0(TemplateMissionViewModel a, TemplateMissionViewModel b) { }
}
```