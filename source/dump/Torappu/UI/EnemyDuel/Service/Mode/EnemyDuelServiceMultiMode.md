# EnemyDuelServiceMultiMode

**Namespace:** `Torappu.UI.EnemyDuel.Service.Mode`


## Fields

- `IEnemyDuelServiceCore m_serviceCore`

- `EnemyDuelTeamServer m_teamSvr`

- `EnemyDuelBattleServer m_battleSvr`

- `EnemyDuelProtocolSuit m_protocolSuite`

- `Server m_activeSvr`

- `EnemyDuelServiceRequestHandler m_handlers`


## Properties

- `Int32 ping`

- `DateTime currentTime`

- `EnemyDuelServiceTeamInfo teamInfo`

- `EnemyDuelServiceBattleInfo battleInfo`

- `EnemyDuelProtocolSuit protocolSuite`


## Methods

- `Int32 get_ping()`

- `DateTime get_currentTime()`

- `EnemyDuelServiceTeamInfo get_teamInfo()`

- `EnemyDuelServiceBattleInfo get_battleInfo()`

- `Void Init(IEnemyDuelServiceCore)`

- `Void Start(TeamJoinEntry)`

- `Void Dispose()`

- `Void Update()`

- `Void SendRequest(EnemyDuelServiceRequest)`

- `EnemyDuelProtocolSuit get_protocolSuite()`

- `Void RefreshServiceStatus()`

- `Void StartBattle(BattleJoinEntry)`

- `Void RevStep(EnemyDuelServiceStepData)`

- `Void TriggerEvent(EnemyDuelServiceEvent, Object)`

- `Boolean _HandleGameReady(EnemyDuelServiceBattleReadyRequest)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service.Mode
public class EnemyDuelServiceMultiMode : IEnemyDuelServiceMode, IHotfixable, IEnemyDuelServerClient
{
	private IEnemyDuelServiceCore m_serviceCore; // 0x10
	private EnemyDuelTeamServer m_teamSvr; // 0x18
	private EnemyDuelBattleServer m_battleSvr; // 0x20
	private EnemyDuelProtocolSuit m_protocolSuite; // 0x28
	private Server m_activeSvr; // 0x30
	private EnemyDuelServiceRequestHandler m_handlers; // 0x38
	private static DelegateBridge __Hotfix0_get_ping; // 0x0
	private static DelegateBridge __Hotfix0_get_currentTime; // 0x8
	private static DelegateBridge __Hotfix0_get_teamInfo; // 0x10
	private static DelegateBridge __Hotfix0_get_battleInfo; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_Start; // 0x28
	private static DelegateBridge __Hotfix0_Dispose; // 0x30
	private static DelegateBridge __Hotfix0_Update; // 0x38
	private static DelegateBridge __Hotfix0_SendRequest; // 0x40
	private static DelegateBridge __Hotfix0_get_protocolSuite; // 0x48
	private static DelegateBridge __Hotfix0_RefreshServiceStatus; // 0x50
	private static DelegateBridge __Hotfix0_StartBattle; // 0x58
	private static DelegateBridge __Hotfix0_RevStep; // 0x60
	private static DelegateBridge __Hotfix0_TriggerEvent; // 0x68
	private static DelegateBridge __Hotfix0__HandleGameReady; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Int32 ping { get; }
	public DateTime currentTime { get; }
	public EnemyDuelServiceTeamInfo teamInfo { get; }
	public EnemyDuelServiceBattleInfo battleInfo { get; }
	public EnemyDuelProtocolSuit protocolSuite { get; }

	// RVA: 0x29acc7c VA: 0x7594fc4c7c
	public Int32 get_ping() { }
	// RVA: 0x29accf0 VA: 0x7594fc4cf0
	public DateTime get_currentTime() { }
	// RVA: 0x29acd64 VA: 0x7594fc4d64
	public EnemyDuelServiceTeamInfo get_teamInfo() { }
	// RVA: 0x29ace3c VA: 0x7594fc4e3c
	public EnemyDuelServiceBattleInfo get_battleInfo() { }
	// RVA: 0x29acf14 VA: 0x7594fc4f14
	public Void Init(IEnemyDuelServiceCore core) { }
	// RVA: 0x29a4a2c VA: 0x7594fbca2c
	public Void Start(TeamJoinEntry entry) { }
	// RVA: 0x29adc8c VA: 0x7594fc5c8c
	public Void Dispose() { }
	// RVA: 0x29ade0c VA: 0x7594fc5e0c
	public Void Update() { }
	// RVA: 0x29ade90 VA: 0x7594fc5e90
	public Void SendRequest(EnemyDuelServiceRequest request) { }
	// RVA: 0x29ae094 VA: 0x7594fc6094
	public EnemyDuelProtocolSuit get_protocolSuite() { }
	// RVA: 0x29ae0fc VA: 0x7594fc60fc
	public Void RefreshServiceStatus() { }
	// RVA: 0x29ae214 VA: 0x7594fc6214
	public Void StartBattle(BattleJoinEntry entry) { }
	// RVA: 0x29ae41c VA: 0x7594fc641c
	public Void RevStep(EnemyDuelServiceStepData step) { }
	// RVA: 0x29ae510 VA: 0x7594fc6510
	public Void TriggerEvent(EnemyDuelServiceEvent evt, Object arg) { }
	// RVA: 0x29ae60c VA: 0x7594fc660c
	public Boolean _HandleGameReady(EnemyDuelServiceBattleReadyRequest req) { }
	// RVA: 0x29ae854 VA: 0x7594fc6854
	public Void .ctor() { }
}
```