# RoguelikeTopicModeViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicModeViewType showMode`

- `RoguelikeTopicMonthSquadViewModel monthSquad`

- `RoguelikeTopicChallengeModeViewModel challenge`

- `RoguelikeTopicActivityEntryCompBaseModel actCompModel`

- `Boolean haveTopicActive`

- `Int64 lastTs`

- `String cacheTopicId`

- `String kvName`

- `String outerBuffCompleteText`

- `Int32 bpPoint`

- `Int32 bpLevel`

- `Boolean isUpdateBp`

- `Boolean isFullStored`

- `String bpUpdateCountdownStr`

- `String bpUpdateName`

- `RoguelikeTopicDifficultyViewSub diffSubViewOnShow`

- `RoguelikeTopicDetail <topicData>k__BackingField`

- `OuterData <playerOuterData>k__BackingField`

- `RoguelikeTopicDifficultyViewModel m_selectDiffModel`

- `Int64 currentStartTs`

- `String zoneName`

- `RoguelikeTopicMode mode`

- `Int32 <modeGrade>k__BackingField`

- `String predefinedId`

- `RoguelikeTopicDifficultyViewModel activeDiffModel`

- `Int64 startTime`

- `Boolean showArchiveTrackpoint`

- `RoguelikeTopicModeViewModelExtension m_extension`


## Properties

- `Boolean showDiffDetail`

- `RoguelikeTopicDetail topicData`

- `OuterData playerOuterData`

- `Int32 modeGrade`

- `RoguelikeTopicDifficultyViewModel currentSelectDiffModel`

- `String hardModeName`


## Methods

- `Boolean get_showDiffDetail()`

- `Void set_showDiffDetail(Boolean)`

- `RoguelikeTopicDetail get_topicData()`

- `Void set_topicData(RoguelikeTopicDetail)`

- `OuterData get_playerOuterData()`

- `Void set_playerOuterData(OuterData)`

- `Int32 get_modeGrade()`

- `Void set_modeGrade(Int32)`

- `T GetExtension()`

- `RoguelikeTopicDifficultyViewModel get_currentSelectDiffModel()`

- `String get_hardModeName()`

- `Void LoadData(String, RoguelikeTopicModeViewModelExtension)`

- `Void SetCurrentDifficulty(RoguelikeTopicDifficultyID)`

- `RoguelikeTopicDifficultyID _InitAndLoadLastDifficulty(String)`

- `Void _UpdateTopicCommonData(String)`

- `Void _UpdateDifficultyList(String)`

- `String GetCurrentActiveMonthSquadId()`

- `Void SetCurrentMonthSquadId(String)`

- `Void SwitchMonthSquadList(Int32)`

- `Boolean SetSelectedChallenge(String)`

- `Boolean CheckIfOpened(String, RoguelikeTopicModeViewType)`

- `Boolean CheckIfUnlocked(String, RoguelikeTopicModeViewType)`

- `Boolean CheckIfModeViewTypeSelectable(RoguelikeTopicModeViewType)`

- `RoguelikeTopicModeViewType _CheckCurrentShowMode()`

- `Void _LoadBpInfo(String)`

- `Void _LoadRogueActivityEntryCompModel()`

- `Void PopDiffSubView()`

- `Boolean CheckDiffSubViewVisible(RoguelikeTopicDifficultyViewSub)`

- `Void SetDiffSubViewVisible(RoguelikeTopicDifficultyViewSub, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicModeViewModel : IHotfixable
{
	public RoguelikeTopicModeViewType showMode; // 0x10
	public RoguelikeTopicMonthSquadViewModel monthSquad; // 0x18
	public RoguelikeTopicChallengeModeViewModel challenge; // 0x20
	public RoguelikeTopicActivityEntryCompBaseModel actCompModel; // 0x28
	public Boolean haveTopicActive; // 0x30
	public Int64 lastTs; // 0x38
	public String cacheTopicId; // 0x40
	public String kvName; // 0x48
	public String outerBuffCompleteText; // 0x50
	public Int32 bpPoint; // 0x58
	public Int32 bpLevel; // 0x5c
	public Boolean isUpdateBp; // 0x60
	public Boolean isFullStored; // 0x61
	public String bpUpdateCountdownStr; // 0x68
	public String bpUpdateName; // 0x70
	public RoguelikeTopicDifficultyViewSub diffSubViewOnShow; // 0x78
	private RoguelikeTopicDetail <topicData>k__BackingField; // 0x80
	private OuterData <playerOuterData>k__BackingField; // 0x88
	private List`1 m_difficultyList; // 0x90
	private RoguelikeTopicDifficultyViewModel m_selectDiffModel; // 0x98
	public Int64 currentStartTs; // 0xa0
	public String zoneName; // 0xa8
	public RoguelikeTopicMode mode; // 0xb0
	private Int32 <modeGrade>k__BackingField; // 0xb4
	public String predefinedId; // 0xb8
	public RoguelikeTopicDifficultyViewModel activeDiffModel; // 0xc0
	public Int64 startTime; // 0xc8
	public Boolean showArchiveTrackpoint; // 0xd0
	private RoguelikeTopicModeViewModelExtension m_extension; // 0xd8
	private static DelegateBridge __Hotfix0_get_showDiffDetail; // 0x0
	private static DelegateBridge __Hotfix0_set_showDiffDetail; // 0x8
	private static DelegateBridge __Hotfix0_get_topicData; // 0x10
	private static DelegateBridge __Hotfix0_set_topicData; // 0x18
	private static DelegateBridge __Hotfix0_get_playerOuterData; // 0x20
	private static DelegateBridge __Hotfix0_set_playerOuterData; // 0x28
	private static DelegateBridge __Hotfix0_get_modeGrade; // 0x30
	private static DelegateBridge __Hotfix0_set_modeGrade; // 0x38
	private static DelegateBridge __Hotfix0_GetExtension; // 0x40
	private static DelegateBridge __Hotfix0_get_difficultyList; // 0x48
	private static DelegateBridge __Hotfix0_get_currentSelectDiffModel; // 0x50
	private static DelegateBridge __Hotfix0_get_hardModeName; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge __Hotfix0_SetCurrentDifficulty; // 0x68
	private static DelegateBridge __Hotfix0__InitAndLoadLastDifficulty; // 0x70
	private static DelegateBridge __Hotfix0__UpdateTopicCommonData; // 0x78
	private static DelegateBridge __Hotfix0__UpdateDifficultyList; // 0x80
	private static DelegateBridge __Hotfix0_GetCurrentActiveMonthSquadId; // 0x88
	private static DelegateBridge __Hotfix0_SetCurrentMonthSquadId; // 0x90
	private static DelegateBridge __Hotfix0_SwitchMonthSquadList; // 0x98
	private static DelegateBridge __Hotfix0_SetSelectedChallenge; // 0xa0
	private static DelegateBridge __Hotfix0_CheckIfOpened; // 0xa8
	private static DelegateBridge __Hotfix0_CheckIfUnlocked; // 0xb0
	private static DelegateBridge __Hotfix0_CheckIfModeViewTypeSelectable; // 0xb8
	private static DelegateBridge __Hotfix0__CheckCurrentShowMode; // 0xc0
	private static DelegateBridge __Hotfix0__LoadBpInfo; // 0xc8
	private static DelegateBridge __Hotfix0__LoadRogueActivityEntryCompModel; // 0xd0
	private static DelegateBridge __Hotfix0_PopDiffSubView; // 0xd8
	private static DelegateBridge __Hotfix0_CheckDiffSubViewVisible; // 0xe0
	private static DelegateBridge __Hotfix0_SetDiffSubViewVisible; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	public Boolean showDiffDetail { get; set; }
	public RoguelikeTopicDetail topicData { get; set; }
	public OuterData playerOuterData { get; set; }
	public Int32 modeGrade { get; set; }
	public List`1 difficultyList { get; }
	public RoguelikeTopicDifficultyViewModel currentSelectDiffModel { get; }
	public String hardModeName { get; }

	// RVA: 0x2678e1c VA: 0x7594c90e1c
	public Boolean get_showDiffDetail() { }
	// RVA: 0x2678e8c VA: 0x7594c90e8c
	public Void set_showDiffDetail(Boolean value) { }
	// RVA: 0x2678f1c VA: 0x7594c90f1c
	public RoguelikeTopicDetail get_topicData() { }
	// RVA: 0x2678f84 VA: 0x7594c90f84
	private Void set_topicData(RoguelikeTopicDetail value) { }
	// RVA: 0x2679008 VA: 0x7594c91008
	public OuterData get_playerOuterData() { }
	// RVA: 0x2679070 VA: 0x7594c91070
	private Void set_playerOuterData(OuterData value) { }
	// RVA: 0x26790f4 VA: 0x7594c910f4
	public Int32 get_modeGrade() { }
	// RVA: 0x267915c VA: 0x7594c9115c
	private Void set_modeGrade(Int32 value) { }
	// RVA: 0x VA: 0x0
	public T GetExtension() { }
	// RVA: 0x26791d8 VA: 0x7594c911d8
	public List`1 get_difficultyList() { }
	// RVA: 0x2679240 VA: 0x7594c91240
	public RoguelikeTopicDifficultyViewModel get_currentSelectDiffModel() { }
	// RVA: 0x26792a8 VA: 0x7594c912a8
	public String get_hardModeName() { }
	// RVA: 0x26710d4 VA: 0x7594c890d4
	public Void LoadData(String topicId, RoguelikeTopicModeViewModelExtension extension) { }
	// RVA: 0x26798c4 VA: 0x7594c918c4
	public Void SetCurrentDifficulty(RoguelikeTopicDifficultyID diffId) { }
	// RVA: 0x267980c VA: 0x7594c9180c
	private RoguelikeTopicDifficultyID _InitAndLoadLastDifficulty(String topicId) { }
	// RVA: 0x26793d4 VA: 0x7594c913d4
	private Void _UpdateTopicCommonData(String topic) { }
	// RVA: 0x267a904 VA: 0x7594c92904
	private Void _UpdateDifficultyList(String topicId) { }
	// RVA: 0x267acac VA: 0x7594c92cac
	public String GetCurrentActiveMonthSquadId() { }
	// RVA: 0x267ad44 VA: 0x7594c92d44
	public Void SetCurrentMonthSquadId(String monthSquadId) { }
	// RVA: 0x2670d48 VA: 0x7594c88d48
	public Void SwitchMonthSquadList(Int32 delta) { }
	// RVA: 0x2670f30 VA: 0x7594c88f30
	public Boolean SetSelectedChallenge(String challengeId) { }
	// RVA: 0x26725d8 VA: 0x7594c8a5d8
	public Boolean CheckIfOpened(String topicId, RoguelikeTopicModeViewType viewType) { }
	// RVA: 0x2672468 VA: 0x7594c8a468
	public Boolean CheckIfUnlocked(String topicId, RoguelikeTopicModeViewType viewType) { }
	// RVA: 0x2672398 VA: 0x7594c8a398
	public Boolean CheckIfModeViewTypeSelectable(RoguelikeTopicModeViewType viewType) { }
	// RVA: 0x2679d1c VA: 0x7594c91d1c
	private RoguelikeTopicModeViewType _CheckCurrentShowMode() { }
	// RVA: 0x2679a58 VA: 0x7594c91a58
	private Void _LoadBpInfo(String topicId) { }
	// RVA: 0x267a7f8 VA: 0x7594c927f8
	private Void _LoadRogueActivityEntryCompModel() { }
	// RVA: 0x267b04c VA: 0x7594c9304c
	public Void PopDiffSubView() { }
	// RVA: 0x267b0d8 VA: 0x7594c930d8
	public Boolean CheckDiffSubViewVisible(RoguelikeTopicDifficultyViewSub sub) { }
	// RVA: 0x267b15c VA: 0x7594c9315c
	public Void SetDiffSubViewVisible(RoguelikeTopicDifficultyViewSub sub, Boolean v) { }
	// RVA: 0x267b1f4 VA: 0x7594c931f4
	public Void .ctor() { }
}
```