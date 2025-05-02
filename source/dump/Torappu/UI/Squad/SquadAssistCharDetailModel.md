# SquadAssistCharDetailModel

**Namespace:** `Torappu.UI.Squad`


## Fields

- `Int32 friendLevel`

- `AvatarInfo friendAvatarInfo`

- `String friendName`

- `String friendNumber`

- `String friendAliasName`

- `Boolean isFriendOnline`

- `String friendLastOnlineTimeStr`

- `Boolean canAddFriend`

- `Boolean isFriend`

- `String nameCardSkinId`

- `Int32 nameCardSkinTmpl`

- `CharUISkinStruct charIllust`

- `EvolvePhase charEvolvePhase`

- `Int32 charLevel`

- `Int32 charPotential`

- `RarityRank charRarity`

- `ProfessionCategory charProfession`

- `String charName`

- `Boolean isSkillLimited`

- `Int32 selectedSkillIndex`

- `String selectedEquipId`

- `String friendUid`

- `Boolean detailViewShow`

- `Int32 enterSeqNum`

- `Single equipScrollNormalizedPos`

- `Boolean m_usePlayerSelection`

- `SharedCharData m_cachedSelectChar`

- `SharedCharData m_cachedOriginChar`

- `String m_friendServerName`

- `DateTime m_lastOnlineTime`

- `ModifiedSharedCharData m_cachedModifiedSharedCharData`

- `Boolean m_isCharShowMultiSlot`


## Methods

- `Void LoadData(Input)`

- `Void _LoadSkill(ref)`

- `Void _LoadEquip(ListDict`2)`

- `Void SelectSkill(Int32)`

- `Void SelectEquip(String)`

- `Void SetDetailViewShow(Boolean)`

- `SquadFriendData ConvertToSquadFriendData()`

- `CharacterShowViewModel GetCharShowViewModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadAssistCharDetailModel : IHotfixable
{
	private const Int32 SKILL_SLOT_MIN; // 0x0
	private const Int32 EQUIP_SLOT_MIN; // 0x0
	public Int32 friendLevel; // 0x10
	public AvatarInfo friendAvatarInfo; // 0x18
	public String friendName; // 0x20
	public String friendNumber; // 0x28
	public String friendAliasName; // 0x30
	public Boolean isFriendOnline; // 0x38
	public String friendLastOnlineTimeStr; // 0x40
	public List`1 friendAssistChars; // 0x48
	public Boolean canAddFriend; // 0x50
	public Boolean isFriend; // 0x51
	public String nameCardSkinId; // 0x58
	public Int32 nameCardSkinTmpl; // 0x60
	public CharUISkinStruct charIllust; // 0x68
	public EvolvePhase charEvolvePhase; // 0x78
	public Int32 charLevel; // 0x7c
	public Int32 charPotential; // 0x80
	public RarityRank charRarity; // 0x84
	public ProfessionCategory charProfession; // 0x88
	public String charName; // 0x90
	public Boolean isSkillLimited; // 0x98
	public List`1 singleSkillLimitList; // 0xa0
	public List`1 charSkills; // 0xa8
	public ListDict`2 charEquips; // 0xb0
	public Int32 selectedSkillIndex; // 0xb8
	public String selectedEquipId; // 0xc0
	public String friendUid; // 0xc8
	public Boolean detailViewShow; // 0xd0
	public Int32 enterSeqNum; // 0xd4
	public Single equipScrollNormalizedPos; // 0xd8
	private Boolean m_usePlayerSelection; // 0xdc
	private SharedCharData m_cachedSelectChar; // 0xe0
	private SharedCharData m_cachedOriginChar; // 0xe8
	private String m_friendServerName; // 0xf0
	private DateTime m_lastOnlineTime; // 0xf8
	private ModifiedSharedCharData m_cachedModifiedSharedCharData; // 0x100
	private Boolean m_isCharShowMultiSlot; // 0x120
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadSkill; // 0x8
	private static DelegateBridge __Hotfix0__LoadEquip; // 0x10
	private static DelegateBridge __Hotfix0_SelectSkill; // 0x18
	private static DelegateBridge __Hotfix0_SelectEquip; // 0x20
	private static DelegateBridge __Hotfix0_SetDetailViewShow; // 0x28
	private static DelegateBridge __Hotfix0_ConvertToSquadFriendData; // 0x30
	private static DelegateBridge __Hotfix0_GetCharShowViewModel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2391834 VA: 0x75949a9834
	public Void LoadData(Input input) { }
	// RVA: 0x2391d4c VA: 0x75949a9d4c
	private Void _LoadSkill(ref ModifiedSharedCharData modifiedData) { }
	// RVA: 0x239204c VA: 0x75949aa04c
	private Void _LoadEquip(ListDict`2 equips) { }
	// RVA: 0x23922e4 VA: 0x75949aa2e4
	public Void SelectSkill(Int32 index) { }
	// RVA: 0x23923ac VA: 0x75949aa3ac
	public Void SelectEquip(String equipId) { }
	// RVA: 0x2392454 VA: 0x75949aa454
	public Void SetDetailViewShow(Boolean show) { }
	// RVA: 0x23924d4 VA: 0x75949aa4d4
	public SquadFriendData ConvertToSquadFriendData() { }
	// RVA: 0x2392644 VA: 0x75949aa644
	public CharacterShowViewModel GetCharShowViewModel() { }
	// RVA: 0x23926f4 VA: 0x75949aa6f4
	public Void .ctor() { }
}
```