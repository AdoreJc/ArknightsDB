# RL02DiceResultVirtueView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Image _icon`

- `Text _desc`

- `Text _tips`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02DiceResultVirtueView : RoguelikeDiceResultView`1
{
	private Image _icon; // 0x18
	private Text _desc; // 0x20
	private Text _tips; // 0x28
	private static DelegateBridge __Hotfix0_get_diceResultShowType; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override DiceResultShowType diceResultShowType { get; }

	// RVA: 0x2b60258 VA: 0x7595178258
	public override DiceResultShowType get_diceResultShowType() { }
	// RVA: 0x2b602c0 VA: 0x75951782c0
	public override Void OnRender(RL02DiceResultVirtueViewModel model) { }
	// RVA: 0x2b603e4 VA: 0x75951783e4
	public Void .ctor() { }
}
```