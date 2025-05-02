# SDKPopupAgreementState

**Namespace:** `HGSDK.UI`


## Fields

- `UIUniWebView _webView`

- `Button _closeBtn`


## Methods

- `Void EventOnCloseClicked()`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKPopupAgreementState : UIState
{
	private UIUniWebView _webView; // 0x50
	private Button _closeBtn; // 0x58
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override PopupState myState { get; }

	// RVA: 0x355f414 VA: 0x7595b77414
	public override PopupState get_myState() { }
	// RVA: 0x355f47c VA: 0x7595b7747c
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x355f52c VA: 0x7595b7752c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x355f69c VA: 0x7595b7769c
	public Void EventOnCloseClicked() { }
	// RVA: 0x355f728 VA: 0x7595b77728
	public Void .ctor() { }
	// RVA: 0x355f794 VA: 0x7595b77794
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
	// RVA: 0x355f798 VA: 0x7595b77798
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```