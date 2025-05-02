# ClimbTowerRewardModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Int32 levelNum`

- `State state`


## Methods

- `Void LoadData(ClimbTowerTaskRewardData, TowerData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerRewardModel : IHotfixable
{
	public Int32 levelNum; // 0x10
	public List`1 rewards; // 0x18
	public State state; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2cdc00c VA: 0x75952f400c
	public Void LoadData(ClimbTowerTaskRewardData rewardItem, TowerData towerPlayerData) { }
	// RVA: 0x2cdc104 VA: 0x75952f4104
	public Void .ctor() { }
}
```