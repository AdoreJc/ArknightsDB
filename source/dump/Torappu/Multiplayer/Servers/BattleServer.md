# BattleServer

**Namespace:** `Torappu.Multiplayer.Servers`


## Fields

- `IBattleClient m_client`

- `BattleEntry m_entry`

- `Boolean m_already`

- `UInt32 m_receivedStep`

- `Boolean m_indetical`

- `GameSettleParam m_settleReq`

- `BattleInfo <battleInfo>k__BackingField`

- `GameSettleInfo m_settle`


## Properties

- `String sceneId`

- `BattleInfo battleInfo`


## Methods

- `String get_sceneId()`

- `BattleInfo get_battleInfo()`

- `Void set_battleInfo(BattleInfo)`

- `Void Start(BattleEntry)`

- `Void Close()`

- `Void NotifySceneAlready()`

- `Void Settle(GameSettleParam)`

- `Void _DoJoin()`

- `Boolean _HandleJoinRet(Protocol)`

- `Boolean _HandleRevStep(Protocol)`

- `Boolean _HandleRevHistoryStep(Protocol)`

- `Void _DoRev(StepData)`

- `Boolean _HandleCheckRet(Protocol)`

- `Boolean _HandleRevPause(Protocol)`

- `Boolean _HandleRevMark(Protocol)`

- `Boolean _HandlePlayerStatusChanged(Protocol)`

- `Boolean _HandleSceneEnd(Protocol)`

- `Boolean _HandleQuitGame(Protocol)`

- `Void _SetLogUpload()`

- `Void <>xLuaBaseProxy_OnNetStateChanged(ConnectionState)`

- `Void <>xLuaBaseProxy_OnConnectionLost(NetLostType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer.Servers
public class BattleServer : Server
{
	private IBattleClient m_client; // 0x58
	private BattleEntry m_entry; // 0x60
	private Boolean m_already; // 0x78
	private UInt32 m_receivedStep; // 0x7c
	private Boolean m_indetical; // 0x80
	private GameSettleParam m_settleReq; // 0x88
	private BattleInfo <battleInfo>k__BackingField; // 0x90
	private GameSettleInfo m_settle; // 0x98
	private static DelegateBridge __Hotfix0_get_sceneId; // 0x0
	private static DelegateBridge __Hotfix0_get_battleInfo; // 0x8
	private static DelegateBridge __Hotfix0_set_battleInfo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18
	private static DelegateBridge __Hotfix0_OnNetStateChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnConnectionLost; // 0x28
	private static DelegateBridge __Hotfix0_Start; // 0x30
	private static DelegateBridge __Hotfix0_Close; // 0x38
	private static DelegateBridge __Hotfix0_NotifySceneAlready; // 0x40
	private static DelegateBridge __Hotfix0_Settle; // 0x48
	private static DelegateBridge __Hotfix0__DoJoin; // 0x50
	private static DelegateBridge __Hotfix0__HandleJoinRet; // 0x58
	private static DelegateBridge __Hotfix0__HandleRevStep; // 0x60
	private static DelegateBridge __Hotfix0__HandleRevHistoryStep; // 0x68
	private static DelegateBridge __Hotfix0__DoRev; // 0x70
	private static DelegateBridge __Hotfix0__HandleCheckRet; // 0x78
	private static DelegateBridge __Hotfix0__HandleRevPause; // 0x80
	private static DelegateBridge __Hotfix0__HandleRevMark; // 0x88
	private static DelegateBridge __Hotfix0__HandlePlayerStatusChanged; // 0x90
	private static DelegateBridge __Hotfix0__HandleGameSettle; // 0x98
	private static DelegateBridge __Hotfix0__HandleSceneEnd; // 0xa0
	private static DelegateBridge __Hotfix0__HandleQuitGame; // 0xa8
	private static DelegateBridge __Hotfix0__SetLogUpload; // 0xb0

	public String sceneId { get; }
	public BattleInfo battleInfo { get; set; }

	// RVA: 0x35952ac VA: 0x7595bad2ac
	public String get_sceneId() { }
	// RVA: 0x3595314 VA: 0x7595bad314
	public BattleInfo get_battleInfo() { }
	// RVA: 0x359537c VA: 0x7595bad37c
	private Void set_battleInfo(BattleInfo value) { }
	// RVA: 0x3595400 VA: 0x7595bad400
	public Void .ctor(IBattleClient cliet) { }
	// RVA: 0x3595900 VA: 0x7595bad900
	protected override Void OnNetStateChanged(ConnectionState state) { }
	// RVA: 0x3595b64 VA: 0x7595badb64
	protected override Void OnConnectionLost(NetLostType type) { }
	// RVA: 0x3595fe8 VA: 0x7595badfe8
	public Void Start(BattleEntry entry) { }
	// RVA: 0x3596134 VA: 0x7595bae134
	public Void Close() { }
	// RVA: 0x35961a0 VA: 0x7595bae1a0
	public Void NotifySceneAlready() { }
	// RVA: 0x359636c VA: 0x7595bae36c
	public Void Settle(GameSettleParam info) { }
	// RVA: 0x3595994 VA: 0x7595bad994
	private Void _DoJoin() { }
	// RVA: 0x35965d8 VA: 0x7595bae5d8
	private Boolean _HandleJoinRet(Protocol protocol) { }
	// RVA: 0x35967d4 VA: 0x7595bae7d4
	private Boolean _HandleRevStep(Protocol protocol) { }
	// RVA: 0x3596b04 VA: 0x7595baeb04
	private Boolean _HandleRevHistoryStep(Protocol protocol) { }
	// RVA: 0x35968a4 VA: 0x7595bae8a4
	private Void _DoRev(StepData step) { }
	// RVA: 0x3596cb0 VA: 0x7595baecb0
	private Boolean _HandleCheckRet(Protocol protocol) { }
	// RVA: 0x3596d30 VA: 0x7595baed30
	private Boolean _HandleRevPause(Protocol protocol) { }
	// RVA: 0x3596f84 VA: 0x7595baef84
	private Boolean _HandleRevMark(Protocol protocol) { }
	// RVA: 0x3597118 VA: 0x7595baf118
	private Boolean _HandlePlayerStatusChanged(Protocol protocol) { }
	// RVA: 0x359741c VA: 0x7595baf41c
	internal Boolean _HandleGameSettle(Protocol protocol) { }
	// RVA: 0x3597514 VA: 0x7595baf514
	private Boolean _HandleSceneEnd(Protocol protocol) { }
	// RVA: 0x35975f8 VA: 0x7595baf5f8
	private Boolean _HandleQuitGame(Protocol protocol) { }
	// RVA: 0x3595eac VA: 0x7595badeac
	private Void _SetLogUpload() { }
	// RVA: 0x359767c VA: 0x7595baf67c
	private Void <>xLuaBaseProxy_OnNetStateChanged(ConnectionState P0) { }
	// RVA: 0x3597684 VA: 0x7595baf684
	private Void <>xLuaBaseProxy_OnConnectionLost(NetLostType P0) { }
}
```