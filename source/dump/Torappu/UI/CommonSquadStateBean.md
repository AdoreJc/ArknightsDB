# CommonSquadStateBean

**Namespace:** `Torappu.UI`


## Fields

- `SquadGroupViewProperty m_squadProperty`

- `ProfessionCategory m_assistProfession`

- `FriendAssistDataStruct m_friendDataCache`

- `ICommonSquadPlugin m_squadPlugin`


## Properties

- `SquadGroupViewProperty squadGroupProp`

- `ProfessionCategory assistProfession`

- `FriendAssistDataStruct friendDataCache`

- `ICommonSquadPlugin squadPlugin`


## Methods

- `SquadGroupViewProperty get_squadGroupProp()`

- `ProfessionCategory get_assistProfession()`

- `Void set_assistProfession(ProfessionCategory)`

- `FriendAssistDataStruct get_friendDataCache()`

- `Void set_friendDataCache(FriendAssistDataStruct)`

- `ICommonSquadPlugin get_squadPlugin()`

- `CharacterCardViewModel PickRandomCharacter()`

- `Void LoadData(InputParams)`

- `Void RefreshData()`

- `Void SaveAllSquadDataToLocalCache()`

- `SquadViewModel TryGetSquadViewModel()`

- `Void ClearAssistCharIfConflict(IList`1)`

- `Void ApplyToFriendAssistBean(SquadFriendAssistStateBean)`

- `Void ReceiveFromFriendAssistBean(SquadFriendAssistStateBean)`

- `Boolean CheckIfCharRuneValid(CharQuery)`

- `Boolean CheckIfFriendLegal()`

- `Void TryRestrictSquadMembers()`

- `Int32 MaxNum4CharSelect()`

- `Boolean IsCurrentSquadEmpty()`

- `Void _LoadDataInternal(InputParams)`

- `Void _InitViewModel(InputParams)`

- `Void _TryRefreshData()`

- `Int32 _GetCurSquadValidMemberNum()`

- `SquadMaxNumInfo _GetSquadMaxRawNumInfo()`

- `Int32 _GetSquadAssistNum()`

- `Int32 _GetSquadMaxCharCount()`

- `ExternalRuneChecker _GetExternalRuneChecker()`

- `SquadMaxNumInfo _GetSquadMaxLimitNumInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CommonSquadStateBean : IStateBean, IHotfixable
{
	private SquadGroupViewProperty m_squadProperty; // 0x10
	private ProfessionCategory m_assistProfession; // 0x18
	private FriendAssistDataStruct m_friendDataCache; // 0x20
	private ICommonSquadPlugin m_squadPlugin; // 0x30
	private static DelegateBridge __Hotfix0_get_squadGroupProp; // 0x0
	private static DelegateBridge __Hotfix0_get_assistProfession; // 0x8
	private static DelegateBridge __Hotfix0_set_assistProfession; // 0x10
	private static DelegateBridge __Hotfix0_get_friendDataCache; // 0x18
	private static DelegateBridge __Hotfix0_set_friendDataCache; // 0x20
	private static DelegateBridge __Hotfix0_get_squadPlugin; // 0x28
	private static DelegateBridge __Hotfix0_PickRandomCharacter; // 0x30
	private static DelegateBridge __Hotfix0_ParseBattleSquadLocal; // 0x38
	private static DelegateBridge __Hotfix0_ParseBattleStartRequestSquad; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge __Hotfix0_RefreshData; // 0x50
	private static DelegateBridge __Hotfix0_SaveAllSquadDataToLocalCache; // 0x58
	private static DelegateBridge __Hotfix0_TryGetSquadViewModel; // 0x60
	private static DelegateBridge __Hotfix0_ClearAssistCharIfConflict; // 0x68
	private static DelegateBridge __Hotfix0_ApplyToFriendAssistBean; // 0x70
	private static DelegateBridge __Hotfix0_ReceiveFromFriendAssistBean; // 0x78
	private static DelegateBridge __Hotfix0_CheckIfCharRuneValid; // 0x80
	private static DelegateBridge __Hotfix0_CheckIfFriendLegal; // 0x88
	private static DelegateBridge __Hotfix0_TryRestrictSquadMembers; // 0x90
	private static DelegateBridge __Hotfix0_MaxNum4CharSelect; // 0x98
	private static DelegateBridge __Hotfix0_IsCurrentSquadEmpty; // 0xa0
	private static DelegateBridge __Hotfix0__LoadDataInternal; // 0xa8
	private static DelegateBridge __Hotfix0__InitViewModel; // 0xb0
	private static DelegateBridge __Hotfix0__TryRefreshData; // 0xb8
	private static DelegateBridge __Hotfix0__GetCurSquadValidMemberNum; // 0xc0
	private static DelegateBridge __Hotfix0__GetSquadMaxRawNumInfo; // 0xc8
	private static DelegateBridge __Hotfix0__GetSquadAssistNum; // 0xd0
	private static DelegateBridge __Hotfix0__GetSquadMaxCharCount; // 0xd8
	private static DelegateBridge __Hotfix0__GetExternalRuneChecker; // 0xe0
	private static DelegateBridge __Hotfix0__GetSquadMaxLimitNumInfo; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	public SquadGroupViewProperty squadGroupProp { get; }
	public ProfessionCategory assistProfession { get; set; }
	public FriendAssistDataStruct friendDataCache { get; set; }
	public ICommonSquadPlugin squadPlugin { get; }

	// RVA: 0x2141d54 VA: 0x7594759d54
	public SquadGroupViewProperty get_squadGroupProp() { }
	// RVA: 0x2141dbc VA: 0x7594759dbc
	public ProfessionCategory get_assistProfession() { }
	// RVA: 0x2141e24 VA: 0x7594759e24
	public Void set_assistProfession(ProfessionCategory value) { }
	// RVA: 0x2141ea0 VA: 0x7594759ea0
	public FriendAssistDataStruct get_friendDataCache() { }
	// RVA: 0x21400f8 VA: 0x75947580f8
	public Void set_friendDataCache(FriendAssistDataStruct value) { }
	// RVA: 0x2141f04 VA: 0x7594759f04
	public ICommonSquadPlugin get_squadPlugin() { }
	// RVA: 0x2141f6c VA: 0x7594759f6c
	public CharacterCardViewModel PickRandomCharacter() { }
	// RVA: 0x21420b0 VA: 0x759475a0b0
	public SquadItemStruct[] ParseBattleSquadLocal() { }
	// RVA: 0x21421f4 VA: 0x759475a1f4
	public List`1 ParseBattleStartRequestSquad() { }
	// RVA: 0x2142488 VA: 0x759475a488
	public Void LoadData(InputParams inputParams) { }
	// RVA: 0x214270c VA: 0x759475a70c
	public Void RefreshData() { }
	// RVA: 0x2142870 VA: 0x759475a870
	public Void SaveAllSquadDataToLocalCache() { }
	// RVA: 0x2141ff8 VA: 0x7594759ff8
	public SquadViewModel TryGetSquadViewModel() { }
	// RVA: 0x2142948 VA: 0x759475a948
	public Void ClearAssistCharIfConflict(IList`1 squadMembers) { }
	// RVA: 0x21429f8 VA: 0x759475a9f8
	public Void ApplyToFriendAssistBean(SquadFriendAssistStateBean assistBean) { }
	// RVA: 0x2142b00 VA: 0x759475ab00
	public Void ReceiveFromFriendAssistBean(SquadFriendAssistStateBean assistBean) { }
	// RVA: 0x213fe48 VA: 0x7594757e48
	public Boolean CheckIfCharRuneValid(CharQuery charQuery) { }
	// RVA: 0x214306c VA: 0x759475b06c
	public Boolean CheckIfFriendLegal() { }
	// RVA: 0x2142c0c VA: 0x759475ac0c
	public Void TryRestrictSquadMembers() { }
	// RVA: 0x21432cc VA: 0x759475b2cc
	public Int32 MaxNum4CharSelect() { }
	// RVA: 0x2143634 VA: 0x759475b634
	public Boolean IsCurrentSquadEmpty() { }
	// RVA: 0x2142628 VA: 0x759475a628
	private Void _LoadDataInternal(InputParams inputParams) { }
	// RVA: 0x21437a8 VA: 0x759475b7a8
	private Void _InitViewModel(InputParams inputParams) { }
	// RVA: 0x2142774 VA: 0x759475a774
	private Void _TryRefreshData() { }
	// RVA: 0x214393c VA: 0x759475b93c
	private Int32 _GetCurSquadValidMemberNum() { }
	// RVA: 0x2143530 VA: 0x759475b530
	private SquadMaxNumInfo _GetSquadMaxRawNumInfo() { }
	// RVA: 0x214343c VA: 0x759475b43c
	private Int32 _GetSquadAssistNum() { }
	// RVA: 0x2143248 VA: 0x759475b248
	private Int32 _GetSquadMaxCharCount() { }
	// RVA: 0x2142f8c VA: 0x759475af8c
	private ExternalRuneChecker _GetExternalRuneChecker() { }
	// RVA: 0x21433b4 VA: 0x759475b3b4
	private SquadMaxNumInfo _GetSquadMaxLimitNumInfo() { }
	// RVA: 0x21439d4 VA: 0x759475b9d4
	public Void .ctor() { }
}
```