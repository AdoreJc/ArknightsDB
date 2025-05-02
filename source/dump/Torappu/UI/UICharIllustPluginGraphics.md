# UICharIllustPluginGraphics

**Namespace:** `Torappu.UI`


## Fields

- `CanvasGroup _alphaHandler`


## Properties

- `Single alpha`


## Methods

- `Single get_alpha()`

- `Void SetColor(Color)`

- `Void SetAlpha(Single)`

- `Tween DOFade(Single, Single)`

- `Void Disable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharIllustPluginGraphics : MonoBehaviour, IHotfixable
{
	private Graphic[] _graphics; // 0x18
	private CanvasGroup _alphaHandler; // 0x20
	private static DelegateBridge __Hotfix0_get_alpha; // 0x0
	private static DelegateBridge __Hotfix0_SetColor; // 0x8
	private static DelegateBridge __Hotfix0_SetAlpha; // 0x10
	private static DelegateBridge __Hotfix0_get_graphics; // 0x18
	private static DelegateBridge __Hotfix0_DOFade; // 0x20
	private static DelegateBridge __Hotfix0_Disable; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Single alpha { get; }
	public IList`1 graphics { get; }

	// RVA: 0x21392e0 VA: 0x75947512e0
	public Single get_alpha() { }
	// RVA: 0x2137814 VA: 0x759474f814
	public Void SetColor(Color color) { }
	// RVA: 0x21380f4 VA: 0x75947500f4
	public Void SetAlpha(Single pAlpha) { }
	// RVA: 0x2137d74 VA: 0x759474fd74
	public IList`1 get_graphics() { }
	// RVA: 0x213832c VA: 0x759475032c
	public Tween DOFade(Single endValue, Single duration) { }
	// RVA: 0x2138978 VA: 0x7594750978
	public Void Disable() { }
	// RVA: 0x2139354 VA: 0x7594751354
	public Void .ctor() { }
}
```