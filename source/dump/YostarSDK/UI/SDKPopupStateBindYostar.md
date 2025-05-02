# SDKPopupStateBindYostar

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

- `Text _textBind`


## Methods

- `Void EventOnCloseClicked()`

- `Void OnBindClicked()`

- `Void _RenderConstText()`

- `Boolean _IsValidEmail(String)`

- `Void _OnAiriSDKBinded(LinkRet)`

- `Boolean <OnRegister>b__16_0(String)`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKPopupStateBindYostar : UIState
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
	private Text _textBind; // 0xb8
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnBindClicked; // 0x20
	private static DelegateBridge __Hotfix0__RenderConstText; // 0x28
	private static DelegateBridge __Hotfix0__IsValidEmail; // 0x30
	private static DelegateBridge __Hotfix0__OnAiriSDKBinded; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override PopupState myState { get; }

	// RVA: 0x2576948 VA: 0x7594b8e948
	public override PopupState get_myState() { }
	// RVA: 0x25769b0 VA: 0x7594b8e9b0
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x2576d30 VA: 0x7594b8ed30
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x25771a0 VA: 0x7594b8f1a0
	public Void EventOnCloseClicked() { }
	// RVA: 0x2577368 VA: 0x7594b8f368
	public Void OnBindClicked() { }
	// RVA: 0x2576f64 VA: 0x7594b8ef64
	private Void _RenderConstText() { }
	// RVA: 0x25776c4 VA: 0x7594b8f6c4
	private Boolean _IsValidEmail(String email) { }
	// RVA: 0x2577768 VA: 0x7594b8f768
	private Void _OnAiriSDKBinded(LinkRet ret) { }
	// RVA: 0x2577960 VA: 0x7594b8f960
	public Void .ctor() { }
	// RVA: 0x2577ab8 VA: 0x7594b8fab8
	private Boolean <OnRegister>b__16_0(String content) { }
	// RVA: 0x2577abc VA: 0x7594b8fabc
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
	// RVA: 0x2577ac0 VA: 0x7594b8fac0
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```