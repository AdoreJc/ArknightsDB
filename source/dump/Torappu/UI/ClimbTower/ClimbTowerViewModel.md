# ClimbTowerViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String towerId`

- `String towerName`

- `String towerSubName`

- `String towerDesc`

- `ClimbTowerTowerType towerType`

- `Int32 recordLayer`

- `Int32 maxLayer`

- `Boolean hasGetMedal`

- `Boolean hasGetHiddenMedal`

- `String medalId`

- `String hiddenMedalId`

- `String bossId`

- `ItemData lowerItemData`

- `ItemData higherItemData`

- `Int32 curLowerItemCount`

- `Int32 curHigherItemCount`

- `Int32 maxLowerItemCount`

- `Int32 maxHigherItemCount`

- `Boolean isInBattle`

- `Boolean isValid`

- `Boolean hasTowerPass`

- `Boolean isHardModeValid`

- `Boolean isHardMode`

- `Int32 hardModeRecordLayer`

- `String hardModeTips`

- `Boolean hasGetHardModeMedal`

- `String hardModeMedalId`

- `String dangerEffectDesc`

- `Int32 subCardStageSort`

- `Int32 m_charCount`

- `Boolean hasEnoughSweepItem`

- `Boolean beUseSweep`

- `Int32 afterSweepLowerItemCount`

- `Int32 afterSweepHigherItemCount`

- `Int32 sweepCost`

- `Int32 unLockSweepNormLayer`

- `Int32 unlockSweepHardLayer`

- `String sweepItemName`

- `Boolean isInConfirmSweep`

- `String tktItemId`

- `Int32 switchHardModeSeqNum`

- `Int32 resetSweepConfirmSeqNum`

- `Boolean m_unlockSweepNormal`

- `Boolean m_unlockSweepHard`


## Properties

- `Boolean unlockSweep`


## Methods

- `Boolean get_unlockSweep()`

- `Void LoadData(String, Boolean)`

- `Void _GetItemInstIds()`

- `Void _LoadSweepReward()`

- `Boolean CheckRewardStatus(String, List`1)`

- `Boolean CheckCreateGame()`

- `Color GetColorByMode()`

- `String GetNamePostfixByMode()`

- `Void SwitchMode()`

- `Void SelectUseSweep()`

- `Void SwitchConfirmSweep()`

- `Void NotifyResetSweepConfirm()`

- `Boolean HaveEnoughCharToStart(out)`

- `Boolean CheckSweepHasNoReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerViewModel : IHotfixable
{
	public String towerId; // 0x10
	public String towerName; // 0x18
	public String towerSubName; // 0x20
	public String towerDesc; // 0x28
	public ClimbTowerTowerType towerType; // 0x30
	public Int32 recordLayer; // 0x34
	public Int32 maxLayer; // 0x38
	public Boolean hasGetMedal; // 0x3c
	public Boolean hasGetHiddenMedal; // 0x3d
	public String medalId; // 0x40
	public String hiddenMedalId; // 0x48
	public String bossId; // 0x50
	public ListDict`2 rewards; // 0x58
	public List`1 notReceivedRewards; // 0x60
	public ItemData lowerItemData; // 0x68
	public ItemData higherItemData; // 0x70
	public Int32 curLowerItemCount; // 0x78
	public Int32 curHigherItemCount; // 0x7c
	public Int32 maxLowerItemCount; // 0x80
	public Int32 maxHigherItemCount; // 0x84
	public Boolean isInBattle; // 0x88
	public Boolean isValid; // 0x89
	public Boolean hasTowerPass; // 0x8a
	public Boolean isHardModeValid; // 0x8b
	public Boolean isHardMode; // 0x8c
	public Int32 hardModeRecordLayer; // 0x90
	public String hardModeTips; // 0x98
	public Boolean hasGetHardModeMedal; // 0xa0
	public String hardModeMedalId; // 0xa8
	public String dangerEffectDesc; // 0xb0
	public Int32 subCardStageSort; // 0xb8
	private List`1 m_normalLevels; // 0xc0
	private List`1 m_hardLevels; // 0xc8
	private Int32 m_charCount; // 0xd0
	public Boolean hasEnoughSweepItem; // 0xd4
	public Boolean beUseSweep; // 0xd5
	public Int32 afterSweepLowerItemCount; // 0xd8
	public Int32 afterSweepHigherItemCount; // 0xdc
	public Int32 sweepCost; // 0xe0
	public Int32 unLockSweepNormLayer; // 0xe4
	public Int32 unlockSweepHardLayer; // 0xe8
	public String sweepItemName; // 0xf0
	public Boolean isInConfirmSweep; // 0xf8
	public List`1 tktInfoList; // 0x100
	public List`1 selectTktInstList; // 0x108
	public String tktItemId; // 0x110
	public Int32 switchHardModeSeqNum; // 0x118
	public Int32 resetSweepConfirmSeqNum; // 0x11c
	private Boolean m_unlockSweepNormal; // 0x120
	private Boolean m_unlockSweepHard; // 0x121
	private static DelegateBridge __Hotfix0_get_outerLevels; // 0x0
	private static DelegateBridge __Hotfix0_get_unlockSweep; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0__LoadLevelViewModelsWithMode; // 0x18
	private static DelegateBridge __Hotfix0__GetItemInstIds; // 0x20
	private static DelegateBridge __Hotfix0__LoadSweepReward; // 0x28
	private static DelegateBridge __Hotfix0_CheckRewardStatus; // 0x30
	private static DelegateBridge __Hotfix0_CheckCreateGame; // 0x38
	private static DelegateBridge __Hotfix0_GetColorByMode; // 0x40
	private static DelegateBridge __Hotfix0_GetNamePostfixByMode; // 0x48
	private static DelegateBridge __Hotfix0_SwitchMode; // 0x50
	private static DelegateBridge __Hotfix0_SelectUseSweep; // 0x58
	private static DelegateBridge __Hotfix0_SwitchConfirmSweep; // 0x60
	private static DelegateBridge __Hotfix0_NotifyResetSweepConfirm; // 0x68
	private static DelegateBridge __Hotfix0_HaveEnoughCharToStart; // 0x70
	private static DelegateBridge __Hotfix0_GetLevelModels; // 0x78
	private static DelegateBridge __Hotfix0_CheckSweepHasNoReward; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public List`1 outerLevels { get; }
	public Boolean unlockSweep { get; }

	// RVA: 0x2cdc174 VA: 0x75952f4174
	public List`1 get_outerLevels() { }
	// RVA: 0x2cdc1ec VA: 0x75952f41ec
	public Boolean get_unlockSweep() { }
	// RVA: 0x2cdc264 VA: 0x75952f4264
	public Void LoadData(String tower, Boolean needReloadTowerMode) { }
	// RVA: 0x2cdd058 VA: 0x75952f5058
	private List`1 _LoadLevelViewModelsWithMode(ClimbTowerSingleTowerData towerData, Boolean hardMode) { }
	// RVA: 0x2cdce04 VA: 0x75952f4e04
	private Void _GetItemInstIds() { }
	// RVA: 0x2cdd31c VA: 0x75952f531c
	private Void _LoadSweepReward() { }
	// RVA: 0x2cdd47c VA: 0x75952f547c
	public Boolean CheckRewardStatus(String tower, List`1 layers) { }
	// RVA: 0x2cdd690 VA: 0x75952f5690
	public Boolean CheckCreateGame() { }
	// RVA: 0x2cdd710 VA: 0x75952f5710
	public Color GetColorByMode() { }
	// RVA: 0x2cdd77c VA: 0x75952f577c
	public String GetNamePostfixByMode() { }
	// RVA: 0x2cdd7e8 VA: 0x75952f57e8
	public Void SwitchMode() { }
	// RVA: 0x2cdd8c4 VA: 0x75952f58c4
	public Void SelectUseSweep() { }
	// RVA: 0x2cdd948 VA: 0x75952f5948
	public Void SwitchConfirmSweep() { }
	// RVA: 0x2cdd9b8 VA: 0x75952f59b8
	public Void NotifyResetSweepConfirm() { }
	// RVA: 0x2cdda28 VA: 0x75952f5a28
	public Boolean HaveEnoughCharToStart(out Int32 minCount) { }
	// RVA: 0x2cddab4 VA: 0x75952f5ab4
	public List`1 GetLevelModels(Boolean isHardMode) { }
	// RVA: 0x2cddb3c VA: 0x75952f5b3c
	public Boolean CheckSweepHasNoReward() { }
	// RVA: 0x2cddbc8 VA: 0x75952f5bc8
	public Void .ctor() { }
}
```