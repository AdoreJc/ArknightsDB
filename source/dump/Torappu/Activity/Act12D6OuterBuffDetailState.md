# Act12D6OuterBuffDetailState

**Namespace:** `Torappu.Activity`


## Fields

- `Act12D6OuterBuffDetailView _view`

- `UIStringEvent _onOuterBuffUpgradeClicked`

- `RectTransform _topMenuContainer`

- `Act12D6OuterBuffDetailStateBean m_stateBean`

- `CommonTopMenu m_topMenu`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnOuterBuffUpgrade(String)`

- `Void <_InitIfNot>b__8_0()`

- `Void <EventOnOuterBuffUpgrade>b__9_0(Act12D6UpgradeOutBuffResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class Act12D6OuterBuffDetailState : PopupFloatState, IHotfixable
{
	private Act12D6OuterBuffDetailView _view; // 0x70
	private UIStringEvent _onOuterBuffUpgradeClicked; // 0x78
	private RectTransform _topMenuContainer; // 0x80
	private Act12D6OuterBuffDetailStateBean m_stateBean; // 0x88
	private CommonTopMenu m_topMenu; // 0x90
	private Boolean m_inited; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnOuterBuffUpgrade; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30b6f58 VA: 0x75956cef58
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30b6fc0 VA: 0x75956cefc0
	protected override Void OnEnter() { }
	// RVA: 0x30b7060 VA: 0x75956cf060
	private Void _InitIfNot() { }
	// RVA: 0x30b7174 VA: 0x75956cf174
	public Void EventOnOuterBuffUpgrade(String buffId) { }
	// RVA: 0x30b755c VA: 0x75956cf55c
	public Void .ctor() { }
	// RVA: 0x30b760c VA: 0x75956cf60c
	private Void <_InitIfNot>b__8_0() { }
	// RVA: 0x30b7614 VA: 0x75956cf614
	private Void <EventOnOuterBuffUpgrade>b__9_0(Act12D6UpgradeOutBuffResponse response) { }
	// RVA: 0x30b761c VA: 0x75956cf61c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```