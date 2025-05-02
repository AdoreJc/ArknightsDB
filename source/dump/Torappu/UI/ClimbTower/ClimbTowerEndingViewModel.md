# ClimbTowerEndingViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String towerId`

- `String towerName`

- `String towerSubName`

- `Int32 floorCurr`

- `Int32 floorTarget`

- `Boolean isTrainTower`

- `String mainCardId`

- `String subCardId`

- `Int32 subCardIndex`

- `Status status`

- `Boolean isHard`

- `Int64 finishTs`

- `Boolean isValid`


## Methods

- `Void LoadData(Boolean, List`1, TowerCurrent, ClimbTowerSettleGameResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEndingViewModel : IHotfixable
{
	public String towerId; // 0x10
	public String towerName; // 0x18
	public String towerSubName; // 0x20
	public Int32 floorCurr; // 0x28
	public Int32 floorTarget; // 0x2c
	public Boolean isTrainTower; // 0x30
	public String mainCardId; // 0x38
	public String subCardId; // 0x40
	public Int32 subCardIndex; // 0x48
	public Status status; // 0x4c
	public Boolean isHard; // 0x50
	public List`1 characterList; // 0x58
	public List`1 trapList; // 0x60
	public Int64 finishTs; // 0x68
	public Boolean isValid; // 0x70
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2c9d708 VA: 0x75952b5708
	public Void LoadData(Boolean isTutorial, List`1 predefinedCharList, TowerCurrent playerCurrent, ClimbTowerSettleGameResponse response) { }
	// RVA: 0x2c9e334 VA: 0x75952b6334
	public Void .ctor() { }
}
```