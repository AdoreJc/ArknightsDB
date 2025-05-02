# Act25sideResearchState

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Act25sideResearchView _view`

- `UIAnimationLocation _enterAnim`

- `CanvasGroup _canvasGroup`

- `Act25sideHarvestButtonView _btnView`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `Boolean m_isInited`

- `Boolean m_hasPlayedEnterAnim`

- `String m_cachedActId`

- `Act25sideResearchPage m_page`

- `Act25sideResearchStateBean m_stateBean`

- `Act25sideDailyHarvestStateBean m_harvestBean`

- `Act25sideResearchPopupController m_popupController`

- `Tween m_enterAnimTween`


## Methods

- `Void _OnEnterAddTokenState(IStateBean)`

- `Void _OnResearchConfirmState(IStateBean)`

- `Void _OnHarvestState(IStateBean)`

- `Void _OnCompleteMissionState(IStateBean)`

- `Void _OnUnlockArchiveState(IStateBean)`

- `Void _OnRewardState(IStateBean)`

- `Void _OnTokenDetail(IStateBean)`

- `Void _InitIfNot()`

- `Void _OnBackClicked()`

- `Void _UpdateProperty(Boolean)`

- `Boolean _HandlePopup(PopupItem)`

- `Void _InitControllerPopup(Act25sideDailyRefreshResponse)`

- `Void _ShowDailyAddCount()`

- `Void _ShowCompleteMission()`

- `Void _ShowUnlockArchive()`

- `Void _ShowDailyHarvest()`

- `Void _AddTopState()`

- `IEnumerator _InitEnterCoroutine()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnShowReward()`

- `Void _EventOnItemSelect(String)`

- `Void _EventOnRouteToStage(RouteStageParam)`

- `Void _EventOnAcceptMission()`

- `Void _EventOnOpenArchive()`

- `Void _EventOnCompleteMission()`

- `IEnumerator _ReceiveItemsCoroutine(List`1, Action)`

- `Void _EventOnHarvestClick()`

- `Void _TryHarvest()`

- `Boolean _HarvestAvailable()`

- `Void OnPageRoutedTriggerPopup()`

- `Void OnTokenDetailClick()`

- `Void <_InitIfNot>b__31_0(GameObject)`

- `Void <_TryHarvest>b__51_0(Act25sideDailyHarvestResponse)`

- `Void <_TryHarvest>b__51_1()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchState : PopupFadeState, IValueMsgReceiver
{
	private Act25sideResearchView _view; // 0x70
	private UIAnimationLocation _enterAnim; // 0x78
	private CanvasGroup _canvasGroup; // 0x88
	private Act25sideHarvestButtonView _btnView; // 0x90
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x98
	public const Int32 MSG_ITEM_SELECT; // 0x0
	public const Int32 MSG_ROUTE_STAGE; // 0x0
	public const Int32 MSG_ACCEPT_MISSION; // 0x0
	public const Int32 MSG_COMPLETE_MISSION; // 0x0
	public const Int32 MSG_OPEN_ARCHIVE; // 0x0
	public const Int32 MSG_SHOW_REWARD; // 0x0
	private Boolean m_isInited; // 0xa0
	private Boolean m_hasPlayedEnterAnim; // 0xa1
	private String m_cachedActId; // 0xa8
	private Act25sideResearchPage m_page; // 0xb0
	private Act25sideResearchStateBean m_stateBean; // 0xb8
	private Act25sideDailyHarvestStateBean m_harvestBean; // 0xc0
	private Act25sideResearchPopupController m_popupController; // 0xc8
	private Tween m_enterAnimTween; // 0xd0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnEnterAddTokenState; // 0x20
	private static DelegateBridge __Hotfix0__OnResearchConfirmState; // 0x28
	private static DelegateBridge __Hotfix0__OnHarvestState; // 0x30
	private static DelegateBridge __Hotfix0__OnCompleteMissionState; // 0x38
	private static DelegateBridge __Hotfix0__OnUnlockArchiveState; // 0x40
	private static DelegateBridge __Hotfix0__OnRewardState; // 0x48
	private static DelegateBridge __Hotfix0__OnTokenDetail; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge __Hotfix0__OnBackClicked; // 0x60
	private static DelegateBridge __Hotfix0__UpdateProperty; // 0x68
	private static DelegateBridge __Hotfix0__HandlePopup; // 0x70
	private static DelegateBridge __Hotfix0__InitControllerPopup; // 0x78
	private static DelegateBridge __Hotfix0__ShowDailyAddCount; // 0x80
	private static DelegateBridge __Hotfix0__ShowCompleteMission; // 0x88
	private static DelegateBridge __Hotfix0__ShowUnlockArchive; // 0x90
	private static DelegateBridge __Hotfix0__ShowDailyHarvest; // 0x98
	private static DelegateBridge __Hotfix0__AddTopState; // 0xa0
	private static DelegateBridge __Hotfix0__InitEnterCoroutine; // 0xa8
	private static DelegateBridge __Hotfix0_OnMessage; // 0xb0
	private static DelegateBridge __Hotfix0__EventOnShowReward; // 0xb8
	private static DelegateBridge __Hotfix0__EventOnItemSelect; // 0xc0
	private static DelegateBridge __Hotfix0__EventOnRouteToStage; // 0xc8
	private static DelegateBridge __Hotfix0__EventOnAcceptMission; // 0xd0
	private static DelegateBridge __Hotfix0__EventOnOpenArchive; // 0xd8
	private static DelegateBridge __Hotfix0__EventOnCompleteMission; // 0xe0
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0xe8
	private static DelegateBridge __Hotfix0__EventOnHarvestClick; // 0xf0
	private static DelegateBridge __Hotfix0__TryHarvest; // 0xf8
	private static DelegateBridge __Hotfix0__HarvestAvailable; // 0x100
	private static DelegateBridge __Hotfix0_OnPageRoutedTriggerPopup; // 0x108
	private static DelegateBridge __Hotfix0_OnTokenDetailClick; // 0x110
	private static DelegateBridge _c__Hotfix0_ctor; // 0x118


	// RVA: 0x327b88c VA: 0x759589388c
	protected override Void OnEnter() { }
	// RVA: 0x327bd9c VA: 0x7595893d9c
	protected override Void OnResume() { }
	// RVA: 0x327c0c8 VA: 0x75958940c8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x327c130 VA: 0x7595894130
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x327c554 VA: 0x7595894554
	private Void _OnEnterAddTokenState(IStateBean stateBean) { }
	// RVA: 0x327c684 VA: 0x7595894684
	private Void _OnResearchConfirmState(IStateBean stateBean) { }
	// RVA: 0x327c7a0 VA: 0x75958947a0
	private Void _OnHarvestState(IStateBean stateBean) { }
	// RVA: 0x327c8b4 VA: 0x75958948b4
	private Void _OnCompleteMissionState(IStateBean stateBean) { }
	// RVA: 0x327c99c VA: 0x759589499c
	private Void _OnUnlockArchiveState(IStateBean stateBean) { }
	// RVA: 0x327ca84 VA: 0x7595894a84
	private Void _OnRewardState(IStateBean stateBean) { }
	// RVA: 0x327cba0 VA: 0x7595894ba0
	private Void _OnTokenDetail(IStateBean stateBean) { }
	// RVA: 0x327b974 VA: 0x7595893974
	private Void _InitIfNot() { }
	// RVA: 0x327ce94 VA: 0x7595894e94
	private Void _OnBackClicked() { }
	// RVA: 0x327beb4 VA: 0x7595893eb4
	private Void _UpdateProperty(Boolean isInit) { }
	// RVA: 0x327cf60 VA: 0x7595894f60
	private Boolean _HandlePopup(PopupItem item) { }
	// RVA: 0x327cd98 VA: 0x7595894d98
	private Void _InitControllerPopup(Act25sideDailyRefreshResponse response) { }
	// RVA: 0x327d034 VA: 0x7595895034
	private Void _ShowDailyAddCount() { }
	// RVA: 0x327d0b4 VA: 0x75958950b4
	private Void _ShowCompleteMission() { }
	// RVA: 0x327d134 VA: 0x7595895134
	private Void _ShowUnlockArchive() { }
	// RVA: 0x327d1b4 VA: 0x75958951b4
	private Void _ShowDailyHarvest() { }
	// RVA: 0x VA: 0x0
	private Void _AddTopState() { }
	// RVA: 0x327c01c VA: 0x759589401c
	private IEnumerator _InitEnterCoroutine() { }
	// RVA: 0x327d25c VA: 0x759589525c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x327dbfc VA: 0x7595895bfc
	private Void _EventOnShowReward() { }
	// RVA: 0x327d3ec VA: 0x75958953ec
	private Void _EventOnItemSelect(String areaId) { }
	// RVA: 0x327d504 VA: 0x7595895504
	private Void _EventOnRouteToStage(RouteStageParam param) { }
	// RVA: 0x327d680 VA: 0x7595895680
	private Void _EventOnAcceptMission() { }
	// RVA: 0x327dabc VA: 0x7595895abc
	private Void _EventOnOpenArchive() { }
	// RVA: 0x327d754 VA: 0x7595895754
	private Void _EventOnCompleteMission() { }
	// RVA: 0x327dc84 VA: 0x7595895c84
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x327dd84 VA: 0x7595895d84
	private Void _EventOnHarvestClick() { }
	// RVA: 0x327dee8 VA: 0x7595895ee8
	private Void _TryHarvest() { }
	// RVA: 0x327de44 VA: 0x7595895e44
	private Boolean _HarvestAvailable() { }
	// RVA: 0x327e1f0 VA: 0x75958961f0
	public Void OnPageRoutedTriggerPopup() { }
	// RVA: 0x327e26c VA: 0x759589626c
	public Void OnTokenDetailClick() { }
	// RVA: 0x327e2ec VA: 0x75958962ec
	public Void .ctor() { }
	// RVA: 0x327e480 VA: 0x7595896480
	private Void <_InitIfNot>b__31_0(GameObject inst) { }
	// RVA: 0x327e538 VA: 0x7595896538
	private Void <_TryHarvest>b__51_0(Act25sideDailyHarvestResponse response) { }
	// RVA: 0x327e630 VA: 0x7595896630
	private Void <_TryHarvest>b__51_1() { }
	// RVA: 0x327e638 VA: 0x7595896638
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x327e640 VA: 0x7595896640
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x327e648 VA: 0x7595896648
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```