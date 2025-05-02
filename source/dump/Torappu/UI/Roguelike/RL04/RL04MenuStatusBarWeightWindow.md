# RL04MenuStatusBarWeightWindow

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Text _txtWeightUp`

- `GameObject _panelView`


## Methods

- `UISwitchTween <>xLuaBaseProxy_GetSwitchTween()`

- `Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04MenuStatusBarWeightWindow : RoguelikeMenuWindow`1
{
	private Text _txtWeightUp; // 0x28
	private GameObject _panelView; // 0x30
	private static DelegateBridge __Hotfix0_get_selectType; // 0x0
	private static DelegateBridge __Hotfix0_GetSwitchTween; // 0x8
	private static DelegateBridge __Hotfix0_RenderSelection; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2b2e1dc VA: 0x75951461dc
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2b2e244 VA: 0x7595146244
	protected override UISwitchTween GetSwitchTween() { }
	// RVA: 0x2b2e2a8 VA: 0x75951462a8
	public override Void RenderSelection(RoguelikeMenuType type, Boolean fastMode) { }
	// RVA: 0x2b2e328 VA: 0x7595146328
	public override Void Render(RL04MenuStatusBarWeightViewModel viewModel) { }
	// RVA: 0x2b2e4c8 VA: 0x75951464c8
	public Void .ctor() { }
	// RVA: 0x2b2e558 VA: 0x7595146558
	private UISwitchTween <>xLuaBaseProxy_GetSwitchTween() { }
	// RVA: 0x2b2e560 VA: 0x7595146560
	private Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType P0, Boolean P1) { }
}
```