# VecBreakSquadStateBean

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `SquadGroupViewProperty m_squadProperty`

- `ProfessionCategory m_assistProfession`

- `FriendAssistDataStruct m_friendDataCache`


## Properties

- `SquadGroupViewProperty squadGroupProp`

- `ProfessionCategory assistProfession`

- `FriendAssistDataStruct friendDataCache`


## Methods

- `SquadGroupViewProperty get_squadGroupProp()`

- `ProfessionCategory get_assistProfession()`

- `Void set_assistProfession(ProfessionCategory)`

- `FriendAssistDataStruct get_friendDataCache()`

- `Void set_friendDataCache(FriendAssistDataStruct)`

- `CharacterCardViewModel PickRandomCharacter()`

- `Void LoadData(InputParams)`

- `Void RefreshData()`

- `Void SaveAllSquadDataToLocalCache()`

- `SquadViewModel TryGetSquadViewModel()`

- `Void ClearAssistCharIfConflict(IList`1)`

- `Void ApplyToFriendAssistBean(SquadFriendAssistStateBean)`

- `Void ReceiveFromFriendAssistBean(SquadFriendAssistStateBean)`

- `Boolean CheckIfCharRuneValid(CharQuery)`

- `Boolean CheckIfCharInDefense(String)`

- `Boolean CheckIfCharInDefenseWithModeCheck(String)`

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

- `Boolean _CheckIfCharInDefense(String, String)`

- `SquadMaxNumInfo _GetSquadMaxLimitNumInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakSquadStateBean : IStateBean, IHotfixable
{
	private SquadGroupViewProperty m_squadProperty; // 0x10
	private ProfessionCategory m_assistProfession; // 0x18
	private FriendAssistDataStruct m_friendDataCache; // 0x20
	private static DelegateBridge __Hotfix0_get_squadGroupProp; // 0x0
	private static DelegateBridge __Hotfix0_get_assistProfession; // 0x8
	private static DelegateBridge __Hotfix0_set_assistProfession; // 0x10
	private static DelegateBridge __Hotfix0_get_friendDataCache; // 0x18
	private static DelegateBridge __Hotfix0_set_friendDataCache; // 0x20
	private static DelegateBridge __Hotfix0_PickRandomCharacter; // 0x28
	private static DelegateBridge __Hotfix0_ParseBattleSquadLocal; // 0x30
	private static DelegateBridge __Hotfix0_ParseBattleStartRequestSquad; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_RefreshData; // 0x48
	private static DelegateBridge __Hotfix0_SaveAllSquadDataToLocalCache; // 0x50
	private static DelegateBridge __Hotfix0_TryGetSquadViewModel; // 0x58
	private static DelegateBridge __Hotfix0_ClearAssistCharIfConflict; // 0x60
	private static DelegateBridge __Hotfix0_ApplyToFriendAssistBean; // 0x68
	private static DelegateBridge __Hotfix0_ReceiveFromFriendAssistBean; // 0x70
	private static DelegateBridge __Hotfix0_CheckIfCharRuneValid; // 0x78
	private static DelegateBridge __Hotfix0_CheckIfCharInDefense; // 0x80
	private static DelegateBridge __Hotfix0_CheckIfCharInDefenseWithModeCheck; // 0x88
	private static DelegateBridge __Hotfix0_CheckIfFriendLegal; // 0x90
	private static DelegateBridge __Hotfix0_TryRestrictSquadMembers; // 0x98
	private static DelegateBridge __Hotfix0_MaxNum4CharSelect; // 0xa0
	private static DelegateBridge __Hotfix0_IsCurrentSquadEmpty; // 0xa8
	private static DelegateBridge __Hotfix0__LoadDataInternal; // 0xb0
	private static DelegateBridge __Hotfix0__InitViewModel; // 0xb8
	private static DelegateBridge __Hotfix0__TryRefreshData; // 0xc0
	private static DelegateBridge __Hotfix0__GetCurSquadValidMemberNum; // 0xc8
	private static DelegateBridge __Hotfix0__GetSquadMaxRawNumInfo; // 0xd0
	private static DelegateBridge __Hotfix0__GetSquadAssistNum; // 0xd8
	private static DelegateBridge __Hotfix0__GetSquadMaxCharCount; // 0xe0
	private static DelegateBridge __Hotfix0__GetExternalRuneChecker; // 0xe8
	private static DelegateBridge __Hotfix0__CheckIfCharInDefense; // 0xf0
	private static DelegateBridge __Hotfix0__GetSquadMaxLimitNumInfo; // 0xf8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x100

	public SquadGroupViewProperty squadGroupProp { get; }
	public ProfessionCategory assistProfession { get; set; }
	public FriendAssistDataStruct friendDataCache { get; set; }

	// RVA: 0x22da42c VA: 0x75948f242c
	public SquadGroupViewProperty get_squadGroupProp() { }
	// RVA: 0x22db9b0 VA: 0x75948f39b0
	public ProfessionCategory get_assistProfession() { }
	// RVA: 0x22dba18 VA: 0x75948f3a18
	public Void set_assistProfession(ProfessionCategory value) { }
	// RVA: 0x22db894 VA: 0x75948f3894
	public FriendAssistDataStruct get_friendDataCache() { }
	// RVA: 0x22df7f8 VA: 0x75948f77f8
	public Void set_friendDataCache(FriendAssistDataStruct value) { }
	// RVA: 0x22dc734 VA: 0x75948f4734
	public CharacterCardViewModel PickRandomCharacter() { }
	// RVA: 0x22dc7c0 VA: 0x75948f47c0
	public SquadItemStruct[] ParseBattleSquadLocal() { }
	// RVA: 0x22dc904 VA: 0x75948f4904
	public List`1 ParseBattleStartRequestSquad() { }
	// RVA: 0x22da384 VA: 0x75948f2384
	public Void LoadData(InputParams inputParams) { }
	// RVA: 0x22da52c VA: 0x75948f252c
	public Void RefreshData() { }
	// RVA: 0x22de9bc VA: 0x75948f69bc
	public Void SaveAllSquadDataToLocalCache() { }
	// RVA: 0x22db8f8 VA: 0x75948f38f8
	public SquadViewModel TryGetSquadViewModel() { }
	// RVA: 0x22ddea8 VA: 0x75948f5ea8
	public Void ClearAssistCharIfConflict(IList`1 squadMembers) { }
	// RVA: 0x22db5a8 VA: 0x75948f35a8
	public Void ApplyToFriendAssistBean(SquadFriendAssistStateBean assistBean) { }
	// RVA: 0x22db780 VA: 0x75948f3780
	public Void ReceiveFromFriendAssistBean(SquadFriendAssistStateBean assistBean) { }
	// RVA: 0x22df558 VA: 0x75948f7558
	public Boolean CheckIfCharRuneValid(CharQuery charQuery) { }
	// RVA: 0x22df4d4 VA: 0x75948f74d4
	public Boolean CheckIfCharInDefense(String charId) { }
	// RVA: 0x22dd854 VA: 0x75948f5854
	public Boolean CheckIfCharInDefenseWithModeCheck(String charId) { }
	// RVA: 0x22dccd4 VA: 0x75948f4cd4
	public Boolean CheckIfFriendLegal() { }
	// RVA: 0x22ddf58 VA: 0x75948f5f58
	public Void TryRestrictSquadMembers() { }
	// RVA: 0x22debf4 VA: 0x75948f6bf4
	public Int32 MaxNum4CharSelect() { }
	// RVA: 0x22dceb0 VA: 0x75948f4eb0
	public Boolean IsCurrentSquadEmpty() { }
	// RVA: 0x22df9f0 VA: 0x75948f79f0
	private Void _LoadDataInternal(InputParams inputParams) { }
	// RVA: 0x22e01c8 VA: 0x75948f81c8
	private Void _InitViewModel(InputParams inputParams) { }
	// RVA: 0x22dfad4 VA: 0x75948f7ad4
	private Void _TryRefreshData() { }
	// RVA: 0x22e0358 VA: 0x75948f8358
	private Int32 _GetCurSquadValidMemberNum() { }
	// RVA: 0x22e00c4 VA: 0x75948f80c4
	private SquadMaxNumInfo _GetSquadMaxRawNumInfo() { }
	// RVA: 0x22dffd0 VA: 0x75948f7fd0
	private Int32 _GetSquadAssistNum() { }
	// RVA: 0x22dfec4 VA: 0x75948f7ec4
	private Int32 _GetSquadMaxCharCount() { }
	// RVA: 0x22dfbd0 VA: 0x75948f7bd0
	private ExternalRuneChecker _GetExternalRuneChecker() { }
	// RVA: 0x22dfcb0 VA: 0x75948f7cb0
	private Boolean _CheckIfCharInDefense(String charId, String excludeStageId) { }
	// RVA: 0x22dff48 VA: 0x75948f7f48
	private SquadMaxNumInfo _GetSquadMaxLimitNumInfo() { }
	// RVA: 0x22df1b8 VA: 0x75948f71b8
	public Void .ctor() { }
}
```