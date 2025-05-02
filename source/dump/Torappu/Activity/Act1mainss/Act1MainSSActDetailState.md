# Act1MainSSActDetailState

**Namespace:** `Torappu.Activity.Act1mainss`


## Fields

- `Act1MainSSActDetaiView _view`

- `RectTransform _topMenuContainer`

- `CommonTopMenu m_topMenu`

- `String m_cachedActivityId`

- `Param m_cachedParam`


## Methods

- `Void OnBackgroundClickEvent()`

- `Void _InitTopMenu()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1mainss
public class Act1MainSSActDetailState : PopupFloatState
{
	private Act1MainSSActDetaiView _view; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private CommonTopMenu m_topMenu; // 0x80
	private String m_cachedActivityId; // 0x88
	private Param m_cachedParam; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnBackgroundClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x338eec4 VA: 0x75959a6ec4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x338ef28 VA: 0x75959a6f28
	public Void OnBackgroundClickEvent() { }
	// RVA: 0x338f030 VA: 0x75959a7030
	protected override Void OnEnter() { }
	// RVA: 0x338f2a8 VA: 0x75959a72a8
	private Void _InitTopMenu() { }
	// RVA: 0x338f4c8 VA: 0x75959a74c8
	public Void .ctor() { }
	// RVA: 0x338f538 VA: 0x75959a7538
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```