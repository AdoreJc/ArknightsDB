# StageSixStarInfo

**Namespace:** ` `


## Fields

- `String sixStarStageDesc`

- `Int32 linkedStageApCost`

- `Boolean needShowCompatible`

- `PlayerSixStarTagFinishState tagFinishState`

- `StageSixStarRuneStatus curStageSixStarRuneStatus`

- `String <stageId>k__BackingField`


## Properties

- `String stageId`


## Methods

- `String get_stageId()`

- `Void set_stageId(String)`

- `Void LoadGameData(StageData)`

- `Void UpdatePlayerData(PlayerStage)`

- `Boolean CheckIfNeedSelectedRunes()`

- `Int32 GetApCost(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StageSixStarInfo : ISpecialStageInfo, IHotfixable
{
	public String sixStarStageDesc; // 0x10
	public List`1 advancedRuneIdList1; // 0x18
	public List`1 advancedRuneIdList2; // 0x20
	public Int32 linkedStageApCost; // 0x28
	public Boolean needShowCompatible; // 0x2c
	public PlayerSixStarTagFinishState tagFinishState; // 0x30
	public List`1 selectedRunes; // 0x38
	public StageSixStarRuneStatus curStageSixStarRuneStatus; // 0x40
	private String <stageId>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_stageId; // 0x0
	private static DelegateBridge __Hotfix0_set_stageId; // 0x8
	private static DelegateBridge __Hotfix0_LoadGameData; // 0x10
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x18
	private static DelegateBridge __Hotfix0_GetSelectedRuneKeys; // 0x20
	private static DelegateBridge __Hotfix0_CheckIfNeedSelectedRunes; // 0x28
	private static DelegateBridge __Hotfix0_GetApCost; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public String stageId { get; set; }

	// RVA: 0x2f7f814 VA: 0x7595597814
	public String get_stageId() { }
	// RVA: 0x2f7f87c VA: 0x759559787c
	public Void set_stageId(String value) { }
	// RVA: 0x2f7f900 VA: 0x7595597900
	public Void LoadGameData(StageData stageData) { }
	// RVA: 0x2f7f9c4 VA: 0x75955979c4
	public Void UpdatePlayerData(PlayerStage playerStage) { }
	// RVA: 0x2f7fb08 VA: 0x7595597b08
	public List`1 GetSelectedRuneKeys() { }
	// RVA: 0x2f7fddc VA: 0x7595597ddc
	public Boolean CheckIfNeedSelectedRunes() { }
	// RVA: 0x2f7e5d4 VA: 0x75955965d4
	public Int32 GetApCost(Int32 oriApCost) { }
	// RVA: 0x2f7f71c VA: 0x759559771c
	public Void .ctor() { }
}
```