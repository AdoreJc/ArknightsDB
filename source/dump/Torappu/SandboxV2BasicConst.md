# SandboxV2BasicConst

**Namespace:** `Torappu`


## Fields

- `String staminaItemId`

- `String goldItemId`

- `String dimensioncoinItemId`

- `String failedCookFood`

- `Int32 maxFoodDuration`

- `Int32 drinkCostOnce`

- `Int32 drinkMakeLimit`

- `String specialMatWater`

- `Int32 workbenchMakeLimit`

- `Int32 logisticsPosLimit`

- `Int32 logisticsUnlockLevel`

- `Int32 logisticsDrinkCost`

- `String logisticsEvacuateTips`

- `String logisticsEvacuateWarning`

- `Int32 baseRepairCost`

- `Int32 portRepairCost`

- `Int32 unitFenceLimit`

- `Int32 unitRareFenceLimit`

- `String cageId`

- `String fenceId`

- `String rareFenceId`

- `String monthlyRushEntryText1`

- `String monthlyEntryUnlockText`

- `String monthlyEntryRiftText`

- `String monthlyRushIntro`

- `ItemBundle monthlyCoin`

- `Int32 squadCharCapacity`

- `Int32 totalSquadCnt`

- `Int32 toolboxCapacity`

- `Int32 toolCntLimitInSquad`

- `Int32 miniSquadCharCapacity`

- `Int32 miniSquadDrinkCost`

- `Int32 normalSquadDrinkCost`

- `Int32 emptySquadDrinkCost`

- `String achieveTypeAll`

- `String constructModeBgmHome`

- `String battleBgmCollect`

- `String battleBgmHunt`

- `String battleBgmEnemyRush`

- `String battleBgmBossRush`

- `String imgLoadingNormalName`

- `String imgLoadingBaseName`

- `String imgUnloadingBaseName`

- `Boolean isChallengeOpen`

- `Boolean isRacingOpen`

- `Boolean hasExploreMode`

- `String modeSelectTips`


## Methods

- `Boolean ShouldSerializeunitRareFenceLimit()`

- `Boolean ShouldSerializerareFenceId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2BasicConst
{
	public String staminaItemId; // 0x10
	public String goldItemId; // 0x18
	public String dimensioncoinItemId; // 0x20
	public String[] alwaysShowItemIdsConstruct; // 0x28
	public String[] alwaysShowItemIds; // 0x30
	public String[] bagBottomBarResType; // 0x38
	public String failedCookFood; // 0x40
	public Int32 maxFoodDuration; // 0x48
	public Int32 drinkCostOnce; // 0x4c
	public Int32 drinkMakeLimit; // 0x50
	public String specialMatWater; // 0x58
	public Int32 workbenchMakeLimit; // 0x60
	public Int32 logisticsPosLimit; // 0x64
	public Int32 logisticsUnlockLevel; // 0x68
	public Int32 logisticsDrinkCost; // 0x6c
	public String logisticsEvacuateTips; // 0x70
	public String logisticsEvacuateWarning; // 0x78
	public Int32 baseRepairCost; // 0x80
	public Int32 portRepairCost; // 0x84
	public Int32 unitFenceLimit; // 0x88
	public Int32 unitRareFenceLimit; // 0x8c
	public String cageId; // 0x90
	public String fenceId; // 0x98
	public String rareFenceId; // 0xa0
	public String monthlyRushEntryText1; // 0xa8
	public String monthlyEntryUnlockText; // 0xb0
	public String monthlyEntryRiftText; // 0xb8
	public String monthlyRushIntro; // 0xc0
	public ItemBundle monthlyCoin; // 0xc8
	public List`1 charRarityColorList; // 0xd0
	public Int32 squadCharCapacity; // 0xd8
	public Int32 totalSquadCnt; // 0xdc
	public Int32 toolboxCapacity; // 0xe0
	public Int32 toolCntLimitInSquad; // 0xe4
	public Int32 miniSquadCharCapacity; // 0xe8
	public Int32 miniSquadDrinkCost; // 0xec
	public Int32 normalSquadDrinkCost; // 0xf0
	public Int32 emptySquadDrinkCost; // 0xf4
	public String achieveTypeAll; // 0xf8
	public String constructModeBgmHome; // 0x100
	public String battleBgmCollect; // 0x108
	public String battleBgmHunt; // 0x110
	public String battleBgmEnemyRush; // 0x118
	public String battleBgmBossRush; // 0x120
	public String imgLoadingNormalName; // 0x128
	public String imgLoadingBaseName; // 0x130
	public String imgUnloadingBaseName; // 0x138
	public Boolean isChallengeOpen; // 0x140
	public Boolean isRacingOpen; // 0x141
	public Boolean hasExploreMode; // 0x142
	public String[] exploreModeBuffDescs; // 0x148
	public String modeSelectTips; // 0x150
	public Dictionary`2 stringRes; // 0x158
	public List`1 diffList; // 0x160
	public List`1 battlePreloadEnemies; // 0x168
	public List`1 battleExcludedTrapsInRush; // 0x170


	// RVA: 0x34f1f34 VA: 0x7595b09f34
	public Boolean ShouldSerializeunitRareFenceLimit() { }
	// RVA: 0x34f1f44 VA: 0x7595b09f44
	public Boolean ShouldSerializerareFenceId() { }
	// RVA: 0x34f1f64 VA: 0x7595b09f64
	public Void .ctor() { }
}
```