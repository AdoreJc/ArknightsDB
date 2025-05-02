# GroceryHomeViewModel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Boolean isGoodPanelShow`

- `String mileStonePointName`

- `Int32 mileStonePoint`

- `Int32 nextMileStonePoint`

- `Int32 currentDay`

- `Boolean hasStageLockedOnlyGoodGroup`

- `State currState`

- `UIItemViewModel dailyReward`

- `String nextSaleTimeDesc`

- `Boolean showNextSaleTimeDesc`

- `String actId`


## Methods

- `Void LoadData(String)`

- `Void RefreshPlayerData()`

- `Void _LoadGoodData(Act27SideData)`

- `Void _RefreshMileStoneData(PlayerAct27SideActivity)`

- `Void _RefreshGoodData(PlayerAct27SideActivity, Int64, Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryHomeViewModel : IHotfixable
{
	public Boolean isGoodPanelShow; // 0x10
	public String mileStonePointName; // 0x18
	public Int32 mileStonePoint; // 0x20
	public Int32 nextMileStonePoint; // 0x24
	public Int32 currentDay; // 0x28
	public Boolean hasStageLockedOnlyGoodGroup; // 0x2c
	public State currState; // 0x30
	public UIItemViewModel dailyReward; // 0x38
	public List`1 shopModelList; // 0x40
	public List`1 goodModelList; // 0x48
	public List`1 launchGoodGroupList; // 0x50
	public String nextSaleTimeDesc; // 0x58
	public Boolean showNextSaleTimeDesc; // 0x60
	public String actId; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge __Hotfix0__LoadGoodData; // 0x10
	private static DelegateBridge __Hotfix0__RefreshMileStoneData; // 0x18
	private static DelegateBridge __Hotfix0__RefreshGoodData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2860ed4 VA: 0x7594e78ed4
	public Void LoadData(String actId) { }
	// RVA: 0x2861360 VA: 0x7594e79360
	public Void RefreshPlayerData() { }
	// RVA: 0x2864450 VA: 0x7594e7c450
	private Void _LoadGoodData(Act27SideData gameData) { }
	// RVA: 0x2864680 VA: 0x7594e7c680
	private Void _RefreshMileStoneData(PlayerAct27SideActivity playerData) { }
	// RVA: 0x28647b4 VA: 0x7594e7c7b4
	private Void _RefreshGoodData(PlayerAct27SideActivity playerData, Int64 currTs, Int64 endTs) { }
	// RVA: 0x286521c VA: 0x7594e7d21c
	public Void .ctor() { }
}
```