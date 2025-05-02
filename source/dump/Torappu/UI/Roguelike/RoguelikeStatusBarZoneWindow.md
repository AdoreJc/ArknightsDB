# RoguelikeStatusBarZoneWindow

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `VariationPanel _variationPanel1`

- `VariationPanel _variationPanel2`


## Methods

- `UISwitchTween <>xLuaBaseProxy_GetSwitchTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarZoneWindow : RoguelikeMenuWindow`1
{
	private static Vector2 WINDOW_HIDE_POS; // 0x0
	private static Vector2 WINDOW_SHOW_POS; // 0x8
	private VariationPanel _variationPanel1; // 0x28
	private VariationPanel _variationPanel2; // 0x30
	private static DelegateBridge __Hotfix0_get_selectType; // 0x10
	private static DelegateBridge __Hotfix0_GetSwitchTween; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2a777cc VA: 0x759508f7cc
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2a77844 VA: 0x759508f844
	protected override UISwitchTween GetSwitchTween() { }
	// RVA: 0x2a77990 VA: 0x759508f990
	public override Void Render(RoguelikeMenuZoneViewModel viewModel) { }
	// RVA: 0x2a77b3c VA: 0x759508fb3c
	public Void .ctor() { }
	// RVA: 0x2a77bdc VA: 0x759508fbdc
	private static Void .cctor() { }
	// RVA: 0x2a77c38 VA: 0x759508fc38
	private UISwitchTween <>xLuaBaseProxy_GetSwitchTween() { }
}
```