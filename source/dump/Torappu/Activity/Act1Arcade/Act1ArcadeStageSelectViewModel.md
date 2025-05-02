# Act1ArcadeStageSelectViewModel

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `String actId`

- `String curSelectStageId`

- `String curSelectZoneId`

- `ActArcadeData arcadeData`

- `PlayerArcadeActivity arcadePlayerData`

- `Act1ArcadeStageBadgeModel badgeModel`

- `Act1ArcadeSingleStageModel curSelectStageModel`

- `Act1ArcadeSingleZoneModel curSelectZoneModel`


## Methods

- `Void LoadData(String)`

- `Void _RefreshCurSelectZoneAndStage(String)`

- `Void UpdateData()`

- `Act1ArcadeSingleStageModel GetStageModel(String)`

- `Act1ArcadeSingleZoneModel GetZoneModel(String)`

- `Void FillBuffRuneList(List`1)`

- `Void SetSelectStage(String)`

- `String GetDefaultSelectStageIdByZoneId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeStageSelectViewModel : IHotfixable
{
	public String actId; // 0x10
	public String curSelectStageId; // 0x18
	public String curSelectZoneId; // 0x20
	public ActArcadeData arcadeData; // 0x28
	public PlayerArcadeActivity arcadePlayerData; // 0x30
	public Act1ArcadeStageBadgeModel badgeModel; // 0x38
	public Act1ArcadeSingleStageModel curSelectStageModel; // 0x40
	public Act1ArcadeSingleZoneModel curSelectZoneModel; // 0x48
	private Dictionary`2 m_stageModelDict; // 0x50
	private Dictionary`2 m_zoneModelDict; // 0x58
	private static DelegateBridge __Hotfix0_get_zoneModelDict; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__RefreshCurSelectZoneAndStage; // 0x10
	private static DelegateBridge __Hotfix0_UpdateData; // 0x18
	private static DelegateBridge __Hotfix0_GetStageModel; // 0x20
	private static DelegateBridge __Hotfix0_GetZoneModel; // 0x28
	private static DelegateBridge __Hotfix0_FillBuffRuneList; // 0x30
	private static DelegateBridge __Hotfix0_SetSelectStage; // 0x38
	private static DelegateBridge __Hotfix0_GetDefaultSelectStageIdByZoneId; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Dictionary`2 zoneModelDict { get; }

	// RVA: 0x340ed38 VA: 0x7595a26d38
	public Dictionary`2 get_zoneModelDict() { }
	// RVA: 0x340eda0 VA: 0x7595a26da0
	public Void LoadData(String activityId) { }
	// RVA: 0x340f3d8 VA: 0x7595a273d8
	private Void _RefreshCurSelectZoneAndStage(String prefBattleStageId) { }
	// RVA: 0x340ef18 VA: 0x7595a26f18
	public Void UpdateData() { }
	// RVA: 0x340f608 VA: 0x7595a27608
	public Act1ArcadeSingleStageModel GetStageModel(String stageId) { }
	// RVA: 0x340f6b8 VA: 0x7595a276b8
	public Act1ArcadeSingleZoneModel GetZoneModel(String zoneId) { }
	// RVA: 0x340f768 VA: 0x7595a27768
	public Void FillBuffRuneList(List`1 runeList) { }
	// RVA: 0x340f7fc VA: 0x7595a277fc
	public Void SetSelectStage(String prefBattleStageId) { }
	// RVA: 0x340f8c0 VA: 0x7595a278c0
	public String GetDefaultSelectStageIdByZoneId(String selectZoneId) { }
	// RVA: 0x340fc7c VA: 0x7595a27c7c
	public Void .ctor() { }
}
```