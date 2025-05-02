# CharTokenViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `AttributeViewModel attributeModel`

- `BattleInfoViewModel battleInfoModel`

- `SkillItemViewModel skillItemViewModel`

- `String pos`

- `String tokenAvatarId`

- `CharacterData tokenCharData`

- `Boolean isTalentShow`

- `Boolean isSkillShow`

- `Boolean isSubProfShow`

- `Boolean haveDetailShow`


## Methods

- `String GetFinalWrappedDesc()`

- `Void _LoadData(Int32, Int32, Int32, Int32, EvolvePhase, String, Int32, Int32, String, String, String, String, CharacterData)`

- `String _GetTokenAvatarId(String, String)`

- `Void _AddTokenShownTalent(TalentData, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharTokenViewModel : IHotfixable
{
	public AttributeViewModel attributeModel; // 0x10
	public BattleInfoViewModel battleInfoModel; // 0x18
	public SkillItemViewModel skillItemViewModel; // 0x20
	public List`1 talentViewModels; // 0x28
	public String pos; // 0x30
	public String tokenAvatarId; // 0x38
	public CharacterData tokenCharData; // 0x40
	public Boolean isTalentShow; // 0x48
	public Boolean isSkillShow; // 0x49
	public Boolean isSubProfShow; // 0x4a
	public Boolean haveDetailShow; // 0x4b
	private static DelegateBridge __Hotfix0_CreateCharTokenViewModel; // 0x0
	private static DelegateBridge __Hotfix1_CreateCharTokenViewModel; // 0x8
	private static DelegateBridge __Hotfix0_GetFinalWrappedDesc; // 0x10
	private static DelegateBridge __Hotfix0__LoadData; // 0x18
	private static DelegateBridge __Hotfix0__GetTokenAvatarId; // 0x20
	private static DelegateBridge __Hotfix0__GetTokenTalentModelList; // 0x28
	private static DelegateBridge __Hotfix0__AddTokenShownTalent; // 0x30
	private static DelegateBridge __Hotfix0__CheckLoadTokenDataValid; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2d55f1c VA: 0x759536df1c
	public static CharTokenViewModel CreateCharTokenViewModel(Int32 hostInstId, String hostTmplId, String tokenId, String hostFocusSkillId, String hostSelectEquipId) { }
	// RVA: 0x2d588c4 VA: 0x75953708c4
	public static CharTokenViewModel CreateCharTokenViewModel(Int32 level, Int32 exp, Int32 favorPoint, Int32 potentialRank, EvolvePhase evolvePhase, String skinId, Int32 equipLevel, Int32 skillLevel, String hostCharId, String hostTmplId, String tokenId, String hostFocusSkillId, String hostSelectEquipId) { }
	// RVA: 0x2d58a20 VA: 0x7595370a20
	public String GetFinalWrappedDesc() { }
	// RVA: 0x2d583a4 VA: 0x75953703a4
	private Void _LoadData(Int32 level, Int32 exp, Int32 favorPoint, Int32 potentialRank, EvolvePhase evolvePhase, String skinId, Int32 equipLevel, Int32 skillLevel, String hostCharId, String tokenId, String hostFocusSkillId, String hostSelectEquipId, CharacterData tokenCharacterData) { }
	// RVA: 0x2d58b2c VA: 0x7595370b2c
	private String _GetTokenAvatarId(String skinId, String tokenId) { }
	// RVA: 0x2d58da8 VA: 0x7595370da8
	private List`1 _GetTokenTalentModelList(EvolvePhase evolvePhase, Int32 level, Int32 potentialRank, String equipId, Int32 equipLevel) { }
	// RVA: 0x2d590d0 VA: 0x75953710d0
	private Void _AddTokenShownTalent(TalentData talentData, List`1 retList) { }
	// RVA: 0x2d58080 VA: 0x7595370080
	private static Boolean _CheckLoadTokenDataValid(String hostCharId, String hostTmplId, String tokenId, out CharacterData outTokenCharData) { }
	// RVA: 0x2d58268 VA: 0x7595370268
	private Void .ctor() { }
}
```