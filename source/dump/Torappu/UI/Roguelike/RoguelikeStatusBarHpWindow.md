# RoguelikeStatusBarHpWindow

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textShieldHpDesc`


## Methods

- `UISwitchTween <>xLuaBaseProxy_GetSwitchTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarHpWindow : RoguelikeMenuWindow`1
{
	private static Vector2 WINDOW_HIDE_POS; // 0x0
	private static Vector2 WINDOW_SHOW_POS; // 0x8
	private Text _textShieldHpDesc; // 0x28
	private static DelegateBridge __Hotfix0_get_selectType; // 0x10
	private static DelegateBridge __Hotfix0_GetSwitchTween; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2a7638c VA: 0x759508e38c
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2a76404 VA: 0x759508e404
	protected override UISwitchTween GetSwitchTween() { }
	// RVA: 0x2a76550 VA: 0x759508e550
	public override Void Render(RoguelikeMenuHpViewModel viewModel) { }
	// RVA: 0x2a76618 VA: 0x759508e618
	public Void .ctor() { }
	// RVA: 0x2a766b8 VA: 0x759508e6b8
	private static Void .cctor() { }
	// RVA: 0x2a76714 VA: 0x759508e714
	private UISwitchTween <>xLuaBaseProxy_GetSwitchTween() { }
}
```