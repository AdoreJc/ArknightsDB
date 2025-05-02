# ClimbTowerSquadExpansionCharModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `TowerCardType m_cardType`

- `String m_charId`

- `CharacterData m_charData`

- `EvolvePhase m_evolvePhase`

- `Int32 m_level`

- `String m_portraitId`


## Properties

- `Boolean isNpc`

- `String charId`

- `CharacterData charData`

- `EvolvePhase evolvePhase`

- `Int32 level`

- `String portraitId`


## Methods

- `Boolean get_isNpc()`

- `String get_charId()`

- `CharacterData get_charData()`

- `EvolvePhase get_evolvePhase()`

- `Int32 get_level()`

- `String get_portraitId()`

- `Void SetData(GameCard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadExpansionCharModel
{
	private TowerCardType m_cardType; // 0x10
	private String m_charId; // 0x18
	private CharacterData m_charData; // 0x20
	private EvolvePhase m_evolvePhase; // 0x28
	private Int32 m_level; // 0x2c
	private String m_portraitId; // 0x30

	public Boolean isNpc { get; }
	public String charId { get; }
	public CharacterData charData { get; }
	public EvolvePhase evolvePhase { get; }
	public Int32 level { get; }
	public String portraitId { get; }

	// RVA: 0x2ccd814 VA: 0x75952e5814
	public Boolean get_isNpc() { }
	// RVA: 0x2cd20b0 VA: 0x75952ea0b0
	public String get_charId() { }
	// RVA: 0x2cd20b8 VA: 0x75952ea0b8
	public CharacterData get_charData() { }
	// RVA: 0x2cd20c0 VA: 0x75952ea0c0
	public EvolvePhase get_evolvePhase() { }
	// RVA: 0x2cd20c8 VA: 0x75952ea0c8
	public Int32 get_level() { }
	// RVA: 0x2cd20d0 VA: 0x75952ea0d0
	public String get_portraitId() { }
	// RVA: 0x2cd1eb8 VA: 0x75952e9eb8
	public Void SetData(GameCard playerChar) { }
	// RVA: 0x2cd1eb0 VA: 0x75952e9eb0
	public Void .ctor() { }
}
```