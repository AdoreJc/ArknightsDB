# TemplateActResUtil

**Namespace:** `Torappu.UI.ActivityStage`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActResUtil : IHotfixable
{
	public const String ACT_LOCAL_CACHE_PREFIX_WATCHED_FAVOR_UP_CHAR_ID; // 0x0
	public const String ACT_LOCAL_CACHE_PREFIX_ACCESSED_ZONE_ID; // 0x0
	public const String ACT_LOCAL_CACHE_PREFIX_ACCESSED_STAGE_ID; // 0x0
	private static DelegateBridge __Hotfix0_get_floatStateEngine; // 0x0
	private static DelegateBridge __Hotfix0_SetFavorUpCharWatched; // 0x8
	private static DelegateBridge __Hotfix0_IsFavorUpCharWatched; // 0x10
	private static DelegateBridge __Hotfix0_SetZoneAccessed; // 0x18
	private static DelegateBridge __Hotfix0_isZoneAccessed; // 0x20
	private static DelegateBridge __Hotfix0_IsStageAccessed; // 0x28
	private static DelegateBridge __Hotfix0_SetStageAccessed; // 0x30
	private static DelegateBridge __Hotfix0_GetAct9D0NewsContentImg; // 0x38
	private static DelegateBridge __Hotfix0_GetAct9D0NewsTitleImg; // 0x40
	private static DelegateBridge __Hotfix0_GetAct9D0NewsLogoImg; // 0x48
	private static DelegateBridge __Hotfix0_GetAct9D0NewsLogoLargeImg; // 0x50
	private static DelegateBridge __Hotfix0__GenerateActLocalCacheKey; // 0x58
	private static DelegateBridge __Hotfix0_GetMissionData; // 0x60
	private static DelegateBridge __Hotfix0_CreateCommonTopMenu; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public static StateEngine floatStateEngine { get; }

	// RVA: 0x30a362c VA: 0x75956bb62c
	public static StateEngine get_floatStateEngine() { }
	// RVA: 0x30a4cb0 VA: 0x75956bccb0
	public static Void SetFavorUpCharWatched(String actId, String charId) { }
	// RVA: 0x30a4dfc VA: 0x75956bcdfc
	public static Boolean IsFavorUpCharWatched(String actId, String charId) { }
	// RVA: 0x30a4eac VA: 0x75956bceac
	public static Void SetZoneAccessed(String actId, String zoneId) { }
	// RVA: 0x30a4f50 VA: 0x75956bcf50
	public static Boolean isZoneAccessed(String actId, String zoneId) { }
	// RVA: 0x30a5000 VA: 0x75956bd000
	public static Boolean IsStageAccessed(String activityId, String stageId) { }
	// RVA: 0x30a50b0 VA: 0x75956bd0b0
	public static Void SetStageAccessed(String activityId, List`1 stageIdList) { }
	// RVA: 0x30a51e0 VA: 0x75956bd1e0
	public static Sprite GetAct9D0NewsContentImg(String actId, String newsPic) { }
	// RVA: 0x30a5288 VA: 0x75956bd288
	public static Sprite GetAct9D0NewsTitleImg(String actId, String titlePic) { }
	// RVA: 0x30a5330 VA: 0x75956bd330
	public static Sprite GetAct9D0NewsLogoImg(String actId, String logoPic) { }
	// RVA: 0x30a53d8 VA: 0x75956bd3d8
	public static Sprite GetAct9D0NewsLogoLargeImg(String actId, String logoPic) { }
	// RVA: 0x30a4d54 VA: 0x75956bcd54
	private static String _GenerateActLocalCacheKey(String actId, String prefix, String id) { }
	// RVA: 0x30a5480 VA: 0x75956bd480
	public static MissionData GetMissionData(String missionID, String activityID) { }
	// RVA: 0x309b4dc VA: 0x75956b34dc
	public static CommonTopMenu CreateCommonTopMenu(RectTransform container, Action onBackClick) { }
	// RVA: 0x30a55d4 VA: 0x75956bd5d4
	public Void .ctor() { }
}
```