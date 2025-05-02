# TeamServer

**Namespace:** `Torappu.Multiplayer.Servers`


## Fields

- `TeamInst m_team`

- `TeamJoinFollower m_joinFollower`

- `TeamInfo <teamInfo>k__BackingField`

- `TeamChatParam m_chatParam`


## Properties

- `TeamInfo teamInfo`


## Methods

- `TeamInfo get_teamInfo()`

- `Void set_teamInfo(TeamInfo)`

- `Void Start(TeamInst, TeamJoinFollower)`

- `Void Close()`

- `Void _DoJoin()`

- `Void _TryInvokeFollower(Boolean)`

- `Boolean _JoinResult(Protocol)`

- `Void _AlertConnectFailed()`

- `Boolean _LeaveResult(Protocol)`

- `Boolean _HandleChatRet(Protocol)`

- `Boolean _HandlePickRet(Protocol)`

- `Boolean _UpdateTeamStatus(Protocol)`

- `Boolean _HandleBattleStart(Protocol)`

- `Void _EnterBattle(STSceneInfo)`

- `Boolean _HandleKickRet(Protocol)`

- `Boolean _HandleSetCharSlotRet(Protocol)`

- `Boolean _HandleSaveSquadRet(Protocol)`

- `Boolean _HandleChooseStageRet(Protocol)`

- `Boolean _HandleGetNameCard(Protocol)`

- `Boolean _HandleSetFlipModeRet(Protocol)`

- `Boolean _HandleSettleLikeRet(Protocol)`

- `Boolean _HandlePlayerStateChanged(Protocol)`

- `Boolean _HandlePlayerConnChanged(Protocol)`

- `STPlayerStatus _GetPlayerStatus(String)`

- `Void <>xLuaBaseProxy_OnNetStateChanged(ConnectionState)`

- `Void <>xLuaBaseProxy_OnConnectionLost(NetLostType)`

- `Void <>xLuaBaseProxy_OnHandleFailedParseMsg(NetMsgID)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer.Servers
public class TeamServer : Server
{
	private TeamInst m_team; // 0x58
	private TeamJoinFollower m_joinFollower; // 0x60
	private TeamInfo <teamInfo>k__BackingField; // 0x68
	private readonly ITeamClient m_client; // 0x70
	private TeamChatParam m_chatParam; // 0x78
	private static DelegateBridge __Hotfix0_get_teamInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_teamInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_OnNetStateChanged; // 0x18
	private static DelegateBridge __Hotfix0_OnConnectionLost; // 0x20
	private static DelegateBridge __Hotfix0_OnHandleFailedParseMsg; // 0x28
	private static DelegateBridge __Hotfix0_Start; // 0x30
	private static DelegateBridge __Hotfix0_Close; // 0x38
	private static DelegateBridge __Hotfix0__DoJoin; // 0x40
	private static DelegateBridge __Hotfix0__TryInvokeFollower; // 0x48
	private static DelegateBridge __Hotfix0__JoinResult; // 0x50
	private static DelegateBridge __Hotfix0__AlertConnectFailed; // 0x58
	private static DelegateBridge __Hotfix0__LeaveResult; // 0x60
	private static DelegateBridge __Hotfix0__HandleChatRet; // 0x68
	private static DelegateBridge __Hotfix0__HandlePickRet; // 0x70
	private static DelegateBridge __Hotfix0__UpdateTeamStatus; // 0x78
	private static DelegateBridge __Hotfix0__HandleBattleStart; // 0x80
	private static DelegateBridge __Hotfix0__EnterBattle; // 0x88
	private static DelegateBridge __Hotfix0__HandleKickRet; // 0x90
	private static DelegateBridge __Hotfix0__HandleSetCharSlotRet; // 0x98
	private static DelegateBridge __Hotfix0__HandleSaveSquadRet; // 0xa0
	private static DelegateBridge __Hotfix0__HandleChooseStageRet; // 0xa8
	private static DelegateBridge __Hotfix0__HandleGetNameCard; // 0xb0
	private static DelegateBridge __Hotfix0__HandleSetFlipModeRet; // 0xb8
	private static DelegateBridge __Hotfix0__HandleSettleLikeRet; // 0xc0
	private static DelegateBridge __Hotfix0__HandlePlayerStateChanged; // 0xc8
	private static DelegateBridge __Hotfix0__HandlePlayerConnChanged; // 0xd0
	private static DelegateBridge __Hotfix0__GetPlayerStatus; // 0xd8

	public TeamInfo teamInfo { get; set; }

	// RVA: 0x35a2490 VA: 0x7595bba490
	public TeamInfo get_teamInfo() { }
	// RVA: 0x35a24f8 VA: 0x7595bba4f8
	private Void set_teamInfo(TeamInfo value) { }
	// RVA: 0x35a257c VA: 0x7595bba57c
	public Void .ctor(ITeamClient client) { }
	// RVA: 0x35a2c38 VA: 0x7595bbac38
	protected override Void OnNetStateChanged(ConnectionState state) { }
	// RVA: 0x35a2eac VA: 0x7595bbaeac
	protected override Void OnConnectionLost(NetLostType type) { }
	// RVA: 0x35a3264 VA: 0x7595bbb264
	protected override Void OnHandleFailedParseMsg(NetMsgID msgId) { }
	// RVA: 0x35a3324 VA: 0x7595bbb324
	public Void Start(TeamInst team, TeamJoinFollower follower) { }
	// RVA: 0x35a3448 VA: 0x7595bbb448
	public Void Close() { }
	// RVA: 0x35a2ccc VA: 0x7595bbaccc
	private Void _DoJoin() { }
	// RVA: 0x35a31b4 VA: 0x7595bbb1b4
	private Void _TryInvokeFollower(Boolean suc) { }
	// RVA: 0x35a34b4 VA: 0x7595bbb4b4
	private Boolean _JoinResult(Protocol protocol) { }
	// RVA: 0x35a3024 VA: 0x7595bbb024
	private Void _AlertConnectFailed() { }
	// RVA: 0x35a35c4 VA: 0x7595bbb5c4
	private Boolean _LeaveResult(Protocol protocol) { }
	// RVA: 0x35a3720 VA: 0x7595bbb720
	private Boolean _HandleChatRet(Protocol protocol) { }
	// RVA: 0x35a3924 VA: 0x7595bbb924
	private Boolean _HandlePickRet(Protocol protocol) { }
	// RVA: 0x35a3ac8 VA: 0x7595bbbac8
	private Boolean _UpdateTeamStatus(Protocol protocol) { }
	// RVA: 0x35a3ec8 VA: 0x7595bbbec8
	private Boolean _HandleBattleStart(Protocol protocol) { }
	// RVA: 0x35a3d48 VA: 0x7595bbbd48
	private Void _EnterBattle(STSceneInfo scene) { }
	// RVA: 0x35a404c VA: 0x7595bbc04c
	private Boolean _HandleKickRet(Protocol protocol) { }
	// RVA: 0x35a429c VA: 0x7595bbc29c
	private Boolean _HandleSetCharSlotRet(Protocol protocol) { }
	// RVA: 0x35a4448 VA: 0x7595bbc448
	private Boolean _HandleSaveSquadRet(Protocol protocol) { }
	// RVA: 0x35a45dc VA: 0x7595bbc5dc
	private Boolean _HandleChooseStageRet(Protocol protocol) { }
	// RVA: 0x35a4758 VA: 0x7595bbc758
	private Boolean _HandleGetNameCard(Protocol protocol) { }
	// RVA: 0x35a4a74 VA: 0x7595bbca74
	private Boolean _HandleSetFlipModeRet(Protocol protocol) { }
	// RVA: 0x35a4bd0 VA: 0x7595bbcbd0
	private Boolean _HandleSettleLikeRet(Protocol protocol) { }
	// RVA: 0x35a4ed8 VA: 0x7595bbced8
	private Boolean _HandlePlayerStateChanged(Protocol protocol) { }
	// RVA: 0x35a5028 VA: 0x7595bbd028
	private Boolean _HandlePlayerConnChanged(Protocol protocol) { }
	// RVA: 0x35a4d20 VA: 0x7595bbcd20
	private STPlayerStatus _GetPlayerStatus(String uid) { }
	// RVA: 0x35a5178 VA: 0x7595bbd178
	private Void <>xLuaBaseProxy_OnNetStateChanged(ConnectionState P0) { }
	// RVA: 0x35a5180 VA: 0x7595bbd180
	private Void <>xLuaBaseProxy_OnConnectionLost(NetLostType P0) { }
	// RVA: 0x35a5188 VA: 0x7595bbd188
	private Void <>xLuaBaseProxy_OnHandleFailedParseMsg(NetMsgID P0) { }
}
```