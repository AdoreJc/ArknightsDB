# TowerSeason

**Namespace:** `Torappu`


## Fields

- `String id`

- `Int64 finishTs`

- `TowerSeasonPeriod period`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TowerSeason
{
	public String id; // 0x10
	public Int64 finishTs; // 0x18
	public Dictionary`2 missions; // 0x20
	public Dictionary`2 passWithGodCard; // 0x28
	public Dictionary`2 towerSlotsMap; // 0x30
	public TowerSeasonPeriod period; // 0x38


	// RVA: 0x32dc090 VA: 0x75958f4090
	public Void .ctor() { }
}
```