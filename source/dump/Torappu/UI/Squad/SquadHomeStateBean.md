# SquadHomeStateBean

**Namespace:** `Torappu.UI.Squad`


## Fields

- `SquadGroupViewProperty squadGroupProperty`

- `SquadLayoutProperty squadLayoutProperty`

- `Int32 renameSquadId`

- `FriendAssistDataStruct friendDataCache`

- `ProfessionCategory assistProfession`

- `SquadMode squadMode`

- `SquadStartButtonTypeEnum startButtonMode`

- `String startButtonOverrideId`

- `ExternalRuneChecker m_externalRuneChecker`

- `SquadMaxNumInfo m_squadMaxNumInfo`

- `Boolean m_isSquadValid`

- `String m_stageId`

- `Boolean m_isRetro`

- `String m_fireworkAnimalId`


## Properties

- `String stageId`

- `Boolean isRetro`

- `String fireworkAnimalId`

- `Boolean isSquadImmutable`

- `Boolean isSkillSelectablePredefine`

- `Boolean isSquadValid`

- `Boolean isFriendLegal`

- `Boolean allowStartBattle`

- `Boolean allowAssistChar`

- `SharedCharData currentFriendAssist`


## Methods

- `String get_stageId()`

- `Boolean get_isRetro()`

- `String get_fireworkAnimalId()`

- `Boolean get_isSquadImmutable()`

- `Boolean get_isSkillSelectablePredefine()`

- `Boolean get_isSquadValid()`

- `Boolean get_isFriendLegal()`

- `Boolean get_allowStartBattle()`

- `Boolean get_allowAssistChar()`

- `Void LoadData(SquadHomeStateBeanParam)`

- `Void CleanAssistChar()`

- `Void RefreshData()`

- `Void _TryReloadSquadData()`

- `Boolean CheckIfSquadChanged()`

- `Boolean CheckIfPredefinedSkillChanged()`

- `SharedCharData get_currentFriendAssist()`

- `Boolean IsCurrentSquadEmpty()`

- `Boolean CanStartBattleWithEmptySquad()`

- `CheckSquadResult CheckCurrentSquadHasExcludedChar()`

- `Boolean CheckIfCharValid(CharQuery)`

- `Void LoadExcludedCharInCurrentSquad(List`1)`

- `SquadModel ParseBattleStartRequestSquad()`

- `Void ApplyToFriendAssistBean(SquadFriendAssistStateBean)`

- `Void ReceiveFromFriendAssistBean(SquadFriendAssistStateBean)`

- `Void CleanFriendCache()`

- `Boolean CheckRequiredCharIncluded()`

- `Void LoadRequiredCharStatus(RequireChar, out, out)`

- `Boolean CheckIfCharRequired(String)`

- `Boolean CheckIfPredefinedSquadSkillChanged(String)`

- `Void _RefreshCharmsList()`

- `Void _RefreshTechesList()`

- `Void _RefreshCarComponentDict()`

- `Void _RefreshBattlePerformanceList()`

- `Void _RefreshTrapToolsList()`

- `Void _RefreshFireworkList()`

- `Boolean _IsStagePassed(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadHomeStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public SquadGroupViewProperty squadGroupProperty; // 0x18
	public SquadLayoutProperty squadLayoutProperty; // 0x20
	public Int32 renameSquadId; // 0x28
	public FriendAssistDataStruct friendDataCache; // 0x30
	public ProfessionCategory assistProfession; // 0x40
	public SquadMode squadMode; // 0x44
	public SquadStartButtonTypeEnum startButtonMode; // 0x48
	public String startButtonOverrideId; // 0x50
	private ExternalRuneChecker m_externalRuneChecker; // 0x58
	private SquadMaxNumInfo m_squadMaxNumInfo; // 0x60
	private Boolean m_isSquadValid; // 0x68
	private String m_stageId; // 0x70
	private PredefinedCard[] m_cachedPredefine; // 0x78
	private Boolean m_isRetro; // 0x80
	private List`1 m_charmList; // 0x88
	private List`1 m_techBranchList; // 0x90
	private String m_fireworkAnimalId; // 0x98
	private List`1 m_fireworkSlotList; // 0xa0
	private Dictionary`2 m_cartComponentsDict; // 0xa8
	private List`1 m_trapToolList; // 0xb0
	private List`1 m_battlePerformanceList; // 0xb8
	private List`1 m_optionalRunes; // 0xc0
	private static DelegateBridge __Hotfix0_get_stageId; // 0x0
	private static DelegateBridge __Hotfix0_get_isRetro; // 0x8
	private static DelegateBridge __Hotfix0_get_charmList; // 0x10
	private static DelegateBridge __Hotfix0_get_techBranchList; // 0x18
	private static DelegateBridge __Hotfix0_get_fireworkAnimalId; // 0x20
	private static DelegateBridge __Hotfix0_get_fireworkSlotList; // 0x28
	private static DelegateBridge __Hotfix0_get_cartComponentsDict; // 0x30
	private static DelegateBridge __Hotfix0_get_trapToolList; // 0x38
	private static DelegateBridge __Hotfix0_get_battlePerformanceList; // 0x40
	private static DelegateBridge __Hotfix0_get_isSquadImmutable; // 0x48
	private static DelegateBridge __Hotfix0_get_isSkillSelectablePredefine; // 0x50
	private static DelegateBridge __Hotfix0_get_isSquadValid; // 0x58
	private static DelegateBridge __Hotfix0_get_isFriendLegal; // 0x60
	private static DelegateBridge __Hotfix0_get_allowStartBattle; // 0x68
	private static DelegateBridge __Hotfix0_get_allowAssistChar; // 0x70
	private static DelegateBridge __Hotfix0_get_optionalPackedRunes; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x80
	private static DelegateBridge __Hotfix0_CleanAssistChar; // 0x88
	private static DelegateBridge __Hotfix0_RefreshData; // 0x90
	private static DelegateBridge __Hotfix0__TryReloadSquadData; // 0x98
	private static DelegateBridge __Hotfix0_CheckIfSquadChanged; // 0xa0
	private static DelegateBridge __Hotfix0_CheckIfPredefinedSkillChanged; // 0xa8
	private static DelegateBridge __Hotfix0_CreateSquadToStartBattle; // 0xb0
	private static DelegateBridge __Hotfix0_get_predefinedSquad; // 0xb8
	private static DelegateBridge __Hotfix0_get_currentSquad; // 0xc0
	private static DelegateBridge __Hotfix0_get_currentFriendAssist; // 0xc8
	private static DelegateBridge __Hotfix0_IsCurrentSquadEmpty; // 0xd0
	private static DelegateBridge __Hotfix0_CanStartBattleWithEmptySquad; // 0xd8
	private static DelegateBridge __Hotfix0_CheckCurrentSquadHasExcludedChar; // 0xe0
	private static DelegateBridge __Hotfix0_CheckIfCharValid; // 0xe8
	private static DelegateBridge __Hotfix0_LoadExcludedCharInCurrentSquad; // 0xf0
	private static DelegateBridge __Hotfix0_ParseBattleStartRequestSquad; // 0xf8
	private static DelegateBridge __Hotfix0_ApplyToFriendAssistBean; // 0x100
	private static DelegateBridge __Hotfix0_ReceiveFromFriendAssistBean; // 0x108
	private static DelegateBridge __Hotfix0_CleanFriendCache; // 0x110
	private static DelegateBridge __Hotfix0_CheckRequiredCharIncluded; // 0x118
	private static DelegateBridge __Hotfix0_GetRequireChars; // 0x120
	private static DelegateBridge __Hotfix0_LoadRequiredCharStatus; // 0x128
	private static DelegateBridge __Hotfix0_CheckIfCharRequired; // 0x130
	private static DelegateBridge __Hotfix0_CheckIfPredefinedSquadSkillChanged; // 0x138
	private static DelegateBridge __Hotfix0_GetRuneListByCharms; // 0x140
	private static DelegateBridge __Hotfix0_GetRuneListByTeches; // 0x148
	private static DelegateBridge __Hotfix0_GetRuneListByBattlePerformances; // 0x150
	private static DelegateBridge __Hotfix0_GetRuneListByTrapTools; // 0x158
	private static DelegateBridge __Hotfix0__RefreshCharmsList; // 0x160
	private static DelegateBridge __Hotfix0__RefreshTechesList; // 0x168
	private static DelegateBridge __Hotfix0__RefreshCarComponentDict; // 0x170
	private static DelegateBridge __Hotfix0__RefreshBattlePerformanceList; // 0x178
	private static DelegateBridge __Hotfix0__RefreshTrapToolsList; // 0x180
	private static DelegateBridge __Hotfix0__RefreshFireworkList; // 0x188
	private static DelegateBridge __Hotfix0__IsStagePassed; // 0x190
	private static DelegateBridge __Hotfix0__GeneOptionalPackedRuneData; // 0x198
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1a0

	public String stageId { get; }
	public Boolean isRetro { get; }
	public List`1 charmList { get; }
	public List`1 techBranchList { get; }
	public String fireworkAnimalId { get; }
	public List`1 fireworkSlotList { get; }
	public Dictionary`2 cartComponentsDict { get; }
	public List`1 trapToolList { get; }
	public List`1 battlePerformanceList { get; }
	public Boolean isSquadImmutable { get; }
	public Boolean isSkillSelectablePredefine { get; }
	public Boolean isSquadValid { get; }
	public Boolean isFriendLegal { get; }
	public Boolean allowStartBattle { get; }
	public Boolean allowAssistChar { get; }
	public List`1 optionalPackedRunes { get; }
	public SquadItemStruct[] predefinedSquad { get; }
	private SquadItemStruct[] currentSquad { get; }
	private SharedCharData currentFriendAssist { get; }

	// RVA: 0x237e2a4 VA: 0x75949962a4
	public String get_stageId() { }
	// RVA: 0x2394d80 VA: 0x75949acd80
	public Boolean get_isRetro() { }
	// RVA: 0x2385ca8 VA: 0x759499dca8
	public List`1 get_charmList() { }
	// RVA: 0x2385ef8 VA: 0x759499def8
	public List`1 get_techBranchList() { }
	// RVA: 0x23869dc VA: 0x759499e9dc
	public String get_fireworkAnimalId() { }
	// RVA: 0x2386974 VA: 0x759499e974
	public List`1 get_fireworkSlotList() { }
	// RVA: 0x2386374 VA: 0x759499e374
	public Dictionary`2 get_cartComponentsDict() { }
	// RVA: 0x2386664 VA: 0x759499e664
	public List`1 get_trapToolList() { }
	// RVA: 0x23863dc VA: 0x759499e3dc
	public List`1 get_battlePerformanceList() { }
	// RVA: 0x237e538 VA: 0x7594996538
	public Boolean get_isSquadImmutable() { }
	// RVA: 0x23814ac VA: 0x75949994ac
	public Boolean get_isSkillSelectablePredefine() { }
	// RVA: 0x2387770 VA: 0x759499f770
	public Boolean get_isSquadValid() { }
	// RVA: 0x2387580 VA: 0x759499f580
	public Boolean get_isFriendLegal() { }
	// RVA: 0x2394de8 VA: 0x75949acde8
	public Boolean get_allowStartBattle() { }
	// RVA: 0x237e4a4 VA: 0x75949964a4
	public Boolean get_allowAssistChar() { }
	// RVA: 0x2386a44 VA: 0x759499ea44
	public List`1 get_optionalPackedRunes() { }
	// RVA: 0x237deb8 VA: 0x7594995eb8
	public Void LoadData(SquadHomeStateBeanParam param) { }
	// RVA: 0x238379c VA: 0x759499b79c
	public Void CleanAssistChar() { }
	// RVA: 0x237d9e0 VA: 0x75949959e0
	public Void RefreshData() { }
	// RVA: 0x2396768 VA: 0x75949ae768
	private Void _TryReloadSquadData() { }
	// RVA: 0x23839c4 VA: 0x759499b9c4
	public Boolean CheckIfSquadChanged() { }
	// RVA: 0x23827a0 VA: 0x759499a7a0
	public Boolean CheckIfPredefinedSkillChanged() { }
	// RVA: 0x2385ab4 VA: 0x759499dab4
	public SquadItemStruct[] CreateSquadToStartBattle() { }
	// RVA: 0x2383828 VA: 0x759499b828
	public SquadItemStruct[] get_predefinedSquad() { }
	// RVA: 0x2396884 VA: 0x75949ae884
	private SquadItemStruct[] get_currentSquad() { }
	// RVA: 0x2396a28 VA: 0x75949aea28
	private SharedCharData get_currentFriendAssist() { }
	// RVA: 0x2387848 VA: 0x759499f848
	public Boolean IsCurrentSquadEmpty() { }
	// RVA: 0x23877d8 VA: 0x759499f7d8
	public Boolean CanStartBattleWithEmptySquad() { }
	// RVA: 0x2382444 VA: 0x759499a444
	public CheckSquadResult CheckCurrentSquadHasExcludedChar() { }
	// RVA: 0x2396b98 VA: 0x75949aeb98
	public Boolean CheckIfCharValid(CharQuery query) { }
	// RVA: 0x238a480 VA: 0x75949a2480
	public Void LoadExcludedCharInCurrentSquad(List`1 result) { }
	// RVA: 0x2386aac VA: 0x759499eaac
	public SquadModel ParseBattleStartRequestSquad() { }
	// RVA: 0x2387fd8 VA: 0x759499ffd8
	public Void ApplyToFriendAssistBean(SquadFriendAssistStateBean assistBean) { }
	// RVA: 0x2388c14 VA: 0x75949a0c14
	public Void ReceiveFromFriendAssistBean(SquadFriendAssistStateBean assistBean) { }
	// RVA: 0x2396c58 VA: 0x75949aec58
	public Void CleanFriendCache() { }
	// RVA: 0x238251c VA: 0x759499a51c
	public Boolean CheckRequiredCharIncluded() { }
	// RVA: 0x23882dc VA: 0x75949a02dc
	public List`1 GetRequireChars() { }
	// RVA: 0x23883b8 VA: 0x75949a03b8
	public Void LoadRequiredCharStatus(RequireChar requiredChar, out Boolean isCharIncluded, out Boolean isEvolveMatch) { }
	// RVA: 0x23890a4 VA: 0x75949a10a4
	public Boolean CheckIfCharRequired(String charId) { }
	// RVA: 0x2382a64 VA: 0x759499aa64
	public Boolean CheckIfPredefinedSquadSkillChanged(String activityId) { }
	// RVA: 0x2385d10 VA: 0x759499dd10
	public static List`1 GetRuneListByCharms(List`1 charmList) { }
	// RVA: 0x2386058 VA: 0x759499e058
	public static List`1 GetRuneListByTeches(Boolean isRetro, String groupId, List`1 techBranchList) { }
	// RVA: 0x2386444 VA: 0x759499e444
	public static List`1 GetRuneListByBattlePerformances(Boolean isRetro, String groupId, List`1 battlePerformanceList) { }
	// RVA: 0x23866cc VA: 0x759499e6cc
	public static List`1 GetRuneListByTrapTools(String groupId, List`1 trapList) { }
	// RVA: 0x23953d0 VA: 0x75949ad3d0
	private Void _RefreshCharmsList() { }
	// RVA: 0x23956c8 VA: 0x75949ad6c8
	private Void _RefreshTechesList() { }
	// RVA: 0x2395a44 VA: 0x75949ada44
	private Void _RefreshCarComponentDict() { }
	// RVA: 0x2396178 VA: 0x75949ae178
	private Void _RefreshBattlePerformanceList() { }
	// RVA: 0x2395d68 VA: 0x75949add68
	private Void _RefreshTrapToolsList() { }
	// RVA: 0x23963e4 VA: 0x75949ae3e4
	private Void _RefreshFireworkList() { }
	// RVA: 0x2396cd0 VA: 0x75949aecd0
	private Boolean _IsStagePassed(String stageId) { }
	// RVA: 0x2394e70 VA: 0x75949ace70
	private List`1 _GeneOptionalPackedRuneData(List`1 optionalRuneKeys, LevelData levelData) { }
	// RVA: 0x2396d5c VA: 0x75949aed5c
	public Void .ctor() { }
}
```