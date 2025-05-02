# BossRushStageDetailViewModel

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `String stageGroupId`

- `String actId`

- `Boolean canSpModeShow`

- `Boolean isSpModeBtnShow`

- `Int32 mapFocusItemIndex`

- `String selectTeamId`

- `Boolean isMapPreviewShow`

- `BossRushStageType m_selectedMode`


## Properties

- `BossRushStageType selectedMode`

- `Int32 waveCount`


## Methods

- `BossRushStageType get_selectedMode()`

- `Int32 get_waveCount()`

- `Void Reset(String, String)`

- `Void SetSelectedModeAndRefreshModel(BossRushStageType, String)`

- `Boolean CheckIfCanHideMapPreview()`

- `Void LoadTeamData(Dictionary`2)`

- `Void _RefreshTeam(BossRushStageModel)`

- `Void LoadStageData(Dictionary`2, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailViewModel : IHotfixable
{
	public String stageGroupId; // 0x10
	public String actId; // 0x18
	public Boolean canSpModeShow; // 0x20
	public Boolean isSpModeBtnShow; // 0x21
	public Int32 mapFocusItemIndex; // 0x24
	public String selectTeamId; // 0x28
	public List`1 teamList; // 0x30
	public Dictionary`2 stageModelMap; // 0x38
	public List`1 waveBossInfo; // 0x40
	public Boolean isMapPreviewShow; // 0x48
	private BossRushStageType m_selectedMode; // 0x4c
	private Dictionary`2 m_teamDataMap; // 0x50
	private Dictionary`2 m_stageIdMap; // 0x58
	private static DelegateBridge __Hotfix0_get_selectedMode; // 0x0
	private static DelegateBridge __Hotfix0_get_waveCount; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge __Hotfix0_SetSelectedModeAndRefreshModel; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfCanHideMapPreview; // 0x20
	private static DelegateBridge __Hotfix0_LoadTeamData; // 0x28
	private static DelegateBridge __Hotfix0__RefreshTeam; // 0x30
	private static DelegateBridge __Hotfix0_LoadStageData; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public BossRushStageType selectedMode { get; }
	public Int32 waveCount { get; }

	// RVA: 0x2e76fb8 VA: 0x759548efb8
	public BossRushStageType get_selectedMode() { }
	// RVA: 0x2e75404 VA: 0x759548d404
	public Int32 get_waveCount() { }
	// RVA: 0x2e78bcc VA: 0x7595490bcc
	public Void Reset(String selectStageId, String selectTeam) { }
	// RVA: 0x2e773a4 VA: 0x759548f3a4
	public Void SetSelectedModeAndRefreshModel(BossRushStageType value, String selectTeam) { }
	// RVA: 0x2e75484 VA: 0x759548d484
	public Boolean CheckIfCanHideMapPreview() { }
	// RVA: 0x2e788c0 VA: 0x75954908c0
	public Void LoadTeamData(Dictionary`2 teamData) { }
	// RVA: 0x2e78dc0 VA: 0x7595490dc0
	private Void _RefreshTeam(BossRushStageModel stageModel) { }
	// RVA: 0x2e782f0 VA: 0x75954902f0
	public Void LoadStageData(Dictionary`2 stageIdMap, Dictionary`2 additionDataMap) { }
	// RVA: 0x2e79104 VA: 0x7595491104
	public Void .ctor() { }
}
```