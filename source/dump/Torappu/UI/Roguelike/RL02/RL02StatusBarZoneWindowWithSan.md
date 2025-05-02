# RL02StatusBarZoneWindowWithSan

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Text _textSan`

- `Text _textSanDesc`

- `GameObject _panelSan`

- `GameObject _panelLine`

- `GameObject _panelVariationTitle`

- `RL02ZoneWithSanViewModel m_cachedModel`


## Methods

- `UISwitchTween <>xLuaBaseProxy_GetSwitchTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02StatusBarZoneWindowWithSan : RoguelikeMenuWindow`1
{
	private static Vector2 WINDOW_HIDE_POS; // 0x0
	private static Vector2 WINDOW_SHOW_POS; // 0x8
	private Text _textSan; // 0x28
	private Text _textSanDesc; // 0x30
	private GameObject _panelSan; // 0x38
	private GameObject _panelLine; // 0x40
	private GameObject _panelVariationTitle; // 0x48
	private VariationItem[] _variationItems; // 0x50
	private RL02ZoneWithSanViewModel m_cachedModel; // 0x58
	private static DelegateBridge __Hotfix0_get_selectType; // 0x10
	private static DelegateBridge __Hotfix0_GetSwitchTween; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2b70424 VA: 0x7595188424
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2b7049c VA: 0x759518849c
	protected override UISwitchTween GetSwitchTween() { }
	// RVA: 0x2b705e8 VA: 0x75951885e8
	public override Void Render(RL02ZoneWithSanViewModel viewModel) { }
	// RVA: 0x2b709d8 VA: 0x75951889d8
	public Void .ctor() { }
	// RVA: 0x2b70a78 VA: 0x7595188a78
	private static Void .cctor() { }
	// RVA: 0x2b70ad4 VA: 0x7595188ad4
	private UISwitchTween <>xLuaBaseProxy_GetSwitchTween() { }
}
```