# UniEquipLevelUpSwitchBoardViewModel

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `Int32 currentLevel`

- `Int32 targetLevel`

- `Boolean showSelectTween`


## Methods

- `Void LoadData(PlayerCharacter, CharacterData, UniEquipData, Int32, Int32, Boolean)`

- `Void SetBoardInfoHeight(Single, Single, Single)`

- `Void _GeneAttributeInfo(PlayerCharacter, UniEquipData)`

- `Void _GeneSubProfession(PlayerCharacter, CharacterData, UniEquipData)`

- `Void _GeneTalents(PlayerCharacter, CharacterData, UniEquipData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipLevelUpSwitchBoardViewModel : IHotfixable
{
	public List`1 boardModelList; // 0x10
	public Int32 currentLevel; // 0x18
	public Int32 targetLevel; // 0x1c
	public Boolean showSelectTween; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SetBoardInfoHeight; // 0x8
	private static DelegateBridge __Hotfix0__GeneAttributeInfo; // 0x10
	private static DelegateBridge __Hotfix0__geneInfoTextForAttr; // 0x18
	private static DelegateBridge __Hotfix0__GeneSubProfession; // 0x20
	private static DelegateBridge __Hotfix0__GeneTalents; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2306dbc VA: 0x759491edbc
	public Void LoadData(PlayerCharacter playerChar, CharacterData charData, UniEquipData uniEquipData, Int32 current, Int32 target, Boolean ifNeedSelectTween) { }
	// RVA: 0x2308d64 VA: 0x7594920d64
	public Void SetBoardInfoHeight(Single basicHeight, Single subProfessionHeight, Single talentHeight) { }
	// RVA: 0x2307178 VA: 0x759491f178
	private Void _GeneAttributeInfo(PlayerCharacter playerChar, UniEquipData uniEquipData) { }
	// RVA: 0x2308f74 VA: 0x7594920f74
	private static Void _geneInfoTextForAttr(List`1 builders, List`1 attributeDeltas, String baseStr, AttributeType attributeType, Boolean eorFlag) { }
	// RVA: 0x23079e0 VA: 0x759491f9e0
	private Void _GeneSubProfession(PlayerCharacter playerChar, CharacterData charData, UniEquipData uniEquipData) { }
	// RVA: 0x23083ec VA: 0x75949203ec
	private Void _GeneTalents(PlayerCharacter playerChar, CharacterData charData, UniEquipData uniEquipData) { }
	// RVA: 0x23093a0 VA: 0x75949213a0
	public Void .ctor() { }
}
```