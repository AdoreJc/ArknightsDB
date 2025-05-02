# CharmItemData

**Namespace:** `Torappu`


## Fields

- `String id`

- `Int32 sort`

- `String name`

- `String icon`

- `String itemUsage`

- `String itemDesc`

- `String itemObtainApproach`

- `CharmRarity rarity`

- `String desc`

- `Int32 price`

- `String specialObtainApproach`

- `String charmType`

- `Boolean obtainInRandom`

- `PackedRuneData runeData`


## Properties

- `String charmEffect`


## Methods

- `String get_charmEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CharmItemData
{
	public String id; // 0x10
	public Int32 sort; // 0x18
	public String name; // 0x20
	public String icon; // 0x28
	public String itemUsage; // 0x30
	public String itemDesc; // 0x38
	public String itemObtainApproach; // 0x40
	public CharmRarity rarity; // 0x48
	public String desc; // 0x50
	public Int32 price; // 0x58
	public String specialObtainApproach; // 0x60
	public String charmType; // 0x68
	public Boolean obtainInRandom; // 0x70
	public String[] dropStages; // 0x78
	public PackedRuneData runeData; // 0x80

	public String charmEffect { get; }

	// RVA: 0x33ca2b0 VA: 0x75959e22b0
	public String get_charmEffect() { }
	// RVA: 0x33ca30c VA: 0x75959e230c
	public Void .ctor() { }
}
```