# RoguelikeMenuRelicAdapterObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeMenuRelicLayout _layout`

- `Boolean _showTrap`

- `Int32 _numLimit`

- `RoguelikeMenuRelicViewModel m_cachedModel`

- `UILayoutDimensionListener m_dimensionListener`


## Methods

- `Void _OnLayoutBoundUpdated()`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`

- `Boolean <>xLuaBaseProxy_IsSelected()`

- `Void <>xLuaBaseProxy_OpenSelf()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuRelicAdapterObject : RoguelikeMenuObject`1
{
	private RoguelikeMenuRelicLayout _layout; // 0x28
	private Boolean _showTrap; // 0x30
	private Int32 _numLimit; // 0x34
	private RoguelikeMenuRelicViewModel m_cachedModel; // 0x38
	private UILayoutDimensionListener m_dimensionListener; // 0x40
	private static DelegateBridge __Hotfix0_get_menuType; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__OnLayoutBoundUpdated; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_IsSelected; // 0x20
	private static DelegateBridge __Hotfix0_OpenSelf; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a40bfc VA: 0x7595058bfc
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a40c64 VA: 0x7595058c64
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2a40e7c VA: 0x7595058e7c
	private Void _OnLayoutBoundUpdated() { }
	// RVA: 0x2a41064 VA: 0x7595059064
	public override Void Render(RoguelikeMenuRelicViewModel viewModel) { }
	// RVA: 0x2a41164 VA: 0x7595059164
	public override Boolean IsSelected() { }
	// RVA: 0x2a411d4 VA: 0x75950591d4
	public override Void OpenSelf() { }
	// RVA: 0x2a41250 VA: 0x7595059250
	public Void .ctor() { }
	// RVA: 0x2a412e8 VA: 0x75950592e8
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
	// RVA: 0x2a412f0 VA: 0x75950592f0
	private Boolean <>xLuaBaseProxy_IsSelected() { }
	// RVA: 0x2a412f8 VA: 0x75950592f8
	private Void <>xLuaBaseProxy_OpenSelf() { }
}
```