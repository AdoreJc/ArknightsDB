# Act1VAutoChessEntryMainViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <actId>k__BackingField`

- `ActState <actState>k__BackingField`

- `Int64 <actRemainTime>k__BackingField`

- `Int64 <actEndTime>k__BackingField`

- `Int64 <protectTs>k__BackingField`

- `Boolean <showActClose>k__BackingField`

- `Boolean <hasNewTeam>k__BackingField`

- `Boolean <hasNewChar>k__BackingField`

- `Boolean <showInGame>k__BackingField`

- `Boolean <hasGameToSettle>k__BackingField`

- `GameState <gameState>k__BackingField`

- `String <selectedModeId>k__BackingField`

- `Int32 <inGameRoundNum>k__BackingField`

- `Boolean <canOpenModeChoice>k__BackingField`

- `Boolean <hasModeNew>k__BackingField`

- `Single <dailyMissionProgress>k__BackingField`

- `Boolean <isDailyComplete>k__BackingField`

- `Boolean <hasUnfinishedActMission>k__BackingField`

- `String <firstMedal>k__BackingField`

- `Int32 <medalProgress>k__BackingField`

- `Int32 <medalMax>k__BackingField`

- `TemplateActivityMilestoneGroupViewModel <tmplMilestoneGroupViewModel>k__BackingField`

- `BasicData m_basicData`

- `PlayerAutoChessV1Activity m_playerData`


## Properties

- `String actId`

- `ActState actState`

- `Int64 actRemainTime`

- `Int64 actEndTime`

- `Int64 protectTs`

- `Boolean showActClose`

- `Boolean hasNewTeam`

- `Boolean hasNewChar`

- `Boolean showInGame`

- `Boolean hasGameToSettle`

- `GameState gameState`

- `String selectedModeId`

- `Int32 inGameRoundNum`

- `Boolean canOpenModeChoice`

- `Boolean hasModeNew`

- `Single dailyMissionProgress`

- `Boolean isDailyComplete`

- `Boolean hasUnfinishedActMission`

- `String firstMedal`

- `Int32 medalProgress`

- `Int32 medalMax`

- `TemplateActivityMilestoneGroupViewModel tmplMilestoneGroupViewModel`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `ActState get_actState()`

- `Void set_actState(ActState)`

- `Int64 get_actRemainTime()`

- `Void set_actRemainTime(Int64)`

- `Int64 get_actEndTime()`

- `Void set_actEndTime(Int64)`

- `Int64 get_protectTs()`

- `Void set_protectTs(Int64)`

- `Boolean get_showActClose()`

- `Void set_showActClose(Boolean)`

- `Boolean get_hasNewTeam()`

- `Void set_hasNewTeam(Boolean)`

- `Boolean get_hasNewChar()`

- `Void set_hasNewChar(Boolean)`

- `Boolean get_showInGame()`

- `Void set_showInGame(Boolean)`

- `Boolean get_hasGameToSettle()`

- `Void set_hasGameToSettle(Boolean)`

- `GameState get_gameState()`

- `Void set_gameState(GameState)`

- `String get_selectedModeId()`

- `Void set_selectedModeId(String)`

- `Int32 get_inGameRoundNum()`

- `Void set_inGameRoundNum(Int32)`

- `Void set_modeDataList(List`1)`

- `Boolean get_canOpenModeChoice()`

- `Void set_canOpenModeChoice(Boolean)`

- `Boolean get_hasModeNew()`

- `Void set_hasModeNew(Boolean)`

- `Single get_dailyMissionProgress()`

- `Void set_dailyMissionProgress(Single)`

- `Boolean get_isDailyComplete()`

- `Void set_isDailyComplete(Boolean)`

- `Boolean get_hasUnfinishedActMission()`

- `Void set_hasUnfinishedActMission(Boolean)`

- `String get_firstMedal()`

- `Void set_firstMedal(String)`

- `Int32 get_medalProgress()`

- `Void set_medalProgress(Int32)`

- `Int32 get_medalMax()`

- `Void set_medalMax(Int32)`

- `TemplateActivityMilestoneGroupViewModel get_tmplMilestoneGroupViewModel()`

- `Void set_tmplMilestoneGroupViewModel(TemplateActivityMilestoneGroupViewModel)`

- `Void _RefreshActState()`

- `Void _RefreshEntryInfoData()`

- `Void _RefreshTrackPoint()`

- `Boolean _CheckNewTeam()`

- `Boolean _CheckChessPoolChessCharsHasNew()`

- `Void _RefreshInGameInfo()`

- `Void _RefreshMedalInfo()`

- `Void <>xLuaBaseProxy_LoadData(String, ActivityAutoChessVerify1Data)`

- `Void <>xLuaBaseProxy_RefreshData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryMainViewModel : Act1VAutoChessEntryBaseSubViewModel
{
	private String <actId>k__BackingField; // 0x28
	private ActState <actState>k__BackingField; // 0x30
	private Int64 <actRemainTime>k__BackingField; // 0x38
	private Int64 <actEndTime>k__BackingField; // 0x40
	private Int64 <protectTs>k__BackingField; // 0x48
	private Boolean <showActClose>k__BackingField; // 0x50
	private Boolean <hasNewTeam>k__BackingField; // 0x51
	private Boolean <hasNewChar>k__BackingField; // 0x52
	private Boolean <showInGame>k__BackingField; // 0x53
	private Boolean <hasGameToSettle>k__BackingField; // 0x54
	private GameState <gameState>k__BackingField; // 0x58
	private String <selectedModeId>k__BackingField; // 0x60
	private Int32 <inGameRoundNum>k__BackingField; // 0x68
	private List`1 <modeDataList>k__BackingField; // 0x70
	private Boolean <canOpenModeChoice>k__BackingField; // 0x78
	private Boolean <hasModeNew>k__BackingField; // 0x79
	private Single <dailyMissionProgress>k__BackingField; // 0x7c
	private Boolean <isDailyComplete>k__BackingField; // 0x80
	private Boolean <hasUnfinishedActMission>k__BackingField; // 0x81
	private String <firstMedal>k__BackingField; // 0x88
	private Int32 <medalProgress>k__BackingField; // 0x90
	private Int32 <medalMax>k__BackingField; // 0x94
	private TemplateActivityMilestoneGroupViewModel <tmplMilestoneGroupViewModel>k__BackingField; // 0x98
	private BasicData m_basicData; // 0xa0
	private PlayerAutoChessV1Activity m_playerData; // 0xa8
	private List`1 m_medalList; // 0xb0
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_actState; // 0x10
	private static DelegateBridge __Hotfix0_set_actState; // 0x18
	private static DelegateBridge __Hotfix0_get_actRemainTime; // 0x20
	private static DelegateBridge __Hotfix0_set_actRemainTime; // 0x28
	private static DelegateBridge __Hotfix0_get_actEndTime; // 0x30
	private static DelegateBridge __Hotfix0_set_actEndTime; // 0x38
	private static DelegateBridge __Hotfix0_get_protectTs; // 0x40
	private static DelegateBridge __Hotfix0_set_protectTs; // 0x48
	private static DelegateBridge __Hotfix0_get_showActClose; // 0x50
	private static DelegateBridge __Hotfix0_set_showActClose; // 0x58
	private static DelegateBridge __Hotfix0_get_hasNewTeam; // 0x60
	private static DelegateBridge __Hotfix0_set_hasNewTeam; // 0x68
	private static DelegateBridge __Hotfix0_get_hasNewChar; // 0x70
	private static DelegateBridge __Hotfix0_set_hasNewChar; // 0x78
	private static DelegateBridge __Hotfix0_get_showInGame; // 0x80
	private static DelegateBridge __Hotfix0_set_showInGame; // 0x88
	private static DelegateBridge __Hotfix0_get_hasGameToSettle; // 0x90
	private static DelegateBridge __Hotfix0_set_hasGameToSettle; // 0x98
	private static DelegateBridge __Hotfix0_get_gameState; // 0xa0
	private static DelegateBridge __Hotfix0_set_gameState; // 0xa8
	private static DelegateBridge __Hotfix0_get_selectedModeId; // 0xb0
	private static DelegateBridge __Hotfix0_set_selectedModeId; // 0xb8
	private static DelegateBridge __Hotfix0_get_inGameRoundNum; // 0xc0
	private static DelegateBridge __Hotfix0_set_inGameRoundNum; // 0xc8
	private static DelegateBridge __Hotfix0_get_modeDataList; // 0xd0
	private static DelegateBridge __Hotfix0_set_modeDataList; // 0xd8
	private static DelegateBridge __Hotfix0_get_canOpenModeChoice; // 0xe0
	private static DelegateBridge __Hotfix0_set_canOpenModeChoice; // 0xe8
	private static DelegateBridge __Hotfix0_get_hasModeNew; // 0xf0
	private static DelegateBridge __Hotfix0_set_hasModeNew; // 0xf8
	private static DelegateBridge __Hotfix0_get_dailyMissionProgress; // 0x100
	private static DelegateBridge __Hotfix0_set_dailyMissionProgress; // 0x108
	private static DelegateBridge __Hotfix0_get_isDailyComplete; // 0x110
	private static DelegateBridge __Hotfix0_set_isDailyComplete; // 0x118
	private static DelegateBridge __Hotfix0_get_hasUnfinishedActMission; // 0x120
	private static DelegateBridge __Hotfix0_set_hasUnfinishedActMission; // 0x128
	private static DelegateBridge __Hotfix0_get_firstMedal; // 0x130
	private static DelegateBridge __Hotfix0_set_firstMedal; // 0x138
	private static DelegateBridge __Hotfix0_get_medalProgress; // 0x140
	private static DelegateBridge __Hotfix0_set_medalProgress; // 0x148
	private static DelegateBridge __Hotfix0_get_medalMax; // 0x150
	private static DelegateBridge __Hotfix0_set_medalMax; // 0x158
	private static DelegateBridge __Hotfix0_get_tmplMilestoneGroupViewModel; // 0x160
	private static DelegateBridge __Hotfix0_set_tmplMilestoneGroupViewModel; // 0x168
	private static DelegateBridge __Hotfix0_LoadData; // 0x170
	private static DelegateBridge __Hotfix0_RefreshData; // 0x178
	private static DelegateBridge __Hotfix0__RefreshActState; // 0x180
	private static DelegateBridge __Hotfix0__RefreshEntryInfoData; // 0x188
	private static DelegateBridge __Hotfix0__RefreshTrackPoint; // 0x190
	private static DelegateBridge __Hotfix0__CheckNewTeam; // 0x198
	private static DelegateBridge __Hotfix0__CheckChessPoolChessCharsHasNew; // 0x1a0
	private static DelegateBridge __Hotfix0__RefreshInGameInfo; // 0x1a8
	private static DelegateBridge __Hotfix0__RefreshMedalInfo; // 0x1b0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1b8

	public String actId { get; set; }
	public ActState actState { get; set; }
	public Int64 actRemainTime { get; set; }
	public Int64 actEndTime { get; set; }
	public Int64 protectTs { get; set; }
	public Boolean showActClose { get; set; }
	public Boolean hasNewTeam { get; set; }
	public Boolean hasNewChar { get; set; }
	public Boolean showInGame { get; set; }
	public Boolean hasGameToSettle { get; set; }
	public GameState gameState { get; set; }
	public String selectedModeId { get; set; }
	public Int32 inGameRoundNum { get; set; }
	public List`1 modeDataList { get; set; }
	public Boolean canOpenModeChoice { get; set; }
	public Boolean hasModeNew { get; set; }
	public Single dailyMissionProgress { get; set; }
	public Boolean isDailyComplete { get; set; }
	public Boolean hasUnfinishedActMission { get; set; }
	public String firstMedal { get; set; }
	public Int32 medalProgress { get; set; }
	public Int32 medalMax { get; set; }
	public TemplateActivityMilestoneGroupViewModel tmplMilestoneGroupViewModel { get; set; }

	// RVA: 0x334eee0 VA: 0x7595966ee0
	public String get_actId() { }
	// RVA: 0x334ef48 VA: 0x7595966f48
	private Void set_actId(String value) { }
	// RVA: 0x334efcc VA: 0x7595966fcc
	public ActState get_actState() { }
	// RVA: 0x334f034 VA: 0x7595967034
	private Void set_actState(ActState value) { }
	// RVA: 0x334f0b0 VA: 0x75959670b0
	public Int64 get_actRemainTime() { }
	// RVA: 0x334f118 VA: 0x7595967118
	private Void set_actRemainTime(Int64 value) { }
	// RVA: 0x334f194 VA: 0x7595967194
	public Int64 get_actEndTime() { }
	// RVA: 0x334f1fc VA: 0x75959671fc
	private Void set_actEndTime(Int64 value) { }
	// RVA: 0x334f278 VA: 0x7595967278
	public Int64 get_protectTs() { }
	// RVA: 0x334f2e0 VA: 0x75959672e0
	private Void set_protectTs(Int64 value) { }
	// RVA: 0x334f35c VA: 0x759596735c
	public Boolean get_showActClose() { }
	// RVA: 0x334f3c4 VA: 0x75959673c4
	private Void set_showActClose(Boolean value) { }
	// RVA: 0x334f444 VA: 0x7595967444
	public Boolean get_hasNewTeam() { }
	// RVA: 0x334f4ac VA: 0x75959674ac
	private Void set_hasNewTeam(Boolean value) { }
	// RVA: 0x334f52c VA: 0x759596752c
	public Boolean get_hasNewChar() { }
	// RVA: 0x334f594 VA: 0x7595967594
	private Void set_hasNewChar(Boolean value) { }
	// RVA: 0x334f614 VA: 0x7595967614
	public Boolean get_showInGame() { }
	// RVA: 0x334f67c VA: 0x759596767c
	private Void set_showInGame(Boolean value) { }
	// RVA: 0x334f6fc VA: 0x75959676fc
	public Boolean get_hasGameToSettle() { }
	// RVA: 0x334f764 VA: 0x7595967764
	private Void set_hasGameToSettle(Boolean value) { }
	// RVA: 0x334f7e4 VA: 0x75959677e4
	public GameState get_gameState() { }
	// RVA: 0x334f84c VA: 0x759596784c
	private Void set_gameState(GameState value) { }
	// RVA: 0x334f8c8 VA: 0x75959678c8
	public String get_selectedModeId() { }
	// RVA: 0x334f930 VA: 0x7595967930
	private Void set_selectedModeId(String value) { }
	// RVA: 0x334f9b4 VA: 0x75959679b4
	public Int32 get_inGameRoundNum() { }
	// RVA: 0x334fa1c VA: 0x7595967a1c
	private Void set_inGameRoundNum(Int32 value) { }
	// RVA: 0x334fa98 VA: 0x7595967a98
	public List`1 get_modeDataList() { }
	// RVA: 0x334fb00 VA: 0x7595967b00
	private Void set_modeDataList(List`1 value) { }
	// RVA: 0x334fb84 VA: 0x7595967b84
	public Boolean get_canOpenModeChoice() { }
	// RVA: 0x334fbec VA: 0x7595967bec
	private Void set_canOpenModeChoice(Boolean value) { }
	// RVA: 0x334fc6c VA: 0x7595967c6c
	public Boolean get_hasModeNew() { }
	// RVA: 0x334fcd4 VA: 0x7595967cd4
	private Void set_hasModeNew(Boolean value) { }
	// RVA: 0x334fd54 VA: 0x7595967d54
	public Single get_dailyMissionProgress() { }
	// RVA: 0x334fdbc VA: 0x7595967dbc
	private Void set_dailyMissionProgress(Single value) { }
	// RVA: 0x334fe38 VA: 0x7595967e38
	public Boolean get_isDailyComplete() { }
	// RVA: 0x334fea0 VA: 0x7595967ea0
	private Void set_isDailyComplete(Boolean value) { }
	// RVA: 0x334ff20 VA: 0x7595967f20
	public Boolean get_hasUnfinishedActMission() { }
	// RVA: 0x334ff88 VA: 0x7595967f88
	private Void set_hasUnfinishedActMission(Boolean value) { }
	// RVA: 0x3350008 VA: 0x7595968008
	public String get_firstMedal() { }
	// RVA: 0x3350070 VA: 0x7595968070
	private Void set_firstMedal(String value) { }
	// RVA: 0x33500f4 VA: 0x75959680f4
	public Int32 get_medalProgress() { }
	// RVA: 0x335015c VA: 0x759596815c
	private Void set_medalProgress(Int32 value) { }
	// RVA: 0x33501d8 VA: 0x75959681d8
	public Int32 get_medalMax() { }
	// RVA: 0x3350240 VA: 0x7595968240
	private Void set_medalMax(Int32 value) { }
	// RVA: 0x33502bc VA: 0x75959682bc
	public TemplateActivityMilestoneGroupViewModel get_tmplMilestoneGroupViewModel() { }
	// RVA: 0x3350324 VA: 0x7595968324
	private Void set_tmplMilestoneGroupViewModel(TemplateActivityMilestoneGroupViewModel value) { }
	// RVA: 0x33503a8 VA: 0x75959683a8
	public override Void LoadData(String actId, ActivityAutoChessVerify1Data actData) { }
	// RVA: 0x3350600 VA: 0x7595968600
	public override Void RefreshData() { }
	// RVA: 0x33506ec VA: 0x75959686ec
	private Void _RefreshActState() { }
	// RVA: 0x3350874 VA: 0x7595968874
	private Void _RefreshEntryInfoData() { }
	// RVA: 0x3350b64 VA: 0x7595968b64
	private Void _RefreshTrackPoint() { }
	// RVA: 0x3350fc4 VA: 0x7595968fc4
	private Boolean _CheckNewTeam() { }
	// RVA: 0x33512c0 VA: 0x75959692c0
	private Boolean _CheckChessPoolChessCharsHasNew() { }
	// RVA: 0x3350a8c VA: 0x7595968a8c
	private Void _RefreshInGameInfo() { }
	// RVA: 0x3350e84 VA: 0x7595968e84
	private Void _RefreshMedalInfo() { }
	// RVA: 0x33513f0 VA: 0x75959693f0
	public Void .ctor() { }
	// RVA: 0x335145c VA: 0x759596945c
	private Void <>xLuaBaseProxy_LoadData(String P0, ActivityAutoChessVerify1Data P1) { }
	// RVA: 0x3351460 VA: 0x7595969460
	private Void <>xLuaBaseProxy_RefreshData() { }
}
```