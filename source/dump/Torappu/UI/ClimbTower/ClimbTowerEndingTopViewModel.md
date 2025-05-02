# ClimbTowerEndingTopViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String towerId`

- `Int32 floorCurr`

- `Int32 floorTarget`

- `Boolean isHard`

- `Boolean isSubCardSelected`

- `ClimbTowerSingleTowerData towerData`

- `Boolean isTowerCompleted`

- `ClimbTowerViewModel towerModel`


## Methods

- `Void LoadData(ClimbTowerViewModel)`

- `Boolean IsLevelPassed(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEndingTopViewModel : IHotfixable
{
	public String towerId; // 0x10
	public Int32 floorCurr; // 0x18
	public Int32 floorTarget; // 0x1c
	public Boolean isHard; // 0x20
	public Boolean isSubCardSelected; // 0x21
	public ClimbTowerSingleTowerData towerData; // 0x28
	public Boolean isTowerCompleted; // 0x30
	public ClimbTowerViewModel towerModel; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_IsLevelPassed; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c9f948 VA: 0x75952b7948
	public Void LoadData(ClimbTowerViewModel model) { }
	// RVA: 0x2c9fab4 VA: 0x75952b7ab4
	public Boolean IsLevelPassed(Int32 layerNum) { }
	// RVA: 0x2c9fa44 VA: 0x75952b7a44
	public Void .ctor() { }
}
```