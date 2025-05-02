# UIBlurFloatPanel

**Namespace:** `Torappu.UI`


## Fields

- `Color _color`

- `Boolean _raycastTarget`

- `UIRenderTextureImage _blurBkg`

- `Boolean m_isInited`

- `UIRenderTextureImage m_bkgImage`

- `CanvasGroup m_alphaHandler`

- `Tween m_sharedTween`


## Methods

- `Void _ResetSharedTween()`

- `Void _InitIfNot()`

- `Void _ShotBlurBackground()`

- `IEnumerator <>xLuaBaseProxy_ShowEffect()`

- `IEnumerator <>xLuaBaseProxy_HideEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIBlurFloatPanel : UIReentrantFloatPanel
{
	private Color _color; // 0x20
	private Boolean _raycastTarget; // 0x30
	private UIRenderTextureImage _blurBkg; // 0x38
	private Boolean m_isInited; // 0x40
	private UIRenderTextureImage m_bkgImage; // 0x48
	private CanvasGroup m_alphaHandler; // 0x50
	private Tween m_sharedTween; // 0x58
	private static DelegateBridge __Hotfix0_ShowEffect; // 0x0
	private static DelegateBridge __Hotfix0_HideEffect; // 0x8
	private static DelegateBridge __Hotfix0__ResetSharedTween; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__ShotBlurBackground; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2241c50 VA: 0x7594859c50
	protected override IEnumerator ShowEffect() { }
	// RVA: 0x2241d24 VA: 0x7594859d24
	protected override IEnumerator HideEffect() { }
	// RVA: 0x2241df8 VA: 0x7594859df8
	private Void _ResetSharedTween() { }
	// RVA: 0x2241ebc VA: 0x7594859ebc
	private Void _InitIfNot() { }
	// RVA: 0x224238c VA: 0x759485a38c
	private Void _ShotBlurBackground() { }
	// RVA: 0x2242440 VA: 0x759485a440
	public Void .ctor() { }
	// RVA: 0x22424c0 VA: 0x759485a4c0
	private IEnumerator <>xLuaBaseProxy_ShowEffect() { }
	// RVA: 0x22424c8 VA: 0x759485a4c8
	private IEnumerator <>xLuaBaseProxy_HideEffect() { }
}
```