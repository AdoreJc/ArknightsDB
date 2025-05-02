# RL02DiceResultMutationView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `GameObject _contentPanel`

- `GameObject _emptyPanel`

- `Image _icon`

- `Text _desc`

- `Text _tips`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02DiceResultMutationView : RoguelikeDiceResultView`1
{
	private GameObject _contentPanel; // 0x18
	private GameObject _emptyPanel; // 0x20
	private Image _icon; // 0x28
	private Text _desc; // 0x30
	private Text _tips; // 0x38
	private static DelegateBridge __Hotfix0_get_diceResultShowType; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override DiceResultShowType diceResultShowType { get; }

	// RVA: 0x2b5f9f0 VA: 0x75951779f0
	public override DiceResultShowType get_diceResultShowType() { }
	// RVA: 0x2b5fa58 VA: 0x7595177a58
	public override Void OnRender(RL02DiceResultMutationViewModel model) { }
	// RVA: 0x2b5fbe4 VA: 0x7595177be4
	public Void .ctor() { }
}
```