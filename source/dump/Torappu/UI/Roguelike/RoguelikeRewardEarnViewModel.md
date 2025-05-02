# RoguelikeRewardEarnViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Int32 currentHp`

- `Int32 deltaHp`

- `Int32 perfectChain`

- `Boolean hasMaxHpLimit`

- `Int32 currentMaxHp`

- `Int32 deltaMaxHp`

- `Int32 initLevel`

- `Int32 currentLevel`

- `Int32 maxLevel`

- `Int32 initExp`

- `Int32 currentExp`

- `Int32 additiveExp`

- `Int32 currentShield`

- `Int32 deltaShield`

- `Int32 popAdd`

- `Int32 popCurrent`

- `Int32 popCurrentMax`

- `RewardHpShowStatus hpShowState`


## Properties

- `Int32 initHp`

- `Int32 initShield`


## Methods

- `Int32 get_initHp()`

- `Int32 get_initShield()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardEarnViewModel : IHotfixable
{
	public Int32 currentHp; // 0x10
	public Int32 deltaHp; // 0x14
	public Int32 perfectChain; // 0x18
	public Boolean hasMaxHpLimit; // 0x1c
	public Int32 currentMaxHp; // 0x20
	public Int32 deltaMaxHp; // 0x24
	public Int32 initLevel; // 0x28
	public Int32 currentLevel; // 0x2c
	public Int32 maxLevel; // 0x30
	public Int32 initExp; // 0x34
	public Int32 currentExp; // 0x38
	public Int32 additiveExp; // 0x3c
	public Int32 currentShield; // 0x40
	public Int32 deltaShield; // 0x44
	public Int32 popAdd; // 0x48
	public List`1 lvUpPopInfos; // 0x50
	public Int32 popCurrent; // 0x58
	public Int32 popCurrentMax; // 0x5c
	public RewardHpShowStatus hpShowState; // 0x60
	public Dictionary`2 currentLevelDataTable; // 0x68
	private static DelegateBridge __Hotfix0_get_initHp; // 0x0
	private static DelegateBridge __Hotfix0_get_initShield; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Int32 initHp { get; }
	public Int32 initShield { get; }

	// RVA: 0x2a97ce4 VA: 0x75950afce4
	public Int32 get_initHp() { }
	// RVA: 0x2a97d50 VA: 0x75950afd50
	public Int32 get_initShield() { }
	// RVA: 0x2aa36b4 VA: 0x75950bb6b4
	public Void .ctor() { }
}
```