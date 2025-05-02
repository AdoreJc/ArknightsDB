# SDKLoginRegisterState

**Namespace:** `HGSDK.UI`


## Fields

- `InputField _phoneNumberInput`

- `SDKInputWarning _phoneNumberWarning`

- `InputField _passwdInput`

- `SDKInputWarning _passwdInputWarn`

- `InputField _passwdAgainInput`

- `SDKInputWarning _passwdAgainInputWarning`

- `SDKCaptchaWidget _captchaWidget`

- `Toggle _policyToggle`

- `SDKToggleWarning _policyToggleWarning`

- `Button _registerBtn`


## Methods

- `Void EventOnRegisterClicked()`

- `Void _OnRegisterSuc(LoginResult)`

- `Void _OnLoginSuc(LoginResult)`

- `Void _OnAccountInvalid()`

- `Boolean <OnRegister>b__12_2(String)`

- `String <OnRegister>b__12_3()`

- `Void <EventOnRegisterClicked>b__13_0()`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKLoginRegisterState : UIState
{
	private InputField _phoneNumberInput; // 0x58
	private SDKInputWarning _phoneNumberWarning; // 0x60
	private InputField _passwdInput; // 0x68
	private SDKInputWarning _passwdInputWarn; // 0x70
	private InputField _passwdAgainInput; // 0x78
	private SDKInputWarning _passwdAgainInputWarning; // 0x80
	private SDKCaptchaWidget _captchaWidget; // 0x88
	private Toggle _policyToggle; // 0x90
	private SDKToggleWarning _policyToggleWarning; // 0x98
	private Button _registerBtn; // 0xa0
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_EventOnRegisterClicked; // 0x10
	private static DelegateBridge __Hotfix0__OnRegisterSuc; // 0x18
	private static DelegateBridge __Hotfix0__OnLoginSuc; // 0x20
	private static DelegateBridge __Hotfix0__OnAccountInvalid; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override LoginState myState { get; }

	// RVA: 0x3557514 VA: 0x7595b6f514
	public override LoginState get_myState() { }
	// RVA: 0x355757c VA: 0x7595b6f57c
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x3557b08 VA: 0x7595b6fb08
	public Void EventOnRegisterClicked() { }
	// RVA: 0x3557be8 VA: 0x7595b6fbe8
	private Void _OnRegisterSuc(LoginResult result) { }
	// RVA: 0x3557de0 VA: 0x7595b6fde0
	private Void _OnLoginSuc(LoginResult result) { }
	// RVA: 0x3557f10 VA: 0x7595b6ff10
	private Void _OnAccountInvalid() { }
	// RVA: 0x3557f80 VA: 0x7595b6ff80
	public Void .ctor() { }
	// RVA: 0x3558010 VA: 0x7595b70010
	private Boolean <OnRegister>b__12_2(String content) { }
	// RVA: 0x3558034 VA: 0x7595b70034
	private String <OnRegister>b__12_3() { }
	// RVA: 0x3558050 VA: 0x7595b70050
	private Void <EventOnRegisterClicked>b__13_0() { }
	// RVA: 0x35581b8 VA: 0x7595b701b8
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
}
```