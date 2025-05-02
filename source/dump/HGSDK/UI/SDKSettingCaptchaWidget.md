# SDKSettingCaptchaWidget

**Namespace:** `HGSDK.UI`


## Fields

- `InputField _captchaInput`

- `SDKInputWarning _captchaInputWarning`

- `Button _sendCaptchaBtn`

- `Text _sendCaptchaBtnText`

- `Single _sendCaptchaCooldown`

- `SDKInputWarning _warningHint`

- `Int64 m_nextAllowCaptchaTs`

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

- `Void _OnUpdate()`

- `Void Start()`

- `Void Update()`

- `Void _OnSendCaptchaSuc(UserSendSmsCodeResponse)`

- `Void _OnSendCaptchaSuc()`

- `Void _OnSendCaptchaFail()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKSettingCaptchaWidget : MonoBehaviour
{
	private InputField _captchaInput; // 0x18
	private SDKInputWarning _captchaInputWarning; // 0x20
	private Button _sendCaptchaBtn; // 0x28
	private Text _sendCaptchaBtnText; // 0x30
	private Single _sendCaptchaCooldown; // 0x38
	private SDKInputWarning _warningHint; // 0x40
	private Func`1 m_onFetchPhoneNumber; // 0x48
	private Int64 m_nextAllowCaptchaTs; // 0x50
	private Options <options>k__BackingField; // 0x58

	public InputField input { get; }
	public String captcha { get; }
	public SDKInputWarning warning { get; }
	public Options options { get; set; }

	// RVA: 0x3752b98 VA: 0x7595d6ab98
	public InputField get_input() { }
	// RVA: 0x3752ba0 VA: 0x7595d6aba0
	public String get_captcha() { }
	// RVA: 0x3752bbc VA: 0x7595d6abbc
	public SDKInputWarning get_warning() { }
	// RVA: 0x3752bc4 VA: 0x7595d6abc4
	public Options get_options() { }
	// RVA: 0x3752bd8 VA: 0x7595d6abd8
	public Void set_options(Options value) { }
	// RVA: 0x3752bf8 VA: 0x7595d6abf8
	public Void RegisterOnFetchPhoneNumber(Func`1 onFetchPhoneNumber) { }
	// RVA: 0x3752c00 VA: 0x7595d6ac00
	public Void EventOnSendCaptchaClicked() { }
	// RVA: 0x3752d98 VA: 0x7595d6ad98
	private Void _OnUpdate() { }
	// RVA: 0x3752f08 VA: 0x7595d6af08
	private Void Start() { }
	// RVA: 0x3752ffc VA: 0x7595d6affc
	private Void Update() { }
	// RVA: 0x3753000 VA: 0x7595d6b000
	private Void _OnSendCaptchaSuc(UserSendSmsCodeResponse response) { }
	// RVA: 0x3753154 VA: 0x7595d6b154
	private Void _OnSendCaptchaSuc() { }
	// RVA: 0x3753224 VA: 0x7595d6b224
	private Void _OnSendCaptchaFail() { }
	// RVA: 0x375322c VA: 0x7595d6b22c
	public Void .ctor() { }
}
```