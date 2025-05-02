# ActMultiV3EntryViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String actId`

- `ActMultiV3LifeCycleViewModel lifeCycleViewModel`

- `ActMultiV3EntryMilestoneViewModel milestoneViewModel`

- `ActMultiV3DailyMissionViewModel dailyViewModel`

- `ActMultiV3EntryManualViewModel manualViewModel`

- `String titlePrefix`

- `String titleSuffix`

- `ActMultiV3EntrySquadViewModel squadViewModel`

- `ActMultiV3EntryStageViewModel stageViewModel`

- `ActMultiV3EntryMatchViewModel matchViewModel`

- `Int32 minSquadCount`

- `Boolean isSquadValid`

- `Boolean tutorialStageCompleted`

- `Int64 bannedUntilTs`

- `String teamId`

- `MatchButtonStatus matchButtonStatus`

- `ActMultiV3ConstToastData constToastData`

- `Double joinRoomLongTimeThreshold`

- `Boolean hasTrainingGroundTrackpoint`


## Methods

- `Void LoadData(String)`

- `MatchButtonStatus _GetMatchButtonStatus()`

- `Void SetInputTeamId(String)`

- `Boolean CheckIsBanned()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3EntryViewModel : IHotfixable
{
	public String actId; // 0x10
	public ActMultiV3LifeCycleViewModel lifeCycleViewModel; // 0x18
	public ActMultiV3EntryMilestoneViewModel milestoneViewModel; // 0x20
	public ActMultiV3DailyMissionViewModel dailyViewModel; // 0x28
	public ActMultiV3EntryManualViewModel manualViewModel; // 0x30
	public String titlePrefix; // 0x38
	public String titleSuffix; // 0x40
	public ActMultiV3EntrySquadViewModel squadViewModel; // 0x48
	public ActMultiV3EntryStageViewModel stageViewModel; // 0x50
	public ActMultiV3EntryMatchViewModel matchViewModel; // 0x58
	public Int32 minSquadCount; // 0x60
	public Boolean isSquadValid; // 0x64
	public Boolean tutorialStageCompleted; // 0x65
	public Int64 bannedUntilTs; // 0x68
	public String teamId; // 0x70
	public MatchButtonStatus matchButtonStatus; // 0x78
	public ActMultiV3ConstToastData constToastData; // 0x80
	public Double joinRoomLongTimeThreshold; // 0x88
	public Boolean hasTrainingGroundTrackpoint; // 0x90
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__GetMatchButtonStatus; // 0x8
	private static DelegateBridge __Hotfix0_SetInputTeamId; // 0x10
	private static DelegateBridge __Hotfix0_CheckIsBanned; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30ea9dc VA: 0x75957029dc
	public Void LoadData(String actId) { }
	// RVA: 0x30f216c VA: 0x759570a16c
	private MatchButtonStatus _GetMatchButtonStatus() { }
	// RVA: 0x30edb1c VA: 0x7595705b1c
	public Void SetInputTeamId(String inputVal) { }
	// RVA: 0x30ed434 VA: 0x7595705434
	public Boolean CheckIsBanned() { }
	// RVA: 0x30f220c VA: 0x759570a20c
	public Void .ctor() { }
}
```