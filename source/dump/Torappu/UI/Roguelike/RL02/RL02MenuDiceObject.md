# RL02MenuDiceObject

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Text _textNum`

- `UIAtlasImage _diceIcon`

- `UIAtlasObject _diceIconAtlas`

- `Int32 m_cachedFaceNum`


## Methods

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02MenuDiceObject : RoguelikeMenuObject`1
{
	private Text _textNum; // 0x28
	private UIAtlasImage _diceIcon; // 0x30
	private UIAtlasObject _diceIconAtlas; // 0x38
	private AtlasConfig[] _diceIconConfig; // 0x40
	private Dictionary`2 m_diceIconNameDict; // 0x48
	private Int32 m_cachedFaceNum; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_get_menuType; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2b6b5ac VA: 0x75951835ac
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2b6b6cc VA: 0x75951836cc
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2b6b734 VA: 0x7595183734
	public override Void Render(RL02DiceViewModel viewModel) { }
	// RVA: 0x2b6b8b8 VA: 0x75951838b8
	public Void .ctor() { }
	// RVA: 0x2b6b99c VA: 0x759518399c
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
}
```