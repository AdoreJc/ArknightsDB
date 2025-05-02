# SDKPayPage

**Namespace:** `HGSDK.UI`


## Fields

- `UIRenderTextureImage _blurImage`

- `CanvasGroup _backPanelImage`

- `Button _closeBtn`

- `SDKPopupWebView _popupWebView`

- `Single _fadeDuration`

- `RectTransform m_backPanelRectTransform`

- `Action m_onFail`

- `PayResult m_payResult`


## Properties

- `PayState state`


## Methods

- `PayState get_state()`

- `Void set_state(PayState)`

- `Void SetCallbacks(Action`1, Action)`

- `Void NotifyPayResult(PayResult)`

- `Void DoPasswordLogin(String, String, Action`1, Action)`

- `Void StartUpgradeGuestAfterLogin(LoginResult)`

- `Void EventOnCloseClicked()`

- `Void EventOnGotoPasswdLogin()`

- `Void EventOnGotoCaptchaLogin()`

- `Void EventOnOpenRegisterLicense()`

- `Void EventOnOpenPrivacyLicense()`

- `Void Update()`

- `Void _OnStateTransitting(UIState, UIState)`

- `Single <>xLuaBaseProxy_get_fadeDuration()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKPayPage : UIPage
{
	private UIState[] _states; // 0x38
	private UIRenderTextureImage _blurImage; // 0x40
	private CanvasGroup _backPanelImage; // 0x48
	private Button _closeBtn; // 0x50
	private SDKPopupWebView _popupWebView; // 0x58
	private Single _fadeDuration; // 0x60
	private UIStateMachine`1 m_stateMachine; // 0x68
	private RectTransform m_backPanelRectTransform; // 0x70
	private Action`1 m_onSuc; // 0x78
	private Action m_onFail; // 0x80
	private PayResult m_payResult; // 0x88
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_set_state; // 0x8
	private static DelegateBridge __Hotfix0_SetCallbacks; // 0x10
	private static DelegateBridge __Hotfix0_NotifyPayResult; // 0x18
	private static DelegateBridge __Hotfix0_get_fadeDuration; // 0x20
	private static DelegateBridge __Hotfix0_DoPasswordLogin; // 0x28
	private static DelegateBridge __Hotfix0_StartUpgradeGuestAfterLogin; // 0x30
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnGotoPasswdLogin; // 0x40
	private static DelegateBridge __Hotfix0_EventOnGotoCaptchaLogin; // 0x48
	private static DelegateBridge __Hotfix0_EventOnOpenRegisterLicense; // 0x50
	private static DelegateBridge __Hotfix0_EventOnOpenPrivacyLicense; // 0x58
	private static DelegateBridge __Hotfix0_OnInit; // 0x60
	private static DelegateBridge __Hotfix0_OnOpen; // 0x68
	private static DelegateBridge __Hotfix0_OnClose; // 0x70
	private static DelegateBridge __Hotfix0_Update; // 0x78
	private static DelegateBridge __Hotfix0__OnStateTransitting; // 0x80
	private static DelegateBridge __Hotfix0__ConstructStateMachine; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	private PayState state { get; set; }
	protected override Single fadeDuration { get; }

	// RVA: 0x3558df4 VA: 0x7595b70df4
	private PayState get_state() { }
	// RVA: 0x3558e7c VA: 0x7595b70e7c
	private Void set_state(PayState value) { }
	// RVA: 0x35592a4 VA: 0x7595b712a4
	public Void SetCallbacks(Action`1 onSuc, Action onFail) { }
	// RVA: 0x3559340 VA: 0x7595b71340
	public Void NotifyPayResult(PayResult payResult) { }
	// RVA: 0x35593d0 VA: 0x7595b713d0
	protected override Single get_fadeDuration() { }
	// RVA: 0x3559438 VA: 0x7595b71438
	public Void DoPasswordLogin(String username, String password, Action`1 onSuc, Action onFail) { }
	// RVA: 0x35595d8 VA: 0x7595b715d8
	public Void StartUpgradeGuestAfterLogin(LoginResult result) { }
	// RVA: 0x3559768 VA: 0x7595b71768
	public Void EventOnCloseClicked() { }
	// RVA: 0x3559894 VA: 0x7595b71894
	public Void EventOnGotoPasswdLogin() { }
	// RVA: 0x3559900 VA: 0x7595b71900
	public Void EventOnGotoCaptchaLogin() { }
	// RVA: 0x355996c VA: 0x7595b7196c
	public Void EventOnOpenRegisterLicense() { }
	// RVA: 0x3559a18 VA: 0x7595b71a18
	public Void EventOnOpenPrivacyLicense() { }
	// RVA: 0x3559ac4 VA: 0x7595b71ac4
	protected override Void OnInit() { }
	// RVA: 0x3559e00 VA: 0x7595b71e00
	protected override Void OnOpen() { }
	// RVA: 0x3559e64 VA: 0x7595b71e64
	protected override Void OnClose() { }
	// RVA: 0x3559f80 VA: 0x7595b71f80
	private Void Update() { }
	// RVA: 0x3558fc8 VA: 0x7595b70fc8
	private Void _OnStateTransitting(UIState curState, UIState nextState) { }
	// RVA: 0x3559cc4 VA: 0x7595b71cc4
	private UIStateMachine`1 _ConstructStateMachine() { }
	// RVA: 0x355a140 VA: 0x7595b72140
	public Void .ctor() { }
	// RVA: 0x355a23c VA: 0x7595b7223c
	private Single <>xLuaBaseProxy_get_fadeDuration() { }
}
```