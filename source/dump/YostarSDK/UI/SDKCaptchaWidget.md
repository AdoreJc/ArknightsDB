# SDKCaptchaWidget

**Namespace:** `YostarSDK.UI`


## Fields

- `InputField _captchaInput`

- `InputField _emailInput`

- `SDKInputWarning _emailInputWarning`

- `Button _sendCaptchaBtn`

- `GameObject _panelRequest`

- `GameObject _panelWait`

- `Text _textCountDown`

- `Single _sendCaptchaCooldown`

- `Int64 m_nextAllowCaptchaTs`

- `StaticStatusKey m_statusKey`


## Properties

- `InputField input`

- `String captcha`


## Methods

- `InputField get_input()`

- `String get_captcha()`

- `Void SyncToStaticStatus(StaticStatusKey)`

- `Void OnSendCaptchaClicked()`

- `Void _OnUpdate()`

- `Void Update()`

- `Void OnDestroy()`

- `Void _VerificationCodeReqCallback(VerificationCodeRet)`

- `Void _OnSendCaptchaSuc()`

- `Void _OnSendCaptchaFail()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKCaptchaWidget : MonoBehaviour
{
	private InputField _captchaInput; // 0x18
	private InputField _emailInput; // 0x20
	private SDKInputWarning _emailInputWarning; // 0x28
	private Button _sendCaptchaBtn; // 0x30
	private GameObject _panelRequest; // 0x38
	private GameObject _panelWait; // 0x40
	private Text _textCountDown; // 0x48
	private Single _sendCaptchaCooldown; // 0x50
	private static Dictionary`2 s_staticStatus; // 0x0
	private Int64 m_nextAllowCaptchaTs; // 0x58
	private StaticStatusKey m_statusKey; // 0x60

	public InputField input { get; }
	public String captcha { get; }

	// RVA: 0x257e884 VA: 0x7594b96884
	public InputField get_input() { }
	// RVA: 0x257e88c VA: 0x7594b9688c
	public String get_captcha() { }
	// RVA: 0x25770dc VA: 0x7594b8f0dc
	public Void SyncToStaticStatus(StaticStatusKey key) { }
	// RVA: 0x257e8a8 VA: 0x7594b968a8
	public Void OnSendCaptchaClicked() { }
	// RVA: 0x257e9bc VA: 0x7594b969bc
	private Void _OnUpdate() { }
	// RVA: 0x257eb28 VA: 0x7594b96b28
	private Void Update() { }
	// RVA: 0x257eb2c VA: 0x7594b96b2c
	private Void OnDestroy() { }
	// RVA: 0x257ebfc VA: 0x7594b96bfc
	private Void _VerificationCodeReqCallback(VerificationCodeRet ret) { }
	// RVA: 0x257ecec VA: 0x7594b96cec
	private Void _OnSendCaptchaSuc() { }
	// RVA: 0x257edac VA: 0x7594b96dac
	private Void _OnSendCaptchaFail() { }
	// RVA: 0x257edb4 VA: 0x7594b96db4
	public Void .ctor() { }
	// RVA: 0x257edc4 VA: 0x7594b96dc4
	private static Void .cctor() { }
}
```