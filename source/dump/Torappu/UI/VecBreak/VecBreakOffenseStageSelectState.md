# VecBreakOffenseStageSelectState

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `RectTransform _topMenuParent`

- `VecBreakOffenseStageSelectView _mainView`

- `VecBreakOffenseStageGroupView _stageGroupView`

- `VecBreakOffensePage m_page`

- `VecBreakOffenseProp m_prop`

- `Int32 m_dialogInst`


## Methods

- `Void _EventOnBtnBack()`

- `Boolean _IsUIStable()`

- `Void EventOnBtnNavPrevClick()`

- `Void EventOnBtnNavNextClick()`

- `Void EventOnBtnMapPreviewClick()`

- `Void EventOnBtnNavToDefensePage()`

- `Void EventOnBtnEnemyClick()`

- `Void EventOnBtnBossClick()`

- `Void EventOnBtnStartBattle()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakOffenseStageSelectState : PopupFadeState
{
	private const String GUIDE_SUB_SIGNAL; // 0x0
	private RectTransform _topMenuParent; // 0x70
	private VecBreakOffenseStageSelectView _mainView; // 0x78
	private VecBreakOffenseStageGroupView _stageGroupView; // 0x80
	private VecBreakOffensePage m_page; // 0x88
	private VecBreakOffenseProp m_prop; // 0x90
	private Int32 m_dialogInst; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__EventOnBtnBack; // 0x20
	private static DelegateBridge __Hotfix0__IsUIStable; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBtnNavPrevClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBtnNavNextClick; // 0x38
	private static DelegateBridge __Hotfix0_EventOnBtnMapPreviewClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnBtnNavToDefensePage; // 0x48
	private static DelegateBridge __Hotfix0_EventOnBtnEnemyClick; // 0x50
	private static DelegateBridge __Hotfix0_EventOnBtnBossClick; // 0x58
	private static DelegateBridge __Hotfix0_EventOnBtnStartBattle; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x22d3c1c VA: 0x75948ebc1c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x22d3c80 VA: 0x75948ebc80
	protected override Void OnEnter() { }
	// RVA: 0x22d3edc VA: 0x75948ebedc
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x22d3fbc VA: 0x75948ebfbc
	protected override Void OnResume() { }
	// RVA: 0x22d4050 VA: 0x75948ec050
	private Void _EventOnBtnBack() { }
	// RVA: 0x22d410c VA: 0x75948ec10c
	private Boolean _IsUIStable() { }
	// RVA: 0x22d41e8 VA: 0x75948ec1e8
	public Void EventOnBtnNavPrevClick() { }
	// RVA: 0x22d42a8 VA: 0x75948ec2a8
	public Void EventOnBtnNavNextClick() { }
	// RVA: 0x22d4388 VA: 0x75948ec388
	public Void EventOnBtnMapPreviewClick() { }
	// RVA: 0x22d4570 VA: 0x75948ec570
	public Void EventOnBtnNavToDefensePage() { }
	// RVA: 0x22d46a8 VA: 0x75948ec6a8
	public Void EventOnBtnEnemyClick() { }
	// RVA: 0x22d47e4 VA: 0x75948ec7e4
	public Void EventOnBtnBossClick() { }
	// RVA: 0x22d4a04 VA: 0x75948eca04
	public Void EventOnBtnStartBattle() { }
	// RVA: 0x22d4d68 VA: 0x75948ecd68
	public Void .ctor() { }
	// RVA: 0x22d4dd8 VA: 0x75948ecdd8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x22d4de0 VA: 0x75948ecde0
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x22d4dec VA: 0x75948ecdec
	private Void <>xLuaBaseProxy_OnResume() { }
}
```