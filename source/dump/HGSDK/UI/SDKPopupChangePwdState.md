# SDKPopupChangePwdState

**Namespace:** `HGSDK.UI`


## Fields

- `InputField _pwdInput`

- `SDKInputWarning _pwdInputWarning`

- `InputField _pwdAgainInput`

- `SDKInputWarning _pwdAgainInputWarning`

- `InputField _captchaInput`

- `SDKCaptchaWidget _captchaWidget`

- `HGSDKSettingNotifyView _notifyView`

- `Button _closeBtn`


## Methods

- `Void EventOnCloseClicked()`

- `Void EventOnChangePwdClicked()`

- `Void _OnAccountInvalid()`

- `Void _OnCaptchaSendSuc(Int64)`

- `Void _CallChangePwd()`

- `Void _ClearLoginInfoAndLogout()`

- `Void _ShowChangePwdFailToast()`

- `Boolean <OnRegister>b__10_1(String)`

- `Void <_CallChangePwd>b__16_0(ChangePwdResponse)`

- `Void <_ClearLoginInfoAndLogout>b__17_0()`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKPopupChangePwdState : UIState
{
	private InputField _pwdInput; // 0x50
	private SDKInputWarning _pwdInputWarning; // 0x58
	private InputField _pwdAgainInput; // 0x60
	private SDKInputWarning _pwdAgainInputWarning; // 0x68
	private InputField _captchaInput; // 0x70
	private SDKCaptchaWidget _captchaWidget; // 0x78
	private HGSDKSettingNotifyView _notifyView; // 0x80
	private Button _closeBtn; // 0x88
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnChangePwdClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnAccountInvalid; // 0x28
	private static DelegateBridge __Hotfix0__OnCaptchaSendSuc; // 0x30
	private static DelegateBridge __Hotfix0__CallChangePwd; // 0x38
	private static DelegateBridge __Hotfix0__ClearLoginInfoAndLogout; // 0x40
	private static DelegateBridge __Hotfix0__ShowChangePwdFailToast; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override PopupState myState { get; }

	// RVA: 0x3560be0 VA: 0x7595b78be0
	public override PopupState get_myState() { }
	// RVA: 0x3560c48 VA: 0x7595b78c48
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x3561088 VA: 0x7595b79088
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x35611fc VA: 0x7595b791fc
	public Void EventOnCloseClicked() { }
	// RVA: 0x3561288 VA: 0x7595b79288
	public Void EventOnChangePwdClicked() { }
	// RVA: 0x35614b8 VA: 0x7595b794b8
	private Void _OnAccountInvalid() { }
	// RVA: 0x3561528 VA: 0x7595b79528
	private Void _OnCaptchaSendSuc(Int64 timeStamp) { }
	// RVA: 0x356131c VA: 0x7595b7931c
	private Void _CallChangePwd() { }
	// RVA: 0x35615e4 VA: 0x7595b795e4
	private Void _ClearLoginInfoAndLogout() { }
	// RVA: 0x35616d8 VA: 0x7595b796d8
	private Void _ShowChangePwdFailToast() { }
	// RVA: 0x35617b0 VA: 0x7595b797b0
	public Void .ctor() { }
	// RVA: 0x356181c VA: 0x7595b7981c
	private Boolean <OnRegister>b__10_1(String content) { }
	// RVA: 0x3561840 VA: 0x7595b79840
	private Void <_CallChangePwd>b__16_0(ChangePwdResponse response) { }
	// RVA: 0x3561938 VA: 0x7595b79938
	private Void <_ClearLoginInfoAndLogout>b__17_0() { }
	// RVA: 0x35619a0 VA: 0x7595b799a0
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
	// RVA: 0x35619a4 VA: 0x7595b799a4
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```