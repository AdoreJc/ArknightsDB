# Act25sideResearchUnlockState

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Act25sideResearchUnlockView _view`

- `UIAnimationLocation _enterAnim`

- `Boolean m_isInited`

- `String m_cachedActId`

- `Act25sideResearchUnlockStateBean m_stateBean`

- `Act25sideResearchUnlockProperty m_prop`

- `Tween m_cachedTween`


## Methods

- `Void _PlayAnim()`

- `Void _UpdateProperty()`

- `Void _InitIfNot()`

- `Void OnDismiss()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchUnlockState : PopupFloatState, IHotfixable
{
	private Act25sideResearchUnlockView _view; // 0x70
	private UIAnimationLocation _enterAnim; // 0x78
	private Boolean m_isInited; // 0x88
	private String m_cachedActId; // 0x90
	private Act25sideResearchUnlockStateBean m_stateBean; // 0x98
	private Act25sideResearchUnlockProperty m_prop; // 0xa0
	private Tween m_cachedTween; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x10
	private static DelegateBridge __Hotfix0__UpdateProperty; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_OnDismiss; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x327edc0 VA: 0x7595896dc0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x327ee28 VA: 0x7595896e28
	protected override Void OnEnter() { }
	// RVA: 0x327f1a8 VA: 0x75958971a8
	private Void _PlayAnim() { }
	// RVA: 0x327f0c8 VA: 0x75958970c8
	private Void _UpdateProperty() { }
	// RVA: 0x327eeac VA: 0x7595896eac
	private Void _InitIfNot() { }
	// RVA: 0x327f794 VA: 0x7595897794
	public Void OnDismiss() { }
	// RVA: 0x327f8f4 VA: 0x75958978f4
	public Void .ctor() { }
	// RVA: 0x327fab4 VA: 0x7595897ab4
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```