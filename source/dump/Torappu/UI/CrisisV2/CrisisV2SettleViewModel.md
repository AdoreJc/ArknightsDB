# CrisisV2SettleViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Boolean isValid`

- `CrisisV2SettleViewType type`

- `Boolean showLeftHp`

- `Int32 leftHp`

- `String playerName`

- `CharUISkinStruct randomIllust`

- `Boolean needPlayHardModeVoice`

- `String stageCode`

- `String stageName`

- `SquadItemStruct assistSquad`

- `SquadSkinInfo assistSkinInfo`

- `Int32 runeCountOld`

- `Int32 runeCountCurrent`

- `Int64 timestamp`

- `Boolean needShowRuneMoreTips`

- `Boolean isNewRecord`

- `Boolean isNewComplete`

- `Int32 scoreCurrent`

- `CrisisV2AppraiseType rank`

- `String seasonId`

- `Boolean isCommentEmpty`

- `String m_stageId`

- `Int32 m_voiceGrade`

- `CrisisV2StageType m_stageType`


## Methods

- `Void LoadData(Param)`

- `Void _LoadBasicInfo(Param)`

- `Boolean _LoadCommentsData(Param)`

- `Int32 _CompareComment(CrisisV2SettleCommentItemViewModel, CrisisV2SettleCommentItemViewModel)`

- `Boolean _LoadRuneData(Param)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2SettleViewModel : IHotfixable
{
	public Boolean isValid; // 0x10
	public CrisisV2SettleViewType type; // 0x14
	public Boolean showLeftHp; // 0x18
	public Int32 leftHp; // 0x1c
	public String playerName; // 0x20
	public CharUISkinStruct randomIllust; // 0x28
	public Boolean needPlayHardModeVoice; // 0x38
	public String stageCode; // 0x40
	public String stageName; // 0x48
	public SquadItemStruct[] squadList; // 0x50
	public SquadItemStruct assistSquad; // 0x58
	public List`1 squadSkinInfoList; // 0x68
	public SquadSkinInfo assistSkinInfo; // 0x70
	public List`1 scoreRecordList; // 0x80
	public List`1 scoreCurrentList; // 0x88
	public List`1 scoreMaxList; // 0x90
	public List`1 scoreDescList; // 0x98
	public Int32 runeCountOld; // 0xa0
	public Int32 runeCountCurrent; // 0xa4
	public List`1 rewardItems; // 0xa8
	public Int64 timestamp; // 0xb0
	public List`1 runeModelList; // 0xb8
	public Boolean needShowRuneMoreTips; // 0xc0
	public Boolean isNewRecord; // 0xc1
	public Boolean isNewComplete; // 0xc2
	public Int32 scoreCurrent; // 0xc4
	public CrisisV2AppraiseType rank; // 0xc8
	public String seasonId; // 0xd0
	public Boolean isCommentEmpty; // 0xd8
	public List`1 leftCommentModelList; // 0xe0
	public List`1 rightCommentModelList; // 0xe8
	private String m_stageId; // 0xf0
	private ListDict`2 m_scoreToAppraiseDataMap; // 0xf8
	private Int32 m_voiceGrade; // 0x100
	private CrisisV2StageType m_stageType; // 0x104
	private static readonly Int32 RUNE_SLOT_SHOW_COUNT; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__LoadBasicInfo; // 0x10
	private static DelegateBridge __Hotfix0__LoadCommentsData; // 0x18
	private static DelegateBridge __Hotfix0__CompareComment; // 0x20
	private static DelegateBridge __Hotfix0__LoadRuneData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2bd4490 VA: 0x75951ec490
	public Void LoadData(Param input) { }
	// RVA: 0x2bd45a4 VA: 0x75951ec5a4
	private Void _LoadBasicInfo(Param input) { }
	// RVA: 0x2bd480c VA: 0x75951ec80c
	private Boolean _LoadCommentsData(Param input) { }
	// RVA: 0x2bd4dd0 VA: 0x75951ecdd0
	private Int32 _CompareComment(CrisisV2SettleCommentItemViewModel commnet1, CrisisV2SettleCommentItemViewModel commnet2) { }
	// RVA: 0x2bd4ad8 VA: 0x75951ecad8
	private Boolean _LoadRuneData(Param input) { }
	// RVA: 0x2bd243c VA: 0x75951ea43c
	public Void .ctor() { }
	// RVA: 0x2bd4f54 VA: 0x75951ecf54
	private static Void .cctor() { }
}
```