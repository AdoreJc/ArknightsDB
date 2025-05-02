# Act6FunGameMode

**Namespace:** ` `


## Fields

- `Boolean m_isMainEnemyFinished`

- `LevelPuzzlePack m_puzzlePack`

- `GridPosition m_lastMainEnemyGridPos`

- `Int32 m_coinCnt`

- `Int32 m_feverCoinCnt`

- `Boolean m_isCoinFever`


## Properties

- `Int32 coinCnt`

- `Boolean isCoinFever`


## Methods

- `Int32 get_coinCnt()`

- `Boolean get_isCoinFever()`

- `Void GainCoin()`

- `Void _ProcessActions()`

- `Boolean _TryExecuteOperation(CharacterAction, ref)`

- `Boolean _WithdrawInternal(Character)`

- `Boolean _TrigSkillInternal(Character)`

- `Boolean _TryTriggerActions(GridPosition)`

- `Void _AddCharacterActions(List`1)`

- `Boolean _TrySummonEnemyBranch(String)`

- `LevelPuzzlePack _GetLevelCharacterActionPack(String, ref)`

- `Void _ParseCameraFOV()`

- `Void _LoadPuzzleConfig()`

- `Void _GetFeverCoinCnt()`

- `Void _LogEnemyReachExit(Enemy)`

- `Void <>xLuaBaseProxy_PreprocessLevelData(LevelData)`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `String <>xLuaBaseProxy_HookTileAppendInfoKey(String)`

- `Void <>xLuaBaseProxy_StartGame(Action)`

- `Void <>xLuaBaseProxy_OnUnitRegistered(Unit)`

- `Void <>xLuaBaseProxy_OnEnemyFinished(Enemy, FinishReason)`

- `Boolean <>xLuaBaseProxy_GameNotFinishCondition()`

- `Void <>xLuaBaseProxy_OnPlayerLifeToZero(PlayerSide)`

- `Void <>xLuaBaseProxy_Tick(Action)`

- `Boolean <>xLuaBaseProxy_HookEnemyReachedExitAudio()`

- `Boolean <>xLuaBaseProxy_HookPlayAudioSignal(String, Unit, Boolean)`

- `Boolean <>xLuaBaseProxy_HookBattleFinishAudio(GameResult)`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act6FunGameMode : DefaultGameMode
{
	public const String ACT6FUN_UI_PLUGIN_PATH; // 0x0
	public const String ACT6FUN_CAMERA_PLUGIN_PATH; // 0x0
	public const String ACT6FUN_PUZZLE_CONFIG_PATH; // 0x0
	private const String ACT6FUN_MAIN_ENEMY_WAVE_NAME; // 0x0
	private static Dictionary`2 HOOKED_TILE_APPEND_INFO; // 0x0
	private const Int32 ENEMY_GAIN_COIN_CNT; // 0x0
	private const Single MIN_CAMERA_ASPECT; // 0x0
	private const Single MAX_CAMERA_ASPECT; // 0x0
	private const Single MIN_CAMERA_FOV; // 0x0
	private const Single MAX_CAMERA_FOV; // 0x0
	private ObjectPtr`1 m_mainEnemy; // 0x20
	private Boolean m_isMainEnemyFinished; // 0x30
	private LevelPuzzlePack m_puzzlePack; // 0x38
	private List`1 m_pendingCharacterActions; // 0x40
	private List`1 m_readyCharacterActions; // 0x48
	private GridPosition m_lastMainEnemyGridPos; // 0x50
	private Int32 m_coinCnt; // 0x58
	private Int32 m_feverCoinCnt; // 0x5c
	private Boolean m_isCoinFever; // 0x60
	private static DelegateBridge __Hotfix0_get_coinCnt; // 0x8
	private static DelegateBridge __Hotfix0_get_isCoinFever; // 0x10
	private static DelegateBridge __Hotfix0_GainCoin; // 0x18
	private static DelegateBridge __Hotfix0_PreprocessLevelData; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_HookTileAppendInfoKey; // 0x30
	private static DelegateBridge __Hotfix0_StartGame; // 0x38
	private static DelegateBridge __Hotfix0_OnUnitRegistered; // 0x40
	private static DelegateBridge __Hotfix0_OnEnemyFinished; // 0x48
	private static DelegateBridge __Hotfix0_GameNotFinishCondition; // 0x50
	private static DelegateBridge __Hotfix0_OnPlayerLifeToZero; // 0x58
	private static DelegateBridge __Hotfix0_Tick; // 0x60
	private static DelegateBridge __Hotfix0_HookEnemyReachedExitAudio; // 0x68
	private static DelegateBridge __Hotfix0_HookPlayAudioSignal; // 0x70
	private static DelegateBridge __Hotfix0_HookBattleFinishAudio; // 0x78
	private static DelegateBridge __Hotfix0__ProcessActions; // 0x80
	private static DelegateBridge __Hotfix0__TryExecuteOperation; // 0x88
	private static DelegateBridge __Hotfix0__WithdrawInternal; // 0x90
	private static DelegateBridge __Hotfix0__TrigSkillInternal; // 0x98
	private static DelegateBridge __Hotfix0__TryTriggerActions; // 0xa0
	private static DelegateBridge __Hotfix0__AddCharacterActions; // 0xa8
	private static DelegateBridge __Hotfix0__TrySummonEnemyBranch; // 0xb0
	private static DelegateBridge __Hotfix0__GetLevelCharacterActionPack; // 0xb8
	private static DelegateBridge __Hotfix0__ParseCameraFOV; // 0xc0
	private static DelegateBridge __Hotfix0__LoadPuzzleConfig; // 0xc8
	private static DelegateBridge __Hotfix0__GetFeverCoinCnt; // 0xd0
	private static DelegateBridge __Hotfix0__LogEnemyReachExit; // 0xd8
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	public Int32 coinCnt { get; }
	public Boolean isCoinFever { get; }
	public override GameModeType gameModeType { get; }

	// RVA: 0x1c8e0ac VA: 0x75942a60ac
	public Int32 get_coinCnt() { }
	// RVA: 0x1c8e124 VA: 0x75942a6124
	public Boolean get_isCoinFever() { }
	// RVA: 0x1c8e19c VA: 0x75942a619c
	public Void GainCoin() { }
	// RVA: 0x1c8e290 VA: 0x75942a6290
	public override Void PreprocessLevelData(LevelData levelData) { }
	// RVA: 0x1c8e464 VA: 0x75942a6464
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1c8eb94 VA: 0x75942a6b94
	public override String HookTileAppendInfoKey(String originTileKey) { }
	// RVA: 0x1c8ec7c VA: 0x75942a6c7c
	public override Void StartGame(Action doDefaultStart) { }
	// RVA: 0x1c8ee70 VA: 0x75942a6e70
	public override Void OnUnitRegistered(Unit unit) { }
	// RVA: 0x1c8f0d4 VA: 0x75942a70d4
	public override Void OnEnemyFinished(Enemy enemy, FinishReason reason) { }
	// RVA: 0x1c8f534 VA: 0x75942a7534
	public override Boolean GameNotFinishCondition() { }
	// RVA: 0x1c8f5b4 VA: 0x75942a75b4
	public override Void OnPlayerLifeToZero(PlayerSide side) { }
	// RVA: 0x1c8f63c VA: 0x75942a763c
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1c8fccc VA: 0x75942a7ccc
	public override Boolean HookEnemyReachedExitAudio() { }
	// RVA: 0x1c8fd8c VA: 0x75942a7d8c
	public override Boolean HookPlayAudioSignal(String ev, Unit unit, Boolean ignorePredefined) { }
	// RVA: 0x1c8ffa4 VA: 0x75942a7fa4
	public override Boolean HookBattleFinishAudio(GameResult result) { }
	// RVA: 0x1c8f9b8 VA: 0x75942a79b8
	private Void _ProcessActions() { }
	// RVA: 0x1c900b4 VA: 0x75942a80b4
	private Boolean _TryExecuteOperation(CharacterAction characterAction, ref Int32 indexInReadyList) { }
	// RVA: 0x1c90564 VA: 0x75942a8564
	private Boolean _WithdrawInternal(Character character) { }
	// RVA: 0x1c90678 VA: 0x75942a8678
	private Boolean _TrigSkillInternal(Character character) { }
	// RVA: 0x1c8f790 VA: 0x75942a7790
	private Boolean _TryTriggerActions(GridPosition pos) { }
	// RVA: 0x1c908dc VA: 0x75942a88dc
	private Void _AddCharacterActions(List`1 actions) { }
	// RVA: 0x1c90a70 VA: 0x75942a8a70
	private Boolean _TrySummonEnemyBranch(String branchId) { }
	// RVA: 0x1c90b58 VA: 0x75942a8b58
	private LevelPuzzlePack _GetLevelCharacterActionPack(String levelId, ref List`1 characterActionPacks) { }
	// RVA: 0x1c8e57c VA: 0x75942a657c
	private Void _ParseCameraFOV() { }
	// RVA: 0x1c8e740 VA: 0x75942a6740
	private Void _LoadPuzzleConfig() { }
	// RVA: 0x1c8ed28 VA: 0x75942a6d28
	private Void _GetFeverCoinCnt() { }
	// RVA: 0x1c8f280 VA: 0x75942a7280
	private Void _LogEnemyReachExit(Enemy enemy) { }
	// RVA: 0x1c90d00 VA: 0x75942a8d00
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1c8b9e8 VA: 0x75942a39e8
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1c90d78 VA: 0x75942a8d78
	private static Void .cctor() { }
	// RVA: 0x1c90eac VA: 0x75942a8eac
	private Void <>xLuaBaseProxy_PreprocessLevelData(LevelData P0) { }
	// RVA: 0x1c90eb4 VA: 0x75942a8eb4
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1c90ebc VA: 0x75942a8ebc
	private String <>xLuaBaseProxy_HookTileAppendInfoKey(String P0) { }
	// RVA: 0x1c90ec4 VA: 0x75942a8ec4
	private Void <>xLuaBaseProxy_StartGame(Action P0) { }
	// RVA: 0x1c90ecc VA: 0x75942a8ecc
	private Void <>xLuaBaseProxy_OnUnitRegistered(Unit P0) { }
	// RVA: 0x1c90ed4 VA: 0x75942a8ed4
	private Void <>xLuaBaseProxy_OnEnemyFinished(Enemy P0, FinishReason P1) { }
	// RVA: 0x1c90edc VA: 0x75942a8edc
	private Boolean <>xLuaBaseProxy_GameNotFinishCondition() { }
	// RVA: 0x1c90ee4 VA: 0x75942a8ee4
	private Void <>xLuaBaseProxy_OnPlayerLifeToZero(PlayerSide P0) { }
	// RVA: 0x1c90eec VA: 0x75942a8eec
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
	// RVA: 0x1c90ef4 VA: 0x75942a8ef4
	private Boolean <>xLuaBaseProxy_HookEnemyReachedExitAudio() { }
	// RVA: 0x1c90efc VA: 0x75942a8efc
	private Boolean <>xLuaBaseProxy_HookPlayAudioSignal(String P0, Unit P1, Boolean P2) { }
	// RVA: 0x1c90f08 VA: 0x75942a8f08
	private Boolean <>xLuaBaseProxy_HookBattleFinishAudio(GameResult P0) { }
	// RVA: 0x1c90f10 VA: 0x75942a8f10
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
}
```