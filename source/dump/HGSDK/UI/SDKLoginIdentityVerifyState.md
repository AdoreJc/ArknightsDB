# SDKLoginIdentityVerifyState

**Namespace:** `HGSDK.UI`


## Fields

- `Text _policyTitle`

- `Text _policyText`

- `InputField _realNameInput`

- `SDKInputWarning _realNameWarning`

- `InputField _idNumberInput`

- `SDKInputWarning _idNumberWarning`

- `Button _verifyBtn`

- `Button _skipBtn`


## Methods

- `Void EventOnSkipClicked()`

- `Void EventOnVerifyClicked()`

- `Void _DoIdentityVerify()`

- `Void _OnProceed(Boolean)`

- `Void _OnSkipped()`

- `Void <EventOnVerifyClicked>b__12_0(CheckIdCardResponse)`

- `Void <_DoIdentityVerify>b__13_0(UserIdentityAuthResponse)`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKLoginIdentityVerifyState : UIState
{
	private Text _policyTitle; // 0x58
	private Text _policyText; // 0x60
	private InputField _realNameInput; // 0x68
	private SDKInputWarning _realNameWarning; // 0x70
	private InputField _idNumberInput; // 0x78
	private SDKInputWarning _idNumberWarning; // 0x80
	private Button _verifyBtn; // 0x88
	private Button _skipBtn; // 0x90
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_EventOnSkipClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnVerifyClicked; // 0x18
	private static DelegateBridge __Hotfix0__DoIdentityVerify; // 0x20
	private static DelegateBridge __Hotfix0__OnProceed; // 0x28
	private static DelegateBridge __Hotfix0__OnSkipped; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override LoginState myState { get; }

	// RVA: 0x3555b88 VA: 0x7595b6db88
	public override LoginState get_myState() { }
	// RVA: 0x3555bf0 VA: 0x7595b6dbf0
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x35560a0 VA: 0x7595b6e0a0
	public Void EventOnSkipClicked() { }
	// RVA: 0x3556268 VA: 0x7595b6e268
	public Void EventOnVerifyClicked() { }
	// RVA: 0x35563c8 VA: 0x7595b6e3c8
	private Void _DoIdentityVerify() { }
	// RVA: 0x35564d8 VA: 0x7595b6e4d8
	private Void _OnProceed(Boolean isMinor) { }
	// RVA: 0x3556144 VA: 0x7595b6e144
	private Void _OnSkipped() { }
	// RVA: 0x3556618 VA: 0x7595b6e618
	public Void .ctor() { }
	// RVA: 0x35566a8 VA: 0x7595b6e6a8
	private Void <EventOnVerifyClicked>b__12_0(CheckIdCardResponse response) { }
	// RVA: 0x35568d0 VA: 0x7595b6e8d0
	private Void <_DoIdentityVerify>b__13_0(UserIdentityAuthResponse response) { }
	// RVA: 0x3556914 VA: 0x7595b6e914
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
}
```