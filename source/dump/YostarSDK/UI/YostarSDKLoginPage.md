# YostarSDKLoginPage

**Namespace:** `YostarSDK.UI`


## Fields

- `Button _returnBtn`

- `UIBlurFloatPanel _blurBkg`

- `Single _switchSlowFadeDuration`

- `Single _switchQuickFadeDuration`

- `Text _textAnnounce`

- `Text _textAccountMenu`

- `Text _textAgreement`

- `Text _textHelpshift`

- `LoginBottomButtonManager m_bottomBtnManager`

- `Action m_onLoginFailCB`


## Properties

- `LoginState state`


## Methods

- `LoginState get_state()`

- `Void set_state(LoginState)`

- `Void SetLoginCallbacks(Action`1, Action)`

- `Void ClearLoginCallbacks()`

- `Void OnAiriSDKInit(InitRet)`

- `Void OnAiriSDKLogin(LoginRet)`

- `Void ProcessLogin()`

- `Void ConfirmLoginWithNewAccountLink(LoginRet, Action)`

- `Void _NewAccountLink(Action)`

- `Void RaiseErrorForLogin(LoginRet, Action)`

- `Void _UpdateBlurBkgStatus(Boolean)`

- `Void Update()`

- `Void EventOnReturnBtnClicked()`

- `Void EventOnPreannounceClicked()`

- `Void EventOnAgreementClicked()`

- `Void EventOnAccountMenuClicked()`

- `Void EventOnHelpshiftClicked()`

- `Void _UpdateReturnStack(LoginState, Boolean)`

- `Void _OnStateTransitionStart(IUIState, IUIState)`

- `Void _RenderConstText()`

- `Void _UpdateBottomButtons()`

- `Single <>xLuaBaseProxy_get_fadeDuration()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class YostarSDKLoginPage : UIPage
{
	private UIState[] _states; // 0x38
	private Button _returnBtn; // 0x40
	private YostarLoginBottomButton[] _bottomButtons; // 0x48
	private UIBlurFloatPanel _blurBkg; // 0x50
	private Single _switchSlowFadeDuration; // 0x58
	private Single _switchQuickFadeDuration; // 0x5c
	private Text _textAnnounce; // 0x60
	private Text _textAccountMenu; // 0x68
	private Text _textAgreement; // 0x70
	private Text _textHelpshift; // 0x78
	private LoginBottomButtonManager m_bottomBtnManager; // 0x80
	private UIStateMachine`1 m_stateMachine; // 0x88
	private Stack`1 m_stateReturnStack; // 0x90
	private Action`1 m_onLoginSucCB; // 0x98
	private Action m_onLoginFailCB; // 0xa0
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_set_state; // 0x8
	private static DelegateBridge __Hotfix0_SetLoginCallbacks; // 0x10
	private static DelegateBridge __Hotfix0_ClearLoginCallbacks; // 0x18
	private static DelegateBridge __Hotfix0_get_fadeDuration; // 0x20
	private static DelegateBridge __Hotfix0_OnAiriSDKInit; // 0x28
	private static DelegateBridge __Hotfix0_OnAiriSDKLogin; // 0x30
	private static DelegateBridge __Hotfix0_ProcessLogin; // 0x38
	private static DelegateBridge __Hotfix0_ConfirmLoginWithNewAccountLink; // 0x40
	private static DelegateBridge __Hotfix0__NewAccountLink; // 0x48
	private static DelegateBridge __Hotfix0_RaiseErrorForLogin; // 0x50
	private static DelegateBridge __Hotfix0__UpdateBlurBkgStatus; // 0x58
	private static DelegateBridge __Hotfix0_OnInit; // 0x60
	private static DelegateBridge __Hotfix0_OnOpen; // 0x68
	private static DelegateBridge __Hotfix0_OnClose; // 0x70
	private static DelegateBridge __Hotfix0_Update; // 0x78
	private static DelegateBridge __Hotfix0_EventOnReturnBtnClicked; // 0x80
	private static DelegateBridge __Hotfix0_EventOnPreannounceClicked; // 0x88
	private static DelegateBridge __Hotfix0_EventOnAgreementClicked; // 0x90
	private static DelegateBridge __Hotfix0_EventOnAccountMenuClicked; // 0x98
	private static DelegateBridge __Hotfix0_EventOnHelpshiftClicked; // 0xa0
	private static DelegateBridge __Hotfix0__UpdateReturnStack; // 0xa8
	private static DelegateBridge __Hotfix0__ConstructStateMachine; // 0xb0
	private static DelegateBridge __Hotfix0__OnStateTransitionStart; // 0xb8
	private static DelegateBridge __Hotfix0__RenderConstText; // 0xc0
	private static DelegateBridge __Hotfix0__UpdateBottomButtons; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	private LoginState state { get; set; }
	protected override Single fadeDuration { get; }

	// RVA: 0x1b495f8 VA: 0x75941615f8
	private LoginState get_state() { }
	// RVA: 0x1b49680 VA: 0x7594161680
	private Void set_state(LoginState value) { }
	// RVA: 0x1b43b64 VA: 0x759415bb64
	public Void SetLoginCallbacks(Action`1 onSuc, Action onFail) { }
	// RVA: 0x1b498b4 VA: 0x75941618b4
	public Void ClearLoginCallbacks() { }
	// RVA: 0x1b49934 VA: 0x7594161934
	protected override Single get_fadeDuration() { }
	// RVA: 0x1b4638c VA: 0x759415e38c
	public Void OnAiriSDKInit(InitRet ret) { }
	// RVA: 0x1b452b8 VA: 0x759415d2b8
	public Void OnAiriSDKLogin(LoginRet ret) { }
	// RVA: 0x1b4536c VA: 0x759415d36c
	public Void ProcessLogin() { }
	// RVA: 0x1b483bc VA: 0x75941603bc
	public Void ConfirmLoginWithNewAccountLink(LoginRet ret, Action onFail) { }
	// RVA: 0x1b49aa4 VA: 0x7594161aa4
	private Void _NewAccountLink(Action onFail) { }
	// RVA: 0x1b45464 VA: 0x759415d464
	public Void RaiseErrorForLogin(LoginRet ret, Action nextStep) { }
	// RVA: 0x1b49bf8 VA: 0x7594161bf8
	private Void _UpdateBlurBkgStatus(Boolean isShow) { }
	// RVA: 0x1b49cbc VA: 0x7594161cbc
	protected override Void OnInit() { }
	// RVA: 0x1b4a100 VA: 0x7594162100
	protected override Void OnOpen() { }
	// RVA: 0x1b4a164 VA: 0x7594162164
	protected override Void OnClose() { }
	// RVA: 0x1b4a1c8 VA: 0x75941621c8
	private Void Update() { }
	// RVA: 0x1b4a2b0 VA: 0x75941622b0
	public Void EventOnReturnBtnClicked() { }
	// RVA: 0x1b4a38c VA: 0x759416238c
	public Void EventOnPreannounceClicked() { }
	// RVA: 0x1b4a3f8 VA: 0x75941623f8
	public Void EventOnAgreementClicked() { }
	// RVA: 0x1b4a4c8 VA: 0x75941624c8
	public Void EventOnAccountMenuClicked() { }
	// RVA: 0x1b4a534 VA: 0x7594162534
	public Void EventOnHelpshiftClicked() { }
	// RVA: 0x1b4a5c0 VA: 0x75941625c0
	private Void _UpdateReturnStack(LoginState newState, Boolean pushToStack) { }
	// RVA: 0x1b49e4c VA: 0x7594161e4c
	private UIStateMachine`1 _ConstructStateMachine() { }
	// RVA: 0x1b4a728 VA: 0x7594162728
	private Void _OnStateTransitionStart(IUIState rawFromState, IUIState rawToState) { }
	// RVA: 0x1b4a00c VA: 0x759416200c
	private Void _RenderConstText() { }
	// RVA: 0x1b499a0 VA: 0x75941619a0
	private Void _UpdateBottomButtons() { }
	// RVA: 0x1b4a8bc VA: 0x75941628bc
	public Void .ctor() { }
	// RVA: 0x1b4aa34 VA: 0x7594162a34
	private Single <>xLuaBaseProxy_get_fadeDuration() { }
}
```