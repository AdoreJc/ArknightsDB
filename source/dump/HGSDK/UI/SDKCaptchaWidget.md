# SDKCaptchaWidget

**Namespace:** `HGSDK.UI`


## Fields

- `InputField _captchaInput`

- `SDKInputWarning _captchaInputWarning`

- `Button _sendCaptchaBtn`

- `Text _sendCaptchaBtnText`

- `Single _sendCaptchaCooldown`

- `SDKInputWarning _warningHint`

- `Int64 m_nextAllowCaptchaTs`

- `Boolean m_canSendCaptcha`

- `Options <options>k__BackingField`


## Properties

- `InputField input`

- `String captcha`

- `SDKInputWarning warning`

- `Options options`


## Methods

- `InputField get_input()`

- `String get_captcha()`

- `SDKInputWarning get_warning()`

- `Options get_options()`

- `Void set_options(Options)`

- `Void RegisterOnFetchPhoneNumber(Func`1)`

- `Void EventOnSendCaptchaClicked()`

- `Void SetNextAllowCaptchaTs(Int64)`

- `Void _OnUpdate()`

- `Void Start()`

- `Void Update()`

- `Void _OnSendCaptchaSucV1(UserSendSmsCodeResponse)`

- `Void _OnSendCaptchaSucV2(APIV2RespWrapper`1)`

- `Void _OnSendCaptchaFailV2(APIV2FailResponse)`

- `Void _OnSendCaptchaSuc()`

- `Void _OnSendCaptchaFail()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKCaptchaWidget : MonoBehaviour, IHotfixable
{
	private InputField _captchaInput; // 0x18
	private SDKInputWarning _captchaInputWarning; // 0x20
	private Button _sendCaptchaBtn; // 0x28
	private Text _sendCaptchaBtnText; // 0x30
	private Single _sendCaptchaCooldown; // 0x38
	private SDKInputWarning _warningHint; // 0x40
	private Func`1 m_onFetchPhoneNumber; // 0x48
	private Int64 m_nextAllowCaptchaTs; // 0x50
	private Boolean m_canSendCaptcha; // 0x58
	private Options <options>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_input; // 0x0
	private static DelegateBridge __Hotfix0_get_captcha; // 0x8
	private static DelegateBridge __Hotfix0_get_warning; // 0x10
	private static DelegateBridge __Hotfix0_get_options; // 0x18
	private static DelegateBridge __Hotfix0_set_options; // 0x20
	private static DelegateBridge __Hotfix0_RegisterOnFetchPhoneNumber; // 0x28
	private static DelegateBridge __Hotfix0_EventOnSendCaptchaClicked; // 0x30
	private static DelegateBridge __Hotfix0_SetNextAllowCaptchaTs; // 0x38
	private static DelegateBridge __Hotfix0__OnUpdate; // 0x40
	private static DelegateBridge __Hotfix0_Start; // 0x48
	private static DelegateBridge __Hotfix0_Update; // 0x50
	private static DelegateBridge __Hotfix0__OnSendCaptchaSucV1; // 0x58
	private static DelegateBridge __Hotfix0__OnSendCaptchaSucV2; // 0x60
	private static DelegateBridge __Hotfix0__OnSendCaptchaFailV2; // 0x68
	private static DelegateBridge __Hotfix0__OnSendCaptchaSuc; // 0x70
	private static DelegateBridge __Hotfix0__OnSendCaptchaFail; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public InputField input { get; }
	public String captcha { get; }
	public SDKInputWarning warning { get; }
	public Options options { get; set; }

	// RVA: 0x3555824 VA: 0x7595b6d824
	public InputField get_input() { }
	// RVA: 0x3558144 VA: 0x7595b70144
	public String get_captcha() { }
	// RVA: 0x355514c VA: 0x7595b6d14c
	public SDKInputWarning get_warning() { }
	// RVA: 0x3565934 VA: 0x7595b7d934
	public Options get_options() { }
	// RVA: 0x355509c VA: 0x7595b6d09c
	public Void set_options(Options value) { }
	// RVA: 0x3555018 VA: 0x7595b6d018
	public Void RegisterOnFetchPhoneNumber(Func`1 onFetchPhoneNumber) { }
	// RVA: 0x35659c4 VA: 0x7595b7d9c4
	public Void EventOnSendCaptchaClicked() { }
	// RVA: 0x355ff24 VA: 0x7595b77f24
	public Void SetNextAllowCaptchaTs(Int64 timeStamp) { }
	// RVA: 0x3565cf8 VA: 0x7595b7dcf8
	private Void _OnUpdate() { }
	// RVA: 0x3565eac VA: 0x7595b7deac
	private Void Start() { }
	// RVA: 0x3566028 VA: 0x7595b7e028
	private Void Update() { }
	// RVA: 0x3566090 VA: 0x7595b7e090
	private Void _OnSendCaptchaSucV1(UserSendSmsCodeResponse response) { }
	// RVA: 0x3566408 VA: 0x7595b7e408
	private Void _OnSendCaptchaSucV2(APIV2RespWrapper`1 response) { }
	// RVA: 0x3566484 VA: 0x7595b7e484
	private Void _OnSendCaptchaFailV2(APIV2FailResponse response) { }
	// RVA: 0x3566258 VA: 0x7595b7e258
	private Void _OnSendCaptchaSuc() { }
	// RVA: 0x356639c VA: 0x7595b7e39c
	private Void _OnSendCaptchaFail() { }
	// RVA: 0x35665f4 VA: 0x7595b7e5f4
	public Void .ctor() { }
}
```