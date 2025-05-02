# CharacterDetailViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `AttributeViewProperty attributeProperty`

- `CharacterProfileViewProperty profileProperty`

- `SkillGroupViewProperty skillProperty`

- `BattleInfoViewProperty battleProperty`

- `CharacterIllustViewProperty illustProperty`

- `SpCharInfoViewProperty spCharInfoProperty`

- `BoolProperty isCharacterLocked`

- `Int32 charInstId`

- `String charId`

- `String tmplId`

- `Boolean isReachMaxEvolve`

- `EvolvePhase evolvePhase`

- `CharacterData charDataCache`

- `Boolean isStarMarked`


## Properties

- `String charName`


## Methods

- `String get_charName()`

- `CharQuery GetCharQuery()`

- `Void LoadData(Int32, Boolean)`

- `Void ClearData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterDetailViewModel : MonoBehaviour, IDataBindWrapper
{
	public AttributeViewProperty attributeProperty; // 0x18
	public CharacterProfileViewProperty profileProperty; // 0x20
	public SkillGroupViewProperty skillProperty; // 0x28
	public BattleInfoViewProperty battleProperty; // 0x30
	public CharacterIllustViewProperty illustProperty; // 0x38
	public SpCharInfoViewProperty spCharInfoProperty; // 0x40
	public BoolProperty isCharacterLocked; // 0x48
	public Int32 charInstId; // 0x50
	public String charId; // 0x58
	public String tmplId; // 0x60
	public Boolean isReachMaxEvolve; // 0x68
	public EvolvePhase evolvePhase; // 0x6c
	public CharacterData charDataCache; // 0x70
	public Boolean isStarMarked; // 0x78

	public String charName { get; }

	// RVA: 0x2d536c4 VA: 0x759536b6c4
	public String get_charName() { }
	// RVA: 0x2d53730 VA: 0x759536b730
	public CharQuery GetCharQuery() { }
	// RVA: 0x2d5378c VA: 0x759536b78c
	public Void LoadData(Int32 charInstIdParam, Boolean autoActivateIllust) { }
	// RVA: 0x2d53d48 VA: 0x759536bd48
	public Void ClearData() { }
	// RVA: 0x2d53e44 VA: 0x759536be44
	public Void .ctor() { }
}
```