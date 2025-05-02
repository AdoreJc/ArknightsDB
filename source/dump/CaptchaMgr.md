# CaptchaMgr

**Namespace:** ` `


## Fields

- `SDKExternalTools m_host`

- `SDKCaptchaHandler <activeHandler>k__BackingField`


## Properties

- `SDKCaptchaHandler activeHandler`


## Methods

- `SDKCaptchaHandler get_activeHandler()`

- `Void set_activeHandler(SDKCaptchaHandler)`

- `IEnumerator FetchCaptchaCoroutine(Dictionary`2, Result)`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : 
protected class CaptchaMgr
{
	private SDKExternalTools m_host; // 0x10
	private SDKCaptchaHandler <activeHandler>k__BackingField; // 0x18

	public SDKCaptchaHandler activeHandler { get; set; }

	// RVA: 0x67d79f4 VA: 0x7598def9f4
	public SDKCaptchaHandler get_activeHandler() { }
	// RVA: 0x67d79fc VA: 0x7598def9fc
	private Void set_activeHandler(SDKCaptchaHandler value) { }
	// RVA: 0x67d5fa8 VA: 0x7598dedfa8
	public Void .ctor(SDKExternalTools host) { }
	// RVA: 0x67d7a04 VA: 0x7598defa04
	public IEnumerator FetchCaptchaCoroutine(Dictionary`2 captchaParams, Result outResult) { }
}
```