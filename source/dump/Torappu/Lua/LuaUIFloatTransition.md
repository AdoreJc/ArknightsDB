# LuaUIFloatTransition

**Namespace:** `Torappu.Lua`


## Fields

- `UIFullScreenImage _background`

- `CanvasGroup _rootView`


## Methods

- `Void _SetupBlurShot()`

- `Void _CleanBlurShot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Lua
internal class LuaUIFloatTransition : LuaUITransEffect
{
	public const Single FADE_DURATION; // 0x0
	private UIFullScreenImage _background; // 0x18
	private CanvasGroup _rootView; // 0x20
	private List`1 m_cameraCache; // 0x28
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x0
	private static DelegateBridge __Hotfix0__SetupBlurShot; // 0x8
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__CleanBlurShot; // 0x18
	private static DelegateBridge __Hotfix0_ShowImmediatly; // 0x20
	private static DelegateBridge __Hotfix0_HideImmediatly; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x35b8e0c VA: 0x7595bd0e0c
	public override IEnumerator ShowCoroutine() { }
	// RVA: 0x35b8ee0 VA: 0x7595bd0ee0
	private Void _SetupBlurShot() { }
	// RVA: 0x35b91c0 VA: 0x7595bd11c0
	public override IEnumerator HideCoroutine() { }
	// RVA: 0x35b9294 VA: 0x7595bd1294
	private Void _CleanBlurShot() { }
	// RVA: 0x35b9414 VA: 0x7595bd1414
	public override Void ShowImmediatly() { }
	// RVA: 0x35b94b0 VA: 0x7595bd14b0
	public override Void HideImmediatly() { }
	// RVA: 0x35b9538 VA: 0x7595bd1538
	public Void .ctor() { }
}
```