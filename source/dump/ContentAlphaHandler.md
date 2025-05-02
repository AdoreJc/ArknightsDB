# ContentAlphaHandler

**Namespace:** ` `


## Fields

- `CanvasGroup m_canvasGroup`

- `Boolean m_isEnabled`


## Methods

- `Boolean _CheckIfValid()`

- `Void SetAlpha(Single)`

- `IEnumerator ShowCoroutine()`

- `IEnumerator HideCoroutine()`

- `CanvasGroup Disable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ContentAlphaHandler : IHotfixable
{
	private CanvasGroup m_canvasGroup; // 0x10
	private Boolean m_isEnabled; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__CheckIfValid; // 0x8
	private static DelegateBridge __Hotfix0_SetAlpha; // 0x10
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_Disable; // 0x28


	// RVA: 0x218ccec VA: 0x75947a4cec
	public Void .ctor(CanvasGroup canvasGroup) { }
	// RVA: 0x218fcc0 VA: 0x75947a7cc0
	private Boolean _CheckIfValid() { }
	// RVA: 0x218dadc VA: 0x75947a5adc
	public Void SetAlpha(Single alpha) { }
	// RVA: 0x218fd70 VA: 0x75947a7d70
	public IEnumerator ShowCoroutine() { }
	// RVA: 0x218fe44 VA: 0x75947a7e44
	public IEnumerator HideCoroutine() { }
	// RVA: 0x218e444 VA: 0x75947a6444
	public CanvasGroup Disable() { }
}
```