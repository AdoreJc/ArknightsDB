# VecBreakSquadGroupViewModel

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `InputParams m_cachedInput`

- `String m_stageId`

- `VecBreakSquadType m_squadType`

- `Boolean m_canAssist`

- `Boolean m_isInputValid`

- `String m_squadId`

- `ExternalRuneChecker m_externalRuneChecker`


## Properties

- `String stageId`

- `VecBreakSquadType squadType`

- `Boolean canAssist`

- `SquadStartButtonTypeEnum startButtonMode`

- `ExternalRuneChecker externalRuneChecker`


## Methods

- `String get_stageId()`

- `VecBreakSquadType get_squadType()`

- `Boolean get_canAssist()`

- `SquadStartButtonTypeEnum get_startButtonMode()`

- `ExternalRuneChecker get_externalRuneChecker()`

- `Void LoadData(InputParams)`

- `SquadMaxNumInfo GetSquadMaxRawNumInfo()`

- `Void SaveAllSquadDataToLocalCache()`

- `Void UpdateMemberStatus()`

- `Boolean _CheckIfInputValid(InputParams)`

- `SquadViewModel _LoadSquadViewModel(InputParams)`

- `SquadViewModel _LoadOffenseSquad(String, Int32)`

- `SquadViewModel _LoadDefenseSquad(String, String, Int32)`

- `Void _FillSquadMembersByLocalCache(List`1, Int32, ref)`

- `Void _FillSquadMembersByPlayerData(Int32, ref)`

- `Void _KickOutDefendCharsFromSquad(SquadViewModel, List`1)`

- `Void _LoadDataFromStage(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakSquadGroupViewModel : SquadGroupViewModel
{
	private InputParams m_cachedInput; // 0x40
	private String m_stageId; // 0x88
	private VecBreakSquadType m_squadType; // 0x90
	private Boolean m_canAssist; // 0x94
	private Boolean m_isInputValid; // 0x95
	private String m_squadId; // 0x98
	private ExternalRuneChecker m_externalRuneChecker; // 0xa0
	private const String OFFENSE_SQUAD_ID; // 0x0
	private const String DEFENSE_SQUAD_ID; // 0x0
	private const Int32 VEC_BREAK_SQUADS_SIZE; // 0x0
	private const Int32 FIRST_SQUAD_FROM_TROOP_INDEX; // 0x0
	private static DelegateBridge __Hotfix0_get_stageId; // 0x0
	private static DelegateBridge __Hotfix0_get_squadType; // 0x8
	private static DelegateBridge __Hotfix0_get_canAssist; // 0x10
	private static DelegateBridge __Hotfix0_get_startButtonMode; // 0x18
	private static DelegateBridge __Hotfix0_get_externalRuneChecker; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_GetSquadMaxRawNumInfo; // 0x30
	private static DelegateBridge __Hotfix0_SaveAllSquadDataToLocalCache; // 0x38
	private static DelegateBridge __Hotfix0_UpdateMemberStatus; // 0x40
	private static DelegateBridge __Hotfix0_GetDefendCharsWithExcludeStageId; // 0x48
	private static DelegateBridge __Hotfix0__CheckIfInputValid; // 0x50
	private static DelegateBridge __Hotfix0__LoadSquadViewModel; // 0x58
	private static DelegateBridge __Hotfix0__LoadOffenseSquad; // 0x60
	private static DelegateBridge __Hotfix0__LoadDefenseSquad; // 0x68
	private static DelegateBridge __Hotfix0__FillSquadMembersByLocalCache; // 0x70
	private static DelegateBridge __Hotfix0__FillSquadMembersByPlayerData; // 0x78
	private static DelegateBridge __Hotfix0__GetDefendCharsWithExcludeStageId; // 0x80
	private static DelegateBridge __Hotfix0__KickOutDefendCharsFromSquad; // 0x88
	private static DelegateBridge __Hotfix0__MigrateSkillIfTmplChanged; // 0x90
	private static DelegateBridge __Hotfix0__MigrateEquipIfTmplChanged; // 0x98
	private static DelegateBridge __Hotfix0__LoadDataFromStage; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public String stageId { get; }
	public VecBreakSquadType squadType { get; }
	public Boolean canAssist { get; }
	public SquadStartButtonTypeEnum startButtonMode { get; }
	public ExternalRuneChecker externalRuneChecker { get; }

	// RVA: 0x22d79b4 VA: 0x75948ef9b4
	public String get_stageId() { }
	// RVA: 0x22d7a2c VA: 0x75948efa2c
	public VecBreakSquadType get_squadType() { }
	// RVA: 0x22d7aa4 VA: 0x75948efaa4
	public Boolean get_canAssist() { }
	// RVA: 0x22d7b24 VA: 0x75948efb24
	public SquadStartButtonTypeEnum get_startButtonMode() { }
	// RVA: 0x22d7b88 VA: 0x75948efb88
	public ExternalRuneChecker get_externalRuneChecker() { }
	// RVA: 0x22d7bf0 VA: 0x75948efbf0
	public Void LoadData(InputParams inputParams) { }
	// RVA: 0x22d8018 VA: 0x75948f0018
	public SquadMaxNumInfo GetSquadMaxRawNumInfo() { }
	// RVA: 0x22d80ec VA: 0x75948f00ec
	public Void SaveAllSquadDataToLocalCache() { }
	// RVA: 0x22d853c VA: 0x75948f053c
	public Void UpdateMemberStatus() { }
	// RVA: 0x22d88c8 VA: 0x75948f08c8
	public List`1 GetDefendCharsWithExcludeStageId(String excludeStageId) { }
	// RVA: 0x22d7da4 VA: 0x75948efda4
	private Boolean _CheckIfInputValid(InputParams inputParams) { }
	// RVA: 0x22d7e78 VA: 0x75948efe78
	private SquadViewModel _LoadSquadViewModel(InputParams inputParams) { }
	// RVA: 0x22d8bd4 VA: 0x75948f0bd4
	private SquadViewModel _LoadOffenseSquad(String actId, Int32 squadSlotMax) { }
	// RVA: 0x22d8ddc VA: 0x75948f0ddc
	private SquadViewModel _LoadDefenseSquad(String actId, String stageId, Int32 squadSlotMax) { }
	// RVA: 0x22d90c8 VA: 0x75948f10c8
	private Void _FillSquadMembersByLocalCache(List`1 cachedSquad, Int32 squadSlotMax, ref SquadItemStruct[] members) { }
	// RVA: 0x22d937c VA: 0x75948f137c
	private Void _FillSquadMembersByPlayerData(Int32 squadIndex, ref SquadItemStruct[] members) { }
	// RVA: 0x22d8968 VA: 0x75948f0968
	private List`1 _GetDefendCharsWithExcludeStageId(String actId, String excludeStageId) { }
	// RVA: 0x22d9698 VA: 0x75948f1698
	private Void _KickOutDefendCharsFromSquad(SquadViewModel squadViewModel, List`1 defendCharInfos) { }
	// RVA: 0x22d98d8 VA: 0x75948f18d8
	private static String _MigrateSkillIfTmplChanged(CharacterCardViewModel curCard, SquadSlotCache savedSlot) { }
	// RVA: 0x22d9ae4 VA: 0x75948f1ae4
	private static String _MigrateEquipIfTmplChanged(CharacterCardViewModel curCard, SquadSlotCache savedSlot) { }
	// RVA: 0x22d7f5c VA: 0x75948eff5c
	private Void _LoadDataFromStage(String stageId) { }
	// RVA: 0x22d9e30 VA: 0x75948f1e30
	public Void .ctor() { }
}
```