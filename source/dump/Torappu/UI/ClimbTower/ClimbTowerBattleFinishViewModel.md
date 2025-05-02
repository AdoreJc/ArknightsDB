# ClimbTowerBattleFinishViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `BattleStageInfo stageInfo`

- `String illustInstId`

- `String towerId`

- `Boolean isHardMode`

- `String towerName`

- `String towerSubName`

- `Int32 totalLayerCount`

- `Int32 currentLayoutCount`

- `Boolean isNewRecord`

- `Boolean isHardStage`

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


## Properties

- `Int32 UnitCount`


## Methods

- `Int32 get_UnitCount()`

- `Void LoadData(Param)`

- `Void _LoadDropItemData(ClimbTowerBattleFinishResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerBattleFinishViewModel : IHotfixable
{
	public BattleStageInfo stageInfo; // 0x10
	public String illustInstId; // 0x80
	public String towerId; // 0x88
	public Boolean isHardMode; // 0x90
	public String towerName; // 0x98
	public String towerSubName; // 0xa0
	public Int32 totalLayerCount; // 0xa8
	public Int32 currentLayoutCount; // 0xac
	public Boolean isNewRecord; // 0xb0
	public List`1 gainUnitIds; // 0xb8
	public Boolean isHardStage; // 0xc0
	public String lowerItemName; // 0xc8
	public String higherItemName; // 0xd0
	public Sprite lowerItemIcon; // 0xd8
	public Sprite higherItemIcon; // 0xe0
	public Int32 lowerItemStartFee; // 0xe8
	public Int32 lowerItemEndFee; // 0xec
	public Int32 lowerItemTotalFee; // 0xf0
	public Int32 lowerItemGain; // 0xf4
	public Int32 higherItemStartFee; // 0xf8
	public Int32 higherItemEndFee; // 0xfc
	public Int32 higherItemGain; // 0x100
	public Int32 higherItemTotalFee; // 0x104
	private static DelegateBridge __Hotfix0_get_UnitCount; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__LoadDropItemData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Int32 UnitCount { get; }

	// RVA: 0x2cd4a04 VA: 0x75952eca04
	public Int32 get_UnitCount() { }
	// RVA: 0x2cd4a84 VA: 0x75952eca84
	public Void LoadData(Param param) { }
	// RVA: 0x2cd4dbc VA: 0x75952ecdbc
	private Void _LoadDropItemData(ClimbTowerBattleFinishResponse response) { }
	// RVA: 0x2cd5054 VA: 0x75952ed054
	public Void .ctor() { }
}
```