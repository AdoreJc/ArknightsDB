# RoguelikeMenuButtonPluginObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _pluginContainer`

- `RoguelikeMenuButtonPlugin m_buttonPrefab`

- `RoguelikeMenuButtonPlugin m_buttonInst`

- `Boolean m_showStateCondition`

- `Boolean m_showDataCondition`


## Methods

- `Void _RenderShowStatus()`

- `Void _RefreshButtonPlugin(RoguelikeMenuAdapter)`

- `Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter, Boolean)`

- `Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuButtonPluginObject : RoguelikeMenuObject`1
{
	private RectTransform _pluginContainer; // 0x28
	private RoguelikeMenuButtonPlugin m_buttonPrefab; // 0x30
	private RoguelikeMenuButtonPlugin m_buttonInst; // 0x38
	private Boolean m_showStateCondition; // 0x40
	private Boolean m_showDataCondition; // 0x41
	private static DelegateBridge __Hotfix0_get_menuType; // 0x0
	private static DelegateBridge __Hotfix0__RenderShowStatus; // 0x8
	private static DelegateBridge __Hotfix0_OnMenuAdapterChanged; // 0x10
	private static DelegateBridge __Hotfix0_RenderSelection; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__RefreshButtonPlugin; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a3e140 VA: 0x7595056140
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a3e1a8 VA: 0x75950561a8
	private Void _RenderShowStatus() { }
	// RVA: 0x2a3e240 VA: 0x7595056240
	public override Void OnMenuAdapterChanged(RoguelikeMenuAdapter adapter, Boolean fastMode) { }
	// RVA: 0x2a3e578 VA: 0x7595056578
	public override Void RenderSelection(RoguelikeMenuType type, Boolean fastMode) { }
	// RVA: 0x2a3e61c VA: 0x759505661c
	public override Void Render(RoguelikeMenuCompViewModel viewModel) { }
	// RVA: 0x2a3e34c VA: 0x759505634c
	private Void _RefreshButtonPlugin(RoguelikeMenuAdapter adapter) { }
	// RVA: 0x2a3e694 VA: 0x7595056694
	public Void .ctor() { }
	// RVA: 0x2a3e724 VA: 0x7595056724
	private Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter P0, Boolean P1) { }
	// RVA: 0x2a3e730 VA: 0x7595056730
	private Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType P0, Boolean P1) { }
}
```