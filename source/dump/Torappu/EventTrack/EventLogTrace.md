# EventLogTrace

**Namespace:** `Torappu.EventTrack`


## Fields

- `EventLogHotUpdateContext m_context`

- `Boolean m_needToLogAvgStartInfo`

- `String m_avgEntryInfo`

- `String m_avgStoryId`

- `Int64 m_storyBeginTs`


## Methods

- `Void EventOnStartBuildingCharControl(String, Boolean, String)`

- `Void EventOnEndBuildingCharControl(String, Boolean, String)`

- `Void EventOnEnemyDuelEmoteClicked(String, String, String, Boolean)`

- `Void EventOnEnemyDuelAfterBattleToEntryClicked(String, String, String)`

- `Void EventOnEnemyDuelAfterBattleToRoomClicked(String, String, String)`

- `Void EventOnEnemyDuelAfterBattleToMatchClicked(String, String, String)`

- `Void EventOnHotUpdateDownloadStart(String, Int64, Boolean)`

- `Void EventOnHotUpdateCheckConsistencyStart(CheckType)`

- `Void RecordHotupdatePrecent(Single)`

- `Void RecordHotupdateDownloadFinish(Boolean)`

- `Void RecordCheckConsistencyFinish(CheckType)`

- `Void RecordDownloadInterrupt(LogTraceErrorCode)`

- `Void RecordCheckConsistencyFail(LogTraceErrorCode)`

- `Void RecordSelectMainPackMode(UpdatePreferenceType, String)`

- `Void RecordUpdateVoiceLangMode(List`1)`

- `Void RecordUpdateTypeList(IList`1)`

- `Void EventOnShopEntryClicked()`

- `Void EventOnGPShopItemClicked(String)`

- `Void EventOnGPShopTabClicked(String)`

- `Void EventOnSkinShopItemClicked(String)`

- `Void EventOnShopTitleClicked(ShopType)`

- `Void SetStoryStartInfo(String, Boolean)`

- `Void SetHandbookInfo(String)`

- `Void SetStoryReviewInfo(String)`

- `Void OnStoryBegin(String)`

- `Void OnStoryEnd(String, String)`

- `Void _LogToSDK(String, Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.EventTrack
public class EventLogTrace : Singleton`1
{
	private EventLogHotUpdateContext m_context; // 0x10
	public const String EVENT_NAME_START; // 0x0
	public const String EVENT_NAME_END; // 0x0
	public const String STORY_ONLY_FIRST_ENTRANCE_NAME; // 0x0
	public const String STORY_ONLY_REPEAT_ENTRANCE_NAME; // 0x0
	public const String HANDBOOK_STORY_ENTRANCE_NAME; // 0x0
	public const String STORY_MINI_REVIEW; // 0x0
	private Boolean m_needToLogAvgStartInfo; // 0x40
	private String m_avgEntryInfo; // 0x48
	private String m_avgStoryId; // 0x50
	private Int64 m_storyBeginTs; // 0x58
	private static DelegateBridge __Hotfix0_EventOnStartBuildingCharControl; // 0x0
	private static DelegateBridge __Hotfix0_EventOnEndBuildingCharControl; // 0x8
	private static DelegateBridge __Hotfix0_EventOnEnemyDuelEmoteClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnEnemyDuelAfterBattleToEntryClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnEnemyDuelAfterBattleToRoomClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnEnemyDuelAfterBattleToMatchClicked; // 0x28
	private static DelegateBridge __Hotfix0__GenPrefList; // 0x30
	private static DelegateBridge __Hotfix0_EventOnHotUpdateDownloadStart; // 0x38
	private static DelegateBridge __Hotfix0_EventOnHotUpdateCheckConsistencyStart; // 0x40
	private static DelegateBridge __Hotfix0_RecordHotupdatePrecent; // 0x48
	private static DelegateBridge __Hotfix0_RecordHotupdateDownloadFinish; // 0x50
	private static DelegateBridge __Hotfix0_RecordCheckConsistencyFinish; // 0x58
	private static DelegateBridge __Hotfix0_RecordDownloadInterrupt; // 0x60
	private static DelegateBridge __Hotfix0_RecordCheckConsistencyFail; // 0x68
	private static DelegateBridge __Hotfix0_RecordSelectMainPackMode; // 0x70
	private static DelegateBridge __Hotfix0_RecordUpdateVoiceLangMode; // 0x78
	private static DelegateBridge __Hotfix0_RecordUpdateTypeList; // 0x80
	private static DelegateBridge __Hotfix0_EventOnShopEntryClicked; // 0x88
	private static DelegateBridge __Hotfix0_EventOnGPShopItemClicked; // 0x90
	private static DelegateBridge __Hotfix0_EventOnGPShopTabClicked; // 0x98
	private static DelegateBridge __Hotfix0_EventOnSkinShopItemClicked; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnShopTitleClicked; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0
	private static DelegateBridge __Hotfix0_SetStoryStartInfo; // 0xb8
	private static DelegateBridge __Hotfix0_SetHandbookInfo; // 0xc0
	private static DelegateBridge __Hotfix0_SetStoryReviewInfo; // 0xc8
	private static DelegateBridge __Hotfix0_OnStoryBegin; // 0xd0
	private static DelegateBridge __Hotfix0_OnStoryEnd; // 0xd8
	private static DelegateBridge __Hotfix0__LogToSDK; // 0xe0


	// RVA: 0x3ee901c VA: 0x759650101c
	public Void EventOnStartBuildingCharControl(String charId, Boolean isOwn, String roomSlotId) { }
	// RVA: 0x3ee93e0 VA: 0x75965013e0
	public Void EventOnEndBuildingCharControl(String charId, Boolean isOwn, String roomSlotId) { }
	// RVA: 0x3ee95ec VA: 0x75965015ec
	public Void EventOnEnemyDuelEmoteClicked(String actId, String sceneId, String modeId, Boolean emoteOn) { }
	// RVA: 0x3ee9868 VA: 0x7596501868
	public Void EventOnEnemyDuelAfterBattleToEntryClicked(String actId, String sceneId, String modeId) { }
	// RVA: 0x3ee9aac VA: 0x7596501aac
	public Void EventOnEnemyDuelAfterBattleToRoomClicked(String actId, String sceneId, String modeId) { }
	// RVA: 0x3ee9cf0 VA: 0x7596501cf0
	public Void EventOnEnemyDuelAfterBattleToMatchClicked(String actId, String sceneId, String modeId) { }
	// RVA: 0x3ee9f34 VA: 0x7596501f34
	private List`1 _GenPrefList() { }
	// RVA: 0x3eea41c VA: 0x759650241c
	public Void EventOnHotUpdateDownloadStart(String versionId, Int64 srcSize, Boolean isPreMain) { }
	// RVA: 0x3eea6e8 VA: 0x75965026e8
	public Void EventOnHotUpdateCheckConsistencyStart(CheckType checkType) { }
	// RVA: 0x3eea950 VA: 0x7596502950
	public Void RecordHotupdatePrecent(Single percent) { }
	// RVA: 0x3eeabe4 VA: 0x7596502be4
	public Void RecordHotupdateDownloadFinish(Boolean ispremain) { }
	// RVA: 0x3eeae1c VA: 0x7596502e1c
	public Void RecordCheckConsistencyFinish(CheckType checkType) { }
	// RVA: 0x3eeb038 VA: 0x7596503038
	public Void RecordDownloadInterrupt(LogTraceErrorCode info) { }
	// RVA: 0x3eeb270 VA: 0x7596503270
	public Void RecordCheckConsistencyFail(LogTraceErrorCode info) { }
	// RVA: 0x3eeb4a8 VA: 0x75965034a8
	public Void RecordSelectMainPackMode(UpdatePreferenceType type, String size) { }
	// RVA: 0x3eeb6bc VA: 0x75965036bc
	public Void RecordUpdateVoiceLangMode(List`1 list) { }
	// RVA: 0x3eeb9e8 VA: 0x75965039e8
	public Void RecordUpdateTypeList(IList`1 srcList) { }
	// RVA: 0x3eebbd4 VA: 0x7596503bd4
	public Void EventOnShopEntryClicked() { }
	// RVA: 0x3eebdb4 VA: 0x7596503db4
	public Void EventOnGPShopItemClicked(String goodId) { }
	// RVA: 0x3eebfac VA: 0x7596503fac
	public Void EventOnGPShopTabClicked(String tabId) { }
	// RVA: 0x3eec1d0 VA: 0x75965041d0
	public Void EventOnSkinShopItemClicked(String skinId) { }
	// RVA: 0x3eec3c8 VA: 0x75965043c8
	public Void EventOnShopTitleClicked(ShopType type) { }
	// RVA: 0x3eec660 VA: 0x7596504660
	private Void .ctor() { }
	// RVA: 0x3eec6f0 VA: 0x75965046f0
	public Void SetStoryStartInfo(String storyId, Boolean isFirstTime) { }
	// RVA: 0x3eec8bc VA: 0x75965048bc
	public Void SetHandbookInfo(String storyId) { }
	// RVA: 0x3eeca64 VA: 0x7596504a64
	public Void SetStoryReviewInfo(String storyId) { }
	// RVA: 0x3eeccbc VA: 0x7596504cbc
	public Void OnStoryBegin(String storyId) { }
	// RVA: 0x3eecf4c VA: 0x7596504f4c
	public Void OnStoryEnd(String storyId, String errorMsg) { }
	// RVA: 0x3ee9228 VA: 0x7596501228
	private Void _LogToSDK(String eventName, Object data) { }
}
```