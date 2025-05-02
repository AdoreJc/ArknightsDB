# TemplateActivityMissionState

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `TemplateActivityMissionHolder _holder`

- `TemplateActivityMissionView _missionView`

- `TemplateActivityCoinView _coinView`

- `RectTransform _topMenuContainer`

- `CommonTopMenu m_topMenu`

- `TemplateActivityController m_cacheController`


## Methods

- `TemplateActivityMissionGroupViewModel GetMissionViewModel(TemplateActivityController)`

- `Void BindController(TemplateActivityController)`

- `Void _InitTopMenu()`

- `Void _RefreshData()`

- `Void EventOnMissionClaimAllClicked()`

- `Void EventOnMissionObjClicked(String)`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void <_InitTopMenu>b__11_0()`

- `Void <EventOnMissionClaimAllClicked>b__13_0(ActivityMissionCheckResponse)`

- `Void <EventOnMissionObjClicked>b__14_0(ActivityConfirmMissionResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityMissionState : PopupFloatState, IBaseActStateHolder, IHotfixable
{
	private TemplateActivityMissionHolder _holder; // 0x70
	private TemplateActivityMissionView _missionView; // 0x78
	private TemplateActivityCoinView _coinView; // 0x80
	private RectTransform _topMenuContainer; // 0x88
	private CommonTopMenu m_topMenu; // 0x90
	private TemplateActivityController m_cacheController; // 0x98
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnExit; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_GetMissionViewModel; // 0x18
	private static DelegateBridge __Hotfix0_BindController; // 0x20
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x28
	private static DelegateBridge __Hotfix0__RefreshData; // 0x30
	private static DelegateBridge __Hotfix0_EventOnMissionClaimAllClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnMissionObjClicked; // 0x40
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x309d5b8 VA: 0x75956b55b8
	protected override Void OnEnter() { }
	// RVA: 0x309d90c VA: 0x75956b590c
	protected override Void OnExit() { }
	// RVA: 0x309da28 VA: 0x75956b5a28
	public override IStateBean GetCacheBean() { }
	// RVA: 0x309da8c VA: 0x75956b5a8c
	public TemplateActivityMissionGroupViewModel GetMissionViewModel(TemplateActivityController controller) { }
	// RVA: 0x309dc50 VA: 0x75956b5c50
	public Void BindController(TemplateActivityController controller) { }
	// RVA: 0x309d6d8 VA: 0x75956b56d8
	private Void _InitTopMenu() { }
	// RVA: 0x309d800 VA: 0x75956b5800
	private Void _RefreshData() { }
	// RVA: 0x309df0c VA: 0x75956b5f0c
	public Void EventOnMissionClaimAllClicked() { }
	// RVA: 0x309e2d0 VA: 0x75956b62d0
	public Void EventOnMissionObjClicked(String missionId) { }
	// RVA: 0x309e544 VA: 0x75956b6544
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x309e62c VA: 0x75956b662c
	public Void .ctor() { }
	// RVA: 0x309e69c VA: 0x75956b669c
	private Void <_InitTopMenu>b__11_0() { }
	// RVA: 0x309e74c VA: 0x75956b674c
	private Void <EventOnMissionClaimAllClicked>b__13_0(ActivityMissionCheckResponse response) { }
	// RVA: 0x309e7a0 VA: 0x75956b67a0
	private Void <EventOnMissionObjClicked>b__14_0(ActivityConfirmMissionResponse response) { }
	// RVA: 0x309e7f4 VA: 0x75956b67f4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x309e7fc VA: 0x75956b67fc
	private Void <>xLuaBaseProxy_OnExit() { }
}
```