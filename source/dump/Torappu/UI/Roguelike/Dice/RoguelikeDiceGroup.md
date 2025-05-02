# RoguelikeDiceGroup

**Namespace:** `Torappu.UI.Roguelike.Dice`


## Fields

- `Animator _animator`


## Methods

- `Void RollTo(RoguelikeDiceModelType, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Dice
public class RoguelikeDiceGroup : MonoBehaviour, IHotfixable
{
	private Animator _animator; // 0x18
	private DiceItem[] _dices; // 0x20
	private const String SIDE_TYPE; // 0x0
	private static DelegateBridge __Hotfix0_RollTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2bb7858 VA: 0x75951cf858
	public Void RollTo(RoguelikeDiceModelType diceType, Int32 sideNum) { }
	// RVA: 0x2bb7a34 VA: 0x75951cfa34
	public Void .ctor() { }
}
```