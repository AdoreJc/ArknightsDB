# EnemyDuelDataCenter

**Namespace:** `Torappu.DataCenter`


## Fields

- `ActivityEnemyDuelData m_actData`

- `ActivityEnemyDuelModeData m_subModeData`

- `Int32 m_curRoundIndex`

- `ActivityEnemyDuelRoundData m_curRoundData`

- `EnemyDuelServiceGameState m_roundState`

- `EnemyDuelBattleStatus m_status`

- `Boolean m_isGameOver`

- `Int32 m_maxRound`

- `EnemyDuelEntryData m_entryData`

- `EnemyDuelBetData m_betData`

- `EnemyDuelSettleData m_settleData`

- `EnemyDuelPlayerData m_selfData`

- `String m_actId`

- `String m_sceneId`

- `String m_currUid`

- `Boolean m_isRoomOwner`

- `Boolean m_isCurAutoChoose`


## Properties

- `Boolean isCurAutoChoose`

- `Boolean isRoomOwner`

- `Int32 curRoundIndex`

- `ActivityEnemyDuelRoundData curRoundData`

- `EnemyDuelModeType curModeType`

- `EnemyDuelServiceGameState curRoundState`

- `Boolean isGameOver`

- `ActivityEnemyDuelConstData constData`

- `String actId`

- `String sceneId`

- `ActivityEnemyDuelData actData`

- `ActivityEnemyDuelModeData subModeData`


## Methods

- `Boolean get_isCurAutoChoose()`

- `Boolean get_isRoomOwner()`

- `Int32 get_curRoundIndex()`

- `ActivityEnemyDuelRoundData get_curRoundData()`

- `EnemyDuelModeType get_curModeType()`

- `EnemyDuelServiceGameState get_curRoundState()`

- `Boolean get_isGameOver()`

- `ActivityEnemyDuelConstData get_constData()`

- `String get_actId()`

- `String get_sceneId()`

- `ActivityEnemyDuelData get_actData()`

- `ActivityEnemyDuelModeData get_subModeData()`

- `Void LoadAndInitData(ActivityEnemyDuelData, ActivityEnemyDuelModeData, String, EnemyDuelInput)`

- `Void PreparePlayerDataBeforeWaveStart(Int32, ActivityEnemyDuelRoundData)`

- `Void ForceUpdateRoundAllStateData(EnemyDuelBattleStatus)`

- `Void OnRoundChanged(Int32)`

- `Void UpdateRoundStateData(EnemyDuelBattleStatus)`

- `Void AssignPlayerDataDict(Dictionary`2)`

- `Void AssignSelfPlayerData(EnemyDuelPlayerData)`

- `Void AddTeamData(EnemyDuelTeamData)`

- `Void RefreshTeamList()`

- `Void OnSingleModeFinishRound(EnemyDuelRoundResult, Int32)`

- `Void OnFinishGame()`

- `Void OnGameQuit()`

- `EnemyDuelPlayerData GetSelfPlayerData()`

- `EnemyDuelBetData GetBetData()`

- `EnemyDuelSettleData GetSettleData()`

- `EnemyDuelSingleFinishSettle FetchSingleFinishOutput()`

- `Void _RefreshPlayerBetData(EnemyDuelBattleStatus)`

- `Void _RefreshPlayerSettleData(EnemyDuelBattleStatus)`

- `Boolean _CheckGameOver()`

- `Void _LogRoundPlayerResult()`

- `Void _LogGameResult()`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DataCenter
public class EnemyDuelDataCenter : SingletonWithMonoHost`2, IDisposable
{
	private ActivityEnemyDuelData m_actData; // 0x10
	private ActivityEnemyDuelModeData m_subModeData; // 0x18
	private Int32 m_curRoundIndex; // 0x20
	private ActivityEnemyDuelRoundData m_curRoundData; // 0x28
	private EnemyDuelServiceGameState m_roundState; // 0x30
	private EnemyDuelBattleStatus m_status; // 0x38
	private Boolean m_isGameOver; // 0x60
	private Int32 m_maxRound; // 0x64
	private readonly List`1 m_teamDataList; // 0x68
	private Dictionary`2 m_playerDataDict; // 0x70
	private EnemyDuelEntryData m_entryData; // 0x78
	private EnemyDuelBetData m_betData; // 0x80
	private EnemyDuelSettleData m_settleData; // 0x88
	private EnemyDuelPlayerData m_selfData; // 0x90
	private List`1 m_roundInfoList; // 0x98
	private List`1 m_rankInfoList; // 0xa0
	private String m_actId; // 0xa8
	private String m_sceneId; // 0xb0
	private String m_currUid; // 0xb8
	private Boolean m_isRoomOwner; // 0xc0
	private Boolean m_isCurAutoChoose; // 0xc1
	private static DelegateBridge __Hotfix0_get_isCurAutoChoose; // 0x0
	private static DelegateBridge __Hotfix0_get_isRoomOwner; // 0x8
	private static DelegateBridge __Hotfix0_get_curRoundIndex; // 0x10
	private static DelegateBridge __Hotfix0_get_curRoundData; // 0x18
	private static DelegateBridge __Hotfix0_get_curModeType; // 0x20
	private static DelegateBridge __Hotfix0_get_curRoundState; // 0x28
	private static DelegateBridge __Hotfix0_get_isGameOver; // 0x30
	private static DelegateBridge __Hotfix0_get_constData; // 0x38
	private static DelegateBridge __Hotfix0_get_actId; // 0x40
	private static DelegateBridge __Hotfix0_get_sceneId; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50
	private static DelegateBridge __Hotfix0_get_actData; // 0x58
	private static DelegateBridge __Hotfix0_get_subModeData; // 0x60
	private static DelegateBridge __Hotfix0_LoadAndInitData; // 0x68
	private static DelegateBridge __Hotfix0_PreparePlayerDataBeforeWaveStart; // 0x70
	private static DelegateBridge __Hotfix0_ForceUpdateRoundAllStateData; // 0x78
	private static DelegateBridge __Hotfix0_OnRoundChanged; // 0x80
	private static DelegateBridge __Hotfix0_UpdateRoundStateData; // 0x88
	private static DelegateBridge __Hotfix0_AssignPlayerDataDict; // 0x90
	private static DelegateBridge __Hotfix0_AssignSelfPlayerData; // 0x98
	private static DelegateBridge __Hotfix0_AddTeamData; // 0xa0
	private static DelegateBridge __Hotfix0_RefreshTeamList; // 0xa8
	private static DelegateBridge __Hotfix0_OnSingleModeFinishRound; // 0xb0
	private static DelegateBridge __Hotfix0_OnFinishGame; // 0xb8
	private static DelegateBridge __Hotfix0_OnGameQuit; // 0xc0
	private static DelegateBridge __Hotfix0_GetPlayerDataDict; // 0xc8
	private static DelegateBridge __Hotfix0_GetSelfPlayerData; // 0xd0
	private static DelegateBridge __Hotfix0_GetTeamData; // 0xd8
	private static DelegateBridge __Hotfix0_GetBetData; // 0xe0
	private static DelegateBridge __Hotfix0_GetSettleData; // 0xe8
	private static DelegateBridge __Hotfix0_FetchSingleFinishOutput; // 0xf0
	private static DelegateBridge __Hotfix0__RefreshPlayerBetData; // 0xf8
	private static DelegateBridge __Hotfix0__RefreshPlayerSettleData; // 0x100
	private static DelegateBridge __Hotfix0__CheckGameOver; // 0x108
	private static DelegateBridge __Hotfix0__LogRoundPlayerResult; // 0x110
	private static DelegateBridge __Hotfix0__LogGameResult; // 0x118
	private static DelegateBridge __Hotfix0_Dispose; // 0x120

	public Boolean isCurAutoChoose { get; }
	public Boolean isRoomOwner { get; }
	public Int32 curRoundIndex { get; }
	public ActivityEnemyDuelRoundData curRoundData { get; }
	public EnemyDuelModeType curModeType { get; }
	public EnemyDuelServiceGameState curRoundState { get; }
	public Boolean isGameOver { get; }
	public ActivityEnemyDuelConstData constData { get; }
	public String actId { get; }
	public String sceneId { get; }
	public ActivityEnemyDuelData actData { get; }
	public ActivityEnemyDuelModeData subModeData { get; }

	// RVA: 0x3e44c5c VA: 0x759645cc5c
	public Boolean get_isCurAutoChoose() { }
	// RVA: 0x3e44cc4 VA: 0x759645ccc4
	public Boolean get_isRoomOwner() { }
	// RVA: 0x3e44d2c VA: 0x759645cd2c
	public Int32 get_curRoundIndex() { }
	// RVA: 0x3e44d94 VA: 0x759645cd94
	public ActivityEnemyDuelRoundData get_curRoundData() { }
	// RVA: 0x3e44dfc VA: 0x759645cdfc
	public EnemyDuelModeType get_curModeType() { }
	// RVA: 0x3e44e70 VA: 0x759645ce70
	public EnemyDuelServiceGameState get_curRoundState() { }
	// RVA: 0x3e44ed8 VA: 0x759645ced8
	public Boolean get_isGameOver() { }
	// RVA: 0x3e44f40 VA: 0x759645cf40
	public ActivityEnemyDuelConstData get_constData() { }
	// RVA: 0x3e44fb4 VA: 0x759645cfb4
	public String get_actId() { }
	// RVA: 0x3e4501c VA: 0x759645d01c
	public String get_sceneId() { }
	// RVA: 0x3e45084 VA: 0x759645d084
	private Void .ctor() { }
	// RVA: 0x3e4530c VA: 0x759645d30c
	public ActivityEnemyDuelData get_actData() { }
	// RVA: 0x3e45374 VA: 0x759645d374
	public ActivityEnemyDuelModeData get_subModeData() { }
	// RVA: 0x3e453dc VA: 0x759645d3dc
	public Void LoadAndInitData(ActivityEnemyDuelData actData, ActivityEnemyDuelModeData subModeData, String actId, EnemyDuelInput inputData) { }
	// RVA: 0x3e454f8 VA: 0x759645d4f8
	public Void PreparePlayerDataBeforeWaveStart(Int32 roundIndex, ActivityEnemyDuelRoundData roundData) { }
	// RVA: 0x3e45590 VA: 0x759645d590
	public Void ForceUpdateRoundAllStateData(EnemyDuelBattleStatus status) { }
	// RVA: 0x3e45ccc VA: 0x759645dccc
	public Void OnRoundChanged(Int32 roundIndex) { }
	// RVA: 0x3e45e6c VA: 0x759645de6c
	public Void UpdateRoundStateData(EnemyDuelBattleStatus status) { }
	// RVA: 0x3e45ff0 VA: 0x759645dff0
	public Void AssignPlayerDataDict(Dictionary`2 playerDataDict) { }
	// RVA: 0x3e46074 VA: 0x759645e074
	public Void AssignSelfPlayerData(EnemyDuelPlayerData playerData) { }
	// RVA: 0x3e460f8 VA: 0x759645e0f8
	public Void AddTeamData(EnemyDuelTeamData teamData) { }
	// RVA: 0x3e461f4 VA: 0x759645e1f4
	public Void RefreshTeamList() { }
	// RVA: 0x3e4629c VA: 0x759645e29c
	public Void OnSingleModeFinishRound(EnemyDuelRoundResult result, Int32 remainingRoundCnt) { }
	// RVA: 0x3e46690 VA: 0x759645e690
	public Void OnFinishGame() { }
	// RVA: 0x3e469a0 VA: 0x759645e9a0
	public Void OnGameQuit() { }
	// RVA: 0x3e46a14 VA: 0x759645ea14
	public Dictionary`2 GetPlayerDataDict() { }
	// RVA: 0x3e46a7c VA: 0x759645ea7c
	public EnemyDuelPlayerData GetSelfPlayerData() { }
	// RVA: 0x3e46ae4 VA: 0x759645eae4
	public List`1 GetTeamData(Boolean isLeft) { }
	// RVA: 0x3e46b9c VA: 0x759645eb9c
	public EnemyDuelBetData GetBetData() { }
	// RVA: 0x3e46c18 VA: 0x759645ec18
	public EnemyDuelSettleData GetSettleData() { }
	// RVA: 0x3e46c94 VA: 0x759645ec94
	public EnemyDuelSingleFinishSettle FetchSingleFinishOutput() { }
	// RVA: 0x3e45760 VA: 0x759645d760
	private Void _RefreshPlayerBetData(EnemyDuelBattleStatus status) { }
	// RVA: 0x3e45a18 VA: 0x759645da18
	private Void _RefreshPlayerSettleData(EnemyDuelBattleStatus status) { }
	// RVA: 0x3e46470 VA: 0x759645e470
	private Boolean _CheckGameOver() { }
	// RVA: 0x3e464f0 VA: 0x759645e4f0
	private Void _LogRoundPlayerResult() { }
	// RVA: 0x3e466f8 VA: 0x759645e6f8
	private Void _LogGameResult() { }
	// RVA: 0x3e46d4c VA: 0x759645ed4c
	public Void Dispose() { }
}
```