# Act1BossRushMissionState

**Namespace:** `Torappu.Activity.Act1BossRush`


## Fields

- `Act1BossRushMissionInfoHolder _infoHolder`

- `TemplateActivityMissionHolder _holder`

- `RectTransform _topMenuContainer`

- `CommonTopMenu m_topMenu`

- `TemplateActivityController m_cacheController`


## Methods

- `Void _InitTopMenu()`

- `Void BindController(TemplateActivityController)`

- `Void <_InitTopMenu>b__7_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushMissionState : PopupFadeState, IBaseActStateHolder, IHotfixable
{
	private Act1BossRushMissionInfoHolder _infoHolder; // 0x70
	private TemplateActivityMissionHolder _holder; // 0x78
	private RectTransform _topMenuContainer; // 0x80
	private CommonTopMenu m_topMenu; // 0x88
	private TemplateActivityController m_cacheController; // 0x90
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x10
	private static DelegateBridge __Hotfix0_BindController; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3195370 VA: 0x75957ad370
	protected override Void OnEnter() { }
	// RVA: 0x3195510 VA: 0x75957ad510
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31953e4 VA: 0x75957ad3e4
	private Void _InitTopMenu() { }
	// RVA: 0x3195574 VA: 0x75957ad574
	public Void BindController(TemplateActivityController controller) { }
	// RVA: 0x31957dc VA: 0x75957ad7dc
	public Void .ctor() { }
	// RVA: 0x319584c VA: 0x75957ad84c
	private Void <_InitTopMenu>b__7_0() { }
	// RVA: 0x31958fc VA: 0x75957ad8fc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```