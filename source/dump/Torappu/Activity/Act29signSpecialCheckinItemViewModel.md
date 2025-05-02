# Act29signSpecialCheckinItemViewModel

**Namespace:** `Torappu.Activity`


## Fields

- `ItemType itemType`

- `Int32 order`

- `ItemStatus itemStatus`

- `ItemConfigGroup configGroup`

- `CheckInDailyInfo dailyInfo`

- `Boolean hasInfoFlag`

- `Boolean canReceiveFlag`

- `Boolean lastTargetFlag`

- `Act29signConfigGroup act29SignConfigGroup`


## Methods

- `Void LoadDataForNormalCheckin(ItemConfigGroup, Int32, CheckInDailyInfo, List`1)`

- `Void LoadDataForAct29signSpecialItem(Int32, List`1, List`1, Color, Color, CheckInDailyInfo, Dictionary`2, Dictionary`2, Func`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class Act29signSpecialCheckinItemViewModel : IHotfixable
{
	public ItemType itemType; // 0x10
	public Int32 order; // 0x14
	public ItemStatus itemStatus; // 0x18
	public ItemConfigGroup configGroup; // 0x20
	public CheckInDailyInfo dailyInfo; // 0xa8
	public Boolean hasInfoFlag; // 0xb0
	public Boolean canReceiveFlag; // 0xb1
	public Boolean lastTargetFlag; // 0xb2
	public Act29signConfigGroup act29SignConfigGroup; // 0xb8
	private static DelegateBridge __Hotfix0_IsAlreadyGotItem; // 0x0
	private static DelegateBridge __Hotfix0_IsLockedItem; // 0x8
	private static DelegateBridge __Hotfix0_IsUnlockedItem; // 0x10
	private static DelegateBridge __Hotfix0_CanReceiveItem; // 0x18
	private static DelegateBridge __Hotfix0_CanReceiveAndLastTarget; // 0x20
	private static DelegateBridge __Hotfix0_GetItemStatus; // 0x28
	private static DelegateBridge __Hotfix0_LoadDataForNormalCheckin; // 0x30
	private static DelegateBridge __Hotfix0_LoadDataForAct29signSpecialItem; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x30b8778 VA: 0x75956d0778
	public static Boolean IsAlreadyGotItem(ItemStatus itemStatus) { }
	// RVA: 0x30b87e4 VA: 0x75956d07e4
	public static Boolean IsLockedItem(ItemStatus itemStatus) { }
	// RVA: 0x30b8850 VA: 0x75956d0850
	public static Boolean IsUnlockedItem(ItemStatus itemStatus) { }
	// RVA: 0x30b88c4 VA: 0x75956d08c4
	public static Boolean CanReceiveItem(ItemStatus itemStatus) { }
	// RVA: 0x30b8934 VA: 0x75956d0934
	public static Boolean CanReceiveAndLastTarget(ItemStatus itemStatus) { }
	// RVA: 0x30b89a0 VA: 0x75956d09a0
	protected static ItemStatus GetItemStatus(Int32 order, List`1 history) { }
	// RVA: 0x30b8b48 VA: 0x75956d0b48
	public Void LoadDataForNormalCheckin(ItemConfigGroup configGroup, Int32 order, CheckInDailyInfo dailyInfo, List`1 history) { }
	// RVA: 0x30b8c8c VA: 0x75956d0c8c
	public Void LoadDataForAct29signSpecialItem(Int32 order, List`1 history, List`1 dynOpt, Color numIconColor, Color progressTextColor, CheckInDailyInfo dailyInfo, Dictionary`2 dynOptionRewardItemDict, Dictionary`2 dynCheckInDict, Func`2 loadSpriteForCurrentAct) { }
	// RVA: 0x30b9280 VA: 0x75956d1280
	public Void .ctor() { }
}
```