# ActCommonFavorUpState

**Namespace:** `Torappu.Activity`


## Fields

- `ActCommonFavorUpView _view`

- `RectTransform _topMenuContainer`

- `CommonTopMenu m_topMenu`

- `ActCommonFavorUpStateBean m_stateBean`


## Methods

- `Void EventOnBackgroundClicked()`

- `Void _InitTopMenu()`

- `Void <_InitTopMenu>b__7_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActCommonFavorUpState : PopupFloatState
{
	private ActCommonFavorUpView _view; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private CommonTopMenu m_topMenu; // 0x80
	private ActCommonFavorUpStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_EventOnBackgroundClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30c46f4 VA: 0x75956dc6f4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30c475c VA: 0x75956dc75c
	protected override Void OnEnter() { }
	// RVA: 0x30c4dcc VA: 0x75956dcdcc
	public Void EventOnBackgroundClicked() { }
	// RVA: 0x30c47f4 VA: 0x75956dc7f4
	private Void _InitTopMenu() { }
	// RVA: 0x30c4ed8 VA: 0x75956dced8
	public Void .ctor() { }
	// RVA: 0x30c4f84 VA: 0x75956dcf84
	private Void <_InitTopMenu>b__7_0() { }
	// RVA: 0x30c4f8c VA: 0x75956dcf8c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```