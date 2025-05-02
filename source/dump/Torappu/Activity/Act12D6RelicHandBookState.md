# Act12D6RelicHandBookState

**Namespace:** `Torappu.Activity`


## Fields

- `Act12D6RelicHandBookView _view`

- `RectTransform _topMenuContainer`

- `Act12D6RelicHandBookStateBean m_stateBean`

- `CommonTopMenu m_topMenu`

- `Boolean m_inited`

- `String m_cachedChosenRelicId`

- `eRelicSortType m_cachedSortType`


## Methods

- `Void _InitIfNot()`

- `Void EventOnRelicClicked(String)`

- `Void EventOnSortRelicAll(Toggle)`

- `Void EventOnSortRelicNew(Toggle)`

- `Void EventOnSortRelicLocked(Toggle)`

- `Void _RenderView(Boolean)`

- `Void <_InitIfNot>b__9_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class Act12D6RelicHandBookState : PopupFloatState, IHotfixable
{
	private Act12D6RelicHandBookView _view; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private Act12D6RelicHandBookStateBean m_stateBean; // 0x80
	private CommonTopMenu m_topMenu; // 0x88
	private Boolean m_inited; // 0x90
	private String m_cachedChosenRelicId; // 0x98
	private eRelicSortType m_cachedSortType; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnRelicClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnSortRelicAll; // 0x20
	private static DelegateBridge __Hotfix0_EventOnSortRelicNew; // 0x28
	private static DelegateBridge __Hotfix0_EventOnSortRelicLocked; // 0x30
	private static DelegateBridge __Hotfix0__RenderView; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x30b7fd0 VA: 0x75956cffd0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30b8038 VA: 0x75956d0038
	protected override Void OnEnter() { }
	// RVA: 0x30b80b8 VA: 0x75956d00b8
	private Void _InitIfNot() { }
	// RVA: 0x30b82b4 VA: 0x75956d02b4
	public Void EventOnRelicClicked(String relicId) { }
	// RVA: 0x30b83b0 VA: 0x75956d03b0
	public Void EventOnSortRelicAll(Toggle sortToggle) { }
	// RVA: 0x30b84b0 VA: 0x75956d04b0
	public Void EventOnSortRelicNew(Toggle sortToggle) { }
	// RVA: 0x30b85b4 VA: 0x75956d05b4
	public Void EventOnSortRelicLocked(Toggle sortToggle) { }
	// RVA: 0x30b81fc VA: 0x75956d01fc
	private Void _RenderView(Boolean force) { }
	// RVA: 0x30b86b8 VA: 0x75956d06b8
	public Void .ctor() { }
	// RVA: 0x30b8768 VA: 0x75956d0768
	private Void <_InitIfNot>b__9_0() { }
	// RVA: 0x30b8770 VA: 0x75956d0770
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```