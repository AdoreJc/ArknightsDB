# PayRegisterState

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

- `Void _OnBindSuc(LoginResult)`

- `Void _OnAccountInvalid()`

- `Boolean <OnRegister>b__14_2(String)`

- `String <OnRegister>b__14_3()`

- `Void <_OnAccountInvalid>b__18_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class PayRegisterState : UIState
{
	private InputField _phoneNumberInput; // 0x48
	private SDKInputWarning _phoneNumberWarning; // 0x50
	private InputField _passwdInput; // 0x58
	private SDKInputWarning _passwdInputWarn; // 0x60
	private InputField _passwdAgainInput; // 0x68
	private SDKInputWarning _passwdAgainInputWarning; // 0x70
	private SDKCaptchaWidget _captchaWidget; // 0x78
	private Toggle _policyToggle; // 0x80
	private SDKToggleWarning _policyToggleWarning; // 0x88
	private Button _registerBtn; // 0x90
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_get_showBackPanel; // 0x8
	private static DelegateBridge __Hotfix0_OnRegister; // 0x10
	private static DelegateBridge __Hotfix0_EventOnRegisterClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnRegisterSuc; // 0x20
	private static DelegateBridge __Hotfix0__OnBindSuc; // 0x28
	private static DelegateBridge __Hotfix0__OnAccountInvalid; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override PayState myState { get; }
	public override Boolean showBackPanel { get; }

	// RVA: 0x355c34c VA: 0x7595b7434c
	public override PayState get_myState() { }
	// RVA: 0x355c3b4 VA: 0x7595b743b4
	public override Boolean get_showBackPanel() { }
	// RVA: 0x355c41c VA: 0x7595b7441c
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x355c9c0 VA: 0x7595b749c0
	public Void EventOnRegisterClicked() { }
	// RVA: 0x355cb18 VA: 0x7595b74b18
	private Void _OnRegisterSuc(LoginResult result) { }
	// RVA: 0x355cce8 VA: 0x7595b74ce8
	private Void _OnBindSuc(LoginResult result) { }
	// RVA: 0x355cdd4 VA: 0x7595b74dd4
	private Void _OnAccountInvalid() { }
	// RVA: 0x355ce9c VA: 0x7595b74e9c
	public Void .ctor() { }
	// RVA: 0x355cf08 VA: 0x7595b74f08
	private Boolean <OnRegister>b__14_2(String content) { }
	// RVA: 0x355cf2c VA: 0x7595b74f2c
	private String <OnRegister>b__14_3() { }
	// RVA: 0x355cf48 VA: 0x7595b74f48
	private Void <_OnAccountInvalid>b__18_0() { }
}
```