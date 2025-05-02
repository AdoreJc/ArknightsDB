# MultiplayerRealMode

**Namespace:** `Torappu.Multiplayer.Mode`


## Fields

- `MultiplayerMgr m_mgr`

- `ProtocolSuite m_suite`

- `TeamServer m_teamSvr`

- `BattleServer m_battleSvr`

- `Server m_statusSvr`

- `RequestHandlers m_reqHandlers`

- `CachedUserInfoForBattle m_cachedUserInfoForBattle`


## Properties

- `String playerUID`

- `TeamInfo teamInfo`

- `BattleInfo battleInfo`

- `String sceneId`

- `Int32 ping`

- `DateTime currentTime`

- `Object cachedUserInfoForBattle`

- `INetProtocolSuite protocolSuite`


## Methods

- `String get_playerUID()`

- `TeamInfo get_teamInfo()`

- `BattleInfo get_battleInfo()`

- `String get_sceneId()`

- `Int32 get_ping()`

- `DateTime get_currentTime()`

- `Object get_cachedUserInfoForBattle()`

- `Void Dispose()`

- `Void Init(MultiplayerMgr)`

- `Void Update()`

- `Void JoinTeam(TeamInst, TeamJoinFollower)`

- `Boolean SendRequest(RequestType, Object)`

- `Boolean _GameReady()`

- `Boolean _ReportSnapshot(GameCheckParam)`

- `Boolean _LeaveTeam()`

- `Boolean _TeamChat(EmojiChatParam)`

- `Boolean _KickPartner(String)`

- `Boolean _ChooseStage(ChooseStageParam)`

- `Boolean _ChoosePos(Int32)`

- `Boolean _ReadyInRoom(Boolean)`

- `Boolean _EntranceReady(Boolean)`

- `Boolean _TurnPick(Int32)`

- `Boolean _TurnSkip(Boolean)`

- `Boolean _SaveSquad(SaveSquadParam)`

- `Boolean _SetCharSlot(SetCharSlotParam)`

- `Boolean _SetSquadReady(Boolean)`

- `Boolean _TeamReady(Boolean)`

- `Boolean _TeamGetNameCard(String)`

- `Boolean _TeamSetFlipMode(Boolean)`

- `Boolean _SettleLike(String)`

- `Boolean _MatchContinueRoom()`

- `Boolean _SendAction(PlayerOprtData)`

- `Boolean _SendMark(GameMarkData)`

- `Boolean _GameSettle(GameSettleParam)`

- `Boolean _GamePause(GamePauseParam)`

- `Boolean _GameGiveUp(Boolean)`

- `Void UpdateTeamStatus()`

- `Void StartBattle(BattleEntry)`

- `Void UpdateBattleStatus(Boolean)`

- `Void RevStep(StepData)`

- `Void Alert(String, ShowCondition, ProcWhenForbid)`

- `INetProtocolSuite get_protocolSuite()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer.Mode
public class MultiplayerRealMode : IMultiplayerMode, IHotfixable, ITeamClient, IServerSupport, IBattleClient
{
	private MultiplayerMgr m_mgr; // 0x10
	private ProtocolSuite m_suite; // 0x18
	private TeamServer m_teamSvr; // 0x20
	private BattleServer m_battleSvr; // 0x28
	private Server m_statusSvr; // 0x30
	private RequestHandlers m_reqHandlers; // 0x38
	private CachedUserInfoForBattle m_cachedUserInfoForBattle; // 0x40
	private static DelegateBridge __Hotfix0_get_playerUID; // 0x0
	private static DelegateBridge __Hotfix0_get_teamInfo; // 0x8
	private static DelegateBridge __Hotfix0_get_battleInfo; // 0x10
	private static DelegateBridge __Hotfix0_get_sceneId; // 0x18
	private static DelegateBridge __Hotfix0_get_ping; // 0x20
	private static DelegateBridge __Hotfix0_get_currentTime; // 0x28
	private static DelegateBridge __Hotfix0_get_cachedUserInfoForBattle; // 0x30
	private static DelegateBridge __Hotfix0_Dispose; // 0x38
	private static DelegateBridge __Hotfix0_Init; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0_JoinTeam; // 0x50
	private static DelegateBridge __Hotfix0_SendRequest; // 0x58
	private static DelegateBridge __Hotfix0__GameReady; // 0x60
	private static DelegateBridge __Hotfix0__ReportSnapshot; // 0x68
	private static DelegateBridge __Hotfix0__LeaveTeam; // 0x70
	private static DelegateBridge __Hotfix0__TeamChat; // 0x78
	private static DelegateBridge __Hotfix0__KickPartner; // 0x80
	private static DelegateBridge __Hotfix0__ChooseStage; // 0x88
	private static DelegateBridge __Hotfix0__ChoosePos; // 0x90
	private static DelegateBridge __Hotfix0__ReadyInRoom; // 0x98
	private static DelegateBridge __Hotfix0__EntranceReady; // 0xa0
	private static DelegateBridge __Hotfix0__TurnPick; // 0xa8
	private static DelegateBridge __Hotfix0__TurnSkip; // 0xb0
	private static DelegateBridge __Hotfix0__SaveSquad; // 0xb8
	private static DelegateBridge __Hotfix0__SetCharSlot; // 0xc0
	private static DelegateBridge __Hotfix0__SetSquadReady; // 0xc8
	private static DelegateBridge __Hotfix0__TeamReady; // 0xd0
	private static DelegateBridge __Hotfix0__TeamGetNameCard; // 0xd8
	private static DelegateBridge __Hotfix0__TeamSetFlipMode; // 0xe0
	private static DelegateBridge __Hotfix0__SettleLike; // 0xe8
	private static DelegateBridge __Hotfix0__MatchContinueRoom; // 0xf0
	private static DelegateBridge __Hotfix0__SendAction; // 0xf8
	private static DelegateBridge __Hotfix0__SendMark; // 0x100
	private static DelegateBridge __Hotfix0__GameSettle; // 0x108
	private static DelegateBridge __Hotfix0__GamePause; // 0x110
	private static DelegateBridge __Hotfix0__GameGiveUp; // 0x118
	private static DelegateBridge __Hotfix0_UpdateTeamStatus; // 0x120
	private static DelegateBridge __Hotfix0_StartBattle; // 0x128
	private static DelegateBridge __Hotfix0_UpdateBattleStatus; // 0x130
	private static DelegateBridge __Hotfix0_RevStep; // 0x138
	private static DelegateBridge __Hotfix0_Alert; // 0x140
	private static DelegateBridge __Hotfix0_get_protocolSuite; // 0x148
	private static DelegateBridge __Hotfix0_get_eventPool; // 0x150
	private static DelegateBridge _c__Hotfix0_ctor; // 0x158

	public String playerUID { get; }
	public TeamInfo teamInfo { get; }
	public BattleInfo battleInfo { get; }
	public String sceneId { get; }
	public Int32 ping { get; }
	public DateTime currentTime { get; }
	public Object cachedUserInfoForBattle { get; }
	public INetProtocolSuite protocolSuite { get; }
	public EventPool`1 eventPool { get; }

	// RVA: 0x35a5654 VA: 0x7595bbd654
	public String get_playerUID() { }
	// RVA: 0x35a56c8 VA: 0x7595bbd6c8
	public TeamInfo get_teamInfo() { }
	// RVA: 0x35a5738 VA: 0x7595bbd738
	public BattleInfo get_battleInfo() { }
	// RVA: 0x35a57ac VA: 0x7595bbd7ac
	public String get_sceneId() { }
	// RVA: 0x35a5820 VA: 0x7595bbd820
	public Int32 get_ping() { }
	// RVA: 0x35a5894 VA: 0x7595bbd894
	public DateTime get_currentTime() { }
	// RVA: 0x35a5908 VA: 0x7595bbd908
	public Object get_cachedUserInfoForBattle() { }
	// RVA: 0x35a5970 VA: 0x7595bbd970
	public Void Dispose() { }
	// RVA: 0x35a5a1c VA: 0x7595bbda1c
	public Void Init(MultiplayerMgr mgr) { }
	// RVA: 0x35a6598 VA: 0x7595bbe598
	public Void Update() { }
	// RVA: 0x35a661c VA: 0x7595bbe61c
	public Void JoinTeam(TeamInst team, TeamJoinFollower follower) { }
	// RVA: 0x35a6704 VA: 0x7595bbe704
	public Boolean SendRequest(RequestType request, Object param) { }
	// RVA: 0x35a6798 VA: 0x7595bbe798
	public Boolean _GameReady() { }
	// RVA: 0x35a6814 VA: 0x7595bbe814
	public Boolean _ReportSnapshot(GameCheckParam check) { }
	// RVA: 0x35a69c8 VA: 0x7595bbe9c8
	private Boolean _LeaveTeam() { }
	// RVA: 0x35a6a58 VA: 0x7595bbea58
	private Boolean _TeamChat(EmojiChatParam param) { }
	// RVA: 0x35a6bb8 VA: 0x7595bbebb8
	private Boolean _KickPartner(String uid) { }
	// RVA: 0x35a6d00 VA: 0x7595bbed00
	private Boolean _ChooseStage(ChooseStageParam chooseStageParam) { }
	// RVA: 0x35a6e58 VA: 0x7595bbee58
	private Boolean _ChoosePos(Int32 pos) { }
	// RVA: 0x35a6f94 VA: 0x7595bbef94
	private Boolean _ReadyInRoom(Boolean isReady) { }
	// RVA: 0x35a70d4 VA: 0x7595bbf0d4
	private Boolean _EntranceReady(Boolean ready) { }
	// RVA: 0x35a7214 VA: 0x7595bbf214
	private Boolean _TurnPick(Int32 charInstId) { }
	// RVA: 0x35a7354 VA: 0x7595bbf354
	private Boolean _TurnSkip(Boolean skip) { }
	// RVA: 0x35a7498 VA: 0x7595bbf498
	private Boolean _SaveSquad(SaveSquadParam param) { }
	// RVA: 0x35a7834 VA: 0x7595bbf834
	private Boolean _SetCharSlot(SetCharSlotParam param) { }
	// RVA: 0x35a7980 VA: 0x7595bbf980
	private Boolean _SetSquadReady(Boolean isReady) { }
	// RVA: 0x35a7ac0 VA: 0x7595bbfac0
	private Boolean _TeamReady(Boolean ready) { }
	// RVA: 0x35a7c00 VA: 0x7595bbfc00
	private Boolean _TeamGetNameCard(String uid) { }
	// RVA: 0x35a7d48 VA: 0x7595bbfd48
	private Boolean _TeamSetFlipMode(Boolean flag) { }
	// RVA: 0x35a7e88 VA: 0x7595bbfe88
	private Boolean _SettleLike(String partnerUid) { }
	// RVA: 0x35a7fd0 VA: 0x7595bbffd0
	private Boolean _MatchContinueRoom() { }
	// RVA: 0x35a80f4 VA: 0x7595bc00f4
	private Boolean _SendAction(PlayerOprtData oprt) { }
	// RVA: 0x35a82ac VA: 0x7595bc02ac
	private Boolean _SendMark(GameMarkData param) { }
	// RVA: 0x35a8444 VA: 0x7595bc0444
	private Boolean _GameSettle(GameSettleParam settleInfo) { }
	// RVA: 0x35a8578 VA: 0x7595bc0578
	private Boolean _GamePause(GamePauseParam param) { }
	// RVA: 0x35a86b4 VA: 0x7595bc06b4
	private Boolean _GameGiveUp(Boolean giveUp) { }
	// RVA: 0x35a881c VA: 0x7595bc081c
	public Void UpdateTeamStatus() { }
	// RVA: 0x35a8920 VA: 0x7595bc0920
	public Void StartBattle(BattleEntry entry) { }
	// RVA: 0x35a8eb4 VA: 0x7595bc0eb4
	public Void UpdateBattleStatus(Boolean inBattle) { }
	// RVA: 0x35a8f60 VA: 0x7595bc0f60
	public Void RevStep(StepData step) { }
	// RVA: 0x35a8fec VA: 0x7595bc0fec
	public Void Alert(String content, ShowCondition condition, ProcWhenForbid proc) { }
	// RVA: 0x35a6960 VA: 0x7595bbe960
	public INetProtocolSuite get_protocolSuite() { }
	// RVA: 0x35a909c VA: 0x7595bc109c
	public EventPool`1 get_eventPool() { }
	// RVA: 0x35a9110 VA: 0x7595bc1110
	public Void .ctor() { }
}
```