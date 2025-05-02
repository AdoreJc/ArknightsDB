# RoguelikeCharInventoryState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _panelTopMenu`

- `RoguelikeCharInventoryStateBean _stateBean`

- `RoguelikeCharSelectView _view`

- `Boolean m_inited`

- `MenuAdapter m_menuAdapter`

- `RoguelikeCommonTopMenu m_topMenu`


## Methods

- `Void _InitIfNot()`

- `Void DealWithCharClick(Int32)`

- `Void EventOnAttrTabClick(CharAttrTabType)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharInventoryState : PopupFadeState
{
	private RectTransform _panelTopMenu; // 0x70
	private RoguelikeCharInventoryStateBean _stateBean; // 0x78
	private RoguelikeCharSelectView _view; // 0x80
	private Boolean m_inited; // 0x88
	private MenuAdapter m_menuAdapter; // 0x90
	private RoguelikeCommonTopMenu m_topMenu; // 0x98
	private List`1 m_pluginContexts; // 0xa0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_DealWithCharClick; // 0x10
	private static DelegateBridge __Hotfix0_EventOnAttrTabClick; // 0x18
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2ac51e8 VA: 0x75950dd1e8
	private Void _InitIfNot() { }
	// RVA: 0x2ac52cc VA: 0x75950dd2cc
	protected override Void OnEnter() { }
	// RVA: 0x2ac5a8c VA: 0x75950dda8c
	public Void DealWithCharClick(Int32 instId) { }
	// RVA: 0x2ac5e30 VA: 0x75950dde30
	public Void EventOnAttrTabClick(CharAttrTabType tabType) { }
	// RVA: 0x2ac5f14 VA: 0x75950ddf14
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ac5f7c VA: 0x75950ddf7c
	public Void .ctor() { }
	// RVA: 0x2ac5fec VA: 0x75950ddfec
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```