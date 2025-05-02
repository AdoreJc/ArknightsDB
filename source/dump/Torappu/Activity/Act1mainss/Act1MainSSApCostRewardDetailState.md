# Act1MainSSApCostRewardDetailState

**Namespace:** `Torappu.Activity.Act1mainss`


## Fields

- `Act1MainSSApCostRewardDetailView _view`

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
public class Act1MainSSApCostRewardDetailState : PopupFloatState
{
	private Act1MainSSApCostRewardDetailView _view; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private CommonTopMenu m_topMenu; // 0x80
	private String m_cachedActivityId; // 0x88
	private Param m_cachedParam; // 0x90
	private static DelegateBridge __Hotfix0_OnBackgroundClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3392060 VA: 0x75959aa060
	public Void OnBackgroundClickEvent() { }
	// RVA: 0x3392168 VA: 0x75959aa168
	public override IStateBean GetCacheBean() { }
	// RVA: 0x33921cc VA: 0x75959aa1cc
	protected override Void OnEnter() { }
	// RVA: 0x3392434 VA: 0x75959aa434
	private Void _InitTopMenu() { }
	// RVA: 0x3392638 VA: 0x75959aa638
	public Void .ctor() { }
	// RVA: 0x33926a8 VA: 0x75959aa6a8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```