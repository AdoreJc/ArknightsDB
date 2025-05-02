# SDKLoginPage

**Namespace:** `HGSDK.UI`


## Fields

- `Button _returnBtn`

- `SDKPopupWebView _popupWebView`

- `Single _switchSlowFadeDuration`

- `Single _switchQuickFadeDuration`

- `Single _appearFadeDuration`

- `Transform _debugStateHolder`

- `GameObject _debugPanel`

- `Action m_onFail`

- `LoginBottomButtonManager m_bottomBtnManager`


## Properties

- `LoginState state`


## Methods

- `LoginState get_state()`

- `Void set_state(LoginState)`

- `Void SetCallbacks(Action`1, Action)`

- `Void DoPasswordLogin(String, String, Action`1, Action)`

- `Void DoAuth(String, Action`1, Action)`

- `Void StartLoginSucPostProcess(LoginResult, Boolean)`

- `Void ConfirmLoginSucAfterIdentityVerify(LoginResult, Boolean)`

- `Void ProceedAfterAgreement()`

- `Void _ConfirmLoginSucWithIdentityVerify(LoginResult, Boolean)`

- `Void _StartCloudAuthVerify(LoginResult)`

- `Void _StartUnbindGrantRelated(LoginResult)`

- `Void EventOnReturnBtnClicked()`

- `Void EventOnAccountHistory()`

- `Void EventOnGotoAccountMenu()`

- `Void EventOnGotoPasswdLogin()`

- `Void EventOnGotoCaptchaLogin()`

- `Void EventOnOpenRegisterLicense()`

- `Void EventOnOpenPrivacyLicense()`

- `Void EventOnOpenPreAnnounce()`

- `Void EventOnOpenGameServiceLicense()`

- `Void Update()`

- `Boolean _TryFindClosestState(IList`1, out)`

- `Boolean _CheckIfInStack(LoginState)`

- `Void _OnLoginSuc(LoginResult)`

- `Void _UpdateReturnStack(LoginState, Boolean)`

- `Void _TestOnlyReloadDebugStates(UIStateMachine`1)`

- `Void EventOnEnableCloudAuth(GameObject)`

- `Single <>xLuaBaseProxy_get_fadeDuration()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKLoginPage : UIPage
{
	private UIState[] _states; // 0x38
	private Button _returnBtn; // 0x40
	private LoginBottomButton[] _bottomButtons; // 0x48
	private SDKPopupWebView _popupWebView; // 0x50
	private Single _switchSlowFadeDuration; // 0x58
	private Single _switchQuickFadeDuration; // 0x5c
	private Single _appearFadeDuration; // 0x60
	private UIState[] _debugStatePrefabs; // 0x68
	private Transform _debugStateHolder; // 0x70
	private GameObject _debugPanel; // 0x78
	private Action`1 m_onSuc; // 0x80
	private Action m_onFail; // 0x88
	private LoginBottomButtonManager m_bottomBtnManager; // 0x90
	private UIStateMachine`1 m_stateMachine; // 0x98
	private Stack`1 m_stateReturnStack; // 0xa0
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_set_state; // 0x8
	private static DelegateBridge __Hotfix0_get_fadeDuration; // 0x10
	private static DelegateBridge __Hotfix0_SetCallbacks; // 0x18
	private static DelegateBridge __Hotfix0_DoPasswordLogin; // 0x20
	private static DelegateBridge __Hotfix0_DoAuth; // 0x28
	private static DelegateBridge __Hotfix0_StartLoginSucPostProcess; // 0x30
	private static DelegateBridge __Hotfix0_ConfirmLoginSucAfterIdentityVerify; // 0x38
	private static DelegateBridge __Hotfix0_ProceedAfterAgreement; // 0x40
	private static DelegateBridge __Hotfix0__ConfirmLoginSucWithIdentityVerify; // 0x48
	private static DelegateBridge __Hotfix0__StartCloudAuthVerify; // 0x50
	private static DelegateBridge __Hotfix0__StartUnbindGrantRelated; // 0x58
	private static DelegateBridge __Hotfix0_EventOnReturnBtnClicked; // 0x60
	private static DelegateBridge __Hotfix0_EventOnAccountHistory; // 0x68
	private static DelegateBridge __Hotfix0_EventOnGotoAccountMenu; // 0x70
	private static DelegateBridge __Hotfix0_EventOnGotoPasswdLogin; // 0x78
	private static DelegateBridge __Hotfix0_EventOnGotoCaptchaLogin; // 0x80
	private static DelegateBridge __Hotfix0_EventOnOpenRegisterLicense; // 0x88
	private static DelegateBridge __Hotfix0_EventOnOpenPrivacyLicense; // 0x90
	private static DelegateBridge __Hotfix0_EventOnOpenPreAnnounce; // 0x98
	private static DelegateBridge __Hotfix0_EventOnOpenGameServiceLicense; // 0xa0
	private static DelegateBridge __Hotfix0_OnInit; // 0xa8
	private static DelegateBridge __Hotfix0_OnOpen; // 0xb0
	private static DelegateBridge __Hotfix0_OnClose; // 0xb8
	private static DelegateBridge __Hotfix0_Update; // 0xc0
	private static DelegateBridge __Hotfix0__TryFindClosestState; // 0xc8
	private static DelegateBridge __Hotfix0__CheckIfInStack; // 0xd0
	private static DelegateBridge __Hotfix0__OnLoginSuc; // 0xd8
	private static DelegateBridge __Hotfix0__UpdateReturnStack; // 0xe0
	private static DelegateBridge __Hotfix0__ConstructStateMachine; // 0xe8
	private static DelegateBridge __Hotfix0__TestOnlyReloadDebugStates; // 0xf0
	private static DelegateBridge __Hotfix0_EventOnEnableCloudAuth; // 0xf8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x100

	private LoginState state { get; set; }
	protected override Single fadeDuration { get; }

	// RVA: 0x35503b4 VA: 0x7595b683b4
	private LoginState get_state() { }
	// RVA: 0x355043c VA: 0x7595b6843c
	private Void set_state(LoginState value) { }
	// RVA: 0x3550684 VA: 0x7595b68684
	protected override Single get_fadeDuration() { }
	// RVA: 0x35506ec VA: 0x7595b686ec
	public Void SetCallbacks(Action`1 onSuc, Action onFail) { }
	// RVA: 0x3550788 VA: 0x7595b68788
	public Void DoPasswordLogin(String username, String password, Action`1 onSuc, Action onFail) { }
	// RVA: 0x3550928 VA: 0x7595b68928
	public Void DoAuth(String token, Action`1 onSuc, Action onFail) { }
	// RVA: 0x3550a78 VA: 0x7595b68a78
	public Void StartLoginSucPostProcess(LoginResult result, Boolean isGuest) { }
	// RVA: 0x3550cf8 VA: 0x7595b68cf8
	public Void ConfirmLoginSucAfterIdentityVerify(LoginResult result, Boolean isGuest) { }
	// RVA: 0x3550f98 VA: 0x7595b68f98
	public Void ProceedAfterAgreement() { }
	// RVA: 0x3550ba0 VA: 0x7595b68ba0
	private Void _ConfirmLoginSucWithIdentityVerify(LoginResult result, Boolean isGuest) { }
	// RVA: 0x3551070 VA: 0x7595b69070
	private Void _StartCloudAuthVerify(LoginResult result) { }
	// RVA: 0x3550dfc VA: 0x7595b68dfc
	private Void _StartUnbindGrantRelated(LoginResult loginResult) { }
	// RVA: 0x3551248 VA: 0x7595b69248
	public Void EventOnReturnBtnClicked() { }
	// RVA: 0x3551324 VA: 0x7595b69324
	public Void EventOnAccountHistory() { }
	// RVA: 0x3551388 VA: 0x7595b69388
	public Void EventOnGotoAccountMenu() { }
	// RVA: 0x35513f4 VA: 0x7595b693f4
	public Void EventOnGotoPasswdLogin() { }
	// RVA: 0x3551460 VA: 0x7595b69460
	public Void EventOnGotoCaptchaLogin() { }
	// RVA: 0x35514cc VA: 0x7595b694cc
	public Void EventOnOpenRegisterLicense() { }
	// RVA: 0x3551578 VA: 0x7595b69578
	public Void EventOnOpenPrivacyLicense() { }
	// RVA: 0x3551624 VA: 0x7595b69624
	public Void EventOnOpenPreAnnounce() { }
	// RVA: 0x3551690 VA: 0x7595b69690
	public Void EventOnOpenGameServiceLicense() { }
	// RVA: 0x355180c VA: 0x7595b6980c
	protected override Void OnInit() { }
	// RVA: 0x3551b1c VA: 0x7595b69b1c
	protected override Void OnOpen() { }
	// RVA: 0x3551b80 VA: 0x7595b69b80
	protected override Void OnClose() { }
	// RVA: 0x3551be4 VA: 0x7595b69be4
	private Void Update() { }
	// RVA: 0x3551ccc VA: 0x7595b69ccc
	private Boolean _TryFindClosestState(IList`1 states, out LoginState result) { }
	// RVA: 0x3551e68 VA: 0x7595b69e68
	private Boolean _CheckIfInStack(LoginState target) { }
	// RVA: 0x3551f70 VA: 0x7595b69f70
	private Void _OnLoginSuc(LoginResult result) { }
	// RVA: 0x355203c VA: 0x7595b6a03c
	private Void _UpdateReturnStack(LoginState newState, Boolean pushToStack) { }
	// RVA: 0x35519bc VA: 0x7595b699bc
	private UIStateMachine`1 _ConstructStateMachine() { }
	// RVA: 0x35521a4 VA: 0x7595b6a1a4
	private Void _TestOnlyReloadDebugStates(UIStateMachine`1 stateMachine) { }
	// RVA: 0x355230c VA: 0x7595b6a30c
	public Void EventOnEnableCloudAuth(GameObject tickObj) { }
	// RVA: 0x3552384 VA: 0x7595b6a384
	public Void .ctor() { }
	// RVA: 0x355250c VA: 0x7595b6a50c
	private Single <>xLuaBaseProxy_get_fadeDuration() { }
}
```