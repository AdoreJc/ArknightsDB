# DialogController

**Namespace:** `Torappu.Battle.Dialog`


## Fields

- `AVGParser m_parser`

- `DirectAssetLoader m_assetLoader`

- `PeriodicTimer m_intervalTicker`

- `Action onSignalEnd`

- `String m_beforeBattleSignal`

- `String m_afterBattleSignal`

- `Boolean m_hasPlayedAfterBattleSignal`

- `Coroutine m_delayCoroutine`

- `Boolean m_gameHasFinished`

- `BattleStoryTree m_storyTree`

- `String m_currentSignal`

- `DialogControllerGameModePlugin m_modePlugin`

- `Blackboard m_blackboard`


## Properties

- `DirectAssetLoader assetLoader`

- `Boolean isPlaying`

- `BattleStoryTree storyTree`

- `Blackboard blackboard`

- `Boolean hasWaveBeforeBattle`

- `Boolean hasWaveAfterBattle`


## Methods

- `DirectAssetLoader get_assetLoader()`

- `Boolean get_isPlaying()`

- `BattleStoryTree get_storyTree()`

- `Boolean ExecuteCommandByIndex(ref, Int32, out)`

- `Void _InitCommandDicIfNot()`

- `Character _GetCharNpc(Command)`

- `Enemy _GetEnemyNpc(Command)`

- `Enemy _GetEnemyNpcByAlias(Command)`

- `Unit _GetNpc(Command)`

- `Unit _GetUnit(String)`

- `Boolean _DoExecuteActionArray(Command, String)`

- `Boolean DoExecuteActionArrayByBlackboard(Command, DialogueActionCommand)`

- `Void _MarkAsDialogTarget(Entity, Boolean)`

- `Void Init()`

- `Void StartDialogWithDelay(String, Single)`

- `IEnumerator _StartDialogDelayDialog(String, Single)`

- `Void StartDialog(String)`

- `Void StartDialog(String, Entity)`

- `Void StopCurrentDialog()`

- `Void OnTick(FP)`

- `Boolean TryStartPendingSourceSignal()`

- `Void AddSignalHook(String, String)`

- `Void TryStartPendingSignal()`

- `Boolean IsSignalValid(SignalWithSource)`

- `Boolean _DoStartSignal(BattleDialogType)`

- `Blackboard get_blackboard()`

- `IEnumerator EndDialog()`

- `Boolean _ExecuteEnd(Command)`

- `Boolean _ExecuteCondition(Command)`

- `Boolean _ExecutePredicate(Command)`

- `Boolean _ExecuteTrue(Command)`

- `Boolean _ExecuteHeader(Command)`

- `Boolean _ExecuteActionArray(Command)`

- `Boolean _ExecuteCreateEffect(Command)`

- `Boolean _ExecuteFinishEffect(Command)`

- `Boolean _ExecuteWithdrawById(Command)`

- `Boolean _ExecuteCameraFocusTo(Command)`

- `Boolean _ExecuteCameraScale(Command)`

- `Boolean _ExecutePlayAnim(Command)`

- `Boolean _ExecuteResetCamera(Command)`

- `Boolean _ExecuteSummonTrap(Command)`

- `Boolean _ExecuteSummonEnemy(Command)`

- `Boolean _ExecuteMoveEnemy(Command)`

- `Boolean _ExecuteEmoji(Command)`

- `Boolean _ExecuteChangeSignal(Command)`

- `Boolean _ExecuteTimeScale(Command)`

- `Boolean _ExecuteShake(Command)`

- `Boolean ExecuteCommand(Command)`

- `Void FinishGame()`

- `String GetBeforeBattleSignal()`

- `String GetAfterBattleSignal()`

- `Boolean CheckContainsValidAfterBattleSignal()`

- `Boolean get_hasWaveBeforeBattle()`

- `Boolean get_hasWaveAfterBattle()`

- `IEnumerator WaveBeforeBattle()`

- `IEnumerator WaveAfterBattle()`

- `Boolean <WaveBeforeBattle>b__85_0()`

- `Boolean <WaveBeforeBattle>b__85_1()`

- `Boolean <WaveAfterBattle>b__86_0()`

- `Boolean <WaveAfterBattle>b__86_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Dialog
public class DialogController : IHotfixable, IWavePlugin
{
	private AVGParser m_parser; // 0x10
	private DirectAssetLoader m_assetLoader; // 0x18
	private PeriodicTimer m_intervalTicker; // 0x20
	private ListDict`2 m_effects; // 0x28
	public Action`1 onSignalStart; // 0x30
	public Action onSignalEnd; // 0x38
	private String m_beforeBattleSignal; // 0x40
	private String m_afterBattleSignal; // 0x48
	private Boolean m_hasPlayedAfterBattleSignal; // 0x50
	private Coroutine m_delayCoroutine; // 0x58
	private Boolean m_gameHasFinished; // 0x60
	private ListDict`2 m_gameModePlugin; // 0x68
	private BattleStoryTree m_storyTree; // 0x70
	private List`1 m_pendingSignal; // 0x78
	private List`1 m_pendingSourceSignal; // 0x80
	private ListDict`2 m_signalHook; // 0x88
	private String m_currentSignal; // 0x90
	private DialogControllerGameModePlugin m_modePlugin; // 0x98
	private Dictionary`2 m_actionCommands; // 0xa0
	private Blackboard m_blackboard; // 0xa8
	private List`1 m_dialogTargets; // 0xb0
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x0
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x8
	private static DelegateBridge __Hotfix0_get_storyTree; // 0x10
	private static DelegateBridge __Hotfix0_ExecuteCommandByIndex; // 0x18
	private static DelegateBridge __Hotfix0__InitCommandDicIfNot; // 0x20
	private static DelegateBridge __Hotfix0__GetCharNpc; // 0x28
	private static DelegateBridge __Hotfix0__GetEnemyNpc; // 0x30
	private static DelegateBridge __Hotfix0__GetEnemyNpcByAlias; // 0x38
	private static DelegateBridge __Hotfix0__GetNpc; // 0x40
	private static DelegateBridge __Hotfix0__GetUnit; // 0x48
	private static DelegateBridge __Hotfix0__DoExecuteActionArray; // 0x50
	private static DelegateBridge __Hotfix0_DoExecuteActionArrayByBlackboard; // 0x58
	private static DelegateBridge __Hotfix0__MarkAsDialogTarget; // 0x60
	private static DelegateBridge __Hotfix0_Init; // 0x68
	private static DelegateBridge __Hotfix0_StartDialogWithDelay; // 0x70
	private static DelegateBridge __Hotfix0__StartDialogDelayDialog; // 0x78
	private static DelegateBridge __Hotfix0_StartDialog; // 0x80
	private static DelegateBridge __Hotfix1_StartDialog; // 0x88
	private static DelegateBridge __Hotfix0_StopCurrentDialog; // 0x90
	private static DelegateBridge __Hotfix0_OnTick; // 0x98
	private static DelegateBridge __Hotfix0_TryStartPendingSourceSignal; // 0xa0
	private static DelegateBridge __Hotfix0_AddSignalHook; // 0xa8
	private static DelegateBridge __Hotfix0_TryStartPendingSignal; // 0xb0
	private static DelegateBridge __Hotfix0_IsSignalValid; // 0xb8
	private static DelegateBridge __Hotfix0__DoStartSignal; // 0xc0
	private static DelegateBridge __Hotfix0_get_blackboard; // 0xc8
	private static DelegateBridge __Hotfix0_GetExecutors; // 0xd0
	private static DelegateBridge __Hotfix0_EndDialog; // 0xd8
	private static DelegateBridge __Hotfix0__ExecuteEnd; // 0xe0
	private static DelegateBridge __Hotfix0__ExecuteCondition; // 0xe8
	private static DelegateBridge __Hotfix0__ExecutePredicate; // 0xf0
	private static DelegateBridge __Hotfix0__ExecuteTrue; // 0xf8
	private static DelegateBridge __Hotfix0__ExecuteHeader; // 0x100
	private static DelegateBridge __Hotfix0__ExecuteActionArray; // 0x108
	private static DelegateBridge __Hotfix0__ExecuteCreateEffect; // 0x110
	private static DelegateBridge __Hotfix0__ExecuteFinishEffect; // 0x118
	private static DelegateBridge __Hotfix0__ExecuteWithdrawById; // 0x120
	private static DelegateBridge __Hotfix0__ExecuteCameraFocusTo; // 0x128
	private static DelegateBridge __Hotfix0__ExecuteCameraScale; // 0x130
	private static DelegateBridge __Hotfix0__ExecutePlayAnim; // 0x138
	private static DelegateBridge __Hotfix0__ExecuteResetCamera; // 0x140
	private static DelegateBridge __Hotfix0__ExecuteSummonTrap; // 0x148
	private static DelegateBridge __Hotfix0__ExecuteSummonEnemy; // 0x150
	private static DelegateBridge __Hotfix0__ExecuteMoveEnemy; // 0x158
	private static DelegateBridge __Hotfix0__ExecuteEmoji; // 0x160
	private static DelegateBridge __Hotfix0__ExecuteChangeSignal; // 0x168
	private static DelegateBridge __Hotfix0__ExecuteTimeScale; // 0x170
	private static DelegateBridge __Hotfix0__ExecuteShake; // 0x178
	private static DelegateBridge __Hotfix0_ExecuteCommand; // 0x180
	private static DelegateBridge __Hotfix0_ConstructOptionsFromCommand; // 0x188
	private static DelegateBridge __Hotfix0_FinishGame; // 0x190
	private static DelegateBridge __Hotfix0_GetBeforeBattleSignal; // 0x198
	private static DelegateBridge __Hotfix0_GetAfterBattleSignal; // 0x1a0
	private static DelegateBridge __Hotfix0_CheckContainsValidAfterBattleSignal; // 0x1a8
	private static DelegateBridge __Hotfix0_get_hasWaveBeforeBattle; // 0x1b0
	private static DelegateBridge __Hotfix0_get_hasWaveAfterBattle; // 0x1b8
	private static DelegateBridge __Hotfix0_WaveBeforeBattle; // 0x1c0
	private static DelegateBridge __Hotfix0_WaveAfterBattle; // 0x1c8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1d0

	public DirectAssetLoader assetLoader { get; }
	public Boolean isPlaying { get; }
	public BattleStoryTree storyTree { get; }
	public Blackboard blackboard { get; }
	public Boolean hasWaveBeforeBattle { get; }
	public Boolean hasWaveAfterBattle { get; }

	// RVA: 0x1d179c4 VA: 0x759432f9c4
	public DirectAssetLoader get_assetLoader() { }
	// RVA: 0x1d17a2c VA: 0x759432fa2c
	public Boolean get_isPlaying() { }
	// RVA: 0x1d17aa4 VA: 0x759432faa4
	public BattleStoryTree get_storyTree() { }
	// RVA: 0x1d17b0c VA: 0x759432fb0c
	public Boolean ExecuteCommandByIndex(ref Int32 commandIndex, Int32 decision, out Command command) { }
	// RVA: 0x1d17ce8 VA: 0x759432fce8
	private Void _InitCommandDicIfNot() { }
	// RVA: 0x1d17ee4 VA: 0x759432fee4
	private Character _GetCharNpc(Command command) { }
	// RVA: 0x1d18370 VA: 0x7594330370
	private Enemy _GetEnemyNpc(Command command) { }
	// RVA: 0x1d184dc VA: 0x75943304dc
	private Enemy _GetEnemyNpcByAlias(Command command) { }
	// RVA: 0x1d18978 VA: 0x7594330978
	private Unit _GetNpc(Command command) { }
	// RVA: 0x1d18000 VA: 0x7594330000
	private Unit _GetUnit(String id) { }
	// RVA: 0x1d18a44 VA: 0x7594330a44
	private Boolean _DoExecuteActionArray(Command command, String actionKey) { }
	// RVA: 0x1d18ba4 VA: 0x7594330ba4
	private Boolean DoExecuteActionArrayByBlackboard(Command command, DialogueActionCommand actionCommand) { }
	// RVA: 0x1d18ebc VA: 0x7594330ebc
	private Void _MarkAsDialogTarget(Entity entity, Boolean isDialogTarget) { }
	// RVA: 0x1d190c0 VA: 0x75943310c0
	public Void Init() { }
	// RVA: 0x1d19dec VA: 0x7594331dec
	public Void StartDialogWithDelay(String signal, Single delay) { }
	// RVA: 0x1d19ef0 VA: 0x7594331ef0
	public IEnumerator _StartDialogDelayDialog(String signal, Single delay) { }
	// RVA: 0x1d19fd8 VA: 0x7594331fd8
	public Void StartDialog(String signal) { }
	// RVA: 0x1d1a0f4 VA: 0x75943320f4
	public Void StartDialog(String signal, Entity source) { }
	// RVA: 0x1d1a248 VA: 0x7594332248
	public Void StopCurrentDialog() { }
	// RVA: 0x1d1a408 VA: 0x7594332408
	public Void OnTick(FP delatTime) { }
	// RVA: 0x1d1a570 VA: 0x7594332570
	private Boolean TryStartPendingSourceSignal() { }
	// RVA: 0x1d1abcc VA: 0x7594332bcc
	public Void AddSignalHook(String originSignal, String targetSignal) { }
	// RVA: 0x1d1a6d8 VA: 0x75943326d8
	private Void TryStartPendingSignal() { }
	// RVA: 0x1d1a7fc VA: 0x75943327fc
	public Boolean IsSignalValid(SignalWithSource signalWithSource) { }
	// RVA: 0x1d1a8f0 VA: 0x75943328f0
	private Boolean _DoStartSignal(BattleDialogType type) { }
	// RVA: 0x1d18b3c VA: 0x7594330b3c
	public Blackboard get_blackboard() { }
	// RVA: 0x1d19464 VA: 0x7594331464
	public Dictionary`2 GetExecutors() { }
	// RVA: 0x1d1acdc VA: 0x7594332cdc
	public IEnumerator EndDialog() { }
	// RVA: 0x1d1ad88 VA: 0x7594332d88
	private Boolean _ExecuteEnd(Command command) { }
	// RVA: 0x1d1b210 VA: 0x7594333210
	private Boolean _ExecuteCondition(Command command) { }
	// RVA: 0x1d1b334 VA: 0x7594333334
	private Boolean _ExecutePredicate(Command command) { }
	// RVA: 0x1d1b3b0 VA: 0x75943333b0
	private Boolean _ExecuteTrue(Command command) { }
	// RVA: 0x1d1b42c VA: 0x759433342c
	private Boolean _ExecuteHeader(Command command) { }
	// RVA: 0x1d1bae8 VA: 0x7594333ae8
	private Boolean _ExecuteActionArray(Command command) { }
	// RVA: 0x1d1bc58 VA: 0x7594333c58
	private Boolean _ExecuteCreateEffect(Command command) { }
	// RVA: 0x1d1bf40 VA: 0x7594333f40
	private Boolean _ExecuteFinishEffect(Command command) { }
	// RVA: 0x1d1c148 VA: 0x7594334148
	private Boolean _ExecuteWithdrawById(Command command) { }
	// RVA: 0x1d1c920 VA: 0x7594334920
	private Boolean _ExecuteCameraFocusTo(Command command) { }
	// RVA: 0x1d1cc30 VA: 0x7594334c30
	private Boolean _ExecuteCameraScale(Command command) { }
	// RVA: 0x1d1cdc0 VA: 0x7594334dc0
	private Boolean _ExecutePlayAnim(Command command) { }
	// RVA: 0x1d1d0f4 VA: 0x75943350f4
	private Boolean _ExecuteResetCamera(Command command) { }
	// RVA: 0x1d1d1e4 VA: 0x75943351e4
	private Boolean _ExecuteSummonTrap(Command command) { }
	// RVA: 0x1d1d4b8 VA: 0x75943354b8
	private Boolean _ExecuteSummonEnemy(Command command) { }
	// RVA: 0x1d1d774 VA: 0x7594335774
	private Boolean _ExecuteMoveEnemy(Command command) { }
	// RVA: 0x1d1dd30 VA: 0x7594335d30
	private Boolean _ExecuteEmoji(Command command) { }
	// RVA: 0x1d1dea0 VA: 0x7594335ea0
	private Boolean _ExecuteChangeSignal(Command command) { }
	// RVA: 0x1d1df88 VA: 0x7594335f88
	private Boolean _ExecuteTimeScale(Command command) { }
	// RVA: 0x1d1e09c VA: 0x759433609c
	private Boolean _ExecuteShake(Command command) { }
	// RVA: 0x1d17bdc VA: 0x759432fbdc
	public Boolean ExecuteCommand(Command command) { }
	// RVA: 0x1d1e2bc VA: 0x75943362bc
	public List`1 ConstructOptionsFromCommand(Command command) { }
	// RVA: 0x1d1e43c VA: 0x759433643c
	public Void FinishGame() { }
	// RVA: 0x1d19c94 VA: 0x7594331c94
	public String GetBeforeBattleSignal() { }
	// RVA: 0x1d19d40 VA: 0x7594331d40
	public String GetAfterBattleSignal() { }
	// RVA: 0x1d1e4e8 VA: 0x75943364e8
	public Boolean CheckContainsValidAfterBattleSignal() { }
	// RVA: 0x1d1e570 VA: 0x7594336570
	public Boolean get_hasWaveBeforeBattle() { }
	// RVA: 0x1d1e5e8 VA: 0x75943365e8
	public Boolean get_hasWaveAfterBattle() { }
	// RVA: 0x1d1e698 VA: 0x7594336698
	public IEnumerator WaveBeforeBattle() { }
	// RVA: 0x1d1e744 VA: 0x7594336744
	public IEnumerator WaveAfterBattle() { }
	// RVA: 0x1d1e7f0 VA: 0x75943367f0
	public Void .ctor() { }
	// RVA: 0x1d1ec5c VA: 0x7594336c5c
	private Boolean <WaveBeforeBattle>b__85_0() { }
	// RVA: 0x1d1ec74 VA: 0x7594336c74
	private Boolean <WaveBeforeBattle>b__85_1() { }
	// RVA: 0x1d1ec8c VA: 0x7594336c8c
	private Boolean <WaveAfterBattle>b__86_0() { }
	// RVA: 0x1d1eca4 VA: 0x7594336ca4
	private Boolean <WaveAfterBattle>b__86_1() { }
}
```