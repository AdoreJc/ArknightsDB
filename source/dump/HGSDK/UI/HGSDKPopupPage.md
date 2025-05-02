# HGSDKPopupPage

**Namespace:** `HGSDK.UI`


## Fields

- `UIBlurFloatPanel _blurBkg`

- `SDKPopupFloatV2 _floatV2`

- `Single _switchQuickFadeDuration`

- `Single _appearFadeDuration`

- `PopupState m_initTargetState`


## Properties

- `PopupState state`


## Methods

- `Void SetInitState(PopupState)`

- `PopupState GetInitTargetState()`

- `PopupState get_state()`

- `Void set_state(PopupState)`

- `Void ClosePage()`

- `Void _UpdateReturnStack(PopupState, Boolean)`

- `Void _OnStateTransitionStart(IUIState, IUIState)`

- `Void _UpdateBlurBkgStatus(Boolean)`

- `Void _StoreToState(PopupState, Object)`

- `Object _GetStoreByState(PopupState)`

- `Single <>xLuaBaseProxy_get_fadeDuration()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class HGSDKPopupPage : UIPage
{
	public const String CAPTCHA_ID_CHANGE_PWD; // 0x0
	public const String CAPTCHA_ID_CHANGE_PHONE_NEW; // 0x0
	public const String CAPTCHA_ID_CHANGE_PHONE_ORI; // 0x0
	public const String CAPTCHA_ID_UNBIND_GRAND; // 0x0
	private UIState[] _states; // 0x38
	private UIBlurFloatPanel _blurBkg; // 0x40
	private SDKPopupFloatV2 _floatV2; // 0x48
	private Single _switchQuickFadeDuration; // 0x50
	private Single _appearFadeDuration; // 0x54
	private UIStateMachine`1 m_stateMachine; // 0x58
	private Stack`1 m_stateReturnStack; // 0x60
	private Dictionary`2 m_stateStore; // 0x68
	private PopupState m_initTargetState; // 0x70
	private static DelegateBridge __Hotfix0_SetInitState; // 0x0
	private static DelegateBridge __Hotfix0_GetInitTargetState; // 0x8
	private static DelegateBridge __Hotfix0_get_state; // 0x10
	private static DelegateBridge __Hotfix0_set_state; // 0x18
	private static DelegateBridge __Hotfix0_get_fadeDuration; // 0x20
	private static DelegateBridge __Hotfix0_ClosePage; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0_OnClose; // 0x38
	private static DelegateBridge __Hotfix0_OnOpen; // 0x40
	private static DelegateBridge __Hotfix0__UpdateReturnStack; // 0x48
	private static DelegateBridge __Hotfix0__ConstructStateMachine; // 0x50
	private static DelegateBridge __Hotfix0__OnStateTransitionStart; // 0x58
	private static DelegateBridge __Hotfix0__UpdateBlurBkgStatus; // 0x60
	private static DelegateBridge __Hotfix0__StoreToState; // 0x68
	private static DelegateBridge __Hotfix0__GetStoreByState; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	private PopupState state { get; set; }
	protected override Single fadeDuration { get; }

	// RVA: 0x355dbb8 VA: 0x7595b75bb8
	public Void SetInitState(PopupState targetState) { }
	// RVA: 0x355dc34 VA: 0x7595b75c34
	public PopupState GetInitTargetState() { }
	// RVA: 0x355dc9c VA: 0x7595b75c9c
	private PopupState get_state() { }
	// RVA: 0x355dd24 VA: 0x7595b75d24
	private Void set_state(PopupState value) { }
	// RVA: 0x355dddc VA: 0x7595b75ddc
	protected override Single get_fadeDuration() { }
	// RVA: 0x355de44 VA: 0x7595b75e44
	public Void ClosePage() { }
	// RVA: 0x355dfd4 VA: 0x7595b75fd4
	protected override Void OnInit() { }
	// RVA: 0x355e2b0 VA: 0x7595b762b0
	protected override Void OnClose() { }
	// RVA: 0x355e350 VA: 0x7595b76350
	protected override Void OnOpen() { }
	// RVA: 0x355e3b4 VA: 0x7595b763b4
	private Void _UpdateReturnStack(PopupState newState, Boolean pushToStack) { }
	// RVA: 0x355e0ac VA: 0x7595b760ac
	private UIStateMachine`1 _ConstructStateMachine() { }
	// RVA: 0x355e4d4 VA: 0x7595b764d4
	private Void _OnStateTransitionStart(IUIState rawFromState, IUIState rawToState) { }
	// RVA: 0x355e6b8 VA: 0x7595b766b8
	private Void _UpdateBlurBkgStatus(Boolean isShow) { }
	// RVA: 0x355e77c VA: 0x7595b7677c
	private Void _StoreToState(PopupState state, Object param) { }
	// RVA: 0x355e828 VA: 0x7595b76828
	private Object _GetStoreByState(PopupState state) { }
	// RVA: 0x355e8c0 VA: 0x7595b768c0
	public Void .ctor() { }
	// RVA: 0x355ea28 VA: 0x7595b76a28
	private Single <>xLuaBaseProxy_get_fadeDuration() { }
}
```