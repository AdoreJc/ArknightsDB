# SDKPopupStateUnbindYostar

**Namespace:** `YostarSDK.UI`


## Fields

- `InputField _emailInput`

- `SDKInputWarning _emailInputWarning`

- `InputField _captchaInput`

- `SDKInputWarning _captchaInputWarning`

- `SDKCaptchaWidget _captchaWidget`

- `YostarSDKAccountBindNotifyView _notifyView`

- `Button _btnClose`

- `Text _textTitle`

- `Text _hintEmail`

- `Text _hintCode`

- `Text _textInvalidEmail`

- `Text _textInvalidCode`

- `Text _textSendCode`

- `Text _textUnbind`


## Methods

- `Void EventOnCloseClicked()`

- `Void OnUnbindClicked()`

- `Void _RenderConstText()`

- `Boolean _IsValidEmail(String)`

- `Void _OnAiriSDKUnbinded(UnLinkRet)`

- `Boolean <OnRegister>b__16_0(String)`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKPopupStateUnbindYostar : UIState
{
	private InputField _emailInput; // 0x50
	private SDKInputWarning _emailInputWarning; // 0x58
	private InputField _captchaInput; // 0x60
	private SDKInputWarning _captchaInputWarning; // 0x68
	private SDKCaptchaWidget _captchaWidget; // 0x70
	private YostarSDKAccountBindNotifyView _notifyView; // 0x78
	private Button _btnClose; // 0x80
	private Text _textTitle; // 0x88
	private Text _hintEmail; // 0x90
	private Text _hintCode; // 0x98
	private Text _textInvalidEmail; // 0xa0
	private Text _textInvalidCode; // 0xa8
	private Text _textSendCode; // 0xb0
	private Text _textUnbind; // 0xb8
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnUnbindClicked; // 0x20
	private static DelegateBridge __Hotfix0__RenderConstText; // 0x28
	private static DelegateBridge __Hotfix0__IsValidEmail; // 0x30
	private static DelegateBridge __Hotfix0__OnAiriSDKUnbinded; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override PopupState myState { get; }

	// RVA: 0x2579a14 VA: 0x7594b91a14
	public override PopupState get_myState() { }
	// RVA: 0x2579a7c VA: 0x7594b91a7c
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x2579cd4 VA: 0x7594b91cd4
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x2579fb0 VA: 0x7594b91fb0
	public Void EventOnCloseClicked() { }
	// RVA: 0x257a03c VA: 0x7594b9203c
	public Void OnUnbindClicked() { }
	// RVA: 0x2579e38 VA: 0x7594b91e38
	private Void _RenderConstText() { }
	// RVA: 0x257a190 VA: 0x7594b92190
	private Boolean _IsValidEmail(String email) { }
	// RVA: 0x257a234 VA: 0x7594b92234
	private Void _OnAiriSDKUnbinded(UnLinkRet ret) { }
	// RVA: 0x257a6c0 VA: 0x7594b926c0
	public Void .ctor() { }
	// RVA: 0x257a72c VA: 0x7594b9272c
	private Boolean <OnRegister>b__16_0(String content) { }
	// RVA: 0x257a730 VA: 0x7594b92730
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
	// RVA: 0x257a734 VA: 0x7594b92734
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```