# PayIdentityVerifyState

**Namespace:** `HGSDK.UI`


## Fields

- `Text _policyTitle`

- `Text _policyText`

- `InputField _realNameInput`

- `SDKInputWarning _realNameWarning`

- `InputField _idNumberInput`

- `SDKInputWarning _idNumberWarning`

- `Button _verifyBtn`


## Methods

- `Void EventOnVerifyClicked()`

- `Void _DoIdentityVerify()`

- `Void <EventOnVerifyClicked>b__12_0(CheckIdCardResponse)`

- `Void <_DoIdentityVerify>b__13_0(UserIdentityAuthResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class PayIdentityVerifyState : UIState
{
	private Text _policyTitle; // 0x48
	private Text _policyText; // 0x50
	private InputField _realNameInput; // 0x58
	private SDKInputWarning _realNameWarning; // 0x60
	private InputField _idNumberInput; // 0x68
	private SDKInputWarning _idNumberWarning; // 0x70
	private Button _verifyBtn; // 0x78
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_get_showBackPanel; // 0x8
	private static DelegateBridge __Hotfix0_OnRegister; // 0x10
	private static DelegateBridge __Hotfix0_EventOnVerifyClicked; // 0x18
	private static DelegateBridge __Hotfix0__DoIdentityVerify; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override PayState myState { get; }
	public override Boolean showBackPanel { get; }

	// RVA: 0x355b088 VA: 0x7595b73088
	public override PayState get_myState() { }
	// RVA: 0x355b0f0 VA: 0x7595b730f0
	public override Boolean get_showBackPanel() { }
	// RVA: 0x355b158 VA: 0x7595b73158
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x355b5a8 VA: 0x7595b735a8
	public Void EventOnVerifyClicked() { }
	// RVA: 0x355b708 VA: 0x7595b73708
	private Void _DoIdentityVerify() { }
	// RVA: 0x355b818 VA: 0x7595b73818
	public Void .ctor() { }
	// RVA: 0x355b884 VA: 0x7595b73884
	private Void <EventOnVerifyClicked>b__12_0(CheckIdCardResponse response) { }
	// RVA: 0x355baac VA: 0x7595b73aac
	private Void <_DoIdentityVerify>b__13_0(UserIdentityAuthResponse response) { }
}
```