# AutoChessLoadState

**Namespace:** ` `


## Fields

- `Boolean m_inited`

- `Single m_estimateRecycleTime`

- `AutoChessGameState m_cachedState`

- `IEnumerator m_loadCoroutine`

- `BattleAudioLoader m_audioLoader`


## Properties

- `ResourceCollectHandler collectHandler`

- `BattleAudioLoader audioLoader`


## Methods

- `ResourceCollectHandler get_collectHandler()`

- `BattleAudioLoader get_audioLoader()`

- `Boolean _NeedReroute()`

- `Void _InitLevelAndInitBattleStatus()`

- `Void _LoadResAndContinue()`

- `Void _RouteFirstState()`

- `Void _ProcessPredefines(Boolean)`

- `Void _ActiveUtilTraps()`

- `Void _ClearAll()`

- `Void _InjectMagicTokenInstToLevelData(List`1)`

- `Void _FinishShopStatePredefined()`

- `Void _AllocatePoolConfigsIfNot()`

- `Void _AddPaddingPreload()`

- `IEnumerator _LoadForBattle(Boolean)`

- `IEnumerator _ResetBattle()`

- `IEnumerator _LoadForShop(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AutoChessLoadState : AutoChessGameStateBase
{
	private static List`1 s_unitCache; // 0x0
	private const Single FINISH_DUMMY_TIME; // 0x0
	private const Single MIX_TIMING; // 0x0
	private const Single TRAP_ACPLANE_ANIM_TIME; // 0x0
	private const Single CAMERA_MOVE_TIME; // 0x0
	private const Single LOAD_BREAK_TIME; // 0x0
	private Boolean m_inited; // 0x10
	private Single m_estimateRecycleTime; // 0x14
	private AutoChessGameState m_cachedState; // 0x18
	private IEnumerator m_loadCoroutine; // 0x20
	private BattleAudioLoader m_audioLoader; // 0x28
	private List`1 m_configs; // 0x30
	private List`1 m_configsForBattle; // 0x38

	public override GameState currentState { get; }
	private ResourceCollectHandler collectHandler { get; }
	private BattleAudioLoader audioLoader { get; }

	// RVA: 0x1cae388 VA: 0x75942c6388
	public override GameState get_currentState() { }
	// RVA: 0x1cae390 VA: 0x75942c6390
	private ResourceCollectHandler get_collectHandler() { }
	// RVA: 0x1cae3f0 VA: 0x75942c63f0
	private BattleAudioLoader get_audioLoader() { }
	// RVA: 0x1cae4c8 VA: 0x75942c64c8
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1cae820 VA: 0x75942c6820
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1cae980 VA: 0x75942c6980
	private Boolean _NeedReroute() { }
	// RVA: 0x1caea18 VA: 0x75942c6a18
	private Void _InitLevelAndInitBattleStatus() { }
	// RVA: 0x1cae688 VA: 0x75942c6688
	private Void _LoadResAndContinue() { }
	// RVA: 0x1cae510 VA: 0x75942c6510
	private Void _RouteFirstState() { }
	// RVA: 0x1caec8c VA: 0x75942c6c8c
	private Void _ProcessPredefines(Boolean isFirstState) { }
	// RVA: 0x1caee9c VA: 0x75942c6e9c
	private Void _ActiveUtilTraps() { }
	// RVA: 0x1cae824 VA: 0x75942c6824
	private Void _ClearAll() { }
	// RVA: 0x1caeff0 VA: 0x75942c6ff0
	private Void _InjectMagicTokenInstToLevelData(List`1 battleChess) { }
	// RVA: 0x1caf168 VA: 0x75942c7168
	private Void _FinishShopStatePredefined() { }
	// RVA: 0x1caf3ac VA: 0x75942c73ac
	private Void _AllocatePoolConfigsIfNot() { }
	// RVA: 0x1caf558 VA: 0x75942c7558
	private Void _AddPaddingPreload() { }
	// RVA: 0x1caec04 VA: 0x75942c6c04
	private IEnumerator _LoadForBattle(Boolean isFirstState) { }
	// RVA: 0x1caf744 VA: 0x75942c7744
	private IEnumerator _ResetBattle() { }
	// RVA: 0x1caeb7c VA: 0x75942c6b7c
	private IEnumerator _LoadForShop(Boolean isFirstState) { }
	// RVA: 0x1caf808 VA: 0x75942c7808
	public Void .ctor() { }
	// RVA: 0x1caf8c8 VA: 0x75942c78c8
	private static Void .cctor() { }
}
```