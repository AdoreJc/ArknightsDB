# CharacterData

**Namespace:** `Torappu`


## Fields

- `String name`

- `String description`

- `Boolean canUseGeneralPotentialItem`

- `Boolean canUseActivityPotentialItem`

- `String potentialItemId`

- `String activityPotentialItemId`

- `String classicPotentialItemId`

- `String nationId`

- `String groupId`

- `String teamId`

- `String displayNumber`

- `String appellation`

- `BuildableType position`

- `String itemUsage`

- `String itemDesc`

- `String itemObtainApproach`

- `Boolean isNotObtainable`

- `Boolean isSpChar`

- `Int32 maxPotentialLevel`

- `RarityRank rarity`

- `ProfessionCategory profession`

- `String subProfessionId`

- `TraitDataBundle trait`

- `AttributesDeltaKeyFrame favorKeyFrames`


## Properties

- `String minPowerId`

- `String maxPowerId`


## Methods

- `Boolean ShouldSerializeclassicPotentialItemId()`

- `Boolean ShouldSerializedisplayTokenDict()`

- `String GetRawDescriptionFormatByTraitBlackboard(Int32, EvolvePhase, Int32)`

- `String get_minPowerId()`

- `String get_maxPowerId()`

- `String GetPowerIdByLevel(PowerLevel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CharacterData
{
	public String name; // 0x10
	public String description; // 0x18
	public Boolean canUseGeneralPotentialItem; // 0x20
	public Boolean canUseActivityPotentialItem; // 0x21
	public String potentialItemId; // 0x28
	public String activityPotentialItemId; // 0x30
	public String classicPotentialItemId; // 0x38
	public String nationId; // 0x40
	public String groupId; // 0x48
	public String teamId; // 0x50
	public String displayNumber; // 0x58
	public String appellation; // 0x60
	public BuildableType position; // 0x68
	public String[] tagList; // 0x70
	public String itemUsage; // 0x78
	public String itemDesc; // 0x80
	public String itemObtainApproach; // 0x88
	public Boolean isNotObtainable; // 0x90
	public Boolean isSpChar; // 0x91
	public Int32 maxPotentialLevel; // 0x94
	public RarityRank rarity; // 0x98
	public ProfessionCategory profession; // 0x9c
	public String subProfessionId; // 0xa0
	public TraitDataBundle trait; // 0xa8
	public PhaseData[] phases; // 0xb0
	public MainSkill[] skills; // 0xb8
	public Dictionary`2 displayTokenDict; // 0xc0
	public TalentDataBundle[] talents; // 0xc8
	public PotentialRank[] potentialRanks; // 0xd0
	public AttributesDeltaKeyFrame favorKeyFrames; // 0xd8
	public SkillLevelCost[] allSkillLvlup; // 0xe0

	public String minPowerId { get; }
	public String maxPowerId { get; }

	// RVA: 0x33c8660 VA: 0x75959e0660
	public Boolean ShouldSerializeclassicPotentialItemId() { }
	// RVA: 0x33c8680 VA: 0x75959e0680
	public Boolean ShouldSerializedisplayTokenDict() { }
	// RVA: 0x33c86d8 VA: 0x75959e06d8
	public String GetRawDescriptionFormatByTraitBlackboard(Int32 level, EvolvePhase phase, Int32 potential) { }
	// RVA: 0x33c8920 VA: 0x75959e0920
	public String get_minPowerId() { }
	// RVA: 0x33c89a0 VA: 0x75959e09a0
	public String get_maxPowerId() { }
	// RVA: 0x33c8a20 VA: 0x75959e0a20
	public String GetPowerIdByLevel(PowerLevel level) { }
	// RVA: 0x33c8a58 VA: 0x75959e0a58
	public Void .ctor() { }
}
```