# Act13SideResUtil

**Namespace:** `Torappu.Activity.Act13Side`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13SideResUtil : IHotfixable
{
	public const String ACT_LOCAL_CACHE_SEARCH_HINT; // 0x0
	public const String ACT_VISIT_MISSION_AFTER_NEW_FLAG; // 0x0
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_GetActDBData; // 0x8
	private static DelegateBridge __Hotfix0_GetPrestigeRankName; // 0x10
	private static DelegateBridge __Hotfix0_GetOrgData; // 0x18
	private static DelegateBridge __Hotfix0_GetOrgName; // 0x20
	private static DelegateBridge __Hotfix0_GetPrestigeMax; // 0x28
	private static DelegateBridge __Hotfix0_IsOrgOpen; // 0x30
	private static DelegateBridge __Hotfix0_CheckDailyMissionCommitable; // 0x38
	private static DelegateBridge __Hotfix0_GetPrestigeCount; // 0x40
	private static DelegateBridge __Hotfix0_GetPrestigeRank; // 0x48
	private static DelegateBridge __Hotfix0_CheckDailyMissionFlag; // 0x50
	private static DelegateBridge __Hotfix0_CheckDailyAgendaFlag; // 0x58
	private static DelegateBridge __Hotfix0_GetAgendaCount; // 0x60
	private static DelegateBridge __Hotfix0_IsBoardFull; // 0x68
	private static DelegateBridge __Hotfix0_IsBattleEnd; // 0x70
	private static DelegateBridge __Hotfix0_LoadOrgLogo; // 0x78
	private static DelegateBridge __Hotfix0_LoadOrgTitle; // 0x80
	private static DelegateBridge __Hotfix0_LoadPrestigeEmoji; // 0x88
	private static DelegateBridge __Hotfix0_LoadLeftBar; // 0x90
	private static DelegateBridge __Hotfix0_LoadUpTitle; // 0x98
	private static DelegateBridge __Hotfix0_LoadMissionAvatar; // 0xa0
	private static DelegateBridge __Hotfix0_LoadMissionPrincipalBg; // 0xa8
	private static DelegateBridge __Hotfix0_IsSearchHintChecked; // 0xb0
	private static DelegateBridge __Hotfix0_SetSearchHintChecked; // 0xb8
	private static DelegateBridge __Hotfix0_IsThirdOrgOpenAndMissionChecked; // 0xc0
	private static DelegateBridge __Hotfix0_IsMissionChecked; // 0xc8
	private static DelegateBridge __Hotfix0_SetMissionChecked; // 0xd0
	private static DelegateBridge __Hotfix0__GenerateActLocalCacheKey; // 0xd8
	private static DelegateBridge __Hotfix0__GetSpriteHubPath; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	public static String activityId { get; }

	// RVA: 0x3426e68 VA: 0x7595a3ee68
	public static String get_activityId() { }
	// RVA: 0x3426f54 VA: 0x7595a3ef54
	public static Act13SideData GetActDBData(String actId) { }
	// RVA: 0x342685c VA: 0x7595a3e85c
	public static String GetPrestigeRankName(String actId, PrestigeRank prestigeRank) { }
	// RVA: 0x3427024 VA: 0x7595a3f024
	public static OrgData GetOrgData(String actId, String orgId) { }
	// RVA: 0x34270e0 VA: 0x7595a3f0e0
	public static String GetOrgName(String actId, String orgId) { }
	// RVA: 0x3427190 VA: 0x7595a3f190
	public static Int32 GetPrestigeMax(OrgData orgData) { }
	// RVA: 0x3426798 VA: 0x7595a3e798
	public static Boolean IsOrgOpen(String actId, String orgId) { }
	// RVA: 0x342726c VA: 0x7595a3f26c
	public static Boolean CheckDailyMissionCommitable(String actId) { }
	// RVA: 0x34265dc VA: 0x7595a3e5dc
	public static Int32 GetPrestigeCount(OrgData orgData) { }
	// RVA: 0x34266a8 VA: 0x7595a3e6a8
	public static PrestigeRank GetPrestigeRank(OrgData orgData, Int32 prestigeCount) { }
	// RVA: 0x34273e8 VA: 0x7595a3f3e8
	public static Boolean CheckDailyMissionFlag(String activityId) { }
	// RVA: 0x34274e4 VA: 0x7595a3f4e4
	public static Boolean CheckDailyAgendaFlag(String activityId) { }
	// RVA: 0x34275e0 VA: 0x7595a3f5e0
	public static Int32 GetAgendaCount(String activityId) { }
	// RVA: 0x34276c8 VA: 0x7595a3f6c8
	public static Boolean IsBoardFull(String actId) { }
	// RVA: 0x3423f28 VA: 0x7595a3bf28
	public static Boolean IsBattleEnd(String actId) { }
	// RVA: 0x3427804 VA: 0x7595a3f804
	public static Sprite LoadOrgLogo(String actId, String orgId) { }
	// RVA: 0x3427940 VA: 0x7595a3f940
	public static Sprite LoadOrgTitle(String actId, String orgId) { }
	// RVA: 0x34279f8 VA: 0x7595a3f9f8
	public static Sprite LoadPrestigeEmoji(String actId, PrestigeRank prestigeRank) { }
	// RVA: 0x3427adc VA: 0x7595a3fadc
	public static Sprite LoadLeftBar(String actId, String groupId) { }
	// RVA: 0x3427b94 VA: 0x7595a3fb94
	public static Sprite LoadUpTitle(String actId, String groupId) { }
	// RVA: 0x3427c4c VA: 0x7595a3fc4c
	public static Sprite LoadMissionAvatar(String actId, String principalId) { }
	// RVA: 0x3427d04 VA: 0x7595a3fd04
	public static Sprite LoadMissionPrincipalBg(String actId, String principalId) { }
	// RVA: 0x3427dbc VA: 0x7595a3fdbc
	public static Boolean IsSearchHintChecked(String activityId) { }
	// RVA: 0x3427e70 VA: 0x7595a3fe70
	public static Void SetSearchHintChecked(String activityId) { }
	// RVA: 0x3427f18 VA: 0x7595a3ff18
	public static Boolean IsThirdOrgOpenAndMissionChecked(String activityId) { }
	// RVA: 0x3428100 VA: 0x7595a40100
	public static Boolean IsMissionChecked(String activityId) { }
	// RVA: 0x34281b4 VA: 0x7595a401b4
	public static Void SetMissionChecked(String activityId) { }
	// RVA: 0x3428280 VA: 0x7595a40280
	private static String _GenerateActLocalCacheKey(String prefix, String activityId, String id) { }
	// RVA: 0x34278bc VA: 0x7595a3f8bc
	private static String _GetSpriteHubPath(String actId) { }
	// RVA: 0x3428328 VA: 0x7595a40328
	public Void .ctor() { }
}
```