# RL03MenuVisionAndChaosWindow

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `SimpleLayoutContent _chaosList`

- `ChaosListAdapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType, Boolean)`

- `UISwitchTween <>xLuaBaseProxy_GetSwitchTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03MenuVisionAndChaosWindow : RoguelikeMenuWindow`1
{
	private RL03MenuVCWindowElement[] _elements; // 0x28
	private SimpleLayoutContent _chaosList; // 0x30
	private ChaosListAdapter m_adapter; // 0x38
	private static DelegateBridge __Hotfix0_get_selectType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_RenderSelection; // 0x10
	private static DelegateBridge __Hotfix0_GetSwitchTween; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2b9fe14 VA: 0x75951b7e14
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2b9fe7c VA: 0x75951b7e7c
	public override Void Render(RL03MenuVisionAndChaosViewModel viewModel) { }
	// RVA: 0x2ba013c VA: 0x75951b813c
	public override Void RenderSelection(RoguelikeMenuType type, Boolean fastMode) { }
	// RVA: 0x2ba0270 VA: 0x75951b8270
	protected override UISwitchTween GetSwitchTween() { }
	// RVA: 0x2b9fff8 VA: 0x75951b7ff8
	private Void _InitIfNot() { }
	// RVA: 0x2ba0454 VA: 0x75951b8454
	public Void .ctor() { }
	// RVA: 0x2ba04e4 VA: 0x75951b84e4
	private Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType P0, Boolean P1) { }
	// RVA: 0x2ba04f0 VA: 0x75951b84f0
	private UISwitchTween <>xLuaBaseProxy_GetSwitchTween() { }
}
```