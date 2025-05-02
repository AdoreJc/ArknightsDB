# RoguelikeItemData

**Namespace:** `Torappu`


## Fields

- `String id`

- `String name`

- `String description`

- `String usage`

- `String obtainApproach`

- `String iconId`

- `RoguelikeItemType type`

- `RoguelikeItemRarity rarity`

- `Int32 value`

- `Int32 sortId`

- `String unlockCond`

- `String unlockCondDesc`

- `RelicStableUnlockParam stableUnlockCond`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeItemData
{
	public String id; // 0x10
	public String name; // 0x18
	public String description; // 0x20
	public String usage; // 0x28
	public String obtainApproach; // 0x30
	public String iconId; // 0x38
	public RoguelikeItemType type; // 0x40
	public RoguelikeItemRarity rarity; // 0x44
	public Int32 value; // 0x48
	public Int32 sortId; // 0x4c
	public String unlockCond; // 0x50
	public String unlockCondDesc; // 0x58
	public List`1 unlockCondParams; // 0x60
	public RelicStableUnlockParam stableUnlockCond; // 0x68


	// RVA: 0x34a8b34 VA: 0x7595ac0b34
	public Void .ctor() { }
}
```