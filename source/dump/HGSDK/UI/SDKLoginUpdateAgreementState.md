# SDKLoginUpdateAgreementState

**Namespace:** `HGSDK.UI`


## Fields

- `Text _registrationTabSelectText`

- `Text _registrationTabUnselectText`

- `Text _PrivacyTabSelectText`

- `Text _PrivacyTabUnselectText`

- `UIUniWebView _webView`

- `TwoStateToggle _agreementToggle`

- `Text _toggleSelectText`

- `Text _toggleUnselectText`

- `TwoStateToggle _confirmBtn`

- `Boolean m_isInited`


## Methods

- `Void OnSelectRegistrationTab()`

- `Void OnSelectPrivacyTab()`

- `Void OnAgreementToggleAgree()`

- `Void OnAgreementToggleDisagree()`

- `Void OnConfirmBtnClick()`

- `Void _InitIfNot()`

- `Void _OnSelectTab(PolicyType)`

- `Void _OnConfirm()`

- `Void <_OnConfirm>b__23_0()`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKLoginUpdateAgreementState : UIState, IHotfixable
{
	private List`1 _tabList; // 0x58
	private Text _registrationTabSelectText; // 0x60
	private Text _registrationTabUnselectText; // 0x68
	private Text _PrivacyTabSelectText; // 0x70
	private Text _PrivacyTabUnselectText; // 0x78
	private UIUniWebView _webView; // 0x80
	private TwoStateToggle _agreementToggle; // 0x88
	private Text _toggleSelectText; // 0x90
	private Text _toggleUnselectText; // 0x98
	private TwoStateToggle _confirmBtn; // 0xa0
	private Boolean m_isInited; // 0xa8
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnSelectRegistrationTab; // 0x18
	private static DelegateBridge __Hotfix0_OnSelectPrivacyTab; // 0x20
	private static DelegateBridge __Hotfix0_OnAgreementToggleAgree; // 0x28
	private static DelegateBridge __Hotfix0_OnAgreementToggleDisagree; // 0x30
	private static DelegateBridge __Hotfix0_OnConfirmBtnClick; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__OnSelectTab; // 0x48
	private static DelegateBridge __Hotfix0__OnConfirm; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override LoginState myState { get; }

	// RVA: 0x35583d0 VA: 0x7595b703d0
	public override LoginState get_myState() { }
	// RVA: 0x3558438 VA: 0x7595b70438
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x35585c0 VA: 0x7595b705c0
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x35587d0 VA: 0x7595b707d0
	public Void OnSelectRegistrationTab() { }
	// RVA: 0x35589b4 VA: 0x7595b709b4
	public Void OnSelectPrivacyTab() { }
	// RVA: 0x3558a20 VA: 0x7595b70a20
	public Void OnAgreementToggleAgree() { }
	// RVA: 0x3558aac VA: 0x7595b70aac
	public Void OnAgreementToggleDisagree() { }
	// RVA: 0x3558b38 VA: 0x7595b70b38
	public Void OnConfirmBtnClick() { }
	// RVA: 0x3558648 VA: 0x7595b70648
	private Void _InitIfNot() { }
	// RVA: 0x355883c VA: 0x7595b7083c
	private Void _OnSelectTab(PolicyType tabType) { }
	// RVA: 0x3558ba0 VA: 0x7595b70ba0
	private Void _OnConfirm() { }
	// RVA: 0x3558cc8 VA: 0x7595b70cc8
	public Void .ctor() { }
	// RVA: 0x3558d58 VA: 0x7595b70d58
	private Void <_OnConfirm>b__23_0() { }
	// RVA: 0x3558d70 VA: 0x7595b70d70
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
	// RVA: 0x3558d74 VA: 0x7595b70d74
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```