# GameAnalytics

**Namespace:** `Torappu`


## Fields

- `String m_channel`

- `String m_subChannel`

- `Boolean m_isInited`


## Methods

- `Boolean IsInited()`

- `Void Init(String, String)`

- `Void Register(String)`

- `Void LoginAccount(String, String)`

- `Void LoginGame()`

- `Void StopGame()`

- `Void OnSyncData()`

- `Void NewGuest(String)`

- `Void CreateRole(String, String)`

- `Void SetLevel(Int32)`

- `Void OnHotUpdateFinished()`

- `Void OnPaySucceed(String, String, Single, String)`

- `Void OnConfirmOrder(String, String)`

- `Void OnCreateOrder(String, Single, String)`

- `Void OnBattleStart(String)`

- `Void OnBattleEnd(String, Boolean, String)`

- `Void OnAdvancedGacha(String)`

- `Void OnNormalGacha(String)`

- `Void OnEvolve(String, EvolvePhase)`

- `Void OnPotentialBoost(String, Int32, Boolean)`

- `Void OnSkillMainLvlup(Int32, Int32, Int32)`

- `Void OnSkillSpecializedUp(Int32, Int32, Int32)`

- `Void OnStoryEnd(String)`

- `Void OnRoomUpgraded(RoomType, Int32)`

- `Void OnSendFriendRequest()`

- `Void OnFetchGpShop(List`1)`

- `Void OnFetchSkinShop(List`1)`

- `Void OnFetchCashShop(List`1)`

- `Void OnPurchaseClicked(String)`

- `Void OnPurchaseCompleted(String)`

- `Void OnApplicationPause(Boolean)`

- `Void OnApplicationQuit()`

- `Boolean _CheckIfInited()`

- `String _GetChannel()`

- `String _GetSubChannel()`

- `Boolean _TryGetCharIdByInstId(Int32, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GameAnalytics : PersistentSingleton`1
{
	private static String s_cachedPlatformStr; // 0x0
	private static Dictionary`2 s_cachedDeviceIdMap; // 0x8
	private const String CHANNEL_OFFICIAL; // 0x0
	private const String CURRENCY_TYPE_CNY; // 0x0
	private String m_channel; // 0x18
	private String m_subChannel; // 0x20
	private Boolean m_isInited; // 0x28
	private static DelegateBridge __Hotfix0_IsInited; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_Register; // 0x20
	private static DelegateBridge __Hotfix0_LoginAccount; // 0x28
	private static DelegateBridge __Hotfix0_LoginGame; // 0x30
	private static DelegateBridge __Hotfix0_StopGame; // 0x38
	private static DelegateBridge __Hotfix0_OnSyncData; // 0x40
	private static DelegateBridge __Hotfix0_NewGuest; // 0x48
	private static DelegateBridge __Hotfix0_CreateRole; // 0x50
	private static DelegateBridge __Hotfix0_SetLevel; // 0x58
	private static DelegateBridge __Hotfix0_OnHotUpdateFinished; // 0x60
	private static DelegateBridge __Hotfix0_OnPaySucceed; // 0x68
	private static DelegateBridge __Hotfix0_OnConfirmOrder; // 0x70
	private static DelegateBridge __Hotfix0_OnCreateOrder; // 0x78
	private static DelegateBridge __Hotfix0_OnBattleStart; // 0x80
	private static DelegateBridge __Hotfix0_OnBattleEnd; // 0x88
	private static DelegateBridge __Hotfix0_OnAdvancedGacha; // 0x90
	private static DelegateBridge __Hotfix0_OnNormalGacha; // 0x98
	private static DelegateBridge __Hotfix0_OnEvolve; // 0xa0
	private static DelegateBridge __Hotfix0_OnPotentialBoost; // 0xa8
	private static DelegateBridge __Hotfix0_OnSkillMainLvlup; // 0xb0
	private static DelegateBridge __Hotfix0_OnSkillSpecializedUp; // 0xb8
	private static DelegateBridge __Hotfix0_OnStoryEnd; // 0xc0
	private static DelegateBridge __Hotfix0_OnRoomUpgraded; // 0xc8
	private static DelegateBridge __Hotfix0_OnSendFriendRequest; // 0xd0
	private static DelegateBridge __Hotfix0_OnFetchGpShop; // 0xd8
	private static DelegateBridge __Hotfix0_OnFetchSkinShop; // 0xe0
	private static DelegateBridge __Hotfix0_OnFetchCashShop; // 0xe8
	private static DelegateBridge __Hotfix0_OnPurchaseClicked; // 0xf0
	private static DelegateBridge __Hotfix0_OnPurchaseCompleted; // 0xf8
	private static DelegateBridge __Hotfix0_OnApplicationPause; // 0x100
	private static DelegateBridge __Hotfix0_OnApplicationQuit; // 0x108
	private static DelegateBridge __Hotfix0__CheckIfInited; // 0x110
	private static DelegateBridge __Hotfix0__GetChannel; // 0x118
	private static DelegateBridge __Hotfix0__GetSubChannel; // 0x120
	private static DelegateBridge __Hotfix0__TryGetCharIdByInstId; // 0x128
	private static DelegateBridge __Hotfix0_GetDeviceIdMap; // 0x130
	private static DelegateBridge __Hotfix0_GetOfficialDeviceId; // 0x138
	private static DelegateBridge __Hotfix0__GetPlatformStr; // 0x140
	private static DelegateBridge __Hotfix0_RecordReplayAvgLogClick; // 0x148
	private static DelegateBridge __Hotfix0_RecordBattleAvgLog; // 0x150
	private static DelegateBridge __Hotfix0_RecordMiniReviewClick; // 0x158
	private static DelegateBridge __Hotfix0_RecordHookBattleAvg; // 0x160
	private static DelegateBridge __Hotfix0_RecordHandbookStart; // 0x168
	private static DelegateBridge __Hotfix0_RecordStartStory; // 0x170
	private static DelegateBridge __Hotfix0_RecordStoryFinish; // 0x178
	private static DelegateBridge __Hotfix0_RecordHotUpdateDownloadStart; // 0x180
	private static DelegateBridge __Hotfix0_RecordHotUpdateCheckConsistencyStart; // 0x188
	private static DelegateBridge __Hotfix0_RecordHotupdatePrecent; // 0x190
	private static DelegateBridge __Hotfix0_RecordHotUpdateDownloadFinish; // 0x198
	private static DelegateBridge __Hotfix0_RecordHotUpdateCheckConsistencyFinish; // 0x1a0
	private static DelegateBridge __Hotfix0_RecordHotupdateDownloadError; // 0x1a8
	private static DelegateBridge __Hotfix0_RecordHotupdateDownloadInterrupt; // 0x1b0
	private static DelegateBridge __Hotfix0_RecordHotUpdateCheckConsistencyError; // 0x1b8
	private static DelegateBridge __Hotfix0_RecordSelectMainPackMode; // 0x1c0
	private static DelegateBridge __Hotfix0_RecordUpdateVoiceLangMode; // 0x1c8
	private static DelegateBridge __Hotfix0_RecordResTypeListChange; // 0x1d0
	private static DelegateBridge __Hotfix0_RecordShopEntryClick; // 0x1d8
	private static DelegateBridge __Hotfix0_RecordShopTitleClick; // 0x1e0
	private static DelegateBridge __Hotfix0_RecordGPShopItemClick; // 0x1e8
	private static DelegateBridge __Hotfix0_RecordGPShopTabClick; // 0x1f0
	private static DelegateBridge __Hotfix0_RecordSkinShopItemClick; // 0x1f8
	private static DelegateBridge __Hotfix0_RecordBuildingCharStartControl; // 0x200
	private static DelegateBridge __Hotfix0_RecordBuildingCharEndControl; // 0x208
	private static DelegateBridge __Hotfix0_RecordEnemyDuelEmoteClicked; // 0x210
	private static DelegateBridge __Hotfix0_RecordEnemyDuelAfterBattleToEntryClicked; // 0x218
	private static DelegateBridge __Hotfix0_RecordEnemyDuelAfterBattleToRoomClicked; // 0x220
	private static DelegateBridge __Hotfix0_RecordEnemyDuelAfterBattleToMatchClicked; // 0x228
	private static DelegateBridge _c__Hotfix0_ctor; // 0x230


	// RVA: 0x2c2e210 VA: 0x7595246210
	public Boolean IsInited() { }
	// RVA: 0x2c2e278 VA: 0x7595246278
	public Void Init(String channel, String subChannel) { }
	// RVA: 0x2c2e40c VA: 0x759524640c
	public Void Register(String channelUid) { }
	// RVA: 0x2c2e5c4 VA: 0x75952465c4
	public Void LoginAccount(String uid, String username) { }
	// RVA: 0x2c2e7d8 VA: 0x75952467d8
	public Void LoginGame() { }
	// RVA: 0x2c2e898 VA: 0x7595246898
	public Void StopGame() { }
	// RVA: 0x2c2e9e0 VA: 0x75952469e0
	public Void OnSyncData() { }
	// RVA: 0x2c2eaa4 VA: 0x7595246aa4
	public Void NewGuest(String channelUid) { }
	// RVA: 0x2c2eb20 VA: 0x7595246b20
	public Void CreateRole(String nickname, String uid) { }
	// RVA: 0x2c2eca8 VA: 0x7595246ca8
	public Void SetLevel(Int32 level) { }
	// RVA: 0x2c2ed24 VA: 0x7595246d24
	public Void OnHotUpdateFinished() { }
	// RVA: 0x2c2ed8c VA: 0x7595246d8c
	public Void OnPaySucceed(String transactionId, String paymentType, Single currencyAmount, String currencyType) { }
	// RVA: 0x2c2eec8 VA: 0x7595246ec8
	public Void OnConfirmOrder(String orderId, String productId) { }
	// RVA: 0x2c2ef48 VA: 0x7595246f48
	public Void OnCreateOrder(String transactionId, Single currencyAmount, String currencyType) { }
	// RVA: 0x2c2eff8 VA: 0x7595246ff8
	public Void OnBattleStart(String stageId) { }
	// RVA: 0x2c2f074 VA: 0x7595247074
	public Void OnBattleEnd(String stageId, Boolean success, String reason) { }
	// RVA: 0x2c2f10c VA: 0x759524710c
	public Void OnAdvancedGacha(String charId) { }
	// RVA: 0x2c2f188 VA: 0x7595247188
	public Void OnNormalGacha(String charId) { }
	// RVA: 0x2c2f204 VA: 0x7595247204
	public Void OnEvolve(String charId, EvolvePhase phase) { }
	// RVA: 0x2c2f288 VA: 0x7595247288
	public Void OnPotentialBoost(String charId, Int32 potentialRank, Boolean succeed) { }
	// RVA: 0x2c2f320 VA: 0x7595247320
	public Void OnSkillMainLvlup(Int32 charInstId, Int32 skillIndex, Int32 mainSkillLvl) { }
	// RVA: 0x2c2f3b8 VA: 0x75952473b8
	public Void OnSkillSpecializedUp(Int32 charInstId, Int32 skillIndex, Int32 specializeLvl) { }
	// RVA: 0x2c2f450 VA: 0x7595247450
	public Void OnStoryEnd(String storyId) { }
	// RVA: 0x2c2f4c8 VA: 0x75952474c8
	public Void OnRoomUpgraded(RoomType roomType, Int32 roomLevel) { }
	// RVA: 0x2c2f548 VA: 0x7595247548
	public Void OnSendFriendRequest() { }
	// RVA: 0x2c2f5ac VA: 0x75952475ac
	public Void OnFetchGpShop(List`1 gpItems) { }
	// RVA: 0x2c2f624 VA: 0x7595247624
	public Void OnFetchSkinShop(List`1 skinItems) { }
	// RVA: 0x2c2f69c VA: 0x759524769c
	public Void OnFetchCashShop(List`1 cashItems) { }
	// RVA: 0x2c2f714 VA: 0x7595247714
	public Void OnPurchaseClicked(String goodId) { }
	// RVA: 0x2c2f78c VA: 0x759524778c
	public Void OnPurchaseCompleted(String goodId) { }
	// RVA: 0x2c2f804 VA: 0x7595247804
	private Void OnApplicationPause(Boolean pause) { }
	// RVA: 0x2c2f87c VA: 0x759524787c
	private Void OnApplicationQuit() { }
	// RVA: 0x2c2e488 VA: 0x7595246488
	private Boolean _CheckIfInited() { }
	// RVA: 0x2c2f8e0 VA: 0x75952478e0
	private String _GetChannel() { }
	// RVA: 0x2c2e3a4 VA: 0x75952463a4
	private String _GetSubChannel() { }
	// RVA: 0x2c2f948 VA: 0x7595247948
	private Boolean _TryGetCharIdByInstId(Int32 charInstId, out String charId) { }
	// RVA: 0x2c2fb28 VA: 0x7595247b28
	public static Dictionary`2 GetDeviceIdMap() { }
	// RVA: 0x2c2fc8c VA: 0x7595247c8c
	public static String GetOfficialDeviceId() { }
	// RVA: 0x2c2fd98 VA: 0x7595247d98
	private static String _GetPlatformStr() { }
	// RVA: 0x2c2fe68 VA: 0x7595247e68
	public static Void RecordReplayAvgLogClick(String storyId) { }
	// RVA: 0x2c2fefc VA: 0x7595247efc
	public static Void RecordBattleAvgLog(String storyId, Boolean isFirstTime) { }
	// RVA: 0x2c2ffa4 VA: 0x7595247fa4
	public static Void RecordMiniReviewClick(String storyId) { }
	// RVA: 0x2c30034 VA: 0x7595248034
	public static Void RecordHookBattleAvg(String storyId) { }
	// RVA: 0x2c300c8 VA: 0x75952480c8
	public static Void RecordHandbookStart(String storyId) { }
	// RVA: 0x2c30158 VA: 0x7595248158
	public static Void RecordStartStory(String storyId) { }
	// RVA: 0x2c301e8 VA: 0x75952481e8
	public static Void RecordStoryFinish(String storyId, String errorMsg) { }
	// RVA: 0x2c30290 VA: 0x7595248290
	public static Void RecordHotUpdateDownloadStart(String srcList, Int64 srcSize, Boolean isPreMain) { }
	// RVA: 0x2c30344 VA: 0x7595248344
	public static Void RecordHotUpdateCheckConsistencyStart(CheckType checkType) { }
	// RVA: 0x2c303d4 VA: 0x75952483d4
	public static Void RecordHotupdatePrecent(Single percent) { }
	// RVA: 0x2c30470 VA: 0x7595248470
	public static Void RecordHotUpdateDownloadFinish(Boolean isPreMain) { }
	// RVA: 0x2c30500 VA: 0x7595248500
	public static Void RecordHotUpdateCheckConsistencyFinish(CheckType checkType) { }
	// RVA: 0x2c30590 VA: 0x7595248590
	public static Void RecordHotupdateDownloadError(LogTraceErrorCode errorInfo) { }
	// RVA: 0x2c30620 VA: 0x7595248620
	public static Void RecordHotupdateDownloadInterrupt() { }
	// RVA: 0x2c306a8 VA: 0x75952486a8
	public static Void RecordHotUpdateCheckConsistencyError() { }
	// RVA: 0x2c30730 VA: 0x7595248730
	public static Void RecordSelectMainPackMode(UpdatePreferenceType type, String size) { }
	// RVA: 0x2c307d8 VA: 0x75952487d8
	public static Void RecordUpdateVoiceLangMode(List`1 list) { }
	// RVA: 0x2c30868 VA: 0x7595248868
	public static Void RecordResTypeListChange(IList`1 typeList) { }
	// RVA: 0x2c308f8 VA: 0x75952488f8
	public static Void RecordShopEntryClick() { }
	// RVA: 0x2c3097c VA: 0x759524897c
	public static Void RecordShopTitleClick(ShopType shopType) { }
	// RVA: 0x2c30a0c VA: 0x7595248a0c
	public static Void RecordGPShopItemClick(String goodId) { }
	// RVA: 0x2c30a9c VA: 0x7595248a9c
	public static Void RecordGPShopTabClick(String tabId) { }
	// RVA: 0x2c30b2c VA: 0x7595248b2c
	public static Void RecordSkinShopItemClick(String skinId) { }
	// RVA: 0x2c30bbc VA: 0x7595248bbc
	public static Void RecordBuildingCharStartControl(String charId, Boolean isOwn, String roomSlotId) { }
	// RVA: 0x2c30c70 VA: 0x7595248c70
	public static Void RecordBuildingCharEndControl(String charId, Boolean isOwn, String roomSlotId) { }
	// RVA: 0x2c30d24 VA: 0x7595248d24
	public static Void RecordEnemyDuelEmoteClicked(String actId, String sceneId, String modeId, Boolean emoteOn) { }
	// RVA: 0x2c30df0 VA: 0x7595248df0
	public static Void RecordEnemyDuelAfterBattleToEntryClicked(String actId, String sceneId, String modeId) { }
	// RVA: 0x2c30ea4 VA: 0x7595248ea4
	public static Void RecordEnemyDuelAfterBattleToRoomClicked(String actId, String sceneId, String modeId) { }
	// RVA: 0x2c30f58 VA: 0x7595248f58
	public static Void RecordEnemyDuelAfterBattleToMatchClicked(String actId, String sceneId, String modeId) { }
	// RVA: 0x2c3100c VA: 0x759524900c
	public Void .ctor() { }
}
```