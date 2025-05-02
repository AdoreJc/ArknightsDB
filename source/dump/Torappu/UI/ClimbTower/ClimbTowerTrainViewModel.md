# ClimbTowerTrainViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Boolean isInBattle`

- `String selectedTower`

- `Boolean isAllComplete`

- `Boolean isInit`


## Methods

- `Void LoadData(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTrainViewModel : IHotfixable
{
	public ListDict`2 towerModel; // 0x10
	public Boolean isInBattle; // 0x18
	public String selectedTower; // 0x20
	public Boolean isAllComplete; // 0x28
	public Boolean isInit; // 0x29
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2cdb18c VA: 0x75952f318c
	public Void LoadData(Boolean resetSelectedTower) { }
	// RVA: 0x2cdb6c0 VA: 0x75952f36c0
	public Void .ctor() { }
}
```