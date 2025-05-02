# Act12D6ResUtil

**Namespace:** `Torappu.Activity.Act12D6`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6ResUtil : IHotfixable
{
	public const String ROGUELIKE_BUFF_ICON_HUB; // 0x0
	public const String ROGUELIKE_BUFF_LEVEL_HUB; // 0x0
	public const String GAME_END_FAIL_ENDING_ID; // 0x0
	public const String GAME_END_FAIL_BACKGROUND_ID; // 0x0
	public const String GAME_END_BKG_HUB; // 0x0
	public const String ACT_LOCAL_CACHE_PREFIX_WATCHED_RELIC; // 0x0
	public const String ACT_LOCAL_CACHE_PREFIX_MODE_CHOICE; // 0x0
	public static Single MILESTONE_HEIGHT; // 0x0
	public static Single MILESTONE_DELTA_HEIGHT; // 0x4
	public static Single MILESTONE_OFFSET; // 0x8
	public static String DEFAULT_MODE; // 0x10
	private static DelegateBridge __Hotfix0_get_activityId; // 0x18
	private static DelegateBridge __Hotfix0_get_floatStateEngine; // 0x20
	private static DelegateBridge __Hotfix0_CreateCommonTopMenu; // 0x28
	private static DelegateBridge __Hotfix0_get_uiItemCard; // 0x30
	private static DelegateBridge __Hotfix0_get_act12d6BuffIconHub; // 0x38
	private static DelegateBridge __Hotfix0_get_act12d6BuffLevelHub; // 0x40
	private static DelegateBridge __Hotfix0_get_activityRoguelikeData; // 0x48
	private static DelegateBridge __Hotfix0_GetAct12D6PlayerInfo; // 0x50
	private static DelegateBridge __Hotfix0_GetAct12D6PlayerInfoFromPlayerData; // 0x58
	private static DelegateBridge __Hotfix0_LoadBuffLevelImage; // 0x60
	private static DelegateBridge __Hotfix0_LoadOuterBuffIcon; // 0x68
	private static DelegateBridge __Hotfix0_LoadGameEndBkgSprite; // 0x70
	private static DelegateBridge __Hotfix0_GetBuffFullLevel; // 0x78
	private static DelegateBridge __Hotfix0_get_mileStoneToken; // 0x80
	private static DelegateBridge __Hotfix0_GetRelicData; // 0x88
	private static DelegateBridge __Hotfix0_SetRelicRead; // 0x90
	private static DelegateBridge __Hotfix0_GenRelicReadStatus; // 0x98
	private static DelegateBridge __Hotfix0_SetModeChoice; // 0xa0
	private static DelegateBridge __Hotfix0_GetModeChoice; // 0xa8
	private static DelegateBridge __Hotfix0__GenerateActLocalCacheKey; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public static String activityId { get; }
	public static StateEngine floatStateEngine { get; }
	public static UIItemCard uiItemCard { get; }
	public static SpriteHub act12d6BuffIconHub { get; }
	public static SpriteHub act12d6BuffLevelHub { get; }
	public static ActivityRoguelikeData activityRoguelikeData { get; }
	public static UIItemViewModel mileStoneToken { get; }

	// RVA: 0x3469728 VA: 0x7595a81728
	public static String get_activityId() { }
	// RVA: 0x3469824 VA: 0x7595a81824
	public static StateEngine get_floatStateEngine() { }
	// RVA: 0x346990c VA: 0x7595a8190c
	public static CommonTopMenu CreateCommonTopMenu(RectTransform container, Action onBackClick) { }
	// RVA: 0x3469a74 VA: 0x7595a81a74
	public static UIItemCard get_uiItemCard() { }
	// RVA: 0x3469af0 VA: 0x7595a81af0
	public static SpriteHub get_act12d6BuffIconHub() { }
	// RVA: 0x3469c40 VA: 0x7595a81c40
	public static SpriteHub get_act12d6BuffLevelHub() { }
	// RVA: 0x3469d90 VA: 0x7595a81d90
	public static ActivityRoguelikeData get_activityRoguelikeData() { }
	// RVA: 0x3469e78 VA: 0x7595a81e78
	public static PlayerRoguelikeActivity GetAct12D6PlayerInfo(String actId) { }
	// RVA: 0x3469f38 VA: 0x7595a81f38
	public static PlayerRoguelikeActivity GetAct12D6PlayerInfoFromPlayerData(String actId, PlayerDataModel playerModel) { }
	// RVA: 0x346a020 VA: 0x7595a82020
	public static Sprite LoadBuffLevelImage(Int32 buffTotalLevel, Boolean isBg) { }
	// RVA: 0x346a238 VA: 0x7595a82238
	public static Sprite LoadOuterBuffIcon(String iconId) { }
	// RVA: 0x346a3b0 VA: 0x7595a823b0
	public static Sprite LoadGameEndBkgSprite(String id) { }
	// RVA: 0x346a584 VA: 0x7595a82584
	public static Int32 GetBuffFullLevel(String buffId) { }
	// RVA: 0x346a788 VA: 0x7595a82788
	public static UIItemViewModel get_mileStoneToken() { }
	// RVA: 0x346a870 VA: 0x7595a82870
	public static RoguelikeItemData GetRelicData(String relicId) { }
	// RVA: 0x346a9b0 VA: 0x7595a829b0
	public static Void SetRelicRead(String relicId) { }
	// RVA: 0x346ab24 VA: 0x7595a82b24
	public static Boolean GenRelicReadStatus(String relicId) { }
	// RVA: 0x346abdc VA: 0x7595a82bdc
	public static Void SetModeChoice(String modeId) { }
	// RVA: 0x346aca8 VA: 0x7595a82ca8
	public static String GetModeChoice() { }
	// RVA: 0x346aa5c VA: 0x7595a82a5c
	private static String _GenerateActLocalCacheKey(String prefix, String id) { }
	// RVA: 0x346ad74 VA: 0x7595a82d74
	public Void .ctor() { }
	// RVA: 0x346adf4 VA: 0x7595a82df4
	private static Void .cctor() { }
}
```