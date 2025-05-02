# PayPasswdLoginState

**Namespace:** `HGSDK.UI`


## Fields

- `InputField _usernameInput`

- `SDKInputWarning _usernameInputWarning`

- `InputField _passwordInput`

- `SDKInputWarning _passwordInputWarning`

- `Button _loginBtn`


## Methods

- `Void EventOnLoginClicked()`

- `Void <EventOnLoginClicked>b__10_0(LoginResult)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class PayPasswdLoginState : UIState
{
	private InputField _usernameInput; // 0x48
	private SDKInputWarning _usernameInputWarning; // 0x50
	private InputField _passwordInput; // 0x58
	private SDKInputWarning _passwordInputWarning; // 0x60
	private Button _loginBtn; // 0x68
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_get_showBackPanel; // 0x8
	private static DelegateBridge __Hotfix0_OnRegister; // 0x10
	private static DelegateBridge __Hotfix0_EventOnLoginClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override PayState myState { get; }
	public override Boolean showBackPanel { get; }

	// RVA: 0x355bd20 VA: 0x7595b73d20
	public override PayState get_myState() { }
	// RVA: 0x355bd88 VA: 0x7595b73d88
	public override Boolean get_showBackPanel() { }
	// RVA: 0x355bdf0 VA: 0x7595b73df0
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x355c0ac VA: 0x7595b740ac
	public Void EventOnLoginClicked() { }
	// RVA: 0x355c1dc VA: 0x7595b741dc
	public Void .ctor() { }
	// RVA: 0x355c248 VA: 0x7595b74248
	private Void <EventOnLoginClicked>b__10_0(LoginResult result) { }
}
```