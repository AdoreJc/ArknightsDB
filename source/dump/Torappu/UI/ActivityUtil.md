# ActivityUtil

**Namespace:** `Torappu.UI`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class ActivityUtil
{
	private static DelegateBridge __Hotfix0_CheckIfMissionActivityUncomplete; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfCollectionActivityUncomplete; // 0x8
	private static DelegateBridge __Hotfix0_GetPicId; // 0x10
	private static DelegateBridge __Hotfix0_CollectionActivityJumpToRelatedSystem; // 0x18
	private static DelegateBridge __Hotfix0_IfCollectionActivityCanJumpToRelatedSystem; // 0x20
	private static DelegateBridge __Hotfix0_FindValidCollectionActivity; // 0x28
	private static DelegateBridge __Hotfix0_FindValidMissionActivity; // 0x30
	private static DelegateBridge __Hotfix0_GetActivityCompleteType; // 0x38
	private static DelegateBridge __Hotfix0_CheckIfCheckinActivityUncomplete; // 0x40
	private static DelegateBridge __Hotfix0_CheckIfCheckinActivityFinished; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfCollectionActivityFinished; // 0x50
	private static DelegateBridge __Hotfix0__CheckRewardListFinished; // 0x58
	private static DelegateBridge __Hotfix0_FindValidCheckinActivity; // 0x60
	private static DelegateBridge __Hotfix0_FindValidAVGActivity; // 0x68
	private static DelegateBridge __Hotfix0_CheckIfLoginActivityUncomplete; // 0x70
	private static DelegateBridge __Hotfix0_CheckIfLoginActivityFinished; // 0x78
	private static DelegateBridge __Hotfix0_CheckIfActivityPopupAfterCheckin; // 0x80
	private static DelegateBridge __Hotfix0_FindValidLoginOnlyActs; // 0x88
	private static DelegateBridge __Hotfix0_GetUILockTargetFromActivity; // 0x90
	private static DelegateBridge __Hotfix0_FindValidPrayOnlyActs; // 0x98
	private static DelegateBridge __Hotfix0_FindValidFlipOnlyActs; // 0xa0
	private static DelegateBridge __Hotfix0_FindValidGridGachaActs; // 0xa8
	private static DelegateBridge __Hotfix0_FindValidActs; // 0xb0
	private static DelegateBridge __Hotfix0_CheckIfPrayOnlyActUncomplete; // 0xb8
	private static DelegateBridge __Hotfix0_CheckIfGridGachaActUncomplete; // 0xc0
	private static DelegateBridge __Hotfix0_FindValidAct17d7Activity; // 0xc8
	private static DelegateBridge __Hotfix0_FindValidActFunActivity; // 0xd0
	private static DelegateBridge __Hotfix0_CheckIfAprilFoolActType; // 0xd8
	private static DelegateBridge __Hotfix1_GetUILockTargetFromActivity; // 0xe0
	private static DelegateBridge __Hotfix0__IsActTypeLockCondCustomized; // 0xe8
	private static DelegateBridge __Hotfix0_CheckActivityHomeRedPoints; // 0xf0
	private static DelegateBridge __Hotfix0_GetPlayerMiniStoryAct; // 0xf8
	private static DelegateBridge __Hotfix0_CheckIfActivityInPlayerData; // 0x100
	private static DelegateBridge __Hotfix0_CheckIfActivityUnlocked; // 0x108
	private static DelegateBridge __Hotfix0_GetActivityMainItemCount; // 0x110
	private static DelegateBridge __Hotfix0_GetActivityInfoFromStage; // 0x118
	private static DelegateBridge __Hotfix0_CheckIfActivityCustomZone; // 0x120
	private static DelegateBridge __Hotfix0_FindMainActivityThemeData; // 0x128
	private static DelegateBridge __Hotfix0_StageCanUseCart; // 0x130
	private static DelegateBridge __Hotfix0_GetRuneListByCart; // 0x138
	private static DelegateBridge __Hotfix0__CheckIfActUnlockedByCustomUnlockCond; // 0x140
	private static DelegateBridge __Hotfix0__GetActCustomUnlockConds; // 0x148
	private static DelegateBridge __Hotfix0__CheckCustomUnlockConds; // 0x150
	private static DelegateBridge __Hotfix0__CheckIfCustomUnlockCondSatisfied; // 0x158
	private static DelegateBridge __Hotfix0__GetCustomUnlockCondAlert; // 0x160
	private static DelegateBridge _c__Hotfix0_ctor; // 0x168


	// RVA: 0x20fe134 VA: 0x7594716134
	public static Boolean CheckIfMissionActivityUncomplete(String actId) { }
	// RVA: 0x20fe224 VA: 0x7594716224
	public static Boolean CheckIfCollectionActivityUncomplete(String actId) { }
	// RVA: 0x20fe41c VA: 0x759471641c
	public static Boolean GetPicId(String activityId, out String picId) { }
	// RVA: 0x20fe5dc VA: 0x75947165dc
	public static Void CollectionActivityJumpToRelatedSystem(String actId, Boolean passPreCheck) { }
	// RVA: 0x20fe774 VA: 0x7594716774
	public static Boolean IfCollectionActivityCanJumpToRelatedSystem(String actId) { }
	// RVA: 0x20fe8a4 VA: 0x75947168a4
	public static List`1 FindValidCollectionActivity() { }
	// RVA: 0x20feb38 VA: 0x7594716b38
	public static List`1 FindValidMissionActivity() { }
	// RVA: 0x20fedc8 VA: 0x7594716dc8
	public static ActivityCompleteType GetActivityCompleteType(String actId) { }
	// RVA: 0x20fee9c VA: 0x7594716e9c
	public static Boolean CheckIfCheckinActivityUncomplete(String actId) { }
	// RVA: 0x20feff8 VA: 0x7594716ff8
	public static Boolean CheckIfCheckinActivityFinished(SortableActivity actId) { }
	// RVA: 0x20ff2d0 VA: 0x75947172d0
	public static Boolean CheckIfCollectionActivityFinished(SortableActivity actId) { }
	// RVA: 0x20ff1cc VA: 0x75947171cc
	public static Boolean _CheckRewardListFinished(Int32 rewardCount, List`1 history) { }
	// RVA: 0x20ff500 VA: 0x7594717500
	public static List`1 FindValidCheckinActivity() { }
	// RVA: 0x20ff794 VA: 0x7594717794
	public static String FindValidAVGActivity() { }
	// RVA: 0x20ff90c VA: 0x759471790c
	public static Boolean CheckIfLoginActivityUncomplete(String actId) { }
	// RVA: 0x20ffa04 VA: 0x7594717a04
	public static Boolean CheckIfLoginActivityFinished(SortableActivity actId) { }
	// RVA: 0x20ffb18 VA: 0x7594717b18
	public static Boolean CheckIfActivityPopupAfterCheckin(String actId) { }
	// RVA: 0x20ffc08 VA: 0x7594717c08
	public static List`1 FindValidLoginOnlyActs() { }
	// RVA: 0x20ffe98 VA: 0x7594717e98
	public static UILockTarget GetUILockTargetFromActivity(String actId) { }
	// RVA: 0x21000a4 VA: 0x75947180a4
	public static List`1 FindValidPrayOnlyActs() { }
	// RVA: 0x2100334 VA: 0x7594718334
	public static List`1 FindValidFlipOnlyActs() { }
	// RVA: 0x21005c4 VA: 0x75947185c4
	public static List`1 FindValidGridGachaActs() { }
	// RVA: 0x2100854 VA: 0x7594718854
	public static List`1 FindValidActs(ActivityType type) { }
	// RVA: 0x2100b38 VA: 0x7594718b38
	public static Boolean CheckIfPrayOnlyActUncomplete(String actId) { }
	// RVA: 0x2100c30 VA: 0x7594718c30
	public static Boolean CheckIfGridGachaActUncomplete(String actId) { }
	// RVA: 0x2100d3c VA: 0x7594718d3c
	public static String FindValidAct17d7Activity() { }
	// RVA: 0x2100ebc VA: 0x7594718ebc
	public static String FindValidActFunActivity() { }
	// RVA: 0x2101010 VA: 0x7594719010
	public static Boolean CheckIfAprilFoolActType(ActivityType type) { }
	// RVA: 0x20fff6c VA: 0x7594717f6c
	public static UILockTarget GetUILockTargetFromActivity(BasicData actBasicData) { }
	// RVA: 0x2101088 VA: 0x7594719088
	private static Boolean _IsActTypeLockCondCustomized(ActivityType type) { }
	// RVA: 0x20fdd94 VA: 0x7594715d94
	public static Boolean CheckActivityHomeRedPoints(String actId) { }
	// RVA: 0x2101204 VA: 0x7594719204
	public static PlayerMiniStoryActivity GetPlayerMiniStoryAct(String actId) { }
	// RVA: 0x21012ec VA: 0x75947192ec
	public static Boolean CheckIfActivityInPlayerData(String actId) { }
	// RVA: 0x2101520 VA: 0x7594719520
	public static Boolean CheckIfActivityUnlocked(String actId, out String lockAlert) { }
	// RVA: 0x2101864 VA: 0x7594719864
	public static Int32 GetActivityMainItemCount(String actId, ActivityType actType) { }
	// RVA: 0x2101a3c VA: 0x7594719a3c
	public static BasicData GetActivityInfoFromStage(String stageId) { }
	// RVA: 0x2101b6c VA: 0x7594719b6c
	public static Boolean CheckIfActivityCustomZone(String zoneId, out BasicData actInfo) { }
	// RVA: 0x2101ca8 VA: 0x7594719ca8
	public static ActivityThemeData FindMainActivityThemeData(Int64 curTs) { }
	// RVA: 0x2101e78 VA: 0x7594719e78
	public static Boolean StageCanUseCart(String stageId) { }
	// RVA: 0x2101f6c VA: 0x7594719f6c
	public static List`1 GetRuneListByCart(Dictionary`2 cartCompDict) { }
	// RVA: 0x21016bc VA: 0x75947196bc
	private static Boolean _CheckIfActUnlockedByCustomUnlockCond(BasicData basicInfo, out String lockAlert) { }
	// RVA: 0x210247c VA: 0x759471a47c
	private static List`1 _GetActCustomUnlockConds(BasicData basicInfo) { }
	// RVA: 0x2102568 VA: 0x759471a568
	private static Boolean _CheckCustomUnlockConds(BasicData basicInfo, List`1 unlockConds, Boolean checkActConds, Boolean checkNonActConds, out String lockAlert) { }
	// RVA: 0x21026ec VA: 0x759471a6ec
	private static Boolean _CheckIfCustomUnlockCondSatisfied(BasicData basicInfo, CustomUnlockCond cond, out String lockAlert) { }
	// RVA: 0x210294c VA: 0x759471a94c
	private static String _GetCustomUnlockCondAlert(BasicData condActData, String condStageId) { }
	// RVA: 0x2102a98 VA: 0x759471aa98
	public Void .ctor() { }
}
```