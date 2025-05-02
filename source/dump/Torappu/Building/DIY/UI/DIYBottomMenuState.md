# DIYBottomMenuState

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYListViewStateBean _stateBean`

- `RectTransform _cursor`

- `MenuState m_currState`

- `Boolean m_isSwitching`


## Methods

- `Void _SwitchToTab(MenuState, Boolean)`

- `IEnumerator _SwitchCoroutine(DIYBottomMenuTabState, DIYBottomMenuTabState)`

- `Void ResetTab()`

- `Void OnOverviewTabPressed()`

- `Void OnRecentTabPressed()`

- `Void OnSinglePressed()`

- `Void OnThemePressed()`

- `Void OnPresetPressed()`

- `Void OnRecentThemePressed()`

- `Void OnRecentSinglePressed()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYBottomMenuState : DIYBottomMenuPopupState
{
	private const Single CURSOR_MOVE_DURATION; // 0x0
	protected DIYListViewStateBean _stateBean; // 0x68
	private DIYBottomMenuTabState[] _tabStates; // 0x70
	private RectTransform _cursor; // 0x78
	private MenuState m_currState; // 0x80
	private Dictionary`2 m_menuStates; // 0x88
	private Boolean m_isSwitching; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__SwitchToTab; // 0x10
	private static DelegateBridge __Hotfix0__SwitchCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_ResetTab; // 0x20
	private static DelegateBridge __Hotfix0_OnOverviewTabPressed; // 0x28
	private static DelegateBridge __Hotfix0_OnRecentTabPressed; // 0x30
	private static DelegateBridge __Hotfix0_OnSinglePressed; // 0x38
	private static DelegateBridge __Hotfix0_OnThemePressed; // 0x40
	private static DelegateBridge __Hotfix0_OnPresetPressed; // 0x48
	private static DelegateBridge __Hotfix0_OnRecentThemePressed; // 0x50
	private static DelegateBridge __Hotfix0_OnRecentSinglePressed; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x382f31c VA: 0x7595e4731c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x382f384 VA: 0x7595e47384
	protected override Void OnEnter() { }
	// RVA: 0x382f534 VA: 0x7595e47534
	private Void _SwitchToTab(MenuState menuState, Boolean fastMode) { }
	// RVA: 0x382f708 VA: 0x7595e47708
	private IEnumerator _SwitchCoroutine(DIYBottomMenuTabState srcMenuState, DIYBottomMenuTabState dstMenuState) { }
	// RVA: 0x382f4c4 VA: 0x7595e474c4
	public Void ResetTab() { }
	// RVA: 0x382f818 VA: 0x7595e47818
	public Void OnOverviewTabPressed() { }
	// RVA: 0x382f888 VA: 0x7595e47888
	public Void OnRecentTabPressed() { }
	// RVA: 0x382f8f8 VA: 0x7595e478f8
	public Void OnSinglePressed() { }
	// RVA: 0x382fb84 VA: 0x7595e47b84
	public Void OnThemePressed() { }
	// RVA: 0x382fd04 VA: 0x7595e47d04
	public Void OnPresetPressed() { }
	// RVA: 0x382fe24 VA: 0x7595e47e24
	public Void OnRecentThemePressed() { }
	// RVA: 0x382ffa4 VA: 0x7595e47fa4
	public Void OnRecentSinglePressed() { }
	// RVA: 0x3830124 VA: 0x7595e48124
	public Void .ctor() { }
	// RVA: 0x3830198 VA: 0x7595e48198
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```