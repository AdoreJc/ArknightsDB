# PayCaptchaLoginState

**Namespace:** `HGSDK.UI`


## Fields

- `InputField _phoneNumberInput`

- `SDKInputWarning _phoneNumberWarning`

- `SDKCaptchaWidget _captchaWidget`

- `Button _loginBtn`


## Methods

- `Void EventOnLoginClicked()`

- `Void _OnInvalidAccount()`

- `String <OnRegister>b__8_1()`

- `Void <EventOnLoginClicked>b__9_0(LoginResult)`

- `Void <_OnInvalidAccount>b__10_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class PayCaptchaLoginState : UIState
{
	private InputField _phoneNumberInput; // 0x48
	private SDKInputWarning _phoneNumberWarning; // 0x50
	private SDKCaptchaWidget _captchaWidget; // 0x58
	private Button _loginBtn; // 0x60
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_get_showBackPanel; // 0x8
	private static DelegateBridge __Hotfix0_OnRegister; // 0x10
	private static DelegateBridge __Hotfix0_EventOnLoginClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnInvalidAccount; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override PayState myState { get; }
	public override Boolean showBackPanel { get; }

	// RVA: 0x355a8e4 VA: 0x7595b728e4
	public override PayState get_myState() { }
	// RVA: 0x355a94c VA: 0x7595b7294c
	public override Boolean get_showBackPanel() { }
	// RVA: 0x355a9b4 VA: 0x7595b729b4
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x355acdc VA: 0x7595b72cdc
	public Void EventOnLoginClicked() { }
	// RVA: 0x355ae14 VA: 0x7595b72e14
	private Void _OnInvalidAccount() { }
	// RVA: 0x355aedc VA: 0x7595b72edc
	public Void .ctor() { }
	// RVA: 0x355af48 VA: 0x7595b72f48
	private String <OnRegister>b__8_1() { }
	// RVA: 0x355af64 VA: 0x7595b72f64
	private Void <EventOnLoginClicked>b__9_0(LoginResult result) { }
	// RVA: 0x355afb0 VA: 0x7595b72fb0
	private Void <_OnInvalidAccount>b__10_0() { }
}
```