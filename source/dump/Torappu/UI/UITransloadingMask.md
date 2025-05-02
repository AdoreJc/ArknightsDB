# UITransloadingMask

**Namespace:** `Torappu.UI`


## Fields

- `UIAnimationLocation _animationForShow`

- `UIAnimationLocation _rippleAnim`

- `Tween m_rippleTween`


## Methods

- `Void <>xLuaBaseProxy_OnShow()`

- `Void <>xLuaBaseProxy_OnHide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UITransloadingMask : UIFloatMask
{
	public const Single ANIM_DURATION; // 0x0
	private UIAnimationLocation _animationForShow; // 0x40
	private UIAnimationLocation _rippleAnim; // 0x50
	private Tween m_rippleTween; // 0x60
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x0
	private static DelegateBridge __Hotfix0_OnShow; // 0x8
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_OnHide; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2258fe4 VA: 0x7594870fe4
	protected override IEnumerator ShowCoroutine() { }
	// RVA: 0x22590b8 VA: 0x75948710b8
	protected override Void OnShow() { }
	// RVA: 0x2259250 VA: 0x7594871250
	protected override IEnumerator HideCoroutine() { }
	// RVA: 0x2259324 VA: 0x7594871324
	protected override Void OnHide() { }
	// RVA: 0x22593c4 VA: 0x75948713c4
	public Void .ctor() { }
	// RVA: 0x2259430 VA: 0x7594871430
	private Void <>xLuaBaseProxy_OnShow() { }
	// RVA: 0x2259434 VA: 0x7594871434
	private Void <>xLuaBaseProxy_OnHide() { }
}
```