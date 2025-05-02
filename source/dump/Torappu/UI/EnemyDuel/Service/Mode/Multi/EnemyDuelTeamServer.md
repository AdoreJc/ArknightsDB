# EnemyDuelTeamServer

**Namespace:** `Torappu.UI.EnemyDuel.Service.Mode.Multi`


## Fields

- `IEnemyDuelServerClient m_client`

- `TeamJoinEntry m_entry`

- `EnemyDuelServiceTeamInfo <teamInfo>k__BackingField`


## Properties

- `EnemyDuelServiceTeamInfo teamInfo`


## Methods

- `EnemyDuelServiceTeamInfo get_teamInfo()`

- `Void set_teamInfo(EnemyDuelServiceTeamInfo)`

- `Void Start(TeamJoinEntry)`

- `Void Stop()`

- `Void _DoJoinTeam()`

- `Void _TryInvokeFollower(Boolean)`

- `Boolean _JoinResult(Protocol)`

- `Boolean _LeaveResult(Protocol)`

- `Boolean _UpdateTeamStatus(Protocol)`

- `Boolean _HandleBattleStart(Protocol)`

- `Void _EnterBattle(STDuelSceneInfo)`

- `Boolean _HandleKickRet(Protocol)`

- `Boolean _HandleGetNameCard(Protocol)`

- `Boolean _HandlePlayerStateChanged(Protocol)`

- `Boolean _HandlePlayerConnStateChanged(Protocol)`

- `Boolean _HandlePlayerNew(Protocol)`

- `Void <>xLuaBaseProxy_OnNetStateChanged(ConnectionState)`

- `Void <>xLuaBaseProxy_OnConnectionLost(NetLostType)`

- `Void <>xLuaBaseProxy_OnHandleFailedParseMsg(NetMsgID)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service.Mode.Multi
public class EnemyDuelTeamServer : Server
{
	private IEnemyDuelServerClient m_client; // 0x58
	private TeamJoinEntry m_entry; // 0x60
	private EnemyDuelServiceTeamInfo <teamInfo>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_teamInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_teamInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_OnNetStateChanged; // 0x18
	private static DelegateBridge __Hotfix0_OnConnectionLost; // 0x20
	private static DelegateBridge __Hotfix0_OnHandleFailedParseMsg; // 0x28
	private static DelegateBridge __Hotfix0_Start; // 0x30
	private static DelegateBridge __Hotfix0_Stop; // 0x38
	private static DelegateBridge __Hotfix0__DoJoinTeam; // 0x40
	private static DelegateBridge __Hotfix0__TryInvokeFollower; // 0x48
	private static DelegateBridge __Hotfix0__JoinResult; // 0x50
	private static DelegateBridge __Hotfix0__LeaveResult; // 0x58
	private static DelegateBridge __Hotfix0__UpdateTeamStatus; // 0x60
	private static DelegateBridge __Hotfix0__HandleBattleStart; // 0x68
	private static DelegateBridge __Hotfix0__EnterBattle; // 0x70
	private static DelegateBridge __Hotfix0__HandleKickRet; // 0x78
	private static DelegateBridge __Hotfix0__HandleGetNameCard; // 0x80
	private static DelegateBridge __Hotfix0__HandlePlayerStateChanged; // 0x88
	private static DelegateBridge __Hotfix0__HandlePlayerConnStateChanged; // 0x90
	private static DelegateBridge __Hotfix0__HandlePlayerNew; // 0x98

	public EnemyDuelServiceTeamInfo teamInfo { get; set; }

	// RVA: 0x29acdd4 VA: 0x7594fc4dd4
	public EnemyDuelServiceTeamInfo get_teamInfo() { }
	// RVA: 0x29b1980 VA: 0x7594fc9980
	private Void set_teamInfo(EnemyDuelServiceTeamInfo value) { }
	// RVA: 0x29ad1dc VA: 0x7594fc51dc
	public Void .ctor(IEnemyDuelServerClient client) { }
	// RVA: 0x29b1a04 VA: 0x7594fc9a04
	protected override Void OnNetStateChanged(ConnectionState state) { }
	// RVA: 0x29b1bec VA: 0x7594fc9bec
	protected override Void OnConnectionLost(NetLostType type) { }
	// RVA: 0x29b1eac VA: 0x7594fc9eac
	protected override Void OnHandleFailedParseMsg(NetMsgID msgId) { }
	// RVA: 0x29adbac VA: 0x7594fc5bac
	public Void Start(TeamJoinEntry entry) { }
	// RVA: 0x29add34 VA: 0x7594fc5d34
	public Void Stop() { }
	// RVA: 0x29b1a98 VA: 0x7594fc9a98
	private Void _DoJoinTeam() { }
	// RVA: 0x29b1e00 VA: 0x7594fc9e00
	private Void _TryInvokeFollower(Boolean suc) { }
	// RVA: 0x29b1f60 VA: 0x7594fc9f60
	private Boolean _JoinResult(Protocol protocol) { }
	// RVA: 0x29b2068 VA: 0x7594fca068
	private Boolean _LeaveResult(Protocol protocol) { }
	// RVA: 0x29b2174 VA: 0x7594fca174
	private Boolean _UpdateTeamStatus(Protocol protocol) { }
	// RVA: 0x29b2534 VA: 0x7594fca534
	private Boolean _HandleBattleStart(Protocol protocol) { }
	// RVA: 0x29b23b4 VA: 0x7594fca3b4
	private Void _EnterBattle(STDuelSceneInfo scene) { }
	// RVA: 0x29b2628 VA: 0x7594fca628
	private Boolean _HandleKickRet(Protocol protocol) { }
	// RVA: 0x29b27b4 VA: 0x7594fca7b4
	private Boolean _HandleGetNameCard(Protocol protocol) { }
	// RVA: 0x29b2924 VA: 0x7594fca924
	private Boolean _HandlePlayerStateChanged(Protocol protocol) { }
	// RVA: 0x29b2c0c VA: 0x7594fcac0c
	private Boolean _HandlePlayerConnStateChanged(Protocol protocol) { }
	// RVA: 0x29b2f28 VA: 0x7594fcaf28
	private Boolean _HandlePlayerNew(Protocol protocol) { }
	// RVA: 0x29b31a4 VA: 0x7594fcb1a4
	private Void <>xLuaBaseProxy_OnNetStateChanged(ConnectionState P0) { }
	// RVA: 0x29b31ac VA: 0x7594fcb1ac
	private Void <>xLuaBaseProxy_OnConnectionLost(NetLostType P0) { }
	// RVA: 0x29b31b4 VA: 0x7594fcb1b4
	private Void <>xLuaBaseProxy_OnHandleFailedParseMsg(NetMsgID P0) { }
}
```