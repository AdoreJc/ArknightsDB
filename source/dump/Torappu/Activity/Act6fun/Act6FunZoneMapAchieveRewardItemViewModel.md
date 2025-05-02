# Act6FunZoneMapAchieveRewardItemViewModel

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `String <rewardId>k__BackingField`

- `Act6FunAchievementRewardData <rewardData>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `Int32 <achievementCount>k__BackingField`

- `Act6FunAchieveRewardItemState <rewardState>k__BackingField`


## Properties

- `String rewardId`

- `Act6FunAchievementRewardData rewardData`

- `Int32 sortId`

- `Int32 achievementCount`

- `Act6FunAchieveRewardItemState rewardState`


## Methods

- `String get_rewardId()`

- `Void set_rewardId(String)`

- `Act6FunAchievementRewardData get_rewardData()`

- `Void set_rewardData(Act6FunAchievementRewardData)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `Int32 get_achievementCount()`

- `Void set_achievementCount(Int32)`

- `Act6FunAchieveRewardItemState get_rewardState()`

- `Void set_rewardState(Act6FunAchieveRewardItemState)`

- `Void LoadData(String, Act6FunAchievementRewardData)`

- `Void RefreshData(Int32, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapAchieveRewardItemViewModel : IHotfixable
{
	private String <rewardId>k__BackingField; // 0x10
	private Act6FunAchievementRewardData <rewardData>k__BackingField; // 0x18
	private Int32 <sortId>k__BackingField; // 0x20
	private Int32 <achievementCount>k__BackingField; // 0x24
	private Act6FunAchieveRewardItemState <rewardState>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_rewardId; // 0x0
	private static DelegateBridge __Hotfix0_set_rewardId; // 0x8
	private static DelegateBridge __Hotfix0_get_rewardData; // 0x10
	private static DelegateBridge __Hotfix0_set_rewardData; // 0x18
	private static DelegateBridge __Hotfix0_get_sortId; // 0x20
	private static DelegateBridge __Hotfix0_set_sortId; // 0x28
	private static DelegateBridge __Hotfix0_get_achievementCount; // 0x30
	private static DelegateBridge __Hotfix0_set_achievementCount; // 0x38
	private static DelegateBridge __Hotfix0_get_rewardState; // 0x40
	private static DelegateBridge __Hotfix0_set_rewardState; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0_RefreshData; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public String rewardId { get; set; }
	public Act6FunAchievementRewardData rewardData { get; set; }
	public Int32 sortId { get; set; }
	public Int32 achievementCount { get; set; }
	public Act6FunAchieveRewardItemState rewardState { get; set; }

	// RVA: 0x31b17ac VA: 0x75957c97ac
	public String get_rewardId() { }
	// RVA: 0x31b1814 VA: 0x75957c9814
	private Void set_rewardId(String value) { }
	// RVA: 0x31b1898 VA: 0x75957c9898
	public Act6FunAchievementRewardData get_rewardData() { }
	// RVA: 0x31b1900 VA: 0x75957c9900
	private Void set_rewardData(Act6FunAchievementRewardData value) { }
	// RVA: 0x31b1984 VA: 0x75957c9984
	public Int32 get_sortId() { }
	// RVA: 0x31b19ec VA: 0x75957c99ec
	private Void set_sortId(Int32 value) { }
	// RVA: 0x31b1a68 VA: 0x75957c9a68
	public Int32 get_achievementCount() { }
	// RVA: 0x31b1ad0 VA: 0x75957c9ad0
	private Void set_achievementCount(Int32 value) { }
	// RVA: 0x31b1b4c VA: 0x75957c9b4c
	public Act6FunAchieveRewardItemState get_rewardState() { }
	// RVA: 0x31b1bb4 VA: 0x75957c9bb4
	private Void set_rewardState(Act6FunAchieveRewardItemState value) { }
	// RVA: 0x31b1c30 VA: 0x75957c9c30
	public Void LoadData(String id, Act6FunAchievementRewardData data) { }
	// RVA: 0x31b1d00 VA: 0x75957c9d00
	public Void RefreshData(Int32 playerAchieveCount, List`1 claimedRewardIdList) { }
	// RVA: 0x31b1de4 VA: 0x75957c9de4
	public Void .ctor() { }
}
```