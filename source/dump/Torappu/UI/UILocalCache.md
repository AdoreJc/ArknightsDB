# UILocalCache

**Namespace:** `Torappu.UI`


## Fields

- `LocalCharSortFilterSetting m_repoSettingCache`

- `LocalCharSortFilterSetting m_secretaryChangeSettingCache`

- `DynIllustLocalCache m_dynIllustCache`

- `Int32 m_serverAnnouceVersion`

- `Int32 m_serverPopUpAnnouceVersion`


## Properties

- `Int32 lastSelectedSquadIndex`

- `Int32 AVGButtonAutoSpeed`

- `Int32 AVGQuickAutoSpeed`

- `Int32 GridGachaSkipAnimation`

- `Int32 serverAnnouceVersion`

- `Int32 localAnnouceVersion`

- `Int32 serverPopUpAnnouceVersion`

- `Int32 localPopUpAnnouceVersion`

- `DeviceLevel deviceLevel`

- `GradingLevel gradingLevel`

- `SimulatorStatus gradingIsSimulator`

- `Boolean aaSettingInited`

- `Int32 serviceLicenseVersion`

- `Int32 DiffGroupAutoSelect`


## Methods

- `Int32 get_lastSelectedSquadIndex()`

- `Void set_lastSelectedSquadIndex(Int32)`

- `Void SetSkillSelectablePredefinedSquadTipsShowed(String)`

- `Boolean CheckSkillSelectablePredefinedSquadTipsShowed(String)`

- `Int32 get_AVGButtonAutoSpeed()`

- `Void set_AVGButtonAutoSpeed(Int32)`

- `Int32 get_AVGQuickAutoSpeed()`

- `Void set_AVGQuickAutoSpeed(Int32)`

- `Int32 get_GridGachaSkipAnimation()`

- `Void set_GridGachaSkipAnimation(Int32)`

- `Int32 get_serverAnnouceVersion()`

- `Void set_serverAnnouceVersion(Int32)`

- `Int32 get_localAnnouceVersion()`

- `Void set_localAnnouceVersion(Int32)`

- `Int32 get_serverPopUpAnnouceVersion()`

- `Void set_serverPopUpAnnouceVersion(Int32)`

- `Int32 get_localPopUpAnnouceVersion()`

- `Void set_localPopUpAnnouceVersion(Int32)`

- `DeviceLevel get_deviceLevel()`

- `Void set_deviceLevel(DeviceLevel)`

- `GradingLevel get_gradingLevel()`

- `Void set_gradingLevel(GradingLevel)`

- `SimulatorStatus get_gradingIsSimulator()`

- `Void set_gradingIsSimulator(SimulatorStatus)`

- `Boolean get_aaSettingInited()`

- `Void set_aaSettingInited(Boolean)`

- `Int32 get_serviceLicenseVersion()`

- `Void set_serviceLicenseVersion(Int32)`

- `Void AddPreAnnounceId(String)`

- `Boolean CheckPreAnnounceId(String)`

- `String _GenPreAnnounceKey(String)`

- `Void AddRetroNewFlag(String)`

- `Boolean CheckRetroNewFlag(String)`

- `String _GenRetroKey(String)`

- `Void SetCharSortType(CharacterSortType)`

- `CharacterSortType GetCharSortType()`

- `Boolean GetIsPlayerRepoStarTopMode(Int32)`

- `Void SetPlayerRepoStarTopMode(Boolean)`

- `Boolean GetIfLoginDynEntrancePlayed(Int64, String)`

- `Void SetLoginDynEntrancePlayed(Int64, String)`

- `Void _EnsurePlayedDynIllustCache(Int64)`

- `Boolean GetShowHomeBirthdaySetting()`

- `Void SetShowHomeBirthdaySetting(Boolean)`

- `Void SetDiffGroupRewardAutoShow(Boolean)`

- `Boolean GetDiffGroupRewardAutoShow()`

- `Void SetDiffGroupAutoSelect(StageDiffGroup)`

- `StageDiffGroup GetDiffGroupAutoSelect()`

- `Int32 get_DiffGroupAutoSelect()`

- `Void set_DiffGroupAutoSelect(Int32)`

- `Void SetSecretaryChangeSortType(CharacterSortType)`

- `CharacterSortType GetSecretaryChangeSortType()`

- `Boolean GetIsPlayerSecretaryChangeStarTopMode()`

- `Void SetPlayerSecretaryChangeStarTopMode(Boolean)`

- `Int32 GetPlayerCharSelectCustomSortTypeWithKey(String, Int32)`

- `Void SetPlayerCharSelectCustomSortTypeWithKey(String, Int32)`

- `Boolean GetIsPlayerRepoFilterPanelShow()`

- `Void SetIsPlayerRepoFilterPanelShow(Boolean)`

- `Boolean GetIsPlayerCharSelectFilterPanelShow()`

- `Void SetIsPlayerCharSelectFilterPanelShow(Boolean)`

- `Int32 GetPlayerStarMarkTopMode(Int32)`

- `Void SetPlayerStarMarkTopMode(Int32)`

- `Boolean IsMultiplayerSquadCopied(String, String)`

- `Void SetMultiplayerSquadCopied(String, String)`

- `String _GetMultiplayerSquadCopyKey(String, String)`

- `Boolean IsAntiSpoilerVisited(String)`

- `Void SetAntiSpoilerChecked(String)`

- `String _GetAntiSpoilerChecked(String)`

- `SquadType LoadRuneSquadCacheV1(String)`

- `Void SaveRuneSquadCacheV1(String, SquadType)`

- `Boolean GuideOnlyCheckGuidebookViewed(String)`

- `Void GuideOnlyAddGuidebookViewed(String)`

- `String _GenGuidebookKey(String)`

- `Boolean EnemyViewedCheck(String)`

- `Void EnemyAddViewed(String)`

- `String _GenEnemyKey(String)`

- `Boolean RecommendShopViewedCheck(String)`

- `Void RecommendShopAddViewed(String)`

- `String _GenRecommendShopKey(String)`

- `Int64 GetLastExtraClickTime(Int64)`

- `Void SetLastExtraClickTime(Int64)`

- `Boolean AnnouceViewedCheck(String)`

- `Void AnnounceAddViewed(String)`

- `String _GenAnnounceKey(String)`

- `Void SetCampaignCachedRotateStageId(String)`

- `String GetCampaignCachedRotateStageId()`

- `Void SetCampaignCachedBriefId(String)`

- `String GetCampaignCachedBriefId()`

- `Void SaveStageCache(Dictionary`2)`

- `Void SaveZoneCache(Dictionary`2)`

- `ActivityLocalCache LoadActivityCache()`

- `Void SaveActivityCache(ActivityLocalCache)`

- `Void SetStageContinuousBattleTimesCache(String, Int32)`

- `Int32 GetStageContinuousBattleTimesCache(String)`

- `Int64 GetLoginCharRotationUpdateTimeStamp()`

- `Void SetLoginCharRotationUpdateTimeStamp(Int64)`

- `CharRotationInfoSet GetCharRotationInfoSet()`

- `Void SaveCharRotationInfoSet(String, List`1, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UILocalCache : Singleton`1, IHotfixable
{
	private const String LAST_SELECTED_SQUAD; // 0x0
	private const String AVG_BUTTON_AUTO_SPEED; // 0x0
	private const String AVG_QUICK_AUTO_SPEED; // 0x0
	private const String GRID_GACHA_SKIP_ANIMATION; // 0x0
	private const String HOME_ANNOUNCE_VERSION; // 0x0
	private const String HOME_ANNOUNCE_POP_UP_VERSION; // 0x0
	private const String MEDAL_BAR_LIST_STATE_CACHE_ENTER; // 0x0
	private const String FIFTH_ANNIV_EXPLORE_CAROUSEL_ITEM; // 0x0
	private const String MEDAL_SHOW_EXPIRED; // 0x0
	private const String STAGE_LOCAL_CACHE; // 0x0
	private const String ZONE_LOCAL_CACHE; // 0x0
	public const String ACT_LOCAL_CACHE; // 0x0
	public const String RETRO_LOCAL_CACHE; // 0x0
	private const String GUIDEBOOK_VIEWED; // 0x0
	private const String ANNOUNCE_VIEWED; // 0x0
	private const String ENEMY_VIEWED; // 0x0
	private const String SHOP_RECOMMEND_VIEWED; // 0x0
	private const String SHOP_EXTRA_QC_VIEWED; // 0x0
	private const String PRE_ANNOUNCED_VIEWED_GROUP; // 0x0
	private const String DEVICE_LEVEL; // 0x0
	private const String GRADING_LEVEL; // 0x0
	private const String GRADING_IS_SIMULATOR; // 0x0
	private const String GRADING_IS_AA_INITED; // 0x0
	private const String SERVICE_LICENSE_VERSION; // 0x0
	private const String LOCAL_RUNE_SQUAD_TEMPLATE_V1; // 0x0
	private const String CRISIS_PERM_RUNE_USE_SPARSE_MODE; // 0x0
	private const String CRISIS_SELECTED_RUNES; // 0x0
	private const String CRISIS_RUNE_GROUP_SELECTED_RUNES; // 0x0
	public const String HOME_ILLUST_LAYOUT_INFO; // 0x0
	private const String CAMP_CACHED_ROTATE_STAGE_ID; // 0x0
	private const String CAMP_CACHED_BRIEF_ID; // 0x0
	private const String UNIEQUIP_CHAR_FIRST_VISIT; // 0x0
	private const String MULTIPLAYER_SQUAD_COPY; // 0x0
	private const String ANTI_SPOLIER_KEY; // 0x0
	private const String DIFF_GROUP_AUTO_SHOW; // 0x0
	private const String DIFF_GROUP_AUTO_SELECT; // 0x0
	public const String RECENT_BATTLE_RECORDS; // 0x0
	public const String UI_MUSIC_TRIGGER_CACHE; // 0x0
	public const String UI_COMMON_TRK_PT; // 0x0
	public const String UI_MUSIC_CONFIG_CACHE; // 0x0
	public const String ACT_ARCHIVE_LOCAL_CACHE; // 0x0
	public const String STORY_REVIEW_MINI_TRIAL_LOCAL_CACHE; // 0x0
	public const String UI_CHAR_CUSTOM_SORT_TYPE_KEY; // 0x0
	public const String UI_CHAR_STARMARK_TOP_LOCAL_CACHE; // 0x0
	public const String UI_REPO_STARMARK_TOP; // 0x0
	public const String UI_ROGUE_LOCALCACHE; // 0x0
	public const String UI_CLIMB_TOWER_LOCAL_CACHE; // 0x0
	public const String UI_SQUAD_PREDEFINED_TIPS_SHOWED; // 0x0
	public const String UI_RES_PREF_ALERT; // 0x0
	public const String UI_CHAR_SELECT_FILTER_SHOW; // 0x0
	public const String UI_REPO_FILTER_SHOW; // 0x0
	public const String LOGIN_DYN_ENTRANCE_PLAY; // 0x0
	public const String UI_BOSS_RUSH_LOCAL_CACHE; // 0x0
	public const String UI_SANDBOX_LOCAL_CACHE; // 0x0
	public const String UI_SIRACUSA_MAP_LOCAL_CACHE; // 0x0
	public const String UI_CRISIS_V2_LOCAL_CACHE; // 0x0
	public const String UI_ACT24SIDE_LOCAL_CACHE; // 0x0
	public const String UI_ACT42D0_LOCAL_CACHE; // 0x0
	public const String UI_TUNING_LOCAL_CACHE; // 0x0
	public const String UI_SANDBOX_V2_LOCAL_CACHE; // 0x0
	private const String STAGE_CONTINUOUS_BATTLE_TIMES_LOCAL_CACHE; // 0x0
	private const String YEAR_5_EXPLORE_IS_NEW; // 0x0
	public const String UI_HOME_BIRTHDAY_SETTING; // 0x0
	public const String UI_VEC_BREAK_LOCAL_CACHE; // 0x0
	public const String UI_ACT_MULTI_V3_LOCAL_CACHE; // 0x0
	public const String UI_ACT1VAUTOCHESS_LOCAL_CACHE; // 0x0
	public const String UI_EMOTICON_THEME_LOCAL_CACHE; // 0x0
	public const String UI_ARCADE_LOCAL_CACHE; // 0x0
	public const String UI_CHAR_ROTATION_LOCAL_CACHE; // 0x0
	public const String UI_CHAR_ROTATION_LAST_LOGIN; // 0x0
	public const String UI_MIX_STORY; // 0x0
	public const String UI_SIX_STAR_LOCAL_CACHE; // 0x0
	public const String UI_ENEMY_DUEL_LOCAL_CACHE; // 0x0
	private LocalCharSortFilterSetting m_repoSettingCache; // 0x10
	private LocalCharSortFilterSetting m_secretaryChangeSettingCache; // 0x18
	private DynIllustLocalCache m_dynIllustCache; // 0x20
	private Int32 m_serverAnnouceVersion; // 0x28
	private Int32 m_serverPopUpAnnouceVersion; // 0x2c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_lastSelectedSquadIndex; // 0x8
	private static DelegateBridge __Hotfix0_set_lastSelectedSquadIndex; // 0x10
	private static DelegateBridge __Hotfix0_SetSkillSelectablePredefinedSquadTipsShowed; // 0x18
	private static DelegateBridge __Hotfix0_CheckSkillSelectablePredefinedSquadTipsShowed; // 0x20
	private static DelegateBridge __Hotfix0_get_AVGButtonAutoSpeed; // 0x28
	private static DelegateBridge __Hotfix0_set_AVGButtonAutoSpeed; // 0x30
	private static DelegateBridge __Hotfix0_get_AVGQuickAutoSpeed; // 0x38
	private static DelegateBridge __Hotfix0_set_AVGQuickAutoSpeed; // 0x40
	private static DelegateBridge __Hotfix0_get_GridGachaSkipAnimation; // 0x48
	private static DelegateBridge __Hotfix0_set_GridGachaSkipAnimation; // 0x50
	private static DelegateBridge __Hotfix0_get_serverAnnouceVersion; // 0x58
	private static DelegateBridge __Hotfix0_set_serverAnnouceVersion; // 0x60
	private static DelegateBridge __Hotfix0_get_localAnnouceVersion; // 0x68
	private static DelegateBridge __Hotfix0_set_localAnnouceVersion; // 0x70
	private static DelegateBridge __Hotfix0_get_serverPopUpAnnouceVersion; // 0x78
	private static DelegateBridge __Hotfix0_set_serverPopUpAnnouceVersion; // 0x80
	private static DelegateBridge __Hotfix0_get_localPopUpAnnouceVersion; // 0x88
	private static DelegateBridge __Hotfix0_set_localPopUpAnnouceVersion; // 0x90
	private static DelegateBridge __Hotfix0_get_medalCacheBarListStateFlag; // 0x98
	private static DelegateBridge __Hotfix0_set_medalCacheBarListStateFlag; // 0xa0
	private static DelegateBridge __Hotfix0_get_fifthAnnivExploreCarouselCount; // 0xa8
	private static DelegateBridge __Hotfix0_set_fifthAnnivExploreCarouselCount; // 0xb0
	private static DelegateBridge __Hotfix0_get_medalShowExpiredStatus; // 0xb8
	private static DelegateBridge __Hotfix0_set_medalShowExpiredStatus; // 0xc0
	private static DelegateBridge __Hotfix0_get_deviceLevel; // 0xc8
	private static DelegateBridge __Hotfix0_set_deviceLevel; // 0xd0
	private static DelegateBridge __Hotfix0_get_gradingLevel; // 0xd8
	private static DelegateBridge __Hotfix0_set_gradingLevel; // 0xe0
	private static DelegateBridge __Hotfix0_get_gradingIsSimulator; // 0xe8
	private static DelegateBridge __Hotfix0_set_gradingIsSimulator; // 0xf0
	private static DelegateBridge __Hotfix0_get_aaSettingInited; // 0xf8
	private static DelegateBridge __Hotfix0_set_aaSettingInited; // 0x100
	private static DelegateBridge __Hotfix0_get_serviceLicenseVersion; // 0x108
	private static DelegateBridge __Hotfix0_set_serviceLicenseVersion; // 0x110
	private static DelegateBridge __Hotfix0_AddPreAnnounceId; // 0x118
	private static DelegateBridge __Hotfix0_CheckPreAnnounceId; // 0x120
	private static DelegateBridge __Hotfix0__GenPreAnnounceKey; // 0x128
	private static DelegateBridge __Hotfix0_AddRetroNewFlag; // 0x130
	private static DelegateBridge __Hotfix0_CheckRetroNewFlag; // 0x138
	private static DelegateBridge __Hotfix0__GenRetroKey; // 0x140
	private static DelegateBridge __Hotfix0_SetCharSortType; // 0x148
	private static DelegateBridge __Hotfix0_GetCharSortType; // 0x150
	private static DelegateBridge __Hotfix0_GetIsPlayerRepoStarTopMode; // 0x158
	private static DelegateBridge __Hotfix0_SetPlayerRepoStarTopMode; // 0x160
	private static DelegateBridge __Hotfix0_GetIfLoginDynEntrancePlayed; // 0x168
	private static DelegateBridge __Hotfix0_SetLoginDynEntrancePlayed; // 0x170
	private static DelegateBridge __Hotfix0__EnsurePlayedDynIllustCache; // 0x178
	private static DelegateBridge __Hotfix0_GetShowHomeBirthdaySetting; // 0x180
	private static DelegateBridge __Hotfix0_SetShowHomeBirthdaySetting; // 0x188
	private static DelegateBridge __Hotfix0_SetDiffGroupRewardAutoShow; // 0x190
	private static DelegateBridge __Hotfix0_GetDiffGroupRewardAutoShow; // 0x198
	private static DelegateBridge __Hotfix0_SetDiffGroupAutoSelect; // 0x1a0
	private static DelegateBridge __Hotfix0_GetDiffGroupAutoSelect; // 0x1a8
	private static DelegateBridge __Hotfix0_get_DiffGroupAutoSelect; // 0x1b0
	private static DelegateBridge __Hotfix0_set_DiffGroupAutoSelect; // 0x1b8
	private static DelegateBridge __Hotfix0_SetSecretaryChangeSortType; // 0x1c0
	private static DelegateBridge __Hotfix0_GetSecretaryChangeSortType; // 0x1c8
	private static DelegateBridge __Hotfix0_GetIsPlayerSecretaryChangeStarTopMode; // 0x1d0
	private static DelegateBridge __Hotfix0_SetPlayerSecretaryChangeStarTopMode; // 0x1d8
	private static DelegateBridge __Hotfix0_GetPlayerCharSelectCustomSortTypeWithKey; // 0x1e0
	private static DelegateBridge __Hotfix0_SetPlayerCharSelectCustomSortTypeWithKey; // 0x1e8
	private static DelegateBridge __Hotfix0_GetIsPlayerRepoFilterPanelShow; // 0x1f0
	private static DelegateBridge __Hotfix0_SetIsPlayerRepoFilterPanelShow; // 0x1f8
	private static DelegateBridge __Hotfix0_GetIsPlayerCharSelectFilterPanelShow; // 0x200
	private static DelegateBridge __Hotfix0_SetIsPlayerCharSelectFilterPanelShow; // 0x208
	private static DelegateBridge __Hotfix0_GetPlayerStarMarkTopMode; // 0x210
	private static DelegateBridge __Hotfix0_SetPlayerStarMarkTopMode; // 0x218
	private static DelegateBridge __Hotfix0_IsMultiplayerSquadCopied; // 0x220
	private static DelegateBridge __Hotfix0_SetMultiplayerSquadCopied; // 0x228
	private static DelegateBridge __Hotfix0__GetMultiplayerSquadCopyKey; // 0x230
	private static DelegateBridge __Hotfix0_IsAntiSpoilerVisited; // 0x238
	private static DelegateBridge __Hotfix0_SetAntiSpoilerChecked; // 0x240
	private static DelegateBridge __Hotfix0__GetAntiSpoilerChecked; // 0x248
	private static DelegateBridge __Hotfix0_LoadRuneSquadCacheV1; // 0x250
	private static DelegateBridge __Hotfix0_SaveRuneSquadCacheV1; // 0x258
	private static DelegateBridge __Hotfix0_GuideOnlyCheckGuidebookViewed; // 0x260
	private static DelegateBridge __Hotfix0_GuideOnlyAddGuidebookViewed; // 0x268
	private static DelegateBridge __Hotfix0__GenGuidebookKey; // 0x270
	private static DelegateBridge __Hotfix0_EnemyViewedCheck; // 0x278
	private static DelegateBridge __Hotfix0_EnemyAddViewed; // 0x280
	private static DelegateBridge __Hotfix0__GenEnemyKey; // 0x288
	private static DelegateBridge __Hotfix0_RecommendShopViewedCheck; // 0x290
	private static DelegateBridge __Hotfix0_RecommendShopAddViewed; // 0x298
	private static DelegateBridge __Hotfix0__GenRecommendShopKey; // 0x2a0
	private static DelegateBridge __Hotfix0_GetLastExtraClickTime; // 0x2a8
	private static DelegateBridge __Hotfix0_SetLastExtraClickTime; // 0x2b0
	private static DelegateBridge __Hotfix0_AnnouceViewedCheck; // 0x2b8
	private static DelegateBridge __Hotfix0_AnnounceAddViewed; // 0x2c0
	private static DelegateBridge __Hotfix0__GenAnnounceKey; // 0x2c8
	private static DelegateBridge __Hotfix0_SetCampaignCachedRotateStageId; // 0x2d0
	private static DelegateBridge __Hotfix0_GetCampaignCachedRotateStageId; // 0x2d8
	private static DelegateBridge __Hotfix0_SetCampaignCachedBriefId; // 0x2e0
	private static DelegateBridge __Hotfix0_GetCampaignCachedBriefId; // 0x2e8
	private static DelegateBridge __Hotfix0_LoadStageCache; // 0x2f0
	private static DelegateBridge __Hotfix0_SaveStageCache; // 0x2f8
	private static DelegateBridge __Hotfix0_LoadZoneCache; // 0x300
	private static DelegateBridge __Hotfix0_SaveZoneCache; // 0x308
	private static DelegateBridge __Hotfix0_LoadActivityCache; // 0x310
	private static DelegateBridge __Hotfix0_SaveActivityCache; // 0x318
	private static DelegateBridge __Hotfix0_SetStageContinuousBattleTimesCache; // 0x320
	private static DelegateBridge __Hotfix0_GetStageContinuousBattleTimesCache; // 0x328
	private static DelegateBridge __Hotfix0_GetLoginCharRotationUpdateTimeStamp; // 0x330
	private static DelegateBridge __Hotfix0_SetLoginCharRotationUpdateTimeStamp; // 0x338
	private static DelegateBridge __Hotfix0_GetCharRotationInfoSet; // 0x340
	private static DelegateBridge __Hotfix0_SaveCharRotationInfoSet; // 0x348

	public Int32 lastSelectedSquadIndex { get; set; }
	public Int32 AVGButtonAutoSpeed { get; set; }
	public Int32 AVGQuickAutoSpeed { get; set; }
	public Int32 GridGachaSkipAnimation { get; set; }
	public Int32 serverAnnouceVersion { get; set; }
	public Int32 localAnnouceVersion { get; set; }
	public Int32 serverPopUpAnnouceVersion { get; set; }
	public Int32 localPopUpAnnouceVersion { get; set; }
	public static Boolean medalCacheBarListStateFlag { get; set; }
	public static Int32 fifthAnnivExploreCarouselCount { get; set; }
	public static Boolean medalShowExpiredStatus { get; set; }
	public DeviceLevel deviceLevel { get; set; }
	public GradingLevel gradingLevel { get; set; }
	public SimulatorStatus gradingIsSimulator { get; set; }
	public Boolean aaSettingInited { get; set; }
	public Int32 serviceLicenseVersion { get; set; }
	public Int32 DiffGroupAutoSelect { get; set; }

	// RVA: 0x21d9600 VA: 0x75947f1600
	protected Void .ctor() { }
	// RVA: 0x21d979c VA: 0x75947f179c
	public Int32 get_lastSelectedSquadIndex() { }
	// RVA: 0x21d9820 VA: 0x75947f1820
	public Void set_lastSelectedSquadIndex(Int32 value) { }
	// RVA: 0x21d98c0 VA: 0x75947f18c0
	public Void SetSkillSelectablePredefinedSquadTipsShowed(String activityId) { }
	// RVA: 0x21d9964 VA: 0x75947f1964
	public Boolean CheckSkillSelectablePredefinedSquadTipsShowed(String activityId) { }
	// RVA: 0x21d9a14 VA: 0x75947f1a14
	public Int32 get_AVGButtonAutoSpeed() { }
	// RVA: 0x21d9a98 VA: 0x75947f1a98
	public Void set_AVGButtonAutoSpeed(Int32 value) { }
	// RVA: 0x21d9b38 VA: 0x75947f1b38
	public Int32 get_AVGQuickAutoSpeed() { }
	// RVA: 0x21d9bbc VA: 0x75947f1bbc
	public Void set_AVGQuickAutoSpeed(Int32 value) { }
	// RVA: 0x21d9c5c VA: 0x75947f1c5c
	public Int32 get_GridGachaSkipAnimation() { }
	// RVA: 0x21d9ce0 VA: 0x75947f1ce0
	public Void set_GridGachaSkipAnimation(Int32 value) { }
	// RVA: 0x21d9d80 VA: 0x75947f1d80
	public Int32 get_serverAnnouceVersion() { }
	// RVA: 0x21d9de8 VA: 0x75947f1de8
	public Void set_serverAnnouceVersion(Int32 value) { }
	// RVA: 0x21d9e64 VA: 0x75947f1e64
	public Int32 get_localAnnouceVersion() { }
	// RVA: 0x21d9ee8 VA: 0x75947f1ee8
	public Void set_localAnnouceVersion(Int32 value) { }
	// RVA: 0x21d9f88 VA: 0x75947f1f88
	public Int32 get_serverPopUpAnnouceVersion() { }
	// RVA: 0x21d9ff0 VA: 0x75947f1ff0
	public Void set_serverPopUpAnnouceVersion(Int32 value) { }
	// RVA: 0x21da06c VA: 0x75947f206c
	public Int32 get_localPopUpAnnouceVersion() { }
	// RVA: 0x21da0f0 VA: 0x75947f20f0
	public Void set_localPopUpAnnouceVersion(Int32 value) { }
	// RVA: 0x21da190 VA: 0x75947f2190
	public static Boolean get_medalCacheBarListStateFlag() { }
	// RVA: 0x21da218 VA: 0x75947f2218
	public static Void set_medalCacheBarListStateFlag(Boolean value) { }
	// RVA: 0x21da2a0 VA: 0x75947f22a0
	public static Int32 get_fifthAnnivExploreCarouselCount() { }
	// RVA: 0x21da31c VA: 0x75947f231c
	public static Void set_fifthAnnivExploreCarouselCount(Int32 value) { }
	// RVA: 0x21da3a0 VA: 0x75947f23a0
	public static Boolean get_medalShowExpiredStatus() { }
	// RVA: 0x21da428 VA: 0x75947f2428
	public static Void set_medalShowExpiredStatus(Boolean value) { }
	// RVA: 0x21da4ac VA: 0x75947f24ac
	public DeviceLevel get_deviceLevel() { }
	// RVA: 0x21da5a8 VA: 0x75947f25a8
	public Void set_deviceLevel(DeviceLevel value) { }
	// RVA: 0x21da648 VA: 0x75947f2648
	public GradingLevel get_gradingLevel() { }
	// RVA: 0x21da740 VA: 0x75947f2740
	public Void set_gradingLevel(GradingLevel value) { }
	// RVA: 0x21da7e0 VA: 0x75947f27e0
	public SimulatorStatus get_gradingIsSimulator() { }
	// RVA: 0x21da8d8 VA: 0x75947f28d8
	public Void set_gradingIsSimulator(SimulatorStatus value) { }
	// RVA: 0x21da978 VA: 0x75947f2978
	public Boolean get_aaSettingInited() { }
	// RVA: 0x21daa78 VA: 0x75947f2a78
	public Void set_aaSettingInited(Boolean value) { }
	// RVA: 0x21dab18 VA: 0x75947f2b18
	public Int32 get_serviceLicenseVersion() { }
	// RVA: 0x21dab9c VA: 0x75947f2b9c
	public Void set_serviceLicenseVersion(Int32 value) { }
	// RVA: 0x21dac3c VA: 0x75947f2c3c
	public Void AddPreAnnounceId(String announceId) { }
	// RVA: 0x21dad60 VA: 0x75947f2d60
	public Boolean CheckPreAnnounceId(String announceId) { }
	// RVA: 0x21dacc8 VA: 0x75947f2cc8
	private String _GenPreAnnounceKey(String key) { }
	// RVA: 0x21dadf8 VA: 0x75947f2df8
	public Void AddRetroNewFlag(String retroId) { }
	// RVA: 0x21daf1c VA: 0x75947f2f1c
	public Boolean CheckRetroNewFlag(String retroId) { }
	// RVA: 0x21dae84 VA: 0x75947f2e84
	private String _GenRetroKey(String key) { }
	// RVA: 0x21dafb4 VA: 0x75947f2fb4
	public Void SetCharSortType(CharacterSortType sortType) { }
	// RVA: 0x21db0c0 VA: 0x75947f30c0
	public CharacterSortType GetCharSortType() { }
	// RVA: 0x21db1a0 VA: 0x75947f31a0
	public Boolean GetIsPlayerRepoStarTopMode(Int32 defaultType) { }
	// RVA: 0x21db244 VA: 0x75947f3244
	public Void SetPlayerRepoStarTopMode(Boolean isStarMarkTop) { }
	// RVA: 0x21db2dc VA: 0x75947f32dc
	public Boolean GetIfLoginDynEntrancePlayed(Int64 timestamp, String dynIllustId) { }
	// RVA: 0x21db5a8 VA: 0x75947f35a8
	public Void SetLoginDynEntrancePlayed(Int64 timestamp, String dynIllustId) { }
	// RVA: 0x21db398 VA: 0x75947f3398
	private Void _EnsurePlayedDynIllustCache(Int64 timestamp) { }
	// RVA: 0x21db6f8 VA: 0x75947f36f8
	public Boolean GetShowHomeBirthdaySetting() { }
	// RVA: 0x21db788 VA: 0x75947f3788
	public Void SetShowHomeBirthdaySetting(Boolean isShow) { }
	// RVA: 0x21db824 VA: 0x75947f3824
	public Void SetDiffGroupRewardAutoShow(Boolean ableToShow) { }
	// RVA: 0x21db8bc VA: 0x75947f38bc
	public Boolean GetDiffGroupRewardAutoShow() { }
	// RVA: 0x21db94c VA: 0x75947f394c
	public Void SetDiffGroupAutoSelect(StageDiffGroup diffGroup) { }
	// RVA: 0x21db9e4 VA: 0x75947f39e4
	public StageDiffGroup GetDiffGroupAutoSelect() { }
	// RVA: 0x21dba68 VA: 0x75947f3a68
	public Int32 get_DiffGroupAutoSelect() { }
	// RVA: 0x21dbaec VA: 0x75947f3aec
	public Void set_DiffGroupAutoSelect(Int32 value) { }
	// RVA: 0x21dbb8c VA: 0x75947f3b8c
	public Void SetSecretaryChangeSortType(CharacterSortType sortType) { }
	// RVA: 0x21dbc14 VA: 0x75947f3c14
	public CharacterSortType GetSecretaryChangeSortType() { }
	// RVA: 0x21dbc84 VA: 0x75947f3c84
	public Boolean GetIsPlayerSecretaryChangeStarTopMode() { }
	// RVA: 0x21dbd6c VA: 0x75947f3d6c
	public Void SetPlayerSecretaryChangeStarTopMode(Boolean isStarMarkTop) { }
	// RVA: 0x21dbe84 VA: 0x75947f3e84
	public Int32 GetPlayerCharSelectCustomSortTypeWithKey(String key, Int32 defaultType) { }
	// RVA: 0x21dbf30 VA: 0x75947f3f30
	public Void SetPlayerCharSelectCustomSortTypeWithKey(String key, Int32 customType) { }
	// RVA: 0x21dbfdc VA: 0x75947f3fdc
	public Boolean GetIsPlayerRepoFilterPanelShow() { }
	// RVA: 0x21dc06c VA: 0x75947f406c
	public Void SetIsPlayerRepoFilterPanelShow(Boolean isSortPanelShow) { }
	// RVA: 0x21dc104 VA: 0x75947f4104
	public Boolean GetIsPlayerCharSelectFilterPanelShow() { }
	// RVA: 0x21dc194 VA: 0x75947f4194
	public Void SetIsPlayerCharSelectFilterPanelShow(Boolean isFilterPanelShow) { }
	// RVA: 0x21dc22c VA: 0x75947f422c
	public Int32 GetPlayerStarMarkTopMode(Int32 defaultMode) { }
	// RVA: 0x21dc2c4 VA: 0x75947f42c4
	public Void SetPlayerStarMarkTopMode(Int32 defaultMode) { }
	// RVA: 0x21dc35c VA: 0x75947f435c
	public Boolean IsMultiplayerSquadCopied(String activityId, String groupId) { }
	// RVA: 0x21dc4a4 VA: 0x75947f44a4
	public Void SetMultiplayerSquadCopied(String activityId, String groupId) { }
	// RVA: 0x21dc400 VA: 0x75947f4400
	private String _GetMultiplayerSquadCopyKey(String activityId, String groupId) { }
	// RVA: 0x21dc53c VA: 0x75947f453c
	public Boolean IsAntiSpoilerVisited(String antiSpoilerId) { }
	// RVA: 0x21dc66c VA: 0x75947f466c
	public Void SetAntiSpoilerChecked(String antiSpoilerId) { }
	// RVA: 0x21dc5d4 VA: 0x75947f45d4
	private String _GetAntiSpoilerChecked(String antiSpoilerId) { }
	// RVA: 0x VA: 0x0
	public SquadType LoadRuneSquadCacheV1(String squadSaveKey) { }
	// RVA: 0x VA: 0x0
	public Void SaveRuneSquadCacheV1(String squadSaveKey, SquadType squadData) { }
	// RVA: 0x21dc6f8 VA: 0x75947f46f8
	public Boolean GuideOnlyCheckGuidebookViewed(String key) { }
	// RVA: 0x21dc828 VA: 0x75947f4828
	public Void GuideOnlyAddGuidebookViewed(String key) { }
	// RVA: 0x21dc790 VA: 0x75947f4790
	private String _GenGuidebookKey(String key) { }
	// RVA: 0x21dc8b4 VA: 0x75947f48b4
	public Boolean EnemyViewedCheck(String key) { }
	// RVA: 0x21dc9e4 VA: 0x75947f49e4
	public Void EnemyAddViewed(String key) { }
	// RVA: 0x21dc94c VA: 0x75947f494c
	private String _GenEnemyKey(String key) { }
	// RVA: 0x21dca70 VA: 0x75947f4a70
	public Boolean RecommendShopViewedCheck(String key) { }
	// RVA: 0x21dcba0 VA: 0x75947f4ba0
	public Void RecommendShopAddViewed(String key) { }
	// RVA: 0x21dcb08 VA: 0x75947f4b08
	private String _GenRecommendShopKey(String key) { }
	// RVA: 0x21dcc2c VA: 0x75947f4c2c
	public Int64 GetLastExtraClickTime(Int64 currentLastClick) { }
	// RVA: 0x21dccfc VA: 0x75947f4cfc
	public Void SetLastExtraClickTime(Int64 currentLastClick) { }
	// RVA: 0x21dcdac VA: 0x75947f4dac
	public Boolean AnnouceViewedCheck(String key) { }
	// RVA: 0x21dcedc VA: 0x75947f4edc
	public Void AnnounceAddViewed(String key) { }
	// RVA: 0x21dce44 VA: 0x75947f4e44
	private String _GenAnnounceKey(String key) { }
	// RVA: 0x21dcf68 VA: 0x75947f4f68
	public Void SetCampaignCachedRotateStageId(String stageId) { }
	// RVA: 0x21dd000 VA: 0x75947f5000
	public String GetCampaignCachedRotateStageId() { }
	// RVA: 0x21dd080 VA: 0x75947f5080
	public Void SetCampaignCachedBriefId(String briefId) { }
	// RVA: 0x21dd118 VA: 0x75947f5118
	public String GetCampaignCachedBriefId() { }
	// RVA: 0x21dd198 VA: 0x75947f5198
	public Dictionary`2 LoadStageCache() { }
	// RVA: 0x21dd23c VA: 0x75947f523c
	public Void SaveStageCache(Dictionary`2 localCache) { }
	// RVA: 0x21dd2f8 VA: 0x75947f52f8
	public Dictionary`2 LoadZoneCache() { }
	// RVA: 0x21dd39c VA: 0x75947f539c
	public Void SaveZoneCache(Dictionary`2 localCache) { }
	// RVA: 0x21dd458 VA: 0x75947f5458
	public ActivityLocalCache LoadActivityCache() { }
	// RVA: 0x21dd52c VA: 0x75947f552c
	public Void SaveActivityCache(ActivityLocalCache localCache) { }
	// RVA: 0x21dd5dc VA: 0x75947f55dc
	public Void SetStageContinuousBattleTimesCache(String stageId, Int32 times) { }
	// RVA: 0x21dd688 VA: 0x75947f5688
	public Int32 GetStageContinuousBattleTimesCache(String stageId) { }
	// RVA: 0x21dd774 VA: 0x75947f5774
	public Int64 GetLoginCharRotationUpdateTimeStamp() { }
	// RVA: 0x21dd8b8 VA: 0x75947f58b8
	public Void SetLoginCharRotationUpdateTimeStamp(Int64 timestamp) { }
	// RVA: 0x21dd984 VA: 0x75947f5984
	public CharRotationInfoSet GetCharRotationInfoSet() { }
	// RVA: 0x21dda4c VA: 0x75947f5a4c
	public Void SaveCharRotationInfoSet(String instId, List`1 skinList, Int32 displayIndex) { }
}
```