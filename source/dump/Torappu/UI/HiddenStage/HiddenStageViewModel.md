# HiddenStageViewModel

**Namespace:** `Torappu.UI.HiddenStage`


## Fields

- `String hiddenStageId`

- `String encodedName`

- `Boolean complete`

- `Boolean unlocked`

- `Boolean isDecodePanel`

- `Boolean playDecodeAnim`

- `Boolean isRetro`

- `String actId`

- `StageViewModel stageViewModel`


## Methods

- `Void LoadData(String)`

- `PlayerHiddenStage _LoadPlayerHiddenData(String)`

- `Void _LoadHiddenMission(String, PlayerHiddenStage)`

- `Void _LoadStageViewModel(String)`

- `Void _LoadActRitroInfo(String)`

- `HiddenStageMissionViewModel _GenMissionViewModel(MissionCalcState, ActivityHiddenStageUnlockConditionData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HiddenStage
public class HiddenStageViewModel : IHotfixable
{
	public String hiddenStageId; // 0x10
	public String encodedName; // 0x18
	public Boolean complete; // 0x20
	public Boolean unlocked; // 0x21
	public Boolean isDecodePanel; // 0x22
	public Boolean playDecodeAnim; // 0x23
	public Boolean isRetro; // 0x24
	public String actId; // 0x28
	public List`1 missionViewModels; // 0x30
	public StageViewModel stageViewModel; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadPlayerHiddenData; // 0x8
	private static DelegateBridge __Hotfix0__LoadHiddenMission; // 0x10
	private static DelegateBridge __Hotfix0__LoadStageViewModel; // 0x18
	private static DelegateBridge __Hotfix0__LoadActRitroInfo; // 0x20
	private static DelegateBridge __Hotfix0__GenMissionViewModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x285c40c VA: 0x7594e7440c
	public Void LoadData(String stageId) { }
	// RVA: 0x285f38c VA: 0x7594e7738c
	private PlayerHiddenStage _LoadPlayerHiddenData(String stageId) { }
	// RVA: 0x285f42c VA: 0x7594e7742c
	private Void _LoadHiddenMission(String stageId, PlayerHiddenStage playerData) { }
	// RVA: 0x285f6d0 VA: 0x7594e776d0
	private Void _LoadStageViewModel(String stageId) { }
	// RVA: 0x285f858 VA: 0x7594e77858
	private Void _LoadActRitroInfo(String stageId) { }
	// RVA: 0x285f91c VA: 0x7594e7791c
	private HiddenStageMissionViewModel _GenMissionViewModel(MissionCalcState state, ActivityHiddenStageUnlockConditionData missionData) { }
	// RVA: 0x285fad4 VA: 0x7594e77ad4
	public Void .ctor() { }
}
```