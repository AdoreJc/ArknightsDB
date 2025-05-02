# AdvancedAutoHideComponent

**Namespace:** `Torappu.UI`


## Fields

- `Single _tweenDuration`

- `Single _waitDuration`

- `CanvasGroup _target`

- `Boolean _controlRaycast`

- `Tweener m_showTweener`

- `Tweener m_hideTweener`

- `Tweener m_waitTweener`

- `Boolean m_isShow`

- `Boolean m_hasInited`


## Methods

- `Void OnDestroy()`

- `Void NotifyInteract()`

- `Void ResetState(Boolean)`

- `Void _InitIfNot()`

- `Void _StartToHide()`

- `Void _StartToShow()`

- `Single _GetTargetAlpha()`

- `Void _SetTargetAlpha(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class AdvancedAutoHideComponent : MonoBehaviour, IHotfixable
{
	private Single _tweenDuration; // 0x18
	private Single _waitDuration; // 0x1c
	private CanvasGroup _target; // 0x20
	private Boolean _controlRaycast; // 0x28
	private Tweener m_showTweener; // 0x30
	private Tweener m_hideTweener; // 0x38
	private Tweener m_waitTweener; // 0x40
	private Boolean m_isShow; // 0x48
	private Boolean m_hasInited; // 0x49
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x0
	private static DelegateBridge __Hotfix0_NotifyInteract; // 0x8
	private static DelegateBridge __Hotfix0_ResetState; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__StartToHide; // 0x20
	private static DelegateBridge __Hotfix0__StartToShow; // 0x28
	private static DelegateBridge __Hotfix0__GetTargetAlpha; // 0x30
	private static DelegateBridge __Hotfix0__SetTargetAlpha; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x220a170 VA: 0x7594822170
	private Void OnDestroy() { }
	// RVA: 0x220a310 VA: 0x7594822310
	public Void NotifyInteract() { }
	// RVA: 0x220a478 VA: 0x7594822478
	public Void ResetState(Boolean isShow) { }
	// RVA: 0x220a598 VA: 0x7594822598
	private Void _InitIfNot() { }
	// RVA: 0x220aad0 VA: 0x7594822ad0
	private Void _StartToHide() { }
	// RVA: 0x220a3a8 VA: 0x75948223a8
	private Void _StartToShow() { }
	// RVA: 0x220ab9c VA: 0x7594822b9c
	private Single _GetTargetAlpha() { }
	// RVA: 0x220ac10 VA: 0x7594822c10
	private Void _SetTargetAlpha(Single alpha) { }
	// RVA: 0x220ac9c VA: 0x7594822c9c
	public Void .ctor() { }
}
```