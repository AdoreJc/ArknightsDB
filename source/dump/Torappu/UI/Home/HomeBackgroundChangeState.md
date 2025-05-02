# HomeBackgroundChangeState

**Namespace:** `Torappu.UI.Home`


## Fields

- `CanvasGroup _alphaHandler`

- `RectTransform _rectCancel`

- `HomeBackgroundChangeView _view`

- `CanvasGroup _hideUI`

- `Boolean m_isInited`

- `Int32 m_instId`

- `HomeBackgroundChangeStateBean m_stateBean`

- `Boolean m_showUIFlag`

- `FadeSwitchTween m_tween`


## Methods

- `Void _InitIfNot()`

- `Void _StartPreviewMode()`

- `Void _ExitPreviewMode()`

- `Void _HandleBgSelectChanged(String)`

- `Boolean _IsStateStable()`

- `Void _CancelChanging()`

- `Void _OnHideIllustClick()`

- `Void _OnSortToggleClick(State)`

- `Void _UpdateSelectingBackground()`

- `Void _OnSetBackgroundSuccess()`

- `Void _OnApplyUIState()`

- `Void _InitView(Boolean)`

- `Void OnDestroy()`

- `Void EventOnCancelClicked()`

- `Void EventOnConfirmChangeClicked()`

- `Void EventOnEditIllustClicked()`

- `Void EventOnHideUiClick()`

- `Void <_UpdateSelectingBackground>b__18_0(CharRotationUpdatePresetResponse)`

- `Void <RegisterToDataListener>b__29_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeBackgroundChangeState : HomeReplaceableState
{
	private CanvasGroup _alphaHandler; // 0x60
	private RectTransform _rectCancel; // 0x68
	private HomeBackgroundChangeView _view; // 0x70
	private CanvasGroup _hideUI; // 0x78
	private Boolean m_isInited; // 0x80
	private Int32 m_instId; // 0x84
	private HomeBackgroundChangeStateBean m_stateBean; // 0x88
	private Boolean m_showUIFlag; // 0x90
	private FadeSwitchTween m_tween; // 0x98
	private const Boolean INIT_SORT_IS_ASCEND; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__StartPreviewMode; // 0x8
	private static DelegateBridge __Hotfix0__ExitPreviewMode; // 0x10
	private static DelegateBridge __Hotfix0__HandleBgSelectChanged; // 0x18
	private static DelegateBridge __Hotfix0__IsStateStable; // 0x20
	private static DelegateBridge __Hotfix0__CancelChanging; // 0x28
	private static DelegateBridge __Hotfix0__OnHideIllustClick; // 0x30
	private static DelegateBridge __Hotfix0__OnSortToggleClick; // 0x38
	private static DelegateBridge __Hotfix0__UpdateSelectingBackground; // 0x40
	private static DelegateBridge __Hotfix0__OnSetBackgroundSuccess; // 0x48
	private static DelegateBridge __Hotfix0__OnApplyUIState; // 0x50
	private static DelegateBridge __Hotfix0__InitView; // 0x58
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x60
	private static DelegateBridge __Hotfix0_ShowEffect; // 0x68
	private static DelegateBridge __Hotfix0_HideEffect; // 0x70
	private static DelegateBridge __Hotfix0_ShowFastMode; // 0x78
	private static DelegateBridge __Hotfix0_HideFastMode; // 0x80
	private static DelegateBridge __Hotfix0_OnEnter; // 0x88
	private static DelegateBridge __Hotfix0_OnExit; // 0x90
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x98
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnCancelClicked; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnConfirmChangeClicked; // 0xb0
	private static DelegateBridge __Hotfix0_EventOnEditIllustClicked; // 0xb8
	private static DelegateBridge __Hotfix0_EventOnHideUiClick; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8


	// RVA: 0x27e7ed0 VA: 0x7594dffed0
	private Void _InitIfNot() { }
	// RVA: 0x27e8068 VA: 0x7594e00068
	private Void _StartPreviewMode() { }
	// RVA: 0x27e8160 VA: 0x7594e00160
	private Void _ExitPreviewMode() { }
	// RVA: 0x27e8288 VA: 0x7594e00288
	private Void _HandleBgSelectChanged(String bgId) { }
	// RVA: 0x27e8314 VA: 0x7594e00314
	private Boolean _IsStateStable() { }
	// RVA: 0x27e8404 VA: 0x7594e00404
	private Void _CancelChanging() { }
	// RVA: 0x27e8534 VA: 0x7594e00534
	private Void _OnHideIllustClick() { }
	// RVA: 0x27e85a8 VA: 0x7594e005a8
	private Void _OnSortToggleClick(State state) { }
	// RVA: 0x27e8638 VA: 0x7594e00638
	private Void _UpdateSelectingBackground() { }
	// RVA: 0x27e88e0 VA: 0x7594e008e0
	private Void _OnSetBackgroundSuccess() { }
	// RVA: 0x27e8954 VA: 0x7594e00954
	private Void _OnApplyUIState() { }
	// RVA: 0x27e89e0 VA: 0x7594e009e0
	private Void _InitView(Boolean ascend) { }
	// RVA: 0x27e8ba0 VA: 0x7594e00ba0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27e8c08 VA: 0x7594e00c08
	protected override IEnumerator ShowEffect(HomeReplaceableState extractState) { }
	// RVA: 0x27e8cf0 VA: 0x7594e00cf0
	protected override IEnumerator HideEffect() { }
	// RVA: 0x27e8dc4 VA: 0x7594e00dc4
	protected override Void ShowFastMode() { }
	// RVA: 0x27e8e54 VA: 0x7594e00e54
	protected override Void HideFastMode() { }
	// RVA: 0x27e8ecc VA: 0x7594e00ecc
	protected override Void OnEnter() { }
	// RVA: 0x27e8f7c VA: 0x7594e00f7c
	protected override Void OnExit() { }
	// RVA: 0x27e9010 VA: 0x7594e01010
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x27e9188 VA: 0x7594e01188
	protected Void OnDestroy() { }
	// RVA: 0x27e91f0 VA: 0x7594e011f0
	public Void EventOnCancelClicked() { }
	// RVA: 0x27e9270 VA: 0x7594e01270
	public Void EventOnConfirmChangeClicked() { }
	// RVA: 0x27e92f0 VA: 0x7594e012f0
	public Void EventOnEditIllustClicked() { }
	// RVA: 0x27e9404 VA: 0x7594e01404
	public Void EventOnHideUiClick() { }
	// RVA: 0x27e9478 VA: 0x7594e01478
	public Void .ctor() { }
	// RVA: 0x27e9530 VA: 0x7594e01530
	private Void <_UpdateSelectingBackground>b__18_0(CharRotationUpdatePresetResponse response) { }
	// RVA: 0x27e9534 VA: 0x7594e01534
	private Void <RegisterToDataListener>b__29_0(IStateBean statebean) { }
	// RVA: 0x27e9610 VA: 0x7594e01610
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27e9618 VA: 0x7594e01618
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x27e9620 VA: 0x7594e01620
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```