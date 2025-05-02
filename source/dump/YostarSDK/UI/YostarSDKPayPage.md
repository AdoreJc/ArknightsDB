# YostarSDKPayPage

**Namespace:** `YostarSDK.UI`


## Fields

- `UIRenderTextureImage _blurImage`

- `Single _fadeDuration`

- `RectTransform m_backPanelRectTransform`

- `U8PayParams m_payParams`

- `PayResult m_payResult`

- `String m_payErrorMsg`


## Properties

- `PayState state`

- `U8PayParams payParams`


## Methods

- `PayState get_state()`

- `Void set_state(PayState)`

- `U8PayParams get_payParams()`

- `Void SetPayCallbacks(U8PayParams, Action`1, Action`1)`

- `Void NotifyPayResult(PayResult, U8PayFailMsg)`

- `Void Update()`

- `Boolean CheckIfAccountSyncOrHalt()`

- `Boolean CheckIfTokenValidOrHalt(ResultCode)`

- `Void _OnStateTransitting(UIState, UIState)`

- `Single <>xLuaBaseProxy_get_fadeDuration()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class YostarSDKPayPage : UIPage
{
	private UIState[] _states; // 0x38
	private UIRenderTextureImage _blurImage; // 0x40
	private Single _fadeDuration; // 0x48
	private UIStateMachine`1 m_stateMachine; // 0x50
	private RectTransform m_backPanelRectTransform; // 0x58
	private Action`1 m_onSuc; // 0x60
	private Action`1 m_onFail; // 0x68
	private U8PayParams m_payParams; // 0x70
	private PayResult m_payResult; // 0x78
	private String m_payErrorMsg; // 0x90
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_set_state; // 0x8
	private static DelegateBridge __Hotfix0_get_fadeDuration; // 0x10
	private static DelegateBridge __Hotfix0_get_payParams; // 0x18
	private static DelegateBridge __Hotfix0_SetPayCallbacks; // 0x20
	private static DelegateBridge __Hotfix0_NotifyPayResult; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0_OnOpen; // 0x38
	private static DelegateBridge __Hotfix0_OnClose; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfAccountSyncOrHalt; // 0x50
	private static DelegateBridge __Hotfix0_CheckIfTokenValidOrHalt; // 0x58
	private static DelegateBridge __Hotfix0__OnStateTransitting; // 0x60
	private static DelegateBridge __Hotfix0__ConstructStateMachine; // 0x68
	private static DelegateBridge __Hotfix0__U8FailMsgToString; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	private PayState state { get; set; }
	protected override Single fadeDuration { get; }
	public U8PayParams payParams { get; }

	// RVA: 0x2575544 VA: 0x7594b8d544
	private PayState get_state() { }
	// RVA: 0x25755cc VA: 0x7594b8d5cc
	private Void set_state(PayState value) { }
	// RVA: 0x257595c VA: 0x7594b8d95c
	protected override Single get_fadeDuration() { }
	// RVA: 0x25759c4 VA: 0x7594b8d9c4
	public U8PayParams get_payParams() { }
	// RVA: 0x2575a2c VA: 0x7594b8da2c
	public Void SetPayCallbacks(U8PayParams payParams, Action`1 onSuc, Action`1 onFail) { }
	// RVA: 0x2575aec VA: 0x7594b8daec
	public Void NotifyPayResult(PayResult payResult, U8PayFailMsg failMsg) { }
	// RVA: 0x2575d90 VA: 0x7594b8dd90
	protected override Void OnInit() { }
	// RVA: 0x2575fc0 VA: 0x7594b8dfc0
	protected override Void OnOpen() { }
	// RVA: 0x2576024 VA: 0x7594b8e024
	protected override Void OnClose() { }
	// RVA: 0x25761ac VA: 0x7594b8e1ac
	private Void Update() { }
	// RVA: 0x2576294 VA: 0x7594b8e294
	public Boolean CheckIfAccountSyncOrHalt() { }
	// RVA: 0x25763cc VA: 0x7594b8e3cc
	public Boolean CheckIfTokenValidOrHalt(ResultCode code) { }
	// RVA: 0x2575718 VA: 0x7594b8d718
	private Void _OnStateTransitting(UIState curState, UIState nextState) { }
	// RVA: 0x2575e84 VA: 0x7594b8de84
	private UIStateMachine`1 _ConstructStateMachine() { }
	// RVA: 0x2575bdc VA: 0x7594b8dbdc
	private static String _U8FailMsgToString(U8PayFailMsg msg) { }
	// RVA: 0x25765c0 VA: 0x7594b8e5c0
	public Void .ctor() { }
	// RVA: 0x25766c4 VA: 0x7594b8e6c4
	private Single <>xLuaBaseProxy_get_fadeDuration() { }
}
```