# HomeThemeChangeState

**Namespace:** `Torappu.UI.Home`


## Fields

- `CanvasGroup _alphaHandler`

- `HomeThemeChangeView _view`

- `CanvasGroup _showUICanvas`

- `RectTransform _rectCancel`

- `HomeThemeChangeStateBean m_stateBean`

- `Boolean m_showUIFlag`

- `FadeSwitchTween m_tween`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnConfirmChangeClicked()`

- `Void EventOnHideUiClick()`

- `Void EventOnHideIllustClick()`

- `Void _OnApplyUIState()`

- `Void CancelClick()`

- `Void OnOpenBackGround()`

- `Boolean _IsStateStable()`

- `Void _CancelChanging()`

- `Void _UpdateSelectingTheme()`

- `Void _OnSetThemeSuccess()`

- `Void _OnSortToggleClick(State)`

- `String _GetAndConsumeRoutedHomeThemeId()`

- `Void <RegisterToDataListener>b__11_0(IStateBean)`

- `Void <_UpdateSelectingTheme>b__25_0(CharRotationUpdatePresetResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeThemeChangeState : HomeReplaceableState
{
	private CanvasGroup _alphaHandler; // 0x60
	private HomeThemeChangeView _view; // 0x68
	private CanvasGroup _showUICanvas; // 0x70
	private RectTransform _rectCancel; // 0x78
	private HomeThemeChangeStateBean m_stateBean; // 0x80
	private Boolean m_showUIFlag; // 0x88
	private FadeSwitchTween m_tween; // 0x90
	private Boolean m_isInited; // 0x98
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_ShowEffect; // 0x20
	private static DelegateBridge __Hotfix0_HideEffect; // 0x28
	private static DelegateBridge __Hotfix0_ShowFastMode; // 0x30
	private static DelegateBridge __Hotfix0_HideFastMode; // 0x38
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x40
	private static DelegateBridge __Hotfix0_EventOnConfirmChangeClicked; // 0x48
	private static DelegateBridge __Hotfix0_EventOnHideUiClick; // 0x50
	private static DelegateBridge __Hotfix0_EventOnHideIllustClick; // 0x58
	private static DelegateBridge __Hotfix0__OnApplyUIState; // 0x60
	private static DelegateBridge __Hotfix0_CancelClick; // 0x68
	private static DelegateBridge __Hotfix0_OnOpenBackGround; // 0x70
	private static DelegateBridge __Hotfix0__IsStateStable; // 0x78
	private static DelegateBridge __Hotfix0__CancelChanging; // 0x80
	private static DelegateBridge __Hotfix0__UpdateSelectingTheme; // 0x88
	private static DelegateBridge __Hotfix0__OnSetThemeSuccess; // 0x90
	private static DelegateBridge __Hotfix0__OnSortToggleClick; // 0x98
	private static DelegateBridge __Hotfix0__GetAndConsumeRoutedHomeThemeId; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x2805144 VA: 0x7594e1d144
	private Void _InitIfNot() { }
	// RVA: 0x28052cc VA: 0x7594e1d2cc
	protected override Void OnEnter() { }
	// RVA: 0x280553c VA: 0x7594e1d53c
	protected override Void OnResume() { }
	// RVA: 0x28057d0 VA: 0x7594e1d7d0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2805948 VA: 0x7594e1d948
	protected override IEnumerator ShowEffect(HomeReplaceableState extractState) { }
	// RVA: 0x2805a30 VA: 0x7594e1da30
	protected override IEnumerator HideEffect() { }
	// RVA: 0x2805b04 VA: 0x7594e1db04
	protected override Void ShowFastMode() { }
	// RVA: 0x2805b94 VA: 0x7594e1db94
	protected override Void HideFastMode() { }
	// RVA: 0x2805c0c VA: 0x7594e1dc0c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2805c74 VA: 0x7594e1dc74
	public Void EventOnConfirmChangeClicked() { }
	// RVA: 0x2805f9c VA: 0x7594e1df9c
	public Void EventOnHideUiClick() { }
	// RVA: 0x280609c VA: 0x7594e1e09c
	public Void EventOnHideIllustClick() { }
	// RVA: 0x2806010 VA: 0x7594e1e010
	private Void _OnApplyUIState() { }
	// RVA: 0x2806110 VA: 0x7594e1e110
	public Void CancelClick() { }
	// RVA: 0x28062a8 VA: 0x7594e1e2a8
	public Void OnOpenBackGround() { }
	// RVA: 0x28063b4 VA: 0x7594e1e3b4
	private Boolean _IsStateStable() { }
	// RVA: 0x2806178 VA: 0x7594e1e178
	private Void _CancelChanging() { }
	// RVA: 0x2805cf4 VA: 0x7594e1dcf4
	private Void _UpdateSelectingTheme() { }
	// RVA: 0x28064a4 VA: 0x7594e1e4a4
	private Void _OnSetThemeSuccess() { }
	// RVA: 0x2806518 VA: 0x7594e1e518
	private Void _OnSortToggleClick(State state) { }
	// RVA: 0x2805434 VA: 0x7594e1d434
	private String _GetAndConsumeRoutedHomeThemeId() { }
	// RVA: 0x28065a8 VA: 0x7594e1e5a8
	public Void .ctor() { }
	// RVA: 0x280665c VA: 0x7594e1e65c
	private Void <RegisterToDataListener>b__11_0(IStateBean statebean) { }
	// RVA: 0x2806768 VA: 0x7594e1e768
	private Void <_UpdateSelectingTheme>b__25_0(CharRotationUpdatePresetResponse response) { }
	// RVA: 0x280676c VA: 0x7594e1e76c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2806774 VA: 0x7594e1e774
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x280677c VA: 0x7594e1e77c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```