# YostarSDKPopupPage

**Namespace:** `YostarSDK.UI`


## Fields

- `Button _returnBtn`

- `UIBlurFloatPanel _blurBkg`

- `Single _switchQuickFadeDuration`

- `Action m_onPageClosed`

- `PopupState m_initTargetState`

- `DataBundle m_initBundle`


## Properties

- `PopupState state`


## Methods

- `Void SetInitState(PopupState, DataBundle)`

- `PopupState GetInitTargetState()`

- `DataBundle GetInitBundle()`

- `Void SetCallbacks(Action)`

- `PopupState get_state()`

- `Void set_state(PopupState)`

- `Void Update()`

- `Boolean CheckIfAccountSyncOrHalt()`

- `Boolean CheckIfTokenValidOrHalt(ResultCode)`

- `Void ClosePage()`

- `Void _UpdateBlurBkgStatus(Boolean)`

- `Void _UpdateReturnStack(PopupState, Boolean)`

- `Void _OnStateTransitionStart(IUIState, IUIState)`

- `Single <>xLuaBaseProxy_get_fadeDuration()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class YostarSDKPopupPage : UIPage
{
	public const String KEY_SHOP_AGREEMENT_TYPE; // 0x0
	private UIState[] _states; // 0x38
	private Button _returnBtn; // 0x40
	private UIBlurFloatPanel _blurBkg; // 0x48
	private Single _switchQuickFadeDuration; // 0x50
	private UIStateMachine`1 m_stateMachine; // 0x58
	private Stack`1 m_stateReturnStack; // 0x60
	private Action m_onPageClosed; // 0x68
	private PopupState m_initTargetState; // 0x70
	private DataBundle m_initBundle; // 0x78
	private static DelegateBridge __Hotfix0_SetInitState; // 0x0
	private static DelegateBridge __Hotfix0_GetInitTargetState; // 0x8
	private static DelegateBridge __Hotfix0_GetInitBundle; // 0x10
	private static DelegateBridge __Hotfix0_SetCallbacks; // 0x18
	private static DelegateBridge __Hotfix0_get_fadeDuration; // 0x20
	private static DelegateBridge __Hotfix0_get_state; // 0x28
	private static DelegateBridge __Hotfix0_set_state; // 0x30
	private static DelegateBridge __Hotfix0_OnInit; // 0x38
	private static DelegateBridge __Hotfix0_OnOpen; // 0x40
	private static DelegateBridge __Hotfix0_OnClose; // 0x48
	private static DelegateBridge __Hotfix0_Update; // 0x50
	private static DelegateBridge __Hotfix0_CheckIfAccountSyncOrHalt; // 0x58
	private static DelegateBridge __Hotfix0_CheckIfTokenValidOrHalt; // 0x60
	private static DelegateBridge __Hotfix0_ClosePage; // 0x68
	private static DelegateBridge __Hotfix0__UpdateBlurBkgStatus; // 0x70
	private static DelegateBridge __Hotfix0__UpdateReturnStack; // 0x78
	private static DelegateBridge __Hotfix0__ConstructStateMachine; // 0x80
	private static DelegateBridge __Hotfix0__OnStateTransitionStart; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	protected override Single fadeDuration { get; }
	private PopupState state { get; set; }

	// RVA: 0x257ac9c VA: 0x7594b92c9c
	public Void SetInitState(PopupState targetState, DataBundle initBundle) { }
	// RVA: 0x2577f10 VA: 0x7594b8ff10
	public PopupState GetInitTargetState() { }
	// RVA: 0x2578c20 VA: 0x7594b90c20
	public DataBundle GetInitBundle() { }
	// RVA: 0x257ad2c VA: 0x7594b92d2c
	public Void SetCallbacks(Action onPageClosed) { }
	// RVA: 0x257adb0 VA: 0x7594b92db0
	protected override Single get_fadeDuration() { }
	// RVA: 0x257ae1c VA: 0x7594b92e1c
	private PopupState get_state() { }
	// RVA: 0x257aea4 VA: 0x7594b92ea4
	private Void set_state(PopupState value) { }
	// RVA: 0x257af5c VA: 0x7594b92f5c
	protected override Void OnInit() { }
	// RVA: 0x257b1ec VA: 0x7594b931ec
	protected override Void OnOpen() { }
	// RVA: 0x257b250 VA: 0x7594b93250
	protected override Void OnClose() { }
	// RVA: 0x257b2d4 VA: 0x7594b932d4
	private Void Update() { }
	// RVA: 0x257762c VA: 0x7594b8f62c
	public Boolean CheckIfAccountSyncOrHalt() { }
	// RVA: 0x2577b9c VA: 0x7594b8fb9c
	public Boolean CheckIfTokenValidOrHalt(ResultCode code) { }
	// RVA: 0x25772ec VA: 0x7594b8f2ec
	public Void ClosePage() { }
	// RVA: 0x257b518 VA: 0x7594b93518
	private Void _UpdateBlurBkgStatus(Boolean isShow) { }
	// RVA: 0x257b5dc VA: 0x7594b935dc
	private Void _UpdateReturnStack(PopupState newState, Boolean pushToStack) { }
	// RVA: 0x257b02c VA: 0x7594b9302c
	private UIStateMachine`1 _ConstructStateMachine() { }
	// RVA: 0x257b744 VA: 0x7594b93744
	private Void _OnStateTransitionStart(IUIState rawFromState, IUIState rawToState) { }
	// RVA: 0x257b8d8 VA: 0x7594b938d8
	public Void .ctor() { }
	// RVA: 0x257b9f0 VA: 0x7594b939f0
	private Single <>xLuaBaseProxy_get_fadeDuration() { }
}
```