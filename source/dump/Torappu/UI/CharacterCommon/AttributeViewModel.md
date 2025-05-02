# AttributeViewModel

**Namespace:** `Torappu.UI.CharacterCommon`


## Fields

- `Int32 level`

- `Int32 maxLevel`

- `Single expProgress`

- `String expDesc`

- `String maxExpDesc`

- `Int32 maxHp`

- `Int32 atk`

- `Int32 def`

- `Single res`

- `String respawnTime`

- `Int32 cost`

- `EvolvePhase evolvePhase`

- `ProfessionCategory professionID`

- `Int32 potentialRank`

- `Int32 favorPercent`

- `Int32 favorBattlePhase`

- `String descrption`

- `String descAdditive`

- `AttributesData favorDelta`

- `Int32 mainSkillLvl`

- `String atkSpeed`

- `String blockNum`

- `String position`

- `String tagsContent`

- `String subProfessionId`


## Methods

- `Void LoadData(CharacterData, String, EvolvePhase, Int32, Int32, Int32, Int32, List`1, Boolean)`

- `Void LoadData(PlayerCharacter, CharacterData, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterCommon
public class AttributeViewModel
{
	private const Int32 TAG_LINE_WIDTH; // 0x0
	public Int32 level; // 0x10
	public Int32 maxLevel; // 0x14
	public Single expProgress; // 0x18
	public String expDesc; // 0x20
	public String maxExpDesc; // 0x28
	public Int32 maxHp; // 0x30
	public Int32 atk; // 0x34
	public Int32 def; // 0x38
	public Single res; // 0x3c
	public String respawnTime; // 0x40
	public Int32 cost; // 0x48
	public EvolvePhase evolvePhase; // 0x4c
	public ProfessionCategory professionID; // 0x50
	public Int32 potentialRank; // 0x54
	public Int32 favorPercent; // 0x58
	public Int32 favorBattlePhase; // 0x5c
	public String descrption; // 0x60
	public String descAdditive; // 0x68
	public AttributesData favorDelta; // 0x70
	public Int32 mainSkillLvl; // 0x78
	public String atkSpeed; // 0x80
	public String blockNum; // 0x88
	public String position; // 0x90
	public String tagsContent; // 0x98
	public String subProfessionId; // 0xa0


	// RVA: 0x2d8dda0 VA: 0x75953a5da0
	public Void LoadData(CharacterData charData, String charId, EvolvePhase evolvePhaseInput, Int32 levelInput, Int32 expInput, Int32 potentialRankInput, Int32 favorPointInput, List`1 equips, Boolean isToken) { }
	// RVA: 0x2d8e528 VA: 0x75953a6528
	public Void LoadData(PlayerCharacter playerChar, CharacterData charData, String selectedEquipId) { }
	// RVA: 0x2d8e6cc VA: 0x75953a66cc
	public Void .ctor() { }
}
```