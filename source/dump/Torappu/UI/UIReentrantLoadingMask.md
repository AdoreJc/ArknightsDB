# UIReentrantLoadingMask

**Namespace:** `Torappu.UI`


## Fields

- `CanvasGroup _ripplePanel`

- `UIAnimationLocation _rippleAnim`

- `Tween m_rippleTween`


## Methods

- `IEnumerator <>xLuaBaseProxy_ShowEffect()`

- `IEnumerator <>xLuaBaseProxy_HideEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIReentrantLoadingMask : UIReentrantFloatPanel
{
	private const Single ANIM_DURATION; // 0x0
	private CanvasGroup _ripplePanel; // 0x20
	private UIAnimationLocation _rippleAnim; // 0x28
	private Tween m_rippleTween; // 0x38
	private static DelegateBridge __Hotfix0_ShowEffect; // 0x0
	private static DelegateBridge __Hotfix0_HideEffect; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22534ac VA: 0x759486b4ac
	protected override IEnumerator ShowEffect() { }
	// RVA: 0x2253580 VA: 0x759486b580
	protected override IEnumerator HideEffect() { }
	// RVA: 0x2253654 VA: 0x759486b654
	public Void .ctor() { }
	// RVA: 0x22536c4 VA: 0x759486b6c4
	private IEnumerator <>xLuaBaseProxy_ShowEffect() { }
	// RVA: 0x22536cc VA: 0x759486b6cc
	private IEnumerator <>xLuaBaseProxy_HideEffect() { }
}
```