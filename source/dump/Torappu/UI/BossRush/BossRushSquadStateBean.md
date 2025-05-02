# BossRushSquadStateBean

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `LevelData m_levelData`

- `String activityId`

- `String stageGroupId`

- `String stageId`

- `SquadStartButtonTypeEnum startButtonMode`

- `Boolean curSquadHasTeamBuff`

- `SquadGroupViewProperty m_squadProperty`

- `ProfessionCategory m_assistProfession`

- `FriendAssistDataStruct m_friendDataCache`

- `ExternalRuneChecker m_externalRuneChecker`


## Properties

- `BossRushStageType bossRushStageType`

- `Boolean isNormalStage`

- `String curSquadTeamId`

- `String teamIdForRequest`

- `SquadGroupViewProperty squadGroupProp`

- `ProfessionCategory assistProfession`

- `FriendAssistDataStruct friendDataCache`

- `Boolean isFriendLegal`


## Methods

- `BossRushStageType get_bossRushStageType()`

- `Boolean get_isNormalStage()`

- `String get_curSquadTeamId()`

- `String get_teamIdForRequest()`

- `SquadGroupViewProperty get_squadGroupProp()`

- `ProfessionCategory get_assistProfession()`

- `Void set_assistProfession(ProfessionCategory)`

- `FriendAssistDataStruct get_friendDataCache()`

- `Void set_friendDataCache(FriendAssistDataStruct)`

- `Boolean get_isFriendLegal()`

- `CharacterCardViewModel PickRandomCharacter()`

- `Void _AddRelicRuneData(List`1, ActivityBossRushData, PlayerBossRushActivity)`

- `Void _AddWaveRuneData(List`1, ActivityBossRushData, PlayerBossRushActivity)`

- `Void _AddTeamRuneData(List`1, ActivityBossRushData)`

- `DataBundle GenDataBundleToJump()`

- `Void LoadData(Params)`

- `Void RefreshData()`

- `Void ApplyToFriendAssistBean(SquadFriendAssistStateBean)`

- `Void ReceiveFromFriendAssistBean(SquadFriendAssistStateBean)`

- `String GetTeamIdByIndex(Int32)`

- `Void SaveAllSquadDataToLocalCache()`

- `Void SaveSquadTeamToLocalCache(String)`

- `Boolean RestrictSquadMembers()`

- `Boolean CheckIfCharSelectable(CharQuery, String)`

- `Boolean CheckIfCharSelectable(Int32, String)`

- `Int32 MaxNum4CharSelect(String)`

- `Boolean IsCurrentSquadEmpty()`

- `Boolean CheckIfCharRuneValid(CharQuery)`

- `Boolean CheckIfCharValid(CharQuery, String)`

- `Boolean CheckIfSelectTeamMember(String, String)`

- `Int32 GetTeamFixMemCount(String)`

- `Void CleanAssistChar()`

- `Void UpdateTeamInfoByIndex(Int32)`

- `Boolean CheckIfPredefinedTeamSkillChanged()`

- `Boolean CheckIfShowPredefineSkillCanChange()`

- `Void SavePredefineSkillCanChangeFlag()`

- `Void _LoadDataInternal(String, String, String, String)`

- `Void _UpdateStartButtonType()`

- `Void _TryRefreshData()`

- `Void _RefreshRelic()`

- `BossRushTeamData _TryGetSquadTeamData(String)`

- `Void _InitTeamSelectedIndex(BossRushSquadGroupViewModel, String)`

- `Void _UpdateTeamInfo(String)`

- `SquadMaxNumInfo _GetSquadMaxRawNumInfo(String, Boolean)`

- `SquadMaxNumInfo _GetSquadMaxLimitNumInfo()`

- `Int32 _GetSquadMaxCharCount(String)`

- `Int32 _GetCurSquadValidMemberNum()`

- `Int32 _GetSquadAssistNum()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushSquadStateBean : IStateBean, IHotfixable
{
	private LevelData m_levelData; // 0x10
	public String activityId; // 0x18
	public String stageGroupId; // 0x20
	public String stageId; // 0x28
	public SquadStartButtonTypeEnum startButtonMode; // 0x30
	public List`1 curSquadTeamPredefinedList; // 0x38
	public Boolean curSquadHasTeamBuff; // 0x40
	private SquadGroupViewProperty m_squadProperty; // 0x48
	private ProfessionCategory m_assistProfession; // 0x50
	private FriendAssistDataStruct m_friendDataCache; // 0x58
	private ExternalRuneChecker m_externalRuneChecker; // 0x68
	private static DelegateBridge __Hotfix0_get_bossRushStageType; // 0x0
	private static DelegateBridge __Hotfix0_get_isNormalStage; // 0x8
	private static DelegateBridge __Hotfix0_get_teamDataDic; // 0x10
	private static DelegateBridge __Hotfix0_get_teamIndexDic; // 0x18
	private static DelegateBridge __Hotfix0_get_curSquadTeamId; // 0x20
	private static DelegateBridge __Hotfix0_get_teamIdForRequest; // 0x28
	private static DelegateBridge __Hotfix0_get_squadGroupProp; // 0x30
	private static DelegateBridge __Hotfix0_get_assistProfession; // 0x38
	private static DelegateBridge __Hotfix0_set_assistProfession; // 0x40
	private static DelegateBridge __Hotfix0_get_friendDataCache; // 0x48
	private static DelegateBridge __Hotfix0_set_friendDataCache; // 0x50
	private static DelegateBridge __Hotfix0_get_isFriendLegal; // 0x58
	private static DelegateBridge __Hotfix0_PickRandomCharacter; // 0x60
	private static DelegateBridge __Hotfix0_ParseBattleSquadLocal; // 0x68
	private static DelegateBridge __Hotfix0_ParseBattleStartRequestSquad; // 0x70
	private static DelegateBridge __Hotfix0_GetRuneListByBossRushRelic; // 0x78
	private static DelegateBridge __Hotfix0__AddRelicRuneData; // 0x80
	private static DelegateBridge __Hotfix0__AddWaveRuneData; // 0x88
	private static DelegateBridge __Hotfix0__AddTeamRuneData; // 0x90
	private static DelegateBridge __Hotfix0_GenDataBundleToJump; // 0x98
	private static DelegateBridge __Hotfix0_LoadData; // 0xa0
	private static DelegateBridge __Hotfix0_RefreshData; // 0xa8
	private static DelegateBridge __Hotfix0_ApplyToFriendAssistBean; // 0xb0
	private static DelegateBridge __Hotfix0_ReceiveFromFriendAssistBean; // 0xb8
	private static DelegateBridge __Hotfix0_GetTeamIdByIndex; // 0xc0
	private static DelegateBridge __Hotfix0_SaveAllSquadDataToLocalCache; // 0xc8
	private static DelegateBridge __Hotfix0_SaveSquadTeamToLocalCache; // 0xd0
	private static DelegateBridge __Hotfix0_RestrictSquadMembers; // 0xd8
	private static DelegateBridge __Hotfix0_CheckIfCharSelectable; // 0xe0
	private static DelegateBridge __Hotfix1_CheckIfCharSelectable; // 0xe8
	private static DelegateBridge __Hotfix0_MaxNum4CharSelect; // 0xf0
	private static DelegateBridge __Hotfix0_IsCurrentSquadEmpty; // 0xf8
	private static DelegateBridge __Hotfix0_CheckIfCharRuneValid; // 0x100
	private static DelegateBridge __Hotfix0_CheckIfCharValid; // 0x108
	private static DelegateBridge __Hotfix0_CheckIfSelectTeamMember; // 0x110
	private static DelegateBridge __Hotfix0_GetTeamFixMemCount; // 0x118
	private static DelegateBridge __Hotfix0_CleanAssistChar; // 0x120
	private static DelegateBridge __Hotfix0_UpdateTeamInfoByIndex; // 0x128
	private static DelegateBridge __Hotfix0_CheckIfPredefinedTeamSkillChanged; // 0x130
	private static DelegateBridge __Hotfix0_CheckIfShowPredefineSkillCanChange; // 0x138
	private static DelegateBridge __Hotfix0_SavePredefineSkillCanChangeFlag; // 0x140
	private static DelegateBridge __Hotfix0__LoadDataInternal; // 0x148
	private static DelegateBridge __Hotfix0__UpdateStartButtonType; // 0x150
	private static DelegateBridge __Hotfix0__TryRefreshData; // 0x158
	private static DelegateBridge __Hotfix0__RefreshRelic; // 0x160
	private static DelegateBridge __Hotfix0__TryGetSquadTeamData; // 0x168
	private static DelegateBridge __Hotfix0__InitTeamSelectedIndex; // 0x170
	private static DelegateBridge __Hotfix0__UpdateTeamInfo; // 0x178
	private static DelegateBridge __Hotfix0__GetSquadMaxRawNumInfo; // 0x180
	private static DelegateBridge __Hotfix0__GetSquadMaxLimitNumInfo; // 0x188
	private static DelegateBridge __Hotfix0__GetSquadMaxCharCount; // 0x190
	private static DelegateBridge __Hotfix0__GetCurSquadValidMemberNum; // 0x198
	private static DelegateBridge __Hotfix0__GetSquadAssistNum; // 0x1a0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1a8

	public BossRushStageType bossRushStageType { get; }
	public Boolean isNormalStage { get; }
	public Dictionary`2 teamDataDic { get; }
	public Dictionary`2 teamIndexDic { get; }
	public String curSquadTeamId { get; }
	public String teamIdForRequest { get; }
	public SquadGroupViewProperty squadGroupProp { get; }
	public ProfessionCategory assistProfession { get; set; }
	public FriendAssistDataStruct friendDataCache { get; set; }
	public Boolean isFriendLegal { get; }

	// RVA: 0x2e6ce68 VA: 0x7595484e68
	public BossRushStageType get_bossRushStageType() { }
	// RVA: 0x2e6772c VA: 0x759547f72c
	public Boolean get_isNormalStage() { }
	// RVA: 0x2e6cf44 VA: 0x7595484f44
	public Dictionary`2 get_teamDataDic() { }
	// RVA: 0x2e6d020 VA: 0x7595485020
	public Dictionary`2 get_teamIndexDic() { }
	// RVA: 0x2e6d0fc VA: 0x75954850fc
	public String get_curSquadTeamId() { }
	// RVA: 0x2e6909c VA: 0x759548109c
	public String get_teamIdForRequest() { }
	// RVA: 0x2e66254 VA: 0x759547e254
	public SquadGroupViewProperty get_squadGroupProp() { }
	// RVA: 0x2e69688 VA: 0x7595481688
	public ProfessionCategory get_assistProfession() { }
	// RVA: 0x2e696f0 VA: 0x75954816f0
	public Void set_assistProfession(ProfessionCategory value) { }
	// RVA: 0x2e69624 VA: 0x7595481624
	public FriendAssistDataStruct get_friendDataCache() { }
	// RVA: 0x2e6cdd8 VA: 0x7595484dd8
	public Void set_friendDataCache(FriendAssistDataStruct value) { }
	// RVA: 0x2e67ce4 VA: 0x759547fce4
	public Boolean get_isFriendLegal() { }
	// RVA: 0x2e68820 VA: 0x7595480820
	public CharacterCardViewModel PickRandomCharacter() { }
	// RVA: 0x2e688ec VA: 0x75954808ec
	public SquadItemStruct[] ParseBattleSquadLocal() { }
	// RVA: 0x2e68a7c VA: 0x7595480a7c
	public List`1 ParseBattleStartRequestSquad() { }
	// RVA: 0x2e68e5c VA: 0x7595480e5c
	public List`1 GetRuneListByBossRushRelic() { }
	// RVA: 0x2e6d4e0 VA: 0x75954854e0
	private Void _AddRelicRuneData(List`1 runeList, ActivityBossRushData bossRushData, PlayerBossRushActivity playerData) { }
	// RVA: 0x2e6d320 VA: 0x7595485320
	private Void _AddWaveRuneData(List`1 runeList, ActivityBossRushData bossRushData, PlayerBossRushActivity playerData) { }
	// RVA: 0x2e6d1d8 VA: 0x75954851d8
	private Void _AddTeamRuneData(List`1 runeList, ActivityBossRushData bossRushData) { }
	// RVA: 0x2e68fcc VA: 0x7595480fcc
	public DataBundle GenDataBundleToJump() { }
	// RVA: 0x2e65f74 VA: 0x759547df74
	public Void LoadData(Params pageParams) { }
	// RVA: 0x2e66350 VA: 0x759547e350
	public Void RefreshData() { }
	// RVA: 0x2e69884 VA: 0x7595481884
	public Void ApplyToFriendAssistBean(SquadFriendAssistStateBean assistBean) { }
	// RVA: 0x2e69b48 VA: 0x7595481b48
	public Void ReceiveFromFriendAssistBean(SquadFriendAssistStateBean assistBean) { }
	// RVA: 0x2e6a758 VA: 0x7595482758
	public String GetTeamIdByIndex(Int32 index) { }
	// RVA: 0x2e6b35c VA: 0x759548335c
	public Void SaveAllSquadDataToLocalCache() { }
	// RVA: 0x2e6b2b0 VA: 0x75954832b0
	public Void SaveSquadTeamToLocalCache(String teamId) { }
	// RVA: 0x2e67160 VA: 0x759547f160
	public Boolean RestrictSquadMembers() { }
	// RVA: 0x2e66a58 VA: 0x759547ea58
	public Boolean CheckIfCharSelectable(CharQuery charQuery, String teamId) { }
	// RVA: 0x2e6acb0 VA: 0x7595482cb0
	public Boolean CheckIfCharSelectable(Int32 instId, String teamId) { }
	// RVA: 0x2e6a95c VA: 0x759548295c
	public Int32 MaxNum4CharSelect(String teamId) { }
	// RVA: 0x2e67f04 VA: 0x759547ff04
	public Boolean IsCurrentSquadEmpty() { }
	// RVA: 0x2e6ca84 VA: 0x7595484a84
	public Boolean CheckIfCharRuneValid(CharQuery charQuery) { }
	// RVA: 0x2e6da94 VA: 0x7595485a94
	public Boolean CheckIfCharValid(CharQuery charQuery, String teamId) { }
	// RVA: 0x2e6a854 VA: 0x7595482854
	public Boolean CheckIfSelectTeamMember(String teamId, String charId) { }
	// RVA: 0x2e6e010 VA: 0x7595486010
	public Int32 GetTeamFixMemCount(String teamId) { }
	// RVA: 0x2e6b188 VA: 0x7595483188
	public Void CleanAssistChar() { }
	// RVA: 0x2e6b224 VA: 0x7595483224
	public Void UpdateTeamInfoByIndex(Int32 selectedIndex) { }
	// RVA: 0x2e67808 VA: 0x759547f808
	public Boolean CheckIfPredefinedTeamSkillChanged() { }
	// RVA: 0x2e67b4c VA: 0x759547fb4c
	public Boolean CheckIfShowPredefineSkillCanChange() { }
	// RVA: 0x2e67c54 VA: 0x759547fc54
	public Void SavePredefineSkillCanChangeFlag() { }
	// RVA: 0x2e6d6c0 VA: 0x75954856c0
	private Void _LoadDataInternal(String actId, String stageGroupId, String stageId, String selectedTeamId) { }
	// RVA: 0x2e6e53c VA: 0x759548653c
	private Void _UpdateStartButtonType() { }
	// RVA: 0x2e6d8e8 VA: 0x75954858e8
	private Void _TryRefreshData() { }
	// RVA: 0x2e6e3b8 VA: 0x75954863b8
	private Void _RefreshRelic() { }
	// RVA: 0x2e6dedc VA: 0x7595485edc
	private BossRushTeamData _TryGetSquadTeamData(String teamId) { }
	// RVA: 0x2e6e31c VA: 0x759548631c
	private Void _InitTeamSelectedIndex(BossRushSquadGroupViewModel squadGroupViewModel, String selectedTeamId) { }
	// RVA: 0x2e6e120 VA: 0x7595486120
	private Void _UpdateTeamInfo(String teamId) { }
	// RVA: 0x2e6dc98 VA: 0x7595485c98
	private SquadMaxNumInfo _GetSquadMaxRawNumInfo(String squadTeamId, Boolean excludePredefined) { }
	// RVA: 0x2e6de54 VA: 0x7595485e54
	private SquadMaxNumInfo _GetSquadMaxLimitNumInfo() { }
	// RVA: 0x2e6d9fc VA: 0x75954859fc
	private Int32 _GetSquadMaxCharCount(String squadTeamId) { }
	// RVA: 0x2e6e5c4 VA: 0x75954865c4
	private Int32 _GetCurSquadValidMemberNum() { }
	// RVA: 0x2e6ddbc VA: 0x7595485dbc
	private Int32 _GetSquadAssistNum() { }
	// RVA: 0x2e6be14 VA: 0x7595483e14
	public Void .ctor() { }
}
```