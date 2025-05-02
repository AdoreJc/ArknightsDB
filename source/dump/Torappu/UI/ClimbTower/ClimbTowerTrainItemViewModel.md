# ClimbTowerTrainItemViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Int32 sortId`

- `String towerId`

- `String towerName`

- `String towerSubName`

- `String towerDesc`

- `Boolean isUnlocked`

- `Boolean isComplete`

- `Boolean isInBattle`

- `ClimbTowerLevelModel levelModel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTrainItemViewModel
{
	public Int32 sortId; // 0x10
	public String towerId; // 0x18
	public String towerName; // 0x20
	public String towerSubName; // 0x28
	public String towerDesc; // 0x30
	public Boolean isUnlocked; // 0x38
	public Boolean isComplete; // 0x39
	public Boolean isInBattle; // 0x3a
	public ClimbTowerLevelModel levelModel; // 0x40


	// RVA: 0x2cdace0 VA: 0x75952f2ce0
	public Void .ctor(ClimbTowerSingleTowerData data, Boolean isInBattle) { }
}
```