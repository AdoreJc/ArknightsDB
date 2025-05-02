# SDKLoginAccountMenuState

**Namespace:** `HGSDK.UI`


## Fields

- `Boolean m_isInvokingCaptcha`


## Methods

- `Void EventOnAccountLoginClicked()`

- `Void EventOnRegisterClicked()`

- `Void _OnLoginSuc(LoginResult)`

- `Void _LegacyDoGuestLogin(String)`

- `Void _LegacyDoGuestCaptchaProcess(LoginProceedInfo)`

- `Void _LegacyInvokeCaptchaSDK(String)`

- `Void _LegacyOnGT3Message(GT3Message)`

- `Void _LegacyOnGuestLoginSuccess(LoginResult, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKLoginAccountMenuState : UIState
{
	private Boolean m_isInvokingCaptcha; // 0x58
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_EventOnAccountLoginClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnRegisterClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__OnLoginSuc; // 0x20
	private static DelegateBridge __Hotfix0__LegacyDoGuestLogin; // 0x28
	private static DelegateBridge __Hotfix0__LegacyDoGuestCaptchaProcess; // 0x30
	private static DelegateBridge __Hotfix0__LegacyInvokeCaptchaSDK; // 0x38
	private static DelegateBridge __Hotfix0__LegacyOnGT3Message; // 0x40
	private static DelegateBridge __Hotfix0__LegacyOnGuestLoginSuccess; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override LoginState myState { get; }

	// RVA: 0x3553a5c VA: 0x7595b6ba5c
	public override LoginState get_myState() { }
	// RVA: 0x3553ac4 VA: 0x7595b6bac4
	public Void EventOnAccountLoginClicked() { }
	// RVA: 0x3553b48 VA: 0x7595b6bb48
	public Void EventOnRegisterClicked() { }
	// RVA: 0x3553bcc VA: 0x7595b6bbcc
	protected override Void OnDestroy() { }
	// RVA: 0x3553c4c VA: 0x7595b6bc4c
	private Void _OnLoginSuc(LoginResult loginResult) { }
	// RVA: 0x3553d10 VA: 0x7595b6bd10
	private Void _LegacyDoGuestLogin(String captcha) { }
	// RVA: 0x3553e70 VA: 0x7595b6be70
	private Void _LegacyDoGuestCaptchaProcess(LoginProceedInfo info) { }
	// RVA: 0x3553fd0 VA: 0x7595b6bfd0
	private Void _LegacyInvokeCaptchaSDK(String initData) { }
	// RVA: 0x35540ec VA: 0x7595b6c0ec
	private Void _LegacyOnGT3Message(GT3Message msg) { }
	// RVA: 0x355418c VA: 0x7595b6c18c
	private Void _LegacyOnGuestLoginSuccess(LoginResult loginResult, String message) { }
	// RVA: 0x355431c VA: 0x7595b6c31c
	public Void .ctor() { }
}
```