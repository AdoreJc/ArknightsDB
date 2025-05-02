# SDKLoginStateYostar

**Namespace:** `YostarSDK.UI`


## Fields

- `InputField _emailInput`

- `SDKInputWarning _emailInputWarning`

- `InputField _captchaInput`

- `SDKInputWarning _captchaInputWarning`

- `Text _textTitle`

- `Text _hintEmail`

- `Text _hintCode`

- `Text _textInvalidEmail`

- `Text _textInvalidCode`

- `Text _textSendCode`

- `Text _textLogin`

- `Action m_latestLoginAction`


## Methods

- `Void OnLoginClicked()`

- `Void _LoginPreventAccountDeleted(Action)`

- `Boolean _IsValidEmail(String)`

- `Void _OnAiriSDKLogin(LoginRet)`

- `Void _RenderConstText()`

- `Boolean <OnRegister>b__14_0(String)`

- `Void <OnLoginClicked>b__16_0()`

- `Void <_OnAiriSDKLogin>b__19_0()`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKLoginStateYostar : UIState
{
	private InputField _emailInput; // 0x50
	private SDKInputWarning _emailInputWarning; // 0x58
	private InputField _captchaInput; // 0x60
	private SDKInputWarning _captchaInputWarning; // 0x68
	private Text _textTitle; // 0x70
	private Text _hintEmail; // 0x78
	private Text _hintCode; // 0x80
	private Text _textInvalidEmail; // 0x88
	private Text _textInvalidCode; // 0x90
	private Text _textSendCode; // 0x98
	private Text _textLogin; // 0xa0
	private Action m_latestLoginAction; // 0xa8
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnLoginClicked; // 0x18
	private static DelegateBridge __Hotfix0__LoginPreventAccountDeleted; // 0x20
	private static DelegateBridge __Hotfix0__IsValidEmail; // 0x28
	private static DelegateBridge __Hotfix0__OnAiriSDKLogin; // 0x30
	private static DelegateBridge __Hotfix0__RenderConstText; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override LoginState myState { get; }

	// RVA: 0x1b48b94 VA: 0x7594160b94
	public override LoginState get_myState() { }
	// RVA: 0x1b48bfc VA: 0x7594160bfc
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x1b48e54 VA: 0x7594160e54
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1b4908c VA: 0x759416108c
	public Void OnLoginClicked() { }
	// RVA: 0x1b49170 VA: 0x7594161170
	private Void _LoginPreventAccountDeleted(Action loginAction) { }
	// RVA: 0x1b4921c VA: 0x759416121c
	private Boolean _IsValidEmail(String email) { }
	// RVA: 0x1b492bc VA: 0x75941612bc
	private Void _OnAiriSDKLogin(LoginRet ret) { }
	// RVA: 0x1b48f2c VA: 0x7594160f2c
	private Void _RenderConstText() { }
	// RVA: 0x1b493ec VA: 0x75941613ec
	public Void .ctor() { }
	// RVA: 0x1b49458 VA: 0x7594161458
	private Boolean <OnRegister>b__14_0(String content) { }
	// RVA: 0x1b4945c VA: 0x759416145c
	private Void <OnLoginClicked>b__16_0() { }
	// RVA: 0x1b4952c VA: 0x759416152c
	private Void <_OnAiriSDKLogin>b__19_0() { }
	// RVA: 0x1b49548 VA: 0x7594161548
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
	// RVA: 0x1b4954c VA: 0x759416154c
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```