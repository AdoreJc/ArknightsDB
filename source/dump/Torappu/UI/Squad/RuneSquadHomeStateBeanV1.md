# RuneSquadHomeStateBeanV1

**Namespace:** `Torappu.UI.Squad`


## Fields

- `SquadGroupViewProperty squadGroupProp`

- `FriendAssistDataStruct friendDataCache`

- `ProfessionCategory assistProfession`

- `ExternalRuneChecker m_runeChecker`

- `SquadMaxNumInfo m_squadMaxNumInfo`

- `String m_runeStageId`

- `String m_squadSaveKey`


## Properties

- `String stageId`


## Methods

- `String get_stageId()`

- `Int32 MaxNum4CharSelect()`

- `Void LoadData(Params)`

- `Void LoadData(Params)`

- `Void LoadDataInternal(String, String, List`1, String)`

- `Void UpdateData()`

- `Void RestrictSquadMembers()`

- `Boolean CheckIfCharValid(CharQuery)`

- `Void _InitCurSquad(String, List`1)`

- `Boolean IsCurrentSquadEmpty()`

- `Boolean CheckIfCharSelectable(CharQuery)`

- `SquadModel ParseBattleStartRequestSquad()`

- `Void ApplyToFriendAssistBean(SquadFriendAssistStateBean)`

- `Void ReceiveFromFriendAssistBean(SquadFriendAssistStateBean)`

- `Void SaveLocalCache()`

- `Void _SaveSquadToCache()`

- `Int32 _GetCurSquadValidMemberNum()`

- `Int32 _GetSquadAssistNum()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class RuneSquadHomeStateBeanV1 : IStateBean, IHotfixable
{
	public SquadGroupViewProperty squadGroupProp; // 0x10
	public FriendAssistDataStruct friendDataCache; // 0x18
	public ProfessionCategory assistProfession; // 0x28
	private ExternalRuneChecker m_runeChecker; // 0x30
	private SquadMaxNumInfo m_squadMaxNumInfo; // 0x38
	private String m_runeStageId; // 0x40
	private String m_squadSaveKey; // 0x48
	private List`1 m_selectedRunes; // 0x50
	private static DelegateBridge __Hotfix0_get_stageId; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedRunes; // 0x8
	private static DelegateBridge __Hotfix0_MaxNum4CharSelect; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix1_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_LoadDataInternal; // 0x28
	private static DelegateBridge __Hotfix0_UpdateData; // 0x30
	private static DelegateBridge __Hotfix0_RestrictSquadMembers; // 0x38
	private static DelegateBridge __Hotfix0_CheckIfCharValid; // 0x40
	private static DelegateBridge __Hotfix0__InitCurSquad; // 0x48
	private static DelegateBridge __Hotfix0_IsCurrentSquadEmpty; // 0x50
	private static DelegateBridge __Hotfix0_CheckIfCharSelectable; // 0x58
	private static DelegateBridge __Hotfix0_CreateSquadToStartBattle; // 0x60
	private static DelegateBridge __Hotfix0_ParseBattleStartRequestSquad; // 0x68
	private static DelegateBridge __Hotfix0__TryLoadSquadForRune; // 0x70
	private static DelegateBridge __Hotfix0__MigrateSkillIfTmplChanged; // 0x78
	private static DelegateBridge __Hotfix0__MigrateEquipIfTmplChanged; // 0x80
	private static DelegateBridge __Hotfix0__LoadFirstPlayerSquad; // 0x88
	private static DelegateBridge __Hotfix0_ApplyToFriendAssistBean; // 0x90
	private static DelegateBridge __Hotfix0_ReceiveFromFriendAssistBean; // 0x98
	private static DelegateBridge __Hotfix0_SaveLocalCache; // 0xa0
	private static DelegateBridge __Hotfix0__SaveSquadToCache; // 0xa8
	private static DelegateBridge __Hotfix0__GetCurSquadValidMemberNum; // 0xb0
	private static DelegateBridge __Hotfix0__GetSquadAssistNum; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public String stageId { get; }
	public List`1 selectedRunes { get; }

	// RVA: 0x238dcc0 VA: 0x75949a5cc0
	public String get_stageId() { }
	// RVA: 0x238dd28 VA: 0x75949a5d28
	public List`1 get_selectedRunes() { }
	// RVA: 0x238dd90 VA: 0x75949a5d90
	public Int32 MaxNum4CharSelect() { }
	// RVA: 0x238ded8 VA: 0x75949a5ed8
	public Void LoadData(Params pageParams) { }
	// RVA: 0x238e17c VA: 0x75949a617c
	public Void LoadData(Params pageParams) { }
	// RVA: 0x238df84 VA: 0x75949a5f84
	protected Void LoadDataInternal(String runeStageId, String levelId, List`1 selectedRunes, String overrideSquadSaveKey) { }
	// RVA: 0x238e618 VA: 0x75949a6618
	public Void UpdateData() { }
	// RVA: 0x238e51c VA: 0x75949a651c
	public Void RestrictSquadMembers() { }
	// RVA: 0x238eab0 VA: 0x75949a6ab0
	public Boolean CheckIfCharValid(CharQuery charQuery) { }
	// RVA: 0x238e224 VA: 0x75949a6224
	private Void _InitCurSquad(String squadSaveKey, List`1 selectedRunes) { }
	// RVA: 0x238f2b4 VA: 0x75949a72b4
	public Boolean IsCurrentSquadEmpty() { }
	// RVA: 0x238f4bc VA: 0x75949a74bc
	public Boolean CheckIfCharSelectable(CharQuery charQuery) { }
	// RVA: 0x238f568 VA: 0x75949a7568
	public SquadItemStruct[] CreateSquadToStartBattle() { }
	// RVA: 0x238f744 VA: 0x75949a7744
	public SquadModel ParseBattleStartRequestSquad() { }
	// RVA: 0x238ecfc VA: 0x75949a6cfc
	private static Boolean _TryLoadSquadForRune(String squadSaveKey, SquadItemStruct[] members) { }
	// RVA: 0x238faac VA: 0x75949a7aac
	private static String _MigrateSkillIfTmplChanged(CharacterCardViewModel curCard, SquadSlotCache savedSlot) { }
	// RVA: 0x238fd48 VA: 0x75949a7d48
	private static String _MigrateEquipIfTmplChanged(CharacterCardViewModel curCard, SquadSlotCache savedSlot) { }
	// RVA: 0x238f028 VA: 0x75949a7028
	private static Void _LoadFirstPlayerSquad(SquadItemStruct[] members) { }
	// RVA: 0x2390280 VA: 0x75949a8280
	public Void ApplyToFriendAssistBean(SquadFriendAssistStateBean assistBean) { }
	// RVA: 0x239046c VA: 0x75949a846c
	public Void ReceiveFromFriendAssistBean(SquadFriendAssistStateBean assistBean) { }
	// RVA: 0x2390570 VA: 0x75949a8570
	public Void SaveLocalCache() { }
	// RVA: 0x23905d8 VA: 0x75949a85d8
	private Void _SaveSquadToCache() { }
	// RVA: 0x2390e30 VA: 0x75949a8e30
	private Int32 _GetCurSquadValidMemberNum() { }
	// RVA: 0x238de48 VA: 0x75949a5e48
	private Int32 _GetSquadAssistNum() { }
	// RVA: 0x238ba14 VA: 0x75949a3a14
	public Void .ctor() { }
}
```