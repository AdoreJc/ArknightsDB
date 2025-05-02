# UIInvisLoadingMask

**Namespace:** `Torappu.UI`


## Fields

- `CanvasGroup _ripplePanel`

- `UIAnimationLocation _rippleAnim`

- `Tween m_fadeTween`

- `Tween m_animTween`

- `Boolean m_showRipple`

- `Boolean m_disableRippleLock`


## Methods

- `Void EventOnClick()`

- `Void _ShowRipple()`

- `IEnumerator _HideRipple()`

- `IEnumerator _AutoShowRippleCoroutine()`

- `Void _ClearFadeTween()`

- `Void <>xLuaBaseProxy_OnShow()`

- `Void <>xLuaBaseProxy_OnHide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIInvisLoadingMask : UIFloatMask
{
	private const Single ANIM_DURATION; // 0x0
	private const Single LONG_TIME_THRESHOLD; // 0x0
	private CanvasGroup _ripplePanel; // 0x40
	private UIAnimationLocation _rippleAnim; // 0x48
	private Tween m_fadeTween; // 0x58
	private Tween m_animTween; // 0x60
	private Boolean m_showRipple; // 0x68
	private Boolean m_disableRippleLock; // 0x69
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_OnShow; // 0x10
	private static DelegateBridge __Hotfix0_OnHide; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x20
	private static DelegateBridge __Hotfix0__ShowRipple; // 0x28
	private static DelegateBridge __Hotfix0__HideRipple; // 0x30
	private static DelegateBridge __Hotfix0__AutoShowRippleCoroutine; // 0x38
	private static DelegateBridge __Hotfix0__ClearFadeTween; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x224973c VA: 0x759486173c
	protected override IEnumerator HideCoroutine() { }
	// RVA: 0x2249810 VA: 0x7594861810
	protected override IEnumerator ShowCoroutine() { }
	// RVA: 0x22498e4 VA: 0x75948618e4
	protected override Void OnShow() { }
	// RVA: 0x2249b58 VA: 0x7594861b58
	protected override Void OnHide() { }
	// RVA: 0x2249bf8 VA: 0x7594861bf8
	public Void EventOnClick() { }
	// RVA: 0x2249c60 VA: 0x7594861c60
	private Void _ShowRipple() { }
	// RVA: 0x2249e74 VA: 0x7594861e74
	private IEnumerator _HideRipple() { }
	// RVA: 0x2249aac VA: 0x7594861aac
	private IEnumerator _AutoShowRippleCoroutine() { }
	// RVA: 0x2249dd4 VA: 0x7594861dd4
	private Void _ClearFadeTween() { }
	// RVA: 0x2249f70 VA: 0x7594861f70
	public Void .ctor() { }
	// RVA: 0x2249fdc VA: 0x7594861fdc
	private Void <>xLuaBaseProxy_OnShow() { }
	// RVA: 0x2249fe0 VA: 0x7594861fe0
	private Void <>xLuaBaseProxy_OnHide() { }
}
```