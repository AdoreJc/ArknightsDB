# ClimbTowerSquadExpansionModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String m_towerId`

- `Int32 m_floor`

- `Int32 m_currentStep`

- `Int32 m_totalStep`

- `ClimbTowerSingleTowerData m_towerData`

- `String m_selectGroupId`

- `String m_selectCharId`

- `Boolean m_canGiveUp`

- `Boolean m_isGiveUpSelected`


## Properties

- `String selectGroupId`

- `String selectCharId`

- `Boolean haveAnySelect`

- `Boolean isGiveUpSelected`

- `Int32 currentStep`

- `Int32 totalStep`

- `String towerName`

- `Int32 currentFloor`

- `String towerId`


## Methods

- `String get_selectGroupId()`

- `String get_selectCharId()`

- `Boolean get_haveAnySelect()`

- `Boolean get_isGiveUpSelected()`

- `Int32 get_currentStep()`

- `Int32 get_totalStep()`

- `String get_towerName()`

- `Int32 get_currentFloor()`

- `String get_towerId()`

- `Void SetData()`

- `Void SetSelect(Boolean, String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadExpansionModel
{
	private String m_towerId; // 0x10
	private Int32 m_floor; // 0x18
	private Int32 m_currentStep; // 0x1c
	private Int32 m_totalStep; // 0x20
	private List`1 m_slotList; // 0x28
	private ClimbTowerSingleTowerData m_towerData; // 0x30
	private String m_selectGroupId; // 0x38
	private String m_selectCharId; // 0x40
	private Boolean m_canGiveUp; // 0x48
	private Boolean m_isGiveUpSelected; // 0x49

	public String selectGroupId { get; }
	public String selectCharId { get; }
	public Boolean haveAnySelect { get; }
	public Boolean isGiveUpSelected { get; }
	public List`1 slotList { get; }
	public Int32 currentStep { get; }
	public Int32 totalStep { get; }
	public String towerName { get; }
	public Int32 currentFloor { get; }
	public String towerId { get; }

	// RVA: 0x2cd1ae4 VA: 0x75952e9ae4
	public String get_selectGroupId() { }
	// RVA: 0x2cd1aec VA: 0x75952e9aec
	public String get_selectCharId() { }
	// RVA: 0x2cd1af4 VA: 0x75952e9af4
	public Boolean get_haveAnySelect() { }
	// RVA: 0x2cd1024 VA: 0x75952e9024
	public Boolean get_isGiveUpSelected() { }
	// RVA: 0x2cd1b28 VA: 0x75952e9b28
	public List`1 get_slotList() { }
	// RVA: 0x2cd1b30 VA: 0x75952e9b30
	public Int32 get_currentStep() { }
	// RVA: 0x2cd1b38 VA: 0x75952e9b38
	public Int32 get_totalStep() { }
	// RVA: 0x2cd1b40 VA: 0x75952e9b40
	public String get_towerName() { }
	// RVA: 0x2cd1b9c VA: 0x75952e9b9c
	public Int32 get_currentFloor() { }
	// RVA: 0x2cd1ba4 VA: 0x75952e9ba4
	public String get_towerId() { }
	// RVA: 0x2ccfb74 VA: 0x75952e7b74
	public Void SetData() { }
	// RVA: 0x2cd0728 VA: 0x75952e8728
	public Void SetSelect(Boolean isGiveUp, String groupId, String charId) { }
	// RVA: 0x2cd1e00 VA: 0x75952e9e00
	public Void .ctor() { }
}
```