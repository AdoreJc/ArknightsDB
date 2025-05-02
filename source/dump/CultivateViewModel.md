# CultivateViewModel

**Namespace:** ` `


## Fields

- `AttributeViewProperty attributeProperty`

- `CharacterProfileViewProperty profileProperty`

- `SkillGroupViewProperty skillProperty`

- `BattleInfoViewProperty battleProperty`

- `SpCharInfoViewProperty spCharInfoProperty`

- `BoolProperty isCharacterLocked`

- `Int32 charInstId`

- `String charId`

- `String tmplId`

- `Boolean isReachMaxEvolve`

- `Boolean isReachMaxPotential`

- `Boolean isPotentialApplicable`

- `EvolvePhase evolvePhase`

- `CharacterData charDataCache`

- `Boolean isStarMarked`

- `String focusSkillId`

- `CharInfoEquipShowParam equipShowParam`


## Properties

- `String charName`


## Methods

- `String get_charName()`

- `CharQuery GetCharQuery()`

- `Void SetSelectSkillId(String)`

- `Boolean IsBtnTokenShow()`

- `String GetTokenId()`

- `String _GetSkillTokenId()`

- `String _GetTalentTokenId()`

- `Void SetEquipId(String)`

- `Void LoadData(Int32)`

- `CharTokenViewModel GeneTokenViewModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CultivateViewModel
{
	public AttributeViewProperty attributeProperty; // 0x10
	public CharacterProfileViewProperty profileProperty; // 0x18
	public SkillGroupViewProperty skillProperty; // 0x20
	public BattleInfoViewProperty battleProperty; // 0x28
	public SpCharInfoViewProperty spCharInfoProperty; // 0x30
	public BoolProperty isCharacterLocked; // 0x38
	public Int32 charInstId; // 0x40
	public String charId; // 0x48
	public String tmplId; // 0x50
	public Boolean isReachMaxEvolve; // 0x58
	public Boolean isReachMaxPotential; // 0x59
	public Boolean isPotentialApplicable; // 0x5a
	public EvolvePhase evolvePhase; // 0x5c
	public CharacterData charDataCache; // 0x60
	public Boolean isStarMarked; // 0x68
	public String focusSkillId; // 0x70
	public CharInfoEquipShowParam equipShowParam; // 0x78

	public String charName { get; }

	// RVA: 0x2d54f78 VA: 0x759536cf78
	public String get_charName() { }
	// RVA: 0x2d54fec VA: 0x759536cfec
	public CharQuery GetCharQuery() { }
	// RVA: 0x2d55048 VA: 0x759536d048
	public Void SetSelectSkillId(String skillId) { }
	// RVA: 0x2d55050 VA: 0x759536d050
	public Boolean IsBtnTokenShow() { }
	// RVA: 0x2d55070 VA: 0x759536d070
	public String GetTokenId() { }
	// RVA: 0x2d5513c VA: 0x759536d13c
	private String _GetSkillTokenId() { }
	// RVA: 0x2d551c0 VA: 0x759536d1c0
	private String _GetTalentTokenId() { }
	// RVA: 0x2d55294 VA: 0x759536d294
	public Void SetEquipId(String equipId) { }
	// RVA: 0x2d557cc VA: 0x759536d7cc
	public Void LoadData(Int32 charInstIdParam) { }
	// RVA: 0x2d55e70 VA: 0x759536de70
	public CharTokenViewModel GeneTokenViewModel() { }
	// RVA: 0x2d56244 VA: 0x759536e244
	public Void .ctor() { }
}
```