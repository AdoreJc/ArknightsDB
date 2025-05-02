# EnemyDuelServiceSingleMode

**Namespace:** `Torappu.UI.EnemyDuel.Service.Mode`


## Fields

- `IEnemyDuelServiceCore m_serviceCore`

- `EnemyDuelServiceTeamInfo <teamInfo>k__BackingField`

- `EnemyDuelServiceBattleInfo <battleInfo>k__BackingField`

- `ActivityEnemyDuelData m_actData`

- `EnemyDuelBattleStatus m_battleStatus`

- `EnemyDuelServiceRequestHandler m_handlers`

- `Int64 m_forEndTime`

- `String playerId`

- `Int32 m_remainRoundCnt`

- `Boolean m_isFinalSettle`


## Properties

- `Int32 ping`

- `DateTime currentTime`

- `EnemyDuelServiceTeamInfo teamInfo`

- `EnemyDuelServiceBattleInfo battleInfo`


## Methods

- `Int32 get_ping()`

- `DateTime get_currentTime()`

- `EnemyDuelServiceTeamInfo get_teamInfo()`

- `Void set_teamInfo(EnemyDuelServiceTeamInfo)`

- `EnemyDuelServiceBattleInfo get_battleInfo()`

- `Void set_battleInfo(EnemyDuelServiceBattleInfo)`

- `Void Init(IEnemyDuelServiceCore)`

- `Void Dispose()`

- `Void Start(SingleBattleEntry)`

- `Void Update()`

- `Void SendRequest(EnemyDuelServiceRequest)`

- `Void _ChangeToEntry()`

- `Void _ChangeToBet()`

- `Void _ChangeToBattle()`

- `Void _ChangeToRoundSettle(Boolean)`

- `Void _ChangeToFinish()`

- `Void _UpdateBattleStatus()`

- `Void _UpdateEndTs(Single, Single, Single)`

- `Int32 _GenRandSeed()`

- `Void _CloseService()`

- `Int64 _GenFutureTs(Single, Single, Single)`

- `Boolean _HandleGameReady(EnemyDuelServiceBattleReadyRequest)`

- `Boolean _HandleBet(EnemyDuelServiceBattleBetRequest)`

- `Boolean _HandleRoundSettle(EnemyDuelServiceBattleRoundSettleRequest)`

- `Boolean _HandleFinalSettle(EnemyDuelServiceBattleFinalSettleRequest)`

- `Boolean _HandleEmotion(EnemyDuelServiceBattleEmotionRequest)`

- `Boolean _HandleGameQuit(EnemyDuelServiceBattleQuitRequest)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service.Mode
public class EnemyDuelServiceSingleMode : IEnemyDuelServiceMode, IHotfixable
{
	private IEnemyDuelServiceCore m_serviceCore; // 0x10
	private EnemyDuelServiceTeamInfo <teamInfo>k__BackingField; // 0x18
	private EnemyDuelServiceBattleInfo <battleInfo>k__BackingField; // 0x20
	private ActivityEnemyDuelData m_actData; // 0x28
	private EnemyDuelBattleStatus m_battleStatus; // 0x30
	private EnemyDuelServiceRequestHandler m_handlers; // 0x58
	private Int64 m_forEndTime; // 0x60
	private String playerId; // 0x68
	private Int32 m_remainRoundCnt; // 0x70
	private Boolean m_isFinalSettle; // 0x74
	private static DelegateBridge __Hotfix0_get_ping; // 0x0
	private static DelegateBridge __Hotfix0_get_currentTime; // 0x8
	private static DelegateBridge __Hotfix0_get_teamInfo; // 0x10
	private static DelegateBridge __Hotfix0_set_teamInfo; // 0x18
	private static DelegateBridge __Hotfix0_get_battleInfo; // 0x20
	private static DelegateBridge __Hotfix0_set_battleInfo; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x30
	private static DelegateBridge __Hotfix0_Dispose; // 0x38
	private static DelegateBridge __Hotfix0_Start; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0_SendRequest; // 0x50
	private static DelegateBridge __Hotfix0__ChangeToEntry; // 0x58
	private static DelegateBridge __Hotfix0__ChangeToBet; // 0x60
	private static DelegateBridge __Hotfix0__ChangeToBattle; // 0x68
	private static DelegateBridge __Hotfix0__ChangeToRoundSettle; // 0x70
	private static DelegateBridge __Hotfix0__ChangeToFinish; // 0x78
	private static DelegateBridge __Hotfix0__UpdateBattleStatus; // 0x80
	private static DelegateBridge __Hotfix0__UpdateEndTs; // 0x88
	private static DelegateBridge __Hotfix0__GenRandSeed; // 0x90
	private static DelegateBridge __Hotfix0__CloseService; // 0x98
	private static DelegateBridge __Hotfix0__GenFutureTs; // 0xa0
	private static DelegateBridge __Hotfix0__HandleGameReady; // 0xa8
	private static DelegateBridge __Hotfix0__HandleBet; // 0xb0
	private static DelegateBridge __Hotfix0__HandleRoundSettle; // 0xb8
	private static DelegateBridge __Hotfix0__HandleFinalSettle; // 0xc0
	private static DelegateBridge __Hotfix0__HandleEmotion; // 0xc8
	private static DelegateBridge __Hotfix0__HandleGameQuit; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	public Int32 ping { get; }
	public DateTime currentTime { get; }
	public EnemyDuelServiceTeamInfo teamInfo { get; set; }
	public EnemyDuelServiceBattleInfo battleInfo { get; set; }

	// RVA: 0x29ae93c VA: 0x7594fc693c
	public Int32 get_ping() { }
	// RVA: 0x29ae9a0 VA: 0x7594fc69a0
	public DateTime get_currentTime() { }
	// RVA: 0x29aea2c VA: 0x7594fc6a2c
	public EnemyDuelServiceTeamInfo get_teamInfo() { }
	// RVA: 0x29aea94 VA: 0x7594fc6a94
	private Void set_teamInfo(EnemyDuelServiceTeamInfo value) { }
	// RVA: 0x29aeb18 VA: 0x7594fc6b18
	public EnemyDuelServiceBattleInfo get_battleInfo() { }
	// RVA: 0x29aeb80 VA: 0x7594fc6b80
	private Void set_battleInfo(EnemyDuelServiceBattleInfo value) { }
	// RVA: 0x29aec04 VA: 0x7594fc6c04
	public Void Init(IEnemyDuelServiceCore host) { }
	// RVA: 0x29af028 VA: 0x7594fc7028
	public Void Dispose() { }
	// RVA: 0x29a4ba8 VA: 0x7594fbcba8
	public Void Start(SingleBattleEntry entry) { }
	// RVA: 0x29af4d4 VA: 0x7594fc74d4
	public Void Update() { }
	// RVA: 0x29afce0 VA: 0x7594fc7ce0
	public Void SendRequest(EnemyDuelServiceRequest request) { }
	// RVA: 0x29af9a0 VA: 0x7594fc79a0
	private Void _ChangeToEntry() { }
	// RVA: 0x29af60c VA: 0x7594fc760c
	private Void _ChangeToBet() { }
	// RVA: 0x29af73c VA: 0x7594fc773c
	private Void _ChangeToBattle() { }
	// RVA: 0x29af7d8 VA: 0x7594fc77d8
	private Void _ChangeToRoundSettle(Boolean auto) { }
	// RVA: 0x29af91c VA: 0x7594fc791c
	private Void _ChangeToFinish() { }
	// RVA: 0x29af320 VA: 0x7594fc7320
	private Void _UpdateBattleStatus() { }
	// RVA: 0x29afd9c VA: 0x7594fc7d9c
	private Void _UpdateEndTs(Single hours, Single minutes, Single second) { }
	// RVA: 0x29af188 VA: 0x7594fc7188
	private Int32 _GenRandSeed() { }
	// RVA: 0x29af08c VA: 0x7594fc708c
	private Void _CloseService() { }
	// RVA: 0x29af1f8 VA: 0x7594fc71f8
	private Int64 _GenFutureTs(Single hours, Single minutes, Single second) { }
	// RVA: 0x29afe4c VA: 0x7594fc7e4c
	private Boolean _HandleGameReady(EnemyDuelServiceBattleReadyRequest request) { }
	// RVA: 0x29afed8 VA: 0x7594fc7ed8
	private Boolean _HandleBet(EnemyDuelServiceBattleBetRequest request) { }
	// RVA: 0x29b015c VA: 0x7594fc815c
	private Boolean _HandleRoundSettle(EnemyDuelServiceBattleRoundSettleRequest request) { }
	// RVA: 0x29b01f4 VA: 0x7594fc81f4
	private Boolean _HandleFinalSettle(EnemyDuelServiceBattleFinalSettleRequest request) { }
	// RVA: 0x29b0320 VA: 0x7594fc8320
	private Boolean _HandleEmotion(EnemyDuelServiceBattleEmotionRequest request) { }
	// RVA: 0x29b0460 VA: 0x7594fc8460
	private Boolean _HandleGameQuit(EnemyDuelServiceBattleQuitRequest request) { }
	// RVA: 0x29b0564 VA: 0x7594fc8564
	public Void .ctor() { }
}
```