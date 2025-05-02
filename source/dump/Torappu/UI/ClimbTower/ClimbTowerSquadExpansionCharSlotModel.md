# ClimbTowerSquadExpansionCharSlotModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String m_groupId`

- `TowerCardType m_cardType`


## Properties

- `String groupId`

- `TowerCardType cardType`

- `Boolean isGroup`

- `Boolean isGiveUpSlot`


## Methods

- `String get_groupId()`

- `TowerCardType get_cardType()`

- `Boolean get_isGroup()`

- `Boolean get_isGiveUpSlot()`

- `ClimbTowerSquadExpansionCharModel FindFirstNormalCharModel()`

- `Void SetData(HalftimeCandidateGroup)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadExpansionCharSlotModel : IClimbTowerExpansionSlot
{
	private String m_groupId; // 0x10
	private TowerCardType m_cardType; // 0x18
	private List`1 m_charList; // 0x20

	public String groupId { get; }
	public TowerCardType cardType { get; }
	public Boolean isGroup { get; }
	public List`1 charList { get; }
	public Boolean isGiveUpSlot { get; }

	// RVA: 0x2cd1e90 VA: 0x75952e9e90
	public String get_groupId() { }
	// RVA: 0x2cd1e98 VA: 0x75952e9e98
	public TowerCardType get_cardType() { }
	// RVA: 0x2cce088 VA: 0x75952e6088
	public Boolean get_isGroup() { }
	// RVA: 0x2cd1ea0 VA: 0x75952e9ea0
	public List`1 get_charList() { }
	// RVA: 0x2cd1ea8 VA: 0x75952e9ea8
	public Boolean get_isGiveUpSlot() { }
	// RVA: 0x2cce210 VA: 0x75952e6210
	public ClimbTowerSquadExpansionCharModel FindFirstNormalCharModel() { }
	// RVA: 0x2cd1c34 VA: 0x75952e9c34
	public Void SetData(HalftimeCandidateGroup candidate) { }
	// RVA: 0x2cd1bac VA: 0x75952e9bac
	public Void .ctor() { }
}
```