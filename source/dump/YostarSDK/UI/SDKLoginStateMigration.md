# SDKLoginStateMigration

**Namespace:** `YostarSDK.UI`


## Fields

- `InputField _migrationCodeInput`

- `SDKInputWarning _migrationCodeInputWarning`

- `InputField _uidInput`

- `SDKInputWarning _uidInputWarning`

- `Button _loginBtn`

- `Text _textTitle`

- `Text _textDesc`

- `Text _hintId`

- `Text _hintCode`

- `Text _textInvalidId`

- `Text _textInvalidCode`

- `Text _textConfirm`


## Methods

- `Void OnLoginClicked()`

- `Void _OnAiriSDKLogin(LoginRet)`

- `Void _RenderConstText()`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKLoginStateMigration : UIState
{
	private InputField _migrationCodeInput; // 0x50
	private SDKInputWarning _migrationCodeInputWarning; // 0x58
	private InputField _uidInput; // 0x60
	private SDKInputWarning _uidInputWarning; // 0x68
	private Button _loginBtn; // 0x70
	private Text _textTitle; // 0x78
	private Text _textDesc; // 0x80
	private Text _hintId; // 0x88
	private Text _hintCode; // 0x90
	private Text _textInvalidId; // 0x98
	private Text _textInvalidCode; // 0xa0
	private Text _textConfirm; // 0xa8
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnLoginClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnAiriSDKLogin; // 0x20
	private static DelegateBridge __Hotfix0__RenderConstText; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override LoginState myState { get; }

	// RVA: 0x1b46610 VA: 0x759415e610
	public override LoginState get_myState() { }
	// RVA: 0x1b46678 VA: 0x759415e678
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x1b46a44 VA: 0x759415ea44
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1b46c7c VA: 0x759415ec7c
	public Void OnLoginClicked() { }
	// RVA: 0x1b46f28 VA: 0x759415ef28
	private Void _OnAiriSDKLogin(LoginRet ret) { }
	// RVA: 0x1b46b1c VA: 0x759415eb1c
	private Void _RenderConstText() { }
	// RVA: 0x1b46fe4 VA: 0x759415efe4
	public Void .ctor() { }
	// RVA: 0x1b47050 VA: 0x759415f050
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
	// RVA: 0x1b47054 VA: 0x759415f054
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```