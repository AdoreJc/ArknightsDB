# SDKLoginCaptchaLoginState

**Namespace:** `HGSDK.UI`


## Fields

- `InputField _phoneNumberInput`

- `SDKInputWarning _phoneNumberWarning`

- `SDKCaptchaWidget _captchaWidget`

- `Button _loginBtn`

- `Text _loginBtnText`


## Methods

- `Void EventOnLoginClicked()`

- `Void _OnServiceSuc(LoginResult)`

- `Void _OnLoginSuc(LoginResult)`

- `Void _OnInvalidAccount()`

- `String <OnRegister>b__7_1()`

- `Void <EventOnLoginClicked>b__9_0()`

- `Void <_OnInvalidAccount>b__12_0()`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKLoginCaptchaLoginState : UIState
{
	private InputField _phoneNumberInput; // 0x58
	private SDKInputWarning _phoneNumberWarning; // 0x60
	private SDKCaptchaWidget _captchaWidget; // 0x68
	private Button _loginBtn; // 0x70
	private Text _loginBtnText; // 0x78
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_EventOnLoginClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnServiceSuc; // 0x20
	private static DelegateBridge __Hotfix0__OnLoginSuc; // 0x28
	private static DelegateBridge __Hotfix0__OnInvalidAccount; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override LoginState myState { get; }

	// RVA: 0x3554ca0 VA: 0x7595b6cca0
	public override LoginState get_myState() { }
	// RVA: 0x3554d08 VA: 0x7595b6cd08
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x35551b4 VA: 0x7595b6d1b4
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3555278 VA: 0x7595b6d278
	public Void EventOnLoginClicked() { }
	// RVA: 0x355534c VA: 0x7595b6d34c
	private Void _OnServiceSuc(LoginResult result) { }
	// RVA: 0x3555510 VA: 0x7595b6d510
	private Void _OnLoginSuc(LoginResult result) { }
	// RVA: 0x35555d4 VA: 0x7595b6d5d4
	private Void _OnInvalidAccount() { }
	// RVA: 0x355569c VA: 0x7595b6d69c
	public Void .ctor() { }
	// RVA: 0x355572c VA: 0x7595b6d72c
	private String <OnRegister>b__7_1() { }
	// RVA: 0x3555748 VA: 0x7595b6d748
	private Void <EventOnLoginClicked>b__9_0() { }
	// RVA: 0x355588c VA: 0x7595b6d88c
	private Void <_OnInvalidAccount>b__12_0() { }
	// RVA: 0x3555894 VA: 0x7595b6d894
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
	// RVA: 0x3555898 VA: 0x7595b6d898
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```