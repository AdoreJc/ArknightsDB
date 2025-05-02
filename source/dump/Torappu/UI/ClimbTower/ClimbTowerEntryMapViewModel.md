# ClimbTowerEntryMapViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Boolean isTrainComplete`


## Methods

- `Void LoadData()`

- `ClimbTowerEntryMapTowerModel GetTowerModel(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryMapViewModel : IHotfixable
{
	public List`1 towerList; // 0x10
	public Boolean isTrainComplete; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_GetTowerModel; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2cd700c VA: 0x75952ef00c
	public Void LoadData() { }
	// RVA: 0x2cd78e8 VA: 0x75952ef8e8
	public ClimbTowerEntryMapTowerModel GetTowerModel(String towerId) { }
	// RVA: 0x2cd7a04 VA: 0x75952efa04
	public Void .ctor() { }
}
```