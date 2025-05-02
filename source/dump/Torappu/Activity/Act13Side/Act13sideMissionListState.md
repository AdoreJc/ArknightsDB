# Act13sideMissionListState

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `TemplateActivityMissionHolder _holder`

- `RectTransform _topMenuContainer`

- `Image _upTitleImg`

- `CommonTopMenu m_topMenu`

- `Act13sideMissionListStateBean m_stateBean`


## Methods

- `Void BindController(TemplateActivityController)`

- `Void _InitTopMenu()`

- `Void <_InitTopMenu>b__9_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideMissionListState : PopupFloatState, IBaseActStateHolder, IHotfixable
{
	private TemplateActivityMissionHolder _holder; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private Image _upTitleImg; // 0x80
	private CommonTopMenu m_topMenu; // 0x88
	private Act13sideMissionListStateBean m_stateBean; // 0x90
	private Action`1 m_onSelectGroup; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_BindController; // 0x10
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x342d01c VA: 0x7595a4501c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x342d084 VA: 0x7595a45084
	protected override Void OnEnter() { }
	// RVA: 0x342d2d8 VA: 0x7595a452d8
	public Void BindController(TemplateActivityController controller) { }
	// RVA: 0x342d1ac VA: 0x7595a451ac
	private Void _InitTopMenu() { }
	// RVA: 0x342d460 VA: 0x7595a45460
	public Void .ctor() { }
	// RVA: 0x342d50c VA: 0x7595a4550c
	private Void <_InitTopMenu>b__9_0() { }
	// RVA: 0x342d5bc VA: 0x7595a455bc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```