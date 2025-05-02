# SDKUnbindLicenseState

**Namespace:** `HGSDK.UI`


## Fields

- `TwoStateToggle _licenseToggle`

- `Button _btnNext`

- `UIUniWebView _webview`

- `State m_toggleState`


## Methods

- `Void _EventOnCloseClicked()`

- `Void _UpdateView()`

- `Void EventOnToggleClicked()`

- `Void EventOnBtnNextClicked()`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `FloatV2Handler <>xLuaBaseProxy_GetFloatV2Handler()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKUnbindLicenseState : UIState
{
	private TwoStateToggle _licenseToggle; // 0x50
	private Button _btnNext; // 0x58
	private Text[] _textsConfirmLicense; // 0x60
	private UIUniWebView _webview; // 0x68
	private State m_toggleState; // 0x70
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_GetFloatV2Handler; // 0x18
	private static DelegateBridge __Hotfix0__EventOnCloseClicked; // 0x20
	private static DelegateBridge __Hotfix0__UpdateView; // 0x28
	private static DelegateBridge __Hotfix0_EventOnToggleClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBtnNextClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override PopupState myState { get; }

	// RVA: 0x3563724 VA: 0x7595b7b724
	public override PopupState get_myState() { }
	// RVA: 0x356378c VA: 0x7595b7b78c
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x356383c VA: 0x7595b7b83c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3563a90 VA: 0x7595b7ba90
	public override FloatV2Handler GetFloatV2Handler() { }
	// RVA: 0x3563bb4 VA: 0x7595b7bbb4
	private Void _EventOnCloseClicked() { }
	// RVA: 0x35639fc VA: 0x7595b7b9fc
	private Void _UpdateView() { }
	// RVA: 0x3563c28 VA: 0x7595b7bc28
	public Void EventOnToggleClicked() { }
	// RVA: 0x3563ca0 VA: 0x7595b7bca0
	public Void EventOnBtnNextClicked() { }
	// RVA: 0x3563d78 VA: 0x7595b7bd78
	public Void .ctor() { }
	// RVA: 0x3563de4 VA: 0x7595b7bde4
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
	// RVA: 0x3563de8 VA: 0x7595b7bde8
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x3563dec VA: 0x7595b7bdec
	private FloatV2Handler <>xLuaBaseProxy_GetFloatV2Handler() { }
}
```