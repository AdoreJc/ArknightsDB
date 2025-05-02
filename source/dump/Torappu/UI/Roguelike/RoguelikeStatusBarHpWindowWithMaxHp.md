# RoguelikeStatusBarHpWindowWithMaxHp

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textShield`


## Methods

- `UISwitchTween <>xLuaBaseProxy_GetSwitchTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarHpWindowWithMaxHp : RoguelikeMenuWindow`1
{
	private static Vector2 WINDOW_HIDE_POS; // 0x0
	private static Vector2 WINDOW_SHOW_POS; // 0x8
	private Text _textShield; // 0x28
	private static DelegateBridge __Hotfix0_get_selectType; // 0x10
	private static DelegateBridge __Hotfix0_GetSwitchTween; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2a76718 VA: 0x759508e718
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2a76790 VA: 0x759508e790
	protected override UISwitchTween GetSwitchTween() { }
	// RVA: 0x2a768dc VA: 0x759508e8dc
	public override Void Render(RoguelikeStatusBarHpWithMaxHpViewModel viewModel) { }
	// RVA: 0x2a769a4 VA: 0x759508e9a4
	public Void .ctor() { }
	// RVA: 0x2a76a44 VA: 0x759508ea44
	private static Void .cctor() { }
	// RVA: 0x2a76aa0 VA: 0x759508eaa0
	private UISwitchTween <>xLuaBaseProxy_GetSwitchTween() { }
}
```