# EnemyDuelUIPlugin

**Namespace:** `Torappu.Battle.UI.EnemyDuel`


## Fields

- `SpeedLevel m_defaultSpeedLevel`

- `ActivityEnemyDuelConstData m_constData`

- `EnemyDuelModeType m_modeType`

- `EnemyDuelServiceGameState m_curRoundState`

- `RoundTimerState m_timerState`

- `PeriodicTimer m_stateTimer`

- `Boolean m_isMultiPlayer`

- `EnemyDuelGameMode m_gameMode`


## Properties

- `EnemyDuelGameMode gameMode`


## Methods

- `EnemyDuelGameMode get_gameMode()`

- `Void OnRequestFinishGame()`

- `Void _HookUITopBar()`

- `Void _OnRoundStateChanged()`

- `Void _OnNextRoundWillStart()`

- `Void _OnBetStart()`

- `Void _OnRoundBattleStart()`

- `Void _OnRoundSettle()`

- `Void _SwitchTimeState(RoundTimerState)`

- `Void _HandleEnemyDuelBattleStart(Object)`

- `Void _HandleEnemyDuelBattleEnd(Object)`

- `Void _HandleBattleStatusChanged(Object)`

- `Void _Bet_TimeEnd()`

- `Void _Settle_TimeEnd()`

- `Void _RoundStartShow_TimeEnd()`

- `Void _OnPlayerBet(Object)`

- `Void _OnPlayerSendEmoji(Object)`

- `Void _HandleEmojiRev(Object)`

- `Void _HandleQuitRev(Object)`

- `Void FixedUpdate()`

- `Void OnDestroy()`

- `Void <OnGameReset>b__15_0(Object)`

- `Void <OnGameReset>b__15_1(Object)`

- `Void <OnDestroy>b__39_0(Object)`

- `Void <OnDestroy>b__39_1(Object)`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnGameStart()`

- `Void <>xLuaBaseProxy_OnGameReset(BattleController)`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Boolean <>xLuaBaseProxy_HookPauseMask(Boolean)`

- `Boolean <>xLuaBaseProxy_HookGameReadyStateSwitch()`

- `Boolean <>xLuaBaseProxy_HookGameStartStateSwitch()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.EnemyDuel
public class EnemyDuelUIPlugin : Plugin
{
	public static readonly UIStateEnum UI_STATE_BATTLE_START; // 0x0
	private List`1 _states; // 0x28
	private SpeedLevel m_defaultSpeedLevel; // 0x30
	private ActivityEnemyDuelConstData m_constData; // 0x38
	private EnemyDuelModeType m_modeType; // 0x40
	private EnemyDuelServiceGameState m_curRoundState; // 0x44
	private RoundTimerState m_timerState; // 0x48
	private PeriodicTimer m_stateTimer; // 0x50
	private Boolean m_isMultiPlayer; // 0x58
	private EnemyDuelGameMode m_gameMode; // 0x60
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x8
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x10
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x18
	private static DelegateBridge __Hotfix0_OnGameReset; // 0x20
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x28
	private static DelegateBridge __Hotfix0_HookPauseMask; // 0x30
	private static DelegateBridge __Hotfix0_HookGameReadyStateSwitch; // 0x38
	private static DelegateBridge __Hotfix0_HookGameStartStateSwitch; // 0x40
	private static DelegateBridge __Hotfix0_OnRequestFinishGame; // 0x48
	private static DelegateBridge __Hotfix0__HookUITopBar; // 0x50
	private static DelegateBridge __Hotfix0__OnRoundStateChanged; // 0x58
	private static DelegateBridge __Hotfix0__OnNextRoundWillStart; // 0x60
	private static DelegateBridge __Hotfix0__OnBetStart; // 0x68
	private static DelegateBridge __Hotfix0__OnRoundBattleStart; // 0x70
	private static DelegateBridge __Hotfix0__OnRoundSettle; // 0x78
	private static DelegateBridge __Hotfix0__SwitchTimeState; // 0x80
	private static DelegateBridge __Hotfix0__HandleEnemyDuelBattleStart; // 0x88
	private static DelegateBridge __Hotfix0__HandleEnemyDuelBattleEnd; // 0x90
	private static DelegateBridge __Hotfix0__HandleBattleStatusChanged; // 0x98
	private static DelegateBridge __Hotfix0__Bet_TimeEnd; // 0xa0
	private static DelegateBridge __Hotfix0__Settle_TimeEnd; // 0xa8
	private static DelegateBridge __Hotfix0__RoundStartShow_TimeEnd; // 0xb0
	private static DelegateBridge __Hotfix0__OnPlayerBet; // 0xb8
	private static DelegateBridge __Hotfix0__OnPlayerSendEmoji; // 0xc0
	private static DelegateBridge __Hotfix0__HandleEmojiRev; // 0xc8
	private static DelegateBridge __Hotfix0__HandleQuitRev; // 0xd0
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0xd8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	private EnemyDuelGameMode gameMode { get; }

	// RVA: 0x208e304 VA: 0x75946a6304
	private EnemyDuelGameMode get_gameMode() { }
	// RVA: 0x208e440 VA: 0x75946a6440
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x208e5f4 VA: 0x75946a65f4
	public override Void OnGameStart() { }
	// RVA: 0x208e7a4 VA: 0x75946a67a4
	public override Void OnGameReset(BattleController battleController) { }
	// RVA: 0x208eab4 VA: 0x75946a6ab4
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x208ec0c VA: 0x75946a6c0c
	public override Boolean HookPauseMask(Boolean isPause) { }
	// RVA: 0x208ec98 VA: 0x75946a6c98
	public override Boolean HookGameReadyStateSwitch() { }
	// RVA: 0x208ed74 VA: 0x75946a6d74
	public override Boolean HookGameStartStateSwitch() { }
	// RVA: 0x208edec VA: 0x75946a6dec
	public Void OnRequestFinishGame() { }
	// RVA: 0x208e554 VA: 0x75946a6554
	private Void _HookUITopBar() { }
	// RVA: 0x208ee8c VA: 0x75946a6e8c
	private Void _OnRoundStateChanged() { }
	// RVA: 0x208efa0 VA: 0x75946a6fa0
	private Void _OnNextRoundWillStart() { }
	// RVA: 0x208f0a8 VA: 0x75946a70a8
	private Void _OnBetStart() { }
	// RVA: 0x208f1d8 VA: 0x75946a71d8
	private Void _OnRoundBattleStart() { }
	// RVA: 0x208f274 VA: 0x75946a7274
	private Void _OnRoundSettle() { }
	// RVA: 0x208f3a4 VA: 0x75946a73a4
	private Void _SwitchTimeState(RoundTimerState newState) { }
	// RVA: 0x208f660 VA: 0x75946a7660
	private Void _HandleEnemyDuelBattleStart(Object arg) { }
	// RVA: 0x208f6f0 VA: 0x75946a76f0
	private Void _HandleEnemyDuelBattleEnd(Object arg) { }
	// RVA: 0x208f83c VA: 0x75946a783c
	private Void _HandleBattleStatusChanged(Object arg) { }
	// RVA: 0x208f560 VA: 0x75946a7560
	private Void _Bet_TimeEnd() { }
	// RVA: 0x208f5ec VA: 0x75946a75ec
	private Void _Settle_TimeEnd() { }
	// RVA: 0x208f4d4 VA: 0x75946a74d4
	private Void _RoundStartShow_TimeEnd() { }
	// RVA: 0x208f8d0 VA: 0x75946a78d0
	private Void _OnPlayerBet(Object arg) { }
	// RVA: 0x208f9e4 VA: 0x75946a79e4
	private Void _OnPlayerSendEmoji(Object arg) { }
	// RVA: 0x208faf4 VA: 0x75946a7af4
	private Void _HandleEmojiRev(Object args) { }
	// RVA: 0x208fbdc VA: 0x75946a7bdc
	private Void _HandleQuitRev(Object args) { }
	// RVA: 0x208fcd8 VA: 0x75946a7cd8
	private Void FixedUpdate() { }
	// RVA: 0x208fe58 VA: 0x75946a7e58
	public Void OnDestroy() { }
	// RVA: 0x2090144 VA: 0x75946a8144
	public Void .ctor() { }
	// RVA: 0x209020c VA: 0x75946a820c
	private static Void .cctor() { }
	// RVA: 0x2090258 VA: 0x75946a8258
	private Void <OnGameReset>b__15_0(Object arg) { }
	// RVA: 0x209025c VA: 0x75946a825c
	private Void <OnGameReset>b__15_1(Object arg) { }
	// RVA: 0x2090260 VA: 0x75946a8260
	private Void <OnDestroy>b__39_0(Object arg) { }
	// RVA: 0x2090264 VA: 0x75946a8264
	private Void <OnDestroy>b__39_1(Object arg) { }
	// RVA: 0x2090268 VA: 0x75946a8268
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x2090270 VA: 0x75946a8270
	private Void <>xLuaBaseProxy_OnGameStart() { }
	// RVA: 0x2090278 VA: 0x75946a8278
	private Void <>xLuaBaseProxy_OnGameReset(BattleController P0) { }
	// RVA: 0x2090280 VA: 0x75946a8280
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x2090288 VA: 0x75946a8288
	private Boolean <>xLuaBaseProxy_HookPauseMask(Boolean P0) { }
	// RVA: 0x2090294 VA: 0x75946a8294
	private Boolean <>xLuaBaseProxy_HookGameReadyStateSwitch() { }
	// RVA: 0x209029c VA: 0x75946a829c
	private Boolean <>xLuaBaseProxy_HookGameStartStateSwitch() { }
}
```