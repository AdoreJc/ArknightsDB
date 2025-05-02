# CommonSquadGroupViewModel

**Namespace:** `Torappu.UI`


## Fields

- `InputParams m_cachedInput`

- `String m_stageId`

- `Boolean m_canAssist`

- `Boolean m_isInputValid`

- `String m_squadId`

- `ExternalRuneChecker m_externalRuneChecker`

- `ICommonSquadPlugin m_squadPlugin`


## Properties

- `String stageId`

- `Boolean canAssist`

- `SquadStartButtonTypeEnum startButtonMode`

- `ExternalRuneChecker externalRuneChecker`


## Methods

- `String get_stageId()`

- `Boolean get_canAssist()`

- `SquadStartButtonTypeEnum get_startButtonMode()`

- `ExternalRuneChecker get_externalRuneChecker()`

- `Void LoadData(InputParams, ICommonSquadPlugin)`

- `SquadMaxNumInfo GetSquadMaxRawNumInfo()`

- `Void SaveAllSquadDataToLocalCache()`

- `Void UpdateMemberStatus()`

- `Boolean _CheckIfInputValid(InputParams)`

- `SquadViewModel _LoadSquadViewModel(InputParams)`

- `SquadViewModel _LoadSquad(String, Int32)`

- `Void _FillSquadMembersByLocalCache(List`1, Int32, ref)`

- `Void _FillSquadMembersByPlayerData(Int32, ref)`

- `Void _LoadDataFromStage(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CommonSquadGroupViewModel : SquadGroupViewModel
{
	private InputParams m_cachedInput; // 0x40
	private String m_stageId; // 0xa8
	private Boolean m_canAssist; // 0xb0
	private Boolean m_isInputValid; // 0xb1
	private String m_squadId; // 0xb8
	private ExternalRuneChecker m_externalRuneChecker; // 0xc0
	private ICommonSquadPlugin m_squadPlugin; // 0xc8
	private const Int32 FIRST_SQUAD_FROM_TROOP_INDEX; // 0x0
	private static DelegateBridge __Hotfix0_get_stageId; // 0x0
	private static DelegateBridge __Hotfix0_get_canAssist; // 0x8
	private static DelegateBridge __Hotfix0_get_startButtonMode; // 0x10
	private static DelegateBridge __Hotfix0_get_externalRuneChecker; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_GetSquadMaxRawNumInfo; // 0x28
	private static DelegateBridge __Hotfix0_SaveAllSquadDataToLocalCache; // 0x30
	private static DelegateBridge __Hotfix0_UpdateMemberStatus; // 0x38
	private static DelegateBridge __Hotfix0__CheckIfInputValid; // 0x40
	private static DelegateBridge __Hotfix0__LoadSquadViewModel; // 0x48
	private static DelegateBridge __Hotfix0__LoadSquad; // 0x50
	private static DelegateBridge __Hotfix0__FillSquadMembersByLocalCache; // 0x58
	private static DelegateBridge __Hotfix0__FillSquadMembersByPlayerData; // 0x60
	private static DelegateBridge __Hotfix0__MigrateSkillIfTmplChanged; // 0x68
	private static DelegateBridge __Hotfix0__MigrateEquipIfTmplChanged; // 0x70
	private static DelegateBridge __Hotfix0__LoadDataFromStage; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public String stageId { get; }
	public Boolean canAssist { get; }
	public SquadStartButtonTypeEnum startButtonMode { get; }
	public ExternalRuneChecker externalRuneChecker { get; }

	// RVA: 0x2140308 VA: 0x7594758308
	public String get_stageId() { }
	// RVA: 0x2140380 VA: 0x7594758380
	public Boolean get_canAssist() { }
	// RVA: 0x2140400 VA: 0x7594758400
	public SquadStartButtonTypeEnum get_startButtonMode() { }
	// RVA: 0x2140464 VA: 0x7594758464
	public ExternalRuneChecker get_externalRuneChecker() { }
	// RVA: 0x21404cc VA: 0x75947584cc
	public Void LoadData(InputParams inputParams, ICommonSquadPlugin squadPlugin) { }
	// RVA: 0x21408cc VA: 0x75947588cc
	public SquadMaxNumInfo GetSquadMaxRawNumInfo() { }
	// RVA: 0x21409b0 VA: 0x75947589b0
	public Void SaveAllSquadDataToLocalCache() { }
	// RVA: 0x2140cf0 VA: 0x7594758cf0
	public Void UpdateMemberStatus() { }
	// RVA: 0x214069c VA: 0x759475869c
	private Boolean _CheckIfInputValid(InputParams inputParams) { }
	// RVA: 0x2140768 VA: 0x7594758768
	private SquadViewModel _LoadSquadViewModel(InputParams inputParams) { }
	// RVA: 0x214107c VA: 0x759475907c
	private SquadViewModel _LoadSquad(String actId, Int32 squadSlotMax) { }
	// RVA: 0x21415a0 VA: 0x75947595a0
	private Void _FillSquadMembersByLocalCache(List`1 cachedSquad, Int32 squadSlotMax, ref SquadItemStruct[] members) { }
	// RVA: 0x2141284 VA: 0x7594759284
	private Void _FillSquadMembersByPlayerData(Int32 squadIndex, ref SquadItemStruct[] members) { }
	// RVA: 0x2141854 VA: 0x7594759854
	private static String _MigrateSkillIfTmplChanged(CharacterCardViewModel curCard, SquadSlotCache savedSlot) { }
	// RVA: 0x2141a60 VA: 0x7594759a60
	private static String _MigrateEquipIfTmplChanged(CharacterCardViewModel curCard, SquadSlotCache savedSlot) { }
	// RVA: 0x2140810 VA: 0x7594758810
	private Void _LoadDataFromStage(String stageId) { }
	// RVA: 0x2141c6c VA: 0x7594759c6c
	public Void .ctor() { }
}
```