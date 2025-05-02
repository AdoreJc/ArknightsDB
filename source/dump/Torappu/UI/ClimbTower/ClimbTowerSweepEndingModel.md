# ClimbTowerSweepEndingModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String towerId`

- `String towerName`

- `String towerSubName`

- `Int32 floorCurr`

- `Int32 floorTarget`

- `Boolean isHard`

- `Int64 finishTs`

- `String lowerItemName`

- `String higherItemName`

- `Sprite lowerItemIcon`

- `Sprite higherItemIcon`

- `Int32 lowerItemStartFee`

- `Int32 lowerItemEndFee`

- `Int32 lowerItemTotalFee`

- `Int32 lowerItemGain`

- `Int32 higherItemStartFee`

- `Int32 higherItemEndFee`

- `Int32 higherItemGain`

- `Int32 higherItemTotalFee`


## Methods

- `Void LoadData(ClimbTowerSweepResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSweepEndingModel : IHotfixable
{
	public String towerId; // 0x10
	public String towerName; // 0x18
	public String towerSubName; // 0x20
	public Int32 floorCurr; // 0x28
	public Int32 floorTarget; // 0x2c
	public Boolean isHard; // 0x30
	public Int64 finishTs; // 0x38
	public String lowerItemName; // 0x40
	public String higherItemName; // 0x48
	public Sprite lowerItemIcon; // 0x50
	public Sprite higherItemIcon; // 0x58
	public Int32 lowerItemStartFee; // 0x60
	public Int32 lowerItemEndFee; // 0x64
	public Int32 lowerItemTotalFee; // 0x68
	public Int32 lowerItemGain; // 0x6c
	public Int32 higherItemStartFee; // 0x70
	public Int32 higherItemEndFee; // 0x74
	public Int32 higherItemGain; // 0x78
	public Int32 higherItemTotalFee; // 0x7c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2cd3a98 VA: 0x75952eba98
	public Void LoadData(ClimbTowerSweepResponse response) { }
	// RVA: 0x2cd3e30 VA: 0x75952ebe30
	public Void .ctor() { }
}
```