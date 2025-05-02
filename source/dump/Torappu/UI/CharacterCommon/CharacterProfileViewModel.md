# CharacterProfileViewModel

**Namespace:** `Torappu.UI.CharacterCommon`


## Fields

- `CharQuery charQuery`

- `String nickName`

- `String realName`

- `RarityRank rarity`

- `String featureDescBasic`

- `String featureDescAdditive`

- `Sprite campLogo`

- `String powerId`

- `Boolean hasMultipleTmpl`

- `String rawFeatureDesc`

- `EvolvePhase evolvePhase`

- `Int32 level`

- `Int32 potentialRank`

- `String currentSelectEquipId`

- `String currentEquipId`

- `Boolean haveAvailEquip`

- `Boolean haveEquip`

- `String subProfessionInfo`


## Methods

- `Int32 GetSelectEquipPosition()`

- `String GetFinalWrappedDesc()`

- `Void OnRefreshEquipInfo(String)`

- `Void _RefreshEquipInfoForTargetEquip(String)`

- `Void LoadData(CharacterData, CharQuery, EvolvePhase, Int32, Int32, Boolean, String, ListDict`2)`

- `Void LoadData(PlayerCharacter, CharacterData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterCommon
public class CharacterProfileViewModel
{
	public CharQuery charQuery; // 0x10
	public String nickName; // 0x28
	public String realName; // 0x30
	public RarityRank rarity; // 0x38
	public CharacterTalentViewModel[] talentDescs; // 0x40
	public List`1 equips; // 0x48
	public String featureDescBasic; // 0x50
	public String featureDescAdditive; // 0x58
	public Sprite campLogo; // 0x60
	public String powerId; // 0x68
	public Boolean hasMultipleTmpl; // 0x70
	public String rawFeatureDesc; // 0x78
	public EvolvePhase evolvePhase; // 0x80
	public Int32 level; // 0x84
	public Int32 potentialRank; // 0x88
	public String currentSelectEquipId; // 0x90
	public String currentEquipId; // 0x98
	public Boolean haveAvailEquip; // 0xa0
	public Boolean haveEquip; // 0xa1
	public String subProfessionInfo; // 0xa8


	// RVA: 0x2d8e91c VA: 0x75953a691c
	public Int32 GetSelectEquipPosition() { }
	// RVA: 0x2d865b0 VA: 0x759539e5b0
	public String GetFinalWrappedDesc() { }
	// RVA: 0x2d8e9e0 VA: 0x75953a69e0
	public Void OnRefreshEquipInfo(String equipId) { }
	// RVA: 0x2d8ea0c VA: 0x75953a6a0c
	private Void _RefreshEquipInfoForTargetEquip(String equipId) { }
	// RVA: 0x2d8ece0 VA: 0x75953a6ce0
	public Void LoadData(CharacterData charData, CharQuery charQuery, EvolvePhase evolvePhase, Int32 level, Int32 potentialRank, Boolean hasMultipleTmpl, String currentEquipId, ListDict`2 currentEquipInfo) { }
	// RVA: 0x2d8f400 VA: 0x75953a7400
	public Void LoadData(PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x2d8f524 VA: 0x75953a7524
	public Void .ctor() { }
}
```