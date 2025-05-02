# BattleCharacterData

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 level`

- `EvolvePhase evolvePhase`

- `Int32 potentialRank`

- `Int32 favorBattlePhase`

- `String prefabKey`

- `String rangeId`

- `CharSkinData skinData`

- `UInt32 uniqueId`

- `ProfessionCategory profession`

- `SubProfessionData subProfessionData`

- `RarityRank rarity`

- `BuildableType deployPositionFromData`

- `String teamKey`

- `Boolean isToken`

- `Boolean isPredefined`

- `Boolean isHidden`

- `Boolean isAssistChar`

- `String tokenOrHostKey`

- `UInt32 tokenOrHostUniqueId`

- `Int32 tokenInitialCnt`

- `BuildCondition buildCondition`

- `Int32 mainSkillIndex`

- `SkillData mainSkill`

- `TraitData trait`

- `String nationId`

- `String groupId`

- `String teamId`

- `SharedData shared`

- `RuntimeData runtimeData`


## Methods

- `String GetPrefabKey()`

- `CharQuery GetCharQuery()`

- `String GetAvatarId()`

- `Boolean TryGetAttackRangeDescModel(Character, Boolean, out)`

- `Boolean CheckGroupTag(IList`1)`

- `Boolean CheckGroupTag(String)`

- `Boolean CheckGroupTagExceptExtraTag(String)`

- `Signiture TakeSigniture()`

- `Boolean CheckSubprofessionTag(String)`

- `BattleCharacterData Duplicate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleCharacterData : BattleEntityData
{
	public Int32 level; // 0x40
	public EvolvePhase evolvePhase; // 0x44
	public Int32 potentialRank; // 0x48
	public Int32 favorBattlePhase; // 0x4c
	public String prefabKey; // 0x50
	public String rangeId; // 0x58
	public CharSkinData skinData; // 0x60
	public UInt32 uniqueId; // 0x68
	public ProfessionCategory profession; // 0x6c
	public SubProfessionData subProfessionData; // 0x70
	public RarityRank rarity; // 0x78
	public BuildableType deployPositionFromData; // 0x7c
	public String teamKey; // 0x80
	public Boolean isToken; // 0x88
	public Boolean isPredefined; // 0x89
	public Boolean isHidden; // 0x8a
	public Boolean isAssistChar; // 0x8b
	public String tokenOrHostKey; // 0x90
	public UInt32 tokenOrHostUniqueId; // 0x98
	public Int32 tokenInitialCnt; // 0x9c
	public BuildCondition buildCondition; // 0xa0
	public Int32 mainSkillIndex; // 0xf0
	public SkillData mainSkill; // 0xf8
	public List`1 talents; // 0x100
	public TraitData trait; // 0x108
	public List`1 uniEquipQueries; // 0x110
	public List`1 uniEquips; // 0x118
	public List`1 uniEquipSettings; // 0x120
	public String nationId; // 0x128
	public String groupId; // 0x130
	public String teamId; // 0x138
	public SharedData shared; // 0x140
	public Nullable`1 attackRangeDesc; // 0x148
	public RuntimeData runtimeData; // 0x160


	// RVA: 0x1c41890 VA: 0x7594259890
	public String GetPrefabKey() { }
	// RVA: 0x1c418c0 VA: 0x75942598c0
	public CharQuery GetCharQuery() { }
	// RVA: 0x1c41924 VA: 0x7594259924
	public String GetAvatarId() { }
	// RVA: 0x1c41978 VA: 0x7594259978
	public Boolean TryGetAttackRangeDescModel(Character characterOrNull, Boolean notLoadFromResource, out AttackRangeDescModel result) { }
	// RVA: 0x1c41b4c VA: 0x7594259b4c
	public Boolean CheckGroupTag(IList`1 groupTags) { }
	// RVA: 0x1c41c68 VA: 0x7594259c68
	public Boolean CheckGroupTag(String groupTag) { }
	// RVA: 0x1c41d80 VA: 0x7594259d80
	public Boolean CheckGroupTagExceptExtraTag(String groupTag) { }
	// RVA: 0x1c41e24 VA: 0x7594259e24
	public Signiture TakeSigniture() { }
	// RVA: 0x1c41e5c VA: 0x7594259e5c
	public Boolean CheckSubprofessionTag(String subprofessionTag) { }
	// RVA: 0x1c41e84 VA: 0x7594259e84
	public BattleCharacterData Duplicate() { }
	// RVA: 0x1c3f0e4 VA: 0x75942570e4
	public Void .ctor() { }
}
```