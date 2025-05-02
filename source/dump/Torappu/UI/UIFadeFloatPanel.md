# UIFadeFloatPanel

**Namespace:** `Torappu.UI`


## Fields

- `CanvasGroup _alphaHandler`

- `Tween m_sharedTween`


## Methods

- `Void _ResetSharedTween()`

- `IEnumerator <>xLuaBaseProxy_ShowEffect()`

- `IEnumerator <>xLuaBaseProxy_HideEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIFadeFloatPanel : UIReentrantFloatPanel
{
	private CanvasGroup _alphaHandler; // 0x20
	private Tween m_sharedTween; // 0x28
	private static DelegateBridge __Hotfix0_ShowEffect; // 0x0
	private static DelegateBridge __Hotfix0_HideEffect; // 0x8
	private static DelegateBridge __Hotfix0__ResetSharedTween; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x22479d8 VA: 0x759485f9d8
	protected override IEnumerator ShowEffect() { }
	// RVA: 0x2247aac VA: 0x759485faac
	protected override IEnumerator HideEffect() { }
	// RVA: 0x2247b80 VA: 0x759485fb80
	private Void _ResetSharedTween() { }
	// RVA: 0x2247c30 VA: 0x759485fc30
	public Void .ctor() { }
	// RVA: 0x2247ca0 VA: 0x759485fca0
	private IEnumerator <>xLuaBaseProxy_ShowEffect() { }
	// RVA: 0x2247ca8 VA: 0x759485fca8
	private IEnumerator <>xLuaBaseProxy_HideEffect() { }
}
```