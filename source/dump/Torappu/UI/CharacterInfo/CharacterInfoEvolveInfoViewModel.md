# CharacterInfoEvolveInfoViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `String charId`

- `EvolvePhase oldEvolvePhase`

- `EvolvePhase newEvolvePhase`

- `AttributesData oldAttributeData`

- `AttributesData newAttributeData`

- `Boolean hasRangeChanged`

- `AttackRangeDescModel oldRangeDescModel`

- `AttackRangeDescModel newRangeDescModel`

- `Boolean hasUpdateTrait`

- `String newTraitStr`

- `Boolean hasUnlockEquip`


## Methods

- `Void LoadData(PlayerCharacter, CharacterData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoEvolveInfoViewModel : IHotfixable
{
	public String charId; // 0x10
	public EvolvePhase oldEvolvePhase; // 0x18
	public EvolvePhase newEvolvePhase; // 0x1c
	public AttributesData oldAttributeData; // 0x20
	public AttributesData newAttributeData; // 0x28
	public List`1 talentStructs; // 0x30
	public List`1 updateSkillDatas; // 0x38
	public Boolean hasRangeChanged; // 0x40
	public AttackRangeDescModel oldRangeDescModel; // 0x48
	public AttackRangeDescModel newRangeDescModel; // 0x58
	public Boolean hasUpdateTrait; // 0x68
	public String newTraitStr; // 0x70
	public Boolean hasUnlockEquip; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2d592e0 VA: 0x75953712e0
	public Void LoadData(PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x2d59b1c VA: 0x7595371b1c
	public Void .ctor() { }
}
```