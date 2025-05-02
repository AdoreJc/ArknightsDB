# RoguelikeMenuRelicWindow

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `SimpleLayoutContent _container`

- `Boolean _showTrap`

- `UIAnimationLocation _showAnim`

- `RowLimitType _limitType`

- `Int32 _limitNum`

- `Adapter m_adapter`

- `Boolean m_cachedShowStatus`

- `Boolean m_cachedLimitStatus`

- `RoguelikeMenuRelicViewModel m_cachedModel`

- `AnimationSwitchTween m_showSwitchTween`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Boolean _GetLimitStatus(RoguelikeMenuRelicViewModel)`

- `Int32 _GetRelicCount(RoguelikeMenuRelicViewModel)`

- `UISwitchTween <>xLuaBaseProxy_GetSwitchTween()`

- `Boolean <>xLuaBaseProxy_IsSelected(RoguelikeMenuType)`

- `Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuRelicWindow : RoguelikeMenuWindow`1
{
	private const Single ANIM_DURATION; // 0x0
	private const Int32 ITEM_COUNT_PER_ROW; // 0x0
	private SimpleLayoutContent _container; // 0x28
	private Boolean _showTrap; // 0x30
	private UIAnimationLocation _showAnim; // 0x38
	private RowLimitType _limitType; // 0x48
	private Int32 _limitNum; // 0x4c
	private Adapter m_adapter; // 0x50
	private Boolean m_cachedShowStatus; // 0x58
	private Boolean m_cachedLimitStatus; // 0x59
	private RoguelikeMenuRelicViewModel m_cachedModel; // 0x60
	private List`1 m_wholeRelicViewModels; // 0x68
	private AnimationSwitchTween m_showSwitchTween; // 0x70
	private Boolean m_inited; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetSwitchTween; // 0x8
	private static DelegateBridge __Hotfix0_get_selectType; // 0x10
	private static DelegateBridge __Hotfix0_IsSelected; // 0x18
	private static DelegateBridge __Hotfix0_RenderSelection; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0__GetLimitStatus; // 0x30
	private static DelegateBridge __Hotfix0__GetRelicCount; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2a73738 VA: 0x759508b738
	private Void _InitIfNot() { }
	// RVA: 0x2a7389c VA: 0x759508b89c
	protected override UISwitchTween GetSwitchTween() { }
	// RVA: 0x2a739a4 VA: 0x759508b9a4
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2a73a0c VA: 0x759508ba0c
	public override Boolean IsSelected(RoguelikeMenuType type) { }
	// RVA: 0x2a73b48 VA: 0x759508bb48
	public override Void RenderSelection(RoguelikeMenuType type, Boolean fastMode) { }
	// RVA: 0x2a73d6c VA: 0x759508bd6c
	public override Void Render(RoguelikeMenuRelicViewModel viewModel) { }
	// RVA: 0x2a73e8c VA: 0x759508be8c
	private Boolean _GetLimitStatus(RoguelikeMenuRelicViewModel viewModel) { }
	// RVA: 0x2a74014 VA: 0x759508c014
	private Int32 _GetRelicCount(RoguelikeMenuRelicViewModel viewModel) { }
	// RVA: 0x2a740b4 VA: 0x759508c0b4
	public Void .ctor() { }
	// RVA: 0x2a74144 VA: 0x759508c144
	private UISwitchTween <>xLuaBaseProxy_GetSwitchTween() { }
	// RVA: 0x2a74294 VA: 0x759508c294
	private Boolean <>xLuaBaseProxy_IsSelected(RoguelikeMenuType P0) { }
	// RVA: 0x2a74298 VA: 0x759508c298
	private Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType P0, Boolean P1) { }
}
```