# HomeMainState

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeMainStateBean _stateBean`

- `Text _versionLabel`

- `Text _nickname`

- `HomeMainTextWidgetHolder _mainlineProgress`

- `HomeAPFloatView _apFloat`

- `HomeDiamondChangeView _diamondChangeView`

- `UIAnimation _homeLoadAnim`

- `PanelActivityViewController _activityController`

- `HomeMainInventoryCountDownView _inventoryCountDownView`

- `HomeMainShopCountDownView _shopCountDownView`

- `HomeActivityOnBattleView _actOnBattleView`

- `HomeMainGachaNoticeView _gachaNoticeView`

- `UIHomeThemeTrackPoint _mailTrackPoint`

- `UIHomeThemeTrackPoint _recruitTrackPoint`

- `UIHomeThemeTrackPoint _characterRepoTrackPoint`

- `UIHomeThemeTrackPoint _infoPolyTrackPoint`

- `HomeBuildingTrackPoint _buildingTrackPoint`

- `UIHomeThemeTrackPoint _missionTrackPoint`

- `UIHomeThemeTrackPoint _friendTrackPoint`

- `UIHomeThemeTrackPoint _OpenServerTrackPoint`

- `UIHomeThemeTrackPoint _returnTrackPoint`

- `UIHomeThemeTrackPoint _announceTrackPoint`

- `UIHomeThemeTrackPoint _apItemTrackPoint`

- `UIHomeThemeTrackPoint _shopTrackPoint`

- `UIHomeThemeTrackPoint _illustTrackPoint`

- `Button _buildingEntry`

- `Button _shopEntry`

- `Button _handbookEntry`

- `GameObject _openServerEntry`

- `GameObject _returnningEntry`

- `TwoStateToggle _returnningEntryToggle`

- `Button _friendEntry`

- `Button _missionEntry`

- `Color _normalFuncBtnColor`

- `Color _pressedFuncBtnColor`

- `Color _lockedFuncBtnColor`

- `ActivityTopBarHolder _activityTopBarHolder`

- `Single _dialogueMaxHeight`

- `Single _dialoguePaddingHeight`

- `UIBlocker m_blocker`

- `Int32 m_instId`

- `Boolean m_isInited`


## Methods

- `Void _ResumeHomeImpl()`

- `Void OnDestroy()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void EventOnStageClick()`

- `Void EventOnCheckInClick()`

- `Void EventOnShopClick()`

- `Void EventOnFriendClick()`

- `Void EventOnMissionClick()`

- `Void EventOnSquadClick()`

- `Void EventOnHandbookClick()`

- `Void EventOnCharacterRepoClick()`

- `Void EventOnAdvancedRecruitClick()`

- `Void EventOnNormalRecruitClick()`

- `Void EventOnClickActivity(String)`

- `Void EventOnItemRepoClick()`

- `Void EventOnMailClick()`

- `Void EventOnHomeIllustClick()`

- `Void EventOnHomeIllustPreviewClick()`

- `Void EventOnAnouncementClick()`

- `Void EventOnSettingClick()`

- `Void EventOnOpenSeverClick()`

- `Void EventOnReturnningClick()`

- `Void EventOnBuyApClick()`

- `Void EventOnExchangeDiamondClick()`

- `Void EventOnBuyApFinish()`

- `Void EventOnExchangeFinish()`

- `Void EventOnRefreshResource(IStateBean)`

- `Void EventOnBuildingClick()`

- `Void EventOnAddDiamondClicked()`

- `Void _LoadHomeBackgroundAndTheme()`

- `Void _BindTrackPoints()`

- `Void _UpdateFuncLockStatus()`

- `Void _InitIfNot()`

- `Void _InitialRender()`

- `Void _OnJumpToActivity(String)`

- `Void _OnJumpToCrisisV2(String)`

- `Void _OnJumpToRoguelike(String)`

- `Void _OnJumpToMainline(String)`

- `Void _OnJumpToSandboxPerm(String)`

- `Void _JumpToSandboxEntryView(String)`

- `Boolean _ShouldTriggerAvg()`

- `Void _TriggerUniEquipAvg()`

- `Void _UniqEquipGuideEndCallback(Story)`

- `Boolean _HandleAutoPopupEvent(AutoPopupItem)`

- `Void NotifyPageRoutedFromNonPluginPage(Boolean)`

- `Void _SyncPlayerStatus()`

- `Void _ErrorWhenCrossDayFailed()`

- `Void _ProcessPlayerStatus()`

- `Void _UpdateAutoPopups()`

- `Void _PlayerDataRelatedRender()`

- `Void _UpdateLockTargetButtonStatus(Button, Boolean)`

- `Void _ShowAnnouncement()`

- `Void _ShowCheckin()`

- `Void _ShowBirthdaySetting()`

- `Void _ShowOpenServer()`

- `Void _ShowReturnPage()`

- `Void _ShowHomeActivity(String)`

- `Void _ShowHomeActivityAvg(String)`

- `Void _ShowHomeBackgroundPreview()`

- `Void _ShowUnFinishedOrders()`

- `Void _ShowHomeCharRotation()`

- `Void _AddPopupState()`

- `Void _LoadIllustView(DisplayHandler)`

- `Void _DisposeIllustConfig()`

- `Boolean _CheckIfHomePageActive()`

- `Void _OnRoutedFromIllustRelatedStates(IStateBean)`

- `Void <RegisterFromDataListener>b__51_0(IStateBean)`

- `Void <_SyncPlayerStatus>b__97_0(PlayerSyncStatusViewModel, Boolean)`

- `Void <_AddPopupState>b__113_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMainState : State, IValueMsgReceiver
{
	private const Int32 SYNC_STATUS_INTERVAL_COUNT; // 0x0
	private const Int32 SYNC_STATUS_INTERVAL_MINUTES; // 0x0
	public const Int32 ON_ROUTE_TO_ZONE; // 0x0
	private HomeMainStateBean _stateBean; // 0x50
	private Text _versionLabel; // 0x58
	private Text _nickname; // 0x60
	private HomeMainTextWidgetHolder _mainlineProgress; // 0x68
	private HomeAPFloatView _apFloat; // 0x70
	private HomeDiamondChangeView _diamondChangeView; // 0x78
	private UIAnimation _homeLoadAnim; // 0x80
	private PanelActivityViewController _activityController; // 0x88
	private HomeMainInventoryCountDownView _inventoryCountDownView; // 0x90
	private HomeMainShopCountDownView _shopCountDownView; // 0x98
	private HomeActivityOnBattleView _actOnBattleView; // 0xa0
	private HomeMainGachaNoticeView _gachaNoticeView; // 0xa8
	private UIHomeThemeTrackPoint _mailTrackPoint; // 0xb0
	private UIHomeThemeTrackPoint _recruitTrackPoint; // 0xb8
	private UIHomeThemeTrackPoint _characterRepoTrackPoint; // 0xc0
	private UIHomeThemeTrackPoint _infoPolyTrackPoint; // 0xc8
	private HomeBuildingTrackPoint _buildingTrackPoint; // 0xd0
	private UIHomeThemeTrackPoint _missionTrackPoint; // 0xd8
	private UIHomeThemeTrackPoint _friendTrackPoint; // 0xe0
	private UIHomeThemeTrackPoint _OpenServerTrackPoint; // 0xe8
	private UIHomeThemeTrackPoint _returnTrackPoint; // 0xf0
	private UIHomeThemeTrackPoint _announceTrackPoint; // 0xf8
	private UIHomeThemeTrackPoint _apItemTrackPoint; // 0x100
	private UIHomeThemeTrackPoint _shopTrackPoint; // 0x108
	private UIHomeThemeTrackPoint _illustTrackPoint; // 0x110
	private Button _buildingEntry; // 0x118
	private Button _shopEntry; // 0x120
	private Button _handbookEntry; // 0x128
	private GameObject _openServerEntry; // 0x130
	private GameObject _returnningEntry; // 0x138
	private TwoStateToggle _returnningEntryToggle; // 0x140
	private Button _friendEntry; // 0x148
	private Button _missionEntry; // 0x150
	private Color _normalFuncBtnColor; // 0x158
	private Color _pressedFuncBtnColor; // 0x168
	private Color _lockedFuncBtnColor; // 0x178
	private ActivityTopBarHolder _activityTopBarHolder; // 0x188
	private Single _dialogueMaxHeight; // 0x190
	private Single _dialoguePaddingHeight; // 0x194
	private UIBlocker m_blocker; // 0x198
	private Int32 m_instId; // 0x1a0
	private Boolean m_isInited; // 0x1a4
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__ResumeHomeImpl; // 0x18
	private static DelegateBridge __Hotfix0_OnPause; // 0x20
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x28
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x30
	private static DelegateBridge __Hotfix0_OnExit; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge __Hotfix0_OnMessage; // 0x48
	private static DelegateBridge __Hotfix0_EventOnStageClick; // 0x50
	private static DelegateBridge __Hotfix0_EventOnCheckInClick; // 0x58
	private static DelegateBridge __Hotfix0_EventOnShopClick; // 0x60
	private static DelegateBridge __Hotfix0_EventOnFriendClick; // 0x68
	private static DelegateBridge __Hotfix0_EventOnMissionClick; // 0x70
	private static DelegateBridge __Hotfix0_EventOnSquadClick; // 0x78
	private static DelegateBridge __Hotfix0_EventOnHandbookClick; // 0x80
	private static DelegateBridge __Hotfix0_EventOnCharacterRepoClick; // 0x88
	private static DelegateBridge __Hotfix0_EventOnAdvancedRecruitClick; // 0x90
	private static DelegateBridge __Hotfix0_EventOnNormalRecruitClick; // 0x98
	private static DelegateBridge __Hotfix0_EventOnClickActivity; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnItemRepoClick; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnMailClick; // 0xb0
	private static DelegateBridge __Hotfix0_EventOnHomeIllustClick; // 0xb8
	private static DelegateBridge __Hotfix0_EventOnHomeIllustPreviewClick; // 0xc0
	private static DelegateBridge __Hotfix0_EventOnAnouncementClick; // 0xc8
	private static DelegateBridge __Hotfix0_EventOnSettingClick; // 0xd0
	private static DelegateBridge __Hotfix0_EventOnOpenSeverClick; // 0xd8
	private static DelegateBridge __Hotfix0_EventOnReturnningClick; // 0xe0
	private static DelegateBridge __Hotfix0_EventOnBuyApClick; // 0xe8
	private static DelegateBridge __Hotfix0_EventOnExchangeDiamondClick; // 0xf0
	private static DelegateBridge __Hotfix0_EventOnBuyApFinish; // 0xf8
	private static DelegateBridge __Hotfix0_EventOnExchangeFinish; // 0x100
	private static DelegateBridge __Hotfix0_EventOnRefreshResource; // 0x108
	private static DelegateBridge __Hotfix0_EventOnBuildingClick; // 0x110
	private static DelegateBridge __Hotfix0_EventOnAddDiamondClicked; // 0x118
	private static DelegateBridge __Hotfix0__LoadHomeBackgroundAndTheme; // 0x120
	private static DelegateBridge __Hotfix0__BindTrackPoints; // 0x128
	private static DelegateBridge __Hotfix0__UpdateFuncLockStatus; // 0x130
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x138
	private static DelegateBridge __Hotfix0__InitialRender; // 0x140
	private static DelegateBridge __Hotfix0__OnJumpToActivity; // 0x148
	private static DelegateBridge __Hotfix0__OnJumpToCrisisV2; // 0x150
	private static DelegateBridge __Hotfix0__OnJumpToRoguelike; // 0x158
	private static DelegateBridge __Hotfix0__OnJumpToMainline; // 0x160
	private static DelegateBridge __Hotfix0__OnJumpToSandboxPerm; // 0x168
	private static DelegateBridge __Hotfix0__JumpToSandboxEntryView; // 0x170
	private static DelegateBridge __Hotfix0__ShouldTriggerAvg; // 0x178
	private static DelegateBridge __Hotfix0__TriggerUniEquipAvg; // 0x180
	private static DelegateBridge __Hotfix0__UniqEquipGuideEndCallback; // 0x188
	private static DelegateBridge __Hotfix0__HandleAutoPopupEvent; // 0x190
	private static DelegateBridge __Hotfix0_NotifyPageRoutedFromNonPluginPage; // 0x198
	private static DelegateBridge __Hotfix0__SyncPlayerStatus; // 0x1a0
	private static DelegateBridge __Hotfix0__ErrorWhenCrossDayFailed; // 0x1a8
	private static DelegateBridge __Hotfix0__ProcessPlayerStatus; // 0x1b0
	private static DelegateBridge __Hotfix0__UpdateAutoPopups; // 0x1b8
	private static DelegateBridge __Hotfix0__PlayerDataRelatedRender; // 0x1c0
	private static DelegateBridge __Hotfix0__UpdateLockTargetButtonStatus; // 0x1c8
	private static DelegateBridge __Hotfix0__ShowAnnouncement; // 0x1d0
	private static DelegateBridge __Hotfix0__ShowCheckin; // 0x1d8
	private static DelegateBridge __Hotfix0__ShowBirthdaySetting; // 0x1e0
	private static DelegateBridge __Hotfix0__ShowOpenServer; // 0x1e8
	private static DelegateBridge __Hotfix0__ShowReturnPage; // 0x1f0
	private static DelegateBridge __Hotfix0__ShowHomeActivity; // 0x1f8
	private static DelegateBridge __Hotfix0__ShowHomeActivityAvg; // 0x200
	private static DelegateBridge __Hotfix0__ShowHomeBackgroundPreview; // 0x208
	private static DelegateBridge __Hotfix0__ShowUnFinishedOrders; // 0x210
	private static DelegateBridge __Hotfix0__ShowHomeCharRotation; // 0x218
	private static DelegateBridge __Hotfix0__AddPopupState; // 0x220
	private static DelegateBridge __Hotfix0__LoadIllustView; // 0x228
	private static DelegateBridge __Hotfix0__DisposeIllustConfig; // 0x230
	private static DelegateBridge __Hotfix0__CheckIfHomePageActive; // 0x238
	private static DelegateBridge __Hotfix0__OnRoutedFromIllustRelatedStates; // 0x240
	private static DelegateBridge _c__Hotfix0_ctor; // 0x248


	// RVA: 0x27f88e0 VA: 0x7594e108e0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27f8948 VA: 0x7594e10948
	protected override Void OnEnter() { }
	// RVA: 0x27f93ec VA: 0x7594e113ec
	protected override Void OnResume() { }
	// RVA: 0x27f9528 VA: 0x7594e11528
	private Void _ResumeHomeImpl() { }
	// RVA: 0x27f9998 VA: 0x7594e11998
	protected override Void OnPause() { }
	// RVA: 0x27f9a98 VA: 0x7594e11a98
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x27f9b10 VA: 0x7594e11b10
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x27f9e38 VA: 0x7594e11e38
	protected override Void OnExit() { }
	// RVA: 0x27f9fa8 VA: 0x7594e11fa8
	private Void OnDestroy() { }
	// RVA: 0x27fa044 VA: 0x7594e12044
	public Void OnMessage(Int32 index, ValueBundle value) { }
	// RVA: 0x27fa1f8 VA: 0x7594e121f8
	public Void EventOnStageClick() { }
	// RVA: 0x27fa290 VA: 0x7594e12290
	public Void EventOnCheckInClick() { }
	// RVA: 0x27fa448 VA: 0x7594e12448
	public Void EventOnShopClick() { }
	// RVA: 0x27fa510 VA: 0x7594e12510
	public Void EventOnFriendClick() { }
	// RVA: 0x27fa5d0 VA: 0x7594e125d0
	public Void EventOnMissionClick() { }
	// RVA: 0x27fa690 VA: 0x7594e12690
	public Void EventOnSquadClick() { }
	// RVA: 0x27fa7e4 VA: 0x7594e127e4
	public Void EventOnHandbookClick() { }
	// RVA: 0x27fa960 VA: 0x7594e12960
	public Void EventOnCharacterRepoClick() { }
	// RVA: 0x27faab4 VA: 0x7594e12ab4
	public Void EventOnAdvancedRecruitClick() { }
	// RVA: 0x27fac08 VA: 0x7594e12c08
	public Void EventOnNormalRecruitClick() { }
	// RVA: 0x27fad5c VA: 0x7594e12d5c
	public Void EventOnClickActivity(String activityId) { }
	// RVA: 0x27faf28 VA: 0x7594e12f28
	public Void EventOnItemRepoClick() { }
	// RVA: 0x27fafc0 VA: 0x7594e12fc0
	public Void EventOnMailClick() { }
	// RVA: 0x27fb058 VA: 0x7594e13058
	public Void EventOnHomeIllustClick() { }
	// RVA: 0x27fb158 VA: 0x7594e13158
	public Void EventOnHomeIllustPreviewClick() { }
	// RVA: 0x27fb258 VA: 0x7594e13258
	public Void EventOnAnouncementClick() { }
	// RVA: 0x27fb3f8 VA: 0x7594e133f8
	public Void EventOnSettingClick() { }
	// RVA: 0x27fb490 VA: 0x7594e13490
	public Void EventOnOpenSeverClick() { }
	// RVA: 0x27fb590 VA: 0x7594e13590
	public Void EventOnReturnningClick() { }
	// RVA: 0x27fb690 VA: 0x7594e13690
	public Void EventOnBuyApClick() { }
	// RVA: 0x27fb714 VA: 0x7594e13714
	public Void EventOnExchangeDiamondClick() { }
	// RVA: 0x27fb798 VA: 0x7594e13798
	public Void EventOnBuyApFinish() { }
	// RVA: 0x27fb83c VA: 0x7594e1383c
	public Void EventOnExchangeFinish() { }
	// RVA: 0x27fb8b0 VA: 0x7594e138b0
	public Void EventOnRefreshResource(IStateBean stateBean) { }
	// RVA: 0x27fb938 VA: 0x7594e13938
	public Void EventOnBuildingClick() { }
	// RVA: 0x27fbab4 VA: 0x7594e13ab4
	public Void EventOnAddDiamondClicked() { }
	// RVA: 0x27f8b48 VA: 0x7594e10b48
	private Void _LoadHomeBackgroundAndTheme() { }
	// RVA: 0x27f8ca4 VA: 0x7594e10ca4
	private Void _BindTrackPoints() { }
	// RVA: 0x27f8e9c VA: 0x7594e10e9c
	private Void _UpdateFuncLockStatus() { }
	// RVA: 0x27f8ac4 VA: 0x7594e10ac4
	private Void _InitIfNot() { }
	// RVA: 0x27f8f9c VA: 0x7594e10f9c
	private Void _InitialRender() { }
	// RVA: 0x27fbd34 VA: 0x7594e13d34
	private Void _OnJumpToActivity(String activityId) { }
	// RVA: 0x27fbe18 VA: 0x7594e13e18
	private Void _OnJumpToCrisisV2(String seasonId) { }
	// RVA: 0x27fbf3c VA: 0x7594e13f3c
	private Void _OnJumpToRoguelike(String topicId) { }
	// RVA: 0x27fa0f0 VA: 0x7594e120f0
	private Void _OnJumpToMainline(String zoneId) { }
	// RVA: 0x27fc064 VA: 0x7594e14064
	private Void _OnJumpToSandboxPerm(String topicId) { }
	// RVA: 0x27fc144 VA: 0x7594e14144
	private Void _JumpToSandboxEntryView(String topicId) { }
	// RVA: 0x27fc1e8 VA: 0x7594e141e8
	private Boolean _ShouldTriggerAvg() { }
	// RVA: 0x27fc2b0 VA: 0x7594e142b0
	private Void _TriggerUniEquipAvg() { }
	// RVA: 0x27fc38c VA: 0x7594e1438c
	private Void _UniqEquipGuideEndCallback(Story story) { }
	// RVA: 0x27fc46c VA: 0x7594e1446c
	private Boolean _HandleAutoPopupEvent(AutoPopupItem popup) { }
	// RVA: 0x27fc8cc VA: 0x7594e148cc
	public Void NotifyPageRoutedFromNonPluginPage(Boolean playedDynEntranceWhenRouted) { }
	// RVA: 0x27fc9dc VA: 0x7594e149dc
	private Void _SyncPlayerStatus() { }
	// RVA: 0x27fcac0 VA: 0x7594e14ac0
	private Void _ErrorWhenCrossDayFailed() { }
	// RVA: 0x27fcc20 VA: 0x7594e14c20
	private Void _ProcessPlayerStatus() { }
	// RVA: 0x27fcdbc VA: 0x7594e14dbc
	private Void _UpdateAutoPopups() { }
	// RVA: 0x27f9868 VA: 0x7594e11868
	private Void _PlayerDataRelatedRender() { }
	// RVA: 0x27fbb94 VA: 0x7594e13b94
	private Void _UpdateLockTargetButtonStatus(Button button, Boolean isUnlocked) { }
	// RVA: 0x27fb2d8 VA: 0x7594e132d8
	private Void _ShowAnnouncement() { }
	// RVA: 0x27fa310 VA: 0x7594e12310
	private Void _ShowCheckin() { }
	// RVA: 0x27fc630 VA: 0x7594e14630
	private Void _ShowBirthdaySetting() { }
	// RVA: 0x27fb510 VA: 0x7594e13510
	private Void _ShowOpenServer() { }
	// RVA: 0x27fb610 VA: 0x7594e13610
	private Void _ShowReturnPage() { }
	// RVA: 0x27fadf8 VA: 0x7594e12df8
	private Void _ShowHomeActivity(String activityId) { }
	// RVA: 0x27fc6b0 VA: 0x7594e146b0
	private Void _ShowHomeActivityAvg(String storyId) { }
	// RVA: 0x27fb1d8 VA: 0x7594e131d8
	private Void _ShowHomeBackgroundPreview() { }
	// RVA: 0x27fc75c VA: 0x7594e1475c
	private Void _ShowUnFinishedOrders() { }
	// RVA: 0x27fb0d8 VA: 0x7594e130d8
	private Void _ShowHomeCharRotation() { }
	// RVA: 0x VA: 0x0
	private Void _AddPopupState() { }
	// RVA: 0x27f973c VA: 0x7594e1173c
	private Void _LoadIllustView(DisplayHandler displayHandler) { }
	// RVA: 0x27f9eac VA: 0x7594e11eac
	private Void _DisposeIllustConfig() { }
	// RVA: 0x27f9478 VA: 0x7594e11478
	private Boolean _CheckIfHomePageActive() { }
	// RVA: 0x27fd310 VA: 0x7594e15310
	private Void _OnRoutedFromIllustRelatedStates(IStateBean stateBean) { }
	// RVA: 0x27fd48c VA: 0x7594e1548c
	public Void .ctor() { }
	// RVA: 0x27fd558 VA: 0x7594e15558
	private Void <RegisterFromDataListener>b__51_0(IStateBean stateBean) { }
	// RVA: 0x27fd574 VA: 0x7594e15574
	private Void <_SyncPlayerStatus>b__97_0(PlayerSyncStatusViewModel response, Boolean isCrossDay) { }
	// RVA: 0x VA: 0x0
	private Void <_AddPopupState>b__113_0() { }
	// RVA: 0x27fd8b0 VA: 0x7594e158b0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27fd8b8 VA: 0x7594e158b8
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x27fd8c0 VA: 0x7594e158c0
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x27fd8c8 VA: 0x7594e158c8
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x27fd8d0 VA: 0x7594e158d0
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x27fd8d8 VA: 0x7594e158d8
	private Void <>xLuaBaseProxy_OnExit() { }
}
```