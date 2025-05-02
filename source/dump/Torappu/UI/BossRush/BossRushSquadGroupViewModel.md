# BossRushSquadGroupViewModel

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `ActivityBossRushData m_cachedActData`

- `String selectingRelicId`

- `String curSquadTeamId`

- `BossRushStageType m_stageType`

- `Boolean m_isNormalStage`


## Properties

- `BossRushStageType stageType`

- `Boolean isNormalStage`


## Methods

- `BossRushStageType get_stageType()`

- `Boolean get_isNormalStage()`

- `Void LoadDataFromTeams(String, String, List`1)`

- `Boolean IsTeamMember(String, String)`

- `Void UpdateCustomMemberStatus()`

- `Boolean IsFreeTeam(String)`

- `Boolean IsTeamSquadHasTeamBuff(String)`

- `Void SetSquadIndexByTeamId(String)`

- `Void _LoadNormalSquad(String, SquadItemStruct[])`

- `Void _LoadTeamSquad(String, String, List`1, SquadItemStruct[])`

- `Void _TryLoadFixPartFromCache(String, String, List`1, SquadItemStruct[])`

- `Void _TryLoadCustomSquadFromCache(String, String, Int32, SquadItemStruct[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushSquadGroupViewModel : SquadGroupViewModel
{
	private ActivityBossRushData m_cachedActData; // 0x40
	private const Int32 NORMAL_SQUAD_COUNT; // 0x0
	public const String NORMAL_SQUAD_ID; // 0x0
	public String selectingRelicId; // 0x48
	public String curSquadTeamId; // 0x50
	public Dictionary`2 teamDataDic; // 0x58
	public Dictionary`2 teamIndexDic; // 0x60
	public Dictionary`2 teamCardViewDic; // 0x68
	private BossRushStageType m_stageType; // 0x70
	private Boolean m_isNormalStage; // 0x74
	private static DelegateBridge __Hotfix0_get_stageType; // 0x0
	private static DelegateBridge __Hotfix0_get_isNormalStage; // 0x8
	private static DelegateBridge __Hotfix0_LoadDataFromTeams; // 0x10
	private static DelegateBridge __Hotfix0_IsTeamMember; // 0x18
	private static DelegateBridge __Hotfix0_UpdateCustomMemberStatus; // 0x20
	private static DelegateBridge __Hotfix0_IsFreeTeam; // 0x28
	private static DelegateBridge __Hotfix0_IsTeamSquadHasTeamBuff; // 0x30
	private static DelegateBridge __Hotfix0_SetSquadIndexByTeamId; // 0x38
	private static DelegateBridge __Hotfix0__GetTeamFixedMemberList; // 0x40
	private static DelegateBridge __Hotfix0__LoadNormalSquad; // 0x48
	private static DelegateBridge __Hotfix0__LoadTeamSquad; // 0x50
	private static DelegateBridge __Hotfix0__TryLoadFixPartFromCache; // 0x58
	private static DelegateBridge __Hotfix0__TryLoadCustomSquadFromCache; // 0x60
	private static DelegateBridge __Hotfix0__MigrateSkillIfTmplChanged; // 0x68
	private static DelegateBridge __Hotfix0__MigrateEquipIfTmplChanged; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public BossRushStageType stageType { get; }
	public Boolean isNormalStage { get; }

	// RVA: 0x2e631e8 VA: 0x759547b1e8
	public BossRushStageType get_stageType() { }
	// RVA: 0x2e6228c VA: 0x759547a28c
	public Boolean get_isNormalStage() { }
	// RVA: 0x2e63250 VA: 0x759547b250
	public Void LoadDataFromTeams(String actId, String stageId, List`1 predefinedSquad) { }
	// RVA: 0x2e62ae8 VA: 0x759547aae8
	public Boolean IsTeamMember(String teamId, String charId) { }
	// RVA: 0x2e63e6c VA: 0x759547be6c
	public Void UpdateCustomMemberStatus() { }
	// RVA: 0x2e62f84 VA: 0x759547af84
	public Boolean IsFreeTeam(String teamId) { }
	// RVA: 0x2e642cc VA: 0x759547c2cc
	public Boolean IsTeamSquadHasTeamBuff(String teamId) { }
	// RVA: 0x2e643d4 VA: 0x759547c3d4
	public Void SetSquadIndexByTeamId(String selectedTeamId) { }
	// RVA: 0x2e63ac4 VA: 0x759547bac4
	private List`1 _GetTeamFixedMemberList(Dictionary`2 predefinedCharDict, BossRushTeamData teamData) { }
	// RVA: 0x2e63a1c VA: 0x759547ba1c
	private Void _LoadNormalSquad(String actId, SquadItemStruct[] squadItemList) { }
	// RVA: 0x2e63d80 VA: 0x759547bd80
	private Void _LoadTeamSquad(String actId, String teamId, List`1 fixTeamMember, SquadItemStruct[] squadItemList) { }
	// RVA: 0x2e648e8 VA: 0x759547c8e8
	private Void _TryLoadFixPartFromCache(String actId, String teamId, List`1 fixTeamMember, SquadItemStruct[] squadItemList) { }
	// RVA: 0x2e645a4 VA: 0x759547c5a4
	private Void _TryLoadCustomSquadFromCache(String actId, String squadId, Int32 fixTeamCount, SquadItemStruct[] squadItemList) { }
	// RVA: 0x2e64b54 VA: 0x759547cb54
	private static String _MigrateSkillIfTmplChanged(CharacterCardViewModel curCard, SquadSlotCache savedSlot) { }
	// RVA: 0x2e64d60 VA: 0x759547cd60
	private static String _MigrateEquipIfTmplChanged(CharacterCardViewModel curCard, SquadSlotCache savedSlot) { }
	// RVA: 0x2e64f6c VA: 0x759547cf6c
	public Void .ctor() { }
}
```