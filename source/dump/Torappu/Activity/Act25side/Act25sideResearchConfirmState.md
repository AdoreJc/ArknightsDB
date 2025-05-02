# Act25sideResearchConfirmState

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Act25sideResearchConfirmView _view`

- `Boolean m_isInited`

- `String m_cachedActId`

- `Act25sideResearchConfirmProperty m_researchConfirmProp`

- `Act25sideResearchConfirmStateBean m_stateBean`


## Methods

- `Void _UpdateProp()`

- `Void _InitIfNot()`

- `Void _EventOnConfirm()`

- `Void <_EventOnConfirm>b__9_0(Act25sideResearchResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchConfirmState : PopupFloatState
{
	private Act25sideResearchConfirmView _view; // 0x70
	private Boolean m_isInited; // 0x78
	private String m_cachedActId; // 0x80
	private Act25sideResearchConfirmProperty m_researchConfirmProp; // 0x88
	private Act25sideResearchConfirmStateBean m_stateBean; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__UpdateProp; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__EventOnConfirm; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3278e10 VA: 0x7595890e10
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3278e78 VA: 0x7595890e78
	protected override Void OnEnter() { }
	// RVA: 0x3279164 VA: 0x7595891164
	private Void _UpdateProp() { }
	// RVA: 0x3278ef4 VA: 0x7595890ef4
	private Void _InitIfNot() { }
	// RVA: 0x3279424 VA: 0x7595891424
	private Void _EventOnConfirm() { }
	// RVA: 0x32796e8 VA: 0x75958916e8
	public Void .ctor() { }
	// RVA: 0x32798a8 VA: 0x75958918a8
	private Void <_EventOnConfirm>b__9_0(Act25sideResearchResponse response) { }
	// RVA: 0x32798b8 VA: 0x75958918b8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```