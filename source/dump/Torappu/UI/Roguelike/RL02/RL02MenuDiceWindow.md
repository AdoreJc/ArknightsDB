# RL02MenuDiceWindow

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Text _dictDesc`

- `UIAtlasImage _diceIcon`

- `UIAtlasObject _diceIconAtlas`

- `Int32 m_cachedFaceNum`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `UISwitchTween <>xLuaBaseProxy_GetSwitchTween()`

- `Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02MenuDiceWindow : RoguelikeMenuWindow`1
{
	private Text _dictDesc; // 0x28
	private UIAtlasImage _diceIcon; // 0x30
	private UIAtlasObject _diceIconAtlas; // 0x38
	private AtlasConfig[] _diceIconConfig; // 0x40
	private Dictionary`2 m_diceIconNameDict; // 0x48
	private Int32 m_cachedFaceNum; // 0x50
	private Boolean m_inited; // 0x54
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_selectType; // 0x8
	private static DelegateBridge __Hotfix0_GetSwitchTween; // 0x10
	private static DelegateBridge __Hotfix0_RenderSelection; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2b6eeb8 VA: 0x7595186eb8
	private Void _InitIfNot() { }
	// RVA: 0x2b6efd0 VA: 0x7595186fd0
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2b6f038 VA: 0x7595187038
	protected override UISwitchTween GetSwitchTween() { }
	// RVA: 0x2b6f09c VA: 0x759518709c
	public override Void RenderSelection(RoguelikeMenuType type, Boolean fastMode) { }
	// RVA: 0x2b6f11c VA: 0x759518711c
	public override Void Render(RL02DiceViewModel viewModel) { }
	// RVA: 0x2b6f298 VA: 0x7595187298
	public Void .ctor() { }
	// RVA: 0x2b6f37c VA: 0x759518737c
	private UISwitchTween <>xLuaBaseProxy_GetSwitchTween() { }
	// RVA: 0x2b6f384 VA: 0x7595187384
	private Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType P0, Boolean P1) { }
}
```