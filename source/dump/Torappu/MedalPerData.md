# MedalPerData

**Namespace:** `Torappu`


## Fields

- `String medalId`

- `String medalName`

- `String medalType`

- `Int32 slotId`

- `MedalRarity rarity`

- `String template`

- `String getMethod`

- `String description`

- `String advancedMedal`

- `String originMedal`

- `Int64 displayTime`

- `Boolean isHidden`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class MedalPerData
{
	public String medalId; // 0x10
	public String medalName; // 0x18
	public String medalType; // 0x20
	public Int32 slotId; // 0x28
	public String[] preMedalIdList; // 0x30
	public MedalRarity rarity; // 0x38
	public String template; // 0x40
	public List`1 unlockParam; // 0x48
	public String getMethod; // 0x50
	public String description; // 0x58
	public String advancedMedal; // 0x60
	public String originMedal; // 0x68
	public Int64 displayTime; // 0x70
	public List`1 expireTimes; // 0x78
	public List`1 medalRewardGroup; // 0x80
	public Boolean isHidden; // 0x88


	// RVA: 0x34a4f84 VA: 0x7595abcf84
	public virtual Boolean ShouldSerializedisplayTime() { }
	// RVA: 0x34a4f8c VA: 0x7595abcf8c
	public virtual Boolean ShouldSerializeisHidden() { }
	// RVA: 0x34a4f94 VA: 0x7595abcf94
	public Void .ctor() { }
}
```