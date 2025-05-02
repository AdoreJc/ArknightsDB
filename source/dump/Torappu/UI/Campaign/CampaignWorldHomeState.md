# CampaignWorldHomeState

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `RectTransform _topMenuContainer`

- `PrefabInstHolder _campFeeHolder`

- `CampaignWorldHomeBriefView _briefView`

- `CampaignWorldSwitchTweenObj _btnResetFocus`

- `RectTransform _arrowContainer`

- `CampaignWorldSwitchTweenObj _arrowPrefab`

- `InternalState m_internalState`

- `Coroutine m_updateCoroutine`

- `Boolean m_inited`

- `Boolean m_isFocusFinished`

- `CampaignFeeView m_campFeeView`


## Methods

- `Void EventOnResetFocusClicked()`

- `Void EventOnBriefClicked()`

- `Void _EventOnCampFeeClicked()`

- `Void _EventOnBackClicked()`

- `Void _InitIfNot()`

- `Void _OnInitCampFee(GameObject)`

- `Void _TryStartUpdateState()`

- `Void _StopUpdateState()`

- `IEnumerator _UpdateState()`

- `Void _CheckGuideBook()`

- `Void _WaitGuideBook()`

- `Void _CheckBrief()`

- `Void _WaitBrief()`

- `Void _CheckFocus()`

- `Void _BeginFocus()`

- `Void _WaitFocus()`

- `Void _FogDisappear()`

- `Void _UpdateView()`

- `Void _ResetView()`

- `Void <RegisterToDataListener>b__19_0(IStateBean)`

- `Void <_BeginFocus>b__37_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldHomeState : PopupFadeState
{
	private const Single FOCUS_DURATION; // 0x0
	private const Single BEGIN_FOCUS_WAIT_TIME; // 0x0
	private const Single FOG_DISAPPEAR_WAIT_TIME; // 0x0
	private const Int32 ARROW_MAX_COUNT; // 0x0
	private const String GUIDE_BOOK_SUB_SIGNAL; // 0x0
	private RectTransform _topMenuContainer; // 0x70
	private PrefabInstHolder _campFeeHolder; // 0x78
	private CampaignWorldHomeBriefView _briefView; // 0x80
	private CampaignWorldSwitchTweenObj _btnResetFocus; // 0x88
	private RectTransform _arrowContainer; // 0x90
	private CampaignWorldSwitchTweenObj _arrowPrefab; // 0x98
	private InternalState m_internalState; // 0xa0
	private Coroutine m_updateCoroutine; // 0xa8
	private Boolean m_inited; // 0xb0
	private Boolean m_isFocusFinished; // 0xb1
	private CampaignFeeView m_campFeeView; // 0xb8
	private List`1 m_arrows; // 0xc0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_OnPause; // 0x20
	private static DelegateBridge __Hotfix0_EventOnResetFocusClicked; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBriefClicked; // 0x30
	private static DelegateBridge __Hotfix0__EventOnCampFeeClicked; // 0x38
	private static DelegateBridge __Hotfix0__EventOnBackClicked; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0__OnInitCampFee; // 0x50
	private static DelegateBridge __Hotfix0__TryStartUpdateState; // 0x58
	private static DelegateBridge __Hotfix0__StopUpdateState; // 0x60
	private static DelegateBridge __Hotfix0__UpdateState; // 0x68
	private static DelegateBridge __Hotfix0__CheckGuideBook; // 0x70
	private static DelegateBridge __Hotfix0__WaitGuideBook; // 0x78
	private static DelegateBridge __Hotfix0__CheckBrief; // 0x80
	private static DelegateBridge __Hotfix0__WaitBrief; // 0x88
	private static DelegateBridge __Hotfix0__CheckFocus; // 0x90
	private static DelegateBridge __Hotfix0__BeginFocus; // 0x98
	private static DelegateBridge __Hotfix0__WaitFocus; // 0xa0
	private static DelegateBridge __Hotfix0__FogDisappear; // 0xa8
	private static DelegateBridge __Hotfix0__UpdateView; // 0xb0
	private static DelegateBridge __Hotfix0__ResetView; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0


	// RVA: 0x2dd1dd4 VA: 0x75953e9dd4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2dd1e38 VA: 0x75953e9e38
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2dd1fb0 VA: 0x75953e9fb0
	protected override Void OnEnter() { }
	// RVA: 0x2dd2518 VA: 0x75953ea518
	protected override Void OnResume() { }
	// RVA: 0x2dd2694 VA: 0x75953ea694
	protected override Void OnPause() { }
	// RVA: 0x2dd2878 VA: 0x75953ea878
	public Void EventOnResetFocusClicked() { }
	// RVA: 0x2dd2a70 VA: 0x75953eaa70
	public Void EventOnBriefClicked() { }
	// RVA: 0x2dd2bc8 VA: 0x75953eabc8
	private Void _EventOnCampFeeClicked() { }
	// RVA: 0x2dd2d20 VA: 0x75953ead20
	private Void _EventOnBackClicked() { }
	// RVA: 0x2dd202c VA: 0x75953ea02c
	private Void _InitIfNot() { }
	// RVA: 0x2dd2de8 VA: 0x75953eade8
	private Void _OnInitCampFee(GameObject campFeeObj) { }
	// RVA: 0x2dd2394 VA: 0x75953ea394
	private Void _TryStartUpdateState() { }
	// RVA: 0x2dd27b4 VA: 0x75953ea7b4
	private Void _StopUpdateState() { }
	// RVA: 0x2dd3050 VA: 0x75953eb050
	private IEnumerator _UpdateState() { }
	// RVA: 0x2dd32b4 VA: 0x75953eb2b4
	private Void _CheckGuideBook() { }
	// RVA: 0x2dd3354 VA: 0x75953eb354
	private Void _WaitGuideBook() { }
	// RVA: 0x2dd33c8 VA: 0x75953eb3c8
	private Void _CheckBrief() { }
	// RVA: 0x2dd3674 VA: 0x75953eb674
	private Void _WaitBrief() { }
	// RVA: 0x2dd3858 VA: 0x75953eb858
	private Void _CheckFocus() { }
	// RVA: 0x2dd398c VA: 0x75953eb98c
	private Void _BeginFocus() { }
	// RVA: 0x2dd3b9c VA: 0x75953ebb9c
	private Void _WaitFocus() { }
	// RVA: 0x2dd3ce4 VA: 0x75953ebce4
	private Void _FogDisappear() { }
	// RVA: 0x2dd3df4 VA: 0x75953ebdf4
	private Void _UpdateView() { }
	// RVA: 0x2dd30fc VA: 0x75953eb0fc
	private Void _ResetView() { }
	// RVA: 0x2dd4074 VA: 0x75953ec074
	public Void .ctor() { }
	// RVA: 0x2dd4138 VA: 0x75953ec138
	private Void <RegisterToDataListener>b__19_0(IStateBean bean) { }
	// RVA: 0x2dd440c VA: 0x75953ec40c
	private Void <_BeginFocus>b__37_0() { }
	// RVA: 0x2dd4418 VA: 0x75953ec418
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2dd4420 VA: 0x75953ec420
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2dd4428 VA: 0x75953ec428
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2dd4430 VA: 0x75953ec430
	private Void <>xLuaBaseProxy_OnPause() { }
}
```