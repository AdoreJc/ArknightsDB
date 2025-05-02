# EnemyDuelBattleServer

**Namespace:** `Torappu.UI.EnemyDuel.Service.Mode.Multi`


## Fields

- `IEnemyDuelServerClient m_client`

- `BattleJoinEntry m_entry`

- `Boolean m_sceneAlready`

- `Boolean m_firstAfterJoin`

- `UInt32 m_receivedStep`

- `EnemyDuelServiceBattleEndInfo m_endInfo`

- `EnemyDuelServiceBattleInfo <battleInfo>k__BackingField`


## Properties

- `EnemyDuelServiceBattleInfo battleInfo`


## Methods

- `EnemyDuelServiceBattleInfo get_battleInfo()`

- `Void set_battleInfo(EnemyDuelServiceBattleInfo)`

- `Void Start(BattleJoinEntry)`

- `Void Stop()`

- `Void NotifySceneAlready()`

- `Void _DoJoin()`

- `Void _SetException(EnemyDuelServiceBattleException, Int32)`

- `Boolean _HandleJoinRet(Protocol)`

- `Boolean _HandleRevStep(Protocol)`

- `Boolean _HandleRevHistoryStep(Protocol)`

- `Void _DoRev(EnemyDuelServiceStepData)`

- `Boolean _HandleBattleStatusChanged(Protocol)`

- `Boolean _HandlerRoundSettle(Protocol)`

- `Boolean _HandleFinalSettle(Protocol)`

- `Boolean _HandleEmojiRev(Protocol)`

- `Boolean _HandleCheckSumRev(Protocol)`

- `Boolean _HandleSceneEnd(Protocol)`

- `Boolean _HandleQuitGame(Protocol)`

- `Void <>xLuaBaseProxy_OnNetStateChanged(ConnectionState)`

- `Void <>xLuaBaseProxy_OnConnectionLost(NetLostType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service.Mode.Multi
public class EnemyDuelBattleServer : Server
{
	private IEnemyDuelServerClient m_client; // 0x58
	private BattleJoinEntry m_entry; // 0x60
	private Boolean m_sceneAlready; // 0x78
	private Boolean m_firstAfterJoin; // 0x79
	private UInt32 m_receivedStep; // 0x7c
	private EnemyDuelServiceBattleEndInfo m_endInfo; // 0x80
	private EnemyDuelServiceBattleInfo <battleInfo>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_battleInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_battleInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_OnNetStateChanged; // 0x18
	private static DelegateBridge __Hotfix0_OnConnectionLost; // 0x20
	private static DelegateBridge __Hotfix0_Start; // 0x28
	private static DelegateBridge __Hotfix0_Stop; // 0x30
	private static DelegateBridge __Hotfix0_NotifySceneAlready; // 0x38
	private static DelegateBridge __Hotfix0__DoJoin; // 0x40
	private static DelegateBridge __Hotfix0__SetException; // 0x48
	private static DelegateBridge __Hotfix0__HandleJoinRet; // 0x50
	private static DelegateBridge __Hotfix0__HandleRevStep; // 0x58
	private static DelegateBridge __Hotfix0__HandleRevHistoryStep; // 0x60
	private static DelegateBridge __Hotfix0__DoRev; // 0x68
	private static DelegateBridge __Hotfix0__HandleBattleStatusChanged; // 0x70
	private static DelegateBridge __Hotfix0__HandlerRoundSettle; // 0x78
	private static DelegateBridge __Hotfix0__HandleFinalSettle; // 0x80
	private static DelegateBridge __Hotfix0__HandleEmojiRev; // 0x88
	private static DelegateBridge __Hotfix0__HandleCheckSumRev; // 0x90
	private static DelegateBridge __Hotfix0__HandleSceneEnd; // 0x98
	private static DelegateBridge __Hotfix0__HandleQuitGame; // 0xa0

	public EnemyDuelServiceBattleInfo battleInfo { get; set; }

	// RVA: 0x29aceac VA: 0x7594fc4eac
	public EnemyDuelServiceBattleInfo get_battleInfo() { }
	// RVA: 0x29b05fc VA: 0x7594fc85fc
	private Void set_battleInfo(EnemyDuelServiceBattleInfo value) { }
	// RVA: 0x29ad670 VA: 0x7594fc5670
	public Void .ctor(IEnemyDuelServerClient client) { }
	// RVA: 0x29b0680 VA: 0x7594fc8680
	protected override Void OnNetStateChanged(ConnectionState state) { }
	// RVA: 0x29b0874 VA: 0x7594fc8874
	protected override Void OnConnectionLost(NetLostType type) { }
	// RVA: 0x29ae2fc VA: 0x7594fc62fc
	public Void Start(BattleJoinEntry entry) { }
	// RVA: 0x29adda0 VA: 0x7594fc5da0
	public Void Stop() { }
	// RVA: 0x29ae698 VA: 0x7594fc6698
	public Void NotifySceneAlready() { }
	// RVA: 0x29b0714 VA: 0x7594fc8714
	private Void _DoJoin() { }
	// RVA: 0x29b0ac0 VA: 0x7594fc8ac0
	private Void _SetException(EnemyDuelServiceBattleException excpt, Int32 excptParam) { }
	// RVA: 0x29b0b4c VA: 0x7594fc8b4c
	private Boolean _HandleJoinRet(Protocol protocol) { }
	// RVA: 0x29b0d20 VA: 0x7594fc8d20
	private Boolean _HandleRevStep(Protocol protocol) { }
	// RVA: 0x29b1064 VA: 0x7594fc9064
	private Boolean _HandleRevHistoryStep(Protocol protocol) { }
	// RVA: 0x29b0df0 VA: 0x7594fc8df0
	private Void _DoRev(EnemyDuelServiceStepData step) { }
	// RVA: 0x29b1214 VA: 0x7594fc9214
	private Boolean _HandleBattleStatusChanged(Protocol protocol) { }
	// RVA: 0x29b1464 VA: 0x7594fc9464
	private Boolean _HandlerRoundSettle(Protocol protocol) { }
	// RVA: 0x29b14e0 VA: 0x7594fc94e0
	private Boolean _HandleFinalSettle(Protocol protocol) { }
	// RVA: 0x29b155c VA: 0x7594fc955c
	private Boolean _HandleEmojiRev(Protocol protocol) { }
	// RVA: 0x29b170c VA: 0x7594fc970c
	private Boolean _HandleCheckSumRev(Protocol protocol) { }
	// RVA: 0x29b1788 VA: 0x7594fc9788
	private Boolean _HandleSceneEnd(Protocol protocol) { }
	// RVA: 0x29b1868 VA: 0x7594fc9868
	private Boolean _HandleQuitGame(Protocol protocol) { }
	// RVA: 0x29b1970 VA: 0x7594fc9970
	private Void <>xLuaBaseProxy_OnNetStateChanged(ConnectionState P0) { }
	// RVA: 0x29b1978 VA: 0x7594fc9978
	private Void <>xLuaBaseProxy_OnConnectionLost(NetLostType P0) { }
}
```