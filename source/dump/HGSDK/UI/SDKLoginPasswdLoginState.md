# SDKLoginPasswdLoginState

**Namespace:** `HGSDK.UI`


## Fields

- `InputField _usernameInput`

- `SDKInputWarning _usernameInputWarning`

- `InputField _passwordInput`

- `SDKInputWarning _passwordInputWarning`

- `Button _loginBtn`

- `Text _loginBtnText`


## Methods

- `Void EventOnLoginClicked()`

- `Void _OnServiceSuc(LoginResult)`

- `Void _OnLoginSuc(LoginResult)`

- `Void <EventOnLoginClicked>b__10_0()`

- `Void <EventOnLoginClicked>b__10_1()`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKLoginPasswdLoginState : UIState
{
	private InputField _usernameInput; // 0x58
	private SDKInputWarning _usernameInputWarning; // 0x60
	private InputField _passwordInput; // 0x68
	private SDKInputWarning _passwordInputWarning; // 0x70
	private Button _loginBtn; // 0x78
	private Text _loginBtnText; // 0x80
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_EventOnLoginClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnServiceSuc; // 0x20
	private static DelegateBridge __Hotfix0__OnLoginSuc; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override LoginState myState { get; }

	// RVA: 0x3556a60 VA: 0x7595b6ea60
	public override LoginState get_myState() { }
	// RVA: 0x3556ac8 VA: 0x7595b6eac8
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x3556d94 VA: 0x7595b6ed94
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3556e58 VA: 0x7595b6ee58
	public Void EventOnLoginClicked() { }
	// RVA: 0x3556f88 VA: 0x7595b6ef88
	private Void _OnServiceSuc(LoginResult result) { }
	// RVA: 0x355714c VA: 0x7595b6f14c
	private Void _OnLoginSuc(LoginResult result) { }
	// RVA: 0x3557210 VA: 0x7595b6f210
	public Void .ctor() { }
	// RVA: 0x35572a0 VA: 0x7595b6f2a0
	private Void <EventOnLoginClicked>b__10_0() { }
	// RVA: 0x35573ac VA: 0x7595b6f3ac
	private Void <EventOnLoginClicked>b__10_1() { }
	// RVA: 0x3557408 VA: 0x7595b6f408
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
	// RVA: 0x355740c VA: 0x7595b6f40c
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```