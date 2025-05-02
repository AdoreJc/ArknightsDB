# ActivityFirstUtil

**Namespace:** `Torappu.Activity.Act1`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstUtil : ActivityStageSingleComponent, IHotfixable
{
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_get_activityType; // 0x8
	private static DelegateBridge __Hotfix0_AchieveBasicInfo; // 0x10
	private static DelegateBridge __Hotfix0_CheckStageOpenFlag; // 0x18
	private static DelegateBridge __Hotfix0_get_uiItemCard; // 0x20
	private static DelegateBridge __Hotfix0_get_commonTopMenu; // 0x28
	private static DelegateBridge __Hotfix0_get_activityData; // 0x30
	private static DelegateBridge __Hotfix0_GetMissionData; // 0x38
	private static DelegateBridge __Hotfix0_GetShopCount; // 0x40
	private static DelegateBridge __Hotfix0_get_playerAct; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public static String activityId { get; }
	public static ActivityType activityType { get; }
	public static UIItemCard uiItemCard { get; }
	public static CommonTopMenu commonTopMenu { get; }
	public static DefaultFirstData activityData { get; }
	public static PlayerDefaultActivity playerAct { get; }

	// RVA: 0x348b5f8 VA: 0x7595aa35f8
	public static String get_activityId() { }
	// RVA: 0x348b6e4 VA: 0x7595aa36e4
	public static ActivityType get_activityType() { }
	// RVA: 0x348a6e8 VA: 0x7595aa26e8
	public static ActivityBasicInfo AchieveBasicInfo() { }
	// RVA: 0x348a800 VA: 0x7595aa2800
	public static Boolean CheckStageOpenFlag(ActivityBasicInfo basicInfo) { }
	// RVA: 0x348b7b4 VA: 0x7595aa37b4
	public static UIItemCard get_uiItemCard() { }
	// RVA: 0x348b2d8 VA: 0x7595aa32d8
	public static CommonTopMenu get_commonTopMenu() { }
	// RVA: 0x348b820 VA: 0x7595aa3820
	public static DefaultFirstData get_activityData() { }
	// RVA: 0x348b99c VA: 0x7595aa399c
	public static MissionData GetMissionData(String missionID, String activityID) { }
	// RVA: 0x348baf0 VA: 0x7595aa3af0
	public static Int32 GetShopCount(String shopId) { }
	// RVA: 0x348a614 VA: 0x7595aa2614
	public static PlayerDefaultActivity get_playerAct() { }
	// RVA: 0x348bb98 VA: 0x7595aa3b98
	public Void .ctor() { }
}
```