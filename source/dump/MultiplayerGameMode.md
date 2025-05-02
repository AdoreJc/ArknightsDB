# MultiplayerGameMode

**Namespace:** ` `


## Fields

- `MultiplayerInput m_data`

- `InternalState m_state`


## Properties

- `InternalState state`

- `Boolean isPrepared`

- `Boolean isRunning`

- `Boolean isPlaying`


## Methods

- `InternalState get_state()`

- `Void set_state(InternalState)`

- `Boolean get_isPrepared()`

- `Boolean get_isRunning()`

- `Boolean get_isPlaying()`

- `Void SetReady()`

- `Void SetPrepared()`

- `Void SetPlaying()`

- `Void SetUnstable()`

- `Boolean NextFrame(Boolean)`

- `Void ApplyOprt(PlayerOprtData)`

- `Void _SendOprt(PlayerOperator, Signiture, GridPosition, Direction)`

- `Void _SendOprtCharacter(CharacterAction, Signiture, GridPosition, Direction)`

- `Boolean <>xLuaBaseProxy_get_allowManualTick()`

- `Boolean <>xLuaBaseProxy_get_isOnline()`

- `Boolean <>xLuaBaseProxy_get_isLargeMap()`

- `Boolean <>xLuaBaseProxy_get_isLowMemoryGameMode()`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `Void <>xLuaBaseProxy_StartGame(Action)`

- `Boolean <>xLuaBaseProxy_HookPlayerOp_Withdraw(Character)`

- `Boolean <>xLuaBaseProxy_HookPlayerOp_Spawn(UInt32, Direction, Tile)`

- `Boolean <>xLuaBaseProxy_HookPlayerOp_TrigSkill(Character)`

- `SpeedLevel <>xLuaBaseProxy_HookSpeedLevel(SpeedLevel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MultiplayerGameMode : DefaultGameMode, IMultiplayerGameMode, IGameMode, IHotfixable
{
	private readonly FrameData m_frameData; // 0x20
	private MultiplayerInput m_data; // 0x28
	private InternalState m_state; // 0x30
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_set_state; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_get_allowManualTick; // 0x18
	private static DelegateBridge __Hotfix0_get_isOnline; // 0x20
	private static DelegateBridge __Hotfix0_get_isLargeMap; // 0x28
	private static DelegateBridge __Hotfix0_get_isLowMemoryGameMode; // 0x30
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x38
	private static DelegateBridge __Hotfix0_Init; // 0x40
	private static DelegateBridge __Hotfix0_StartGame; // 0x48
	private static DelegateBridge __Hotfix0_HookPlayerOp_Withdraw; // 0x50
	private static DelegateBridge __Hotfix0_HookPlayerOp_Spawn; // 0x58
	private static DelegateBridge __Hotfix0_HookPlayerOp_TrigSkill; // 0x60
	private static DelegateBridge __Hotfix0_HookSpeedLevel; // 0x68
	private static DelegateBridge __Hotfix0_get_isPrepared; // 0x70
	private static DelegateBridge __Hotfix0_get_isRunning; // 0x78
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x80
	private static DelegateBridge __Hotfix0_SetReady; // 0x88
	private static DelegateBridge __Hotfix0_SetPrepared; // 0x90
	private static DelegateBridge __Hotfix0_SetPlaying; // 0x98
	private static DelegateBridge __Hotfix0_SetUnstable; // 0xa0
	private static DelegateBridge __Hotfix0_NextFrame; // 0xa8
	private static DelegateBridge __Hotfix0_ApplyOprt; // 0xb0
	private static DelegateBridge __Hotfix0__SendOprt; // 0xb8
	private static DelegateBridge __Hotfix0__SendOprtCharacter; // 0xc0

	private InternalState state { get; set; }
	public override Boolean allowManualTick { get; }
	public override Boolean isOnline { get; }
	public override Boolean isLargeMap { get; }
	public override Boolean isLowMemoryGameMode { get; }
	public override GameModeType gameModeType { get; }
	public Boolean isPrepared { get; }
	public Boolean isRunning { get; }
	public Boolean isPlaying { get; }

	// RVA: 0x1ced7d4 VA: 0x75943057d4
	private InternalState get_state() { }
	// RVA: 0x1ced89c VA: 0x759430589c
	private Void set_state(InternalState value) { }
	// RVA: 0x1ced978 VA: 0x7594305978
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1ceda40 VA: 0x7594305a40
	public override Boolean get_allowManualTick() { }
	// RVA: 0x1cedaa8 VA: 0x7594305aa8
	public override Boolean get_isOnline() { }
	// RVA: 0x1cedb10 VA: 0x7594305b10
	public override Boolean get_isLargeMap() { }
	// RVA: 0x1cedb78 VA: 0x7594305b78
	public override Boolean get_isLowMemoryGameMode() { }
	// RVA: 0x1cedbe0 VA: 0x7594305be0
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1cedc48 VA: 0x7594305c48
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1cedda8 VA: 0x7594305da8
	public override Void StartGame(Action doDefaultStart) { }
	// RVA: 0x1cede40 VA: 0x7594305e40
	public override Boolean HookPlayerOp_Withdraw(Character character) { }
	// RVA: 0x1cee110 VA: 0x7594306110
	public override Boolean HookPlayerOp_Spawn(UInt32 uniqueId, Direction direction, Tile tile) { }
	// RVA: 0x1cee280 VA: 0x7594306280
	public override Boolean HookPlayerOp_TrigSkill(Character character) { }
	// RVA: 0x1cee3a8 VA: 0x75943063a8
	public override SpeedLevel HookSpeedLevel(SpeedLevel originSpeedLevel) { }
	// RVA: 0x1cee424 VA: 0x7594306424
	public Boolean get_isPrepared() { }
	// RVA: 0x1cee494 VA: 0x7594306494
	public Boolean get_isRunning() { }
	// RVA: 0x1cedf68 VA: 0x7594305f68
	public Boolean get_isPlaying() { }
	// RVA: 0x1cee518 VA: 0x7594306518
	public Void SetReady() { }
	// RVA: 0x1cee584 VA: 0x7594306584
	public Void SetPrepared() { }
	// RVA: 0x1cee5f0 VA: 0x75943065f0
	public Void SetPlaying() { }
	// RVA: 0x1cee65c VA: 0x759430665c
	public Void SetUnstable() { }
	// RVA: 0x1cee6c8 VA: 0x75943066c8
	public Boolean NextFrame(Boolean additional) { }
	// RVA: 0x1cee7b8 VA: 0x75943067b8
	public Void ApplyOprt(PlayerOprtData oprt) { }
	// RVA: 0x1cee960 VA: 0x7594306960
	private Void _SendOprt(PlayerOperator oprt, Signiture sig, GridPosition grid, Direction dir) { }
	// RVA: 0x1cedfd8 VA: 0x7594305fd8
	private Void _SendOprtCharacter(CharacterAction oprt, Signiture sig, GridPosition grid, Direction dir) { }
	// RVA: 0x1ceea94 VA: 0x7594306a94
	private Boolean <>xLuaBaseProxy_get_allowManualTick() { }
	// RVA: 0x1ceea9c VA: 0x7594306a9c
	private Boolean <>xLuaBaseProxy_get_isOnline() { }
	// RVA: 0x1ceeaa4 VA: 0x7594306aa4
	private Boolean <>xLuaBaseProxy_get_isLargeMap() { }
	// RVA: 0x1ceeaac VA: 0x7594306aac
	private Boolean <>xLuaBaseProxy_get_isLowMemoryGameMode() { }
	// RVA: 0x1ceeab4 VA: 0x7594306ab4
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1ceeabc VA: 0x7594306abc
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1ceeac4 VA: 0x7594306ac4
	private Void <>xLuaBaseProxy_StartGame(Action P0) { }
	// RVA: 0x1ceeacc VA: 0x7594306acc
	private Boolean <>xLuaBaseProxy_HookPlayerOp_Withdraw(Character P0) { }
	// RVA: 0x1ceead4 VA: 0x7594306ad4
	private Boolean <>xLuaBaseProxy_HookPlayerOp_Spawn(UInt32 P0, Direction P1, Tile P2) { }
	// RVA: 0x1ceeadc VA: 0x7594306adc
	private Boolean <>xLuaBaseProxy_HookPlayerOp_TrigSkill(Character P0) { }
	// RVA: 0x1ceeae4 VA: 0x7594306ae4
	private SpeedLevel <>xLuaBaseProxy_HookSpeedLevel(SpeedLevel P0) { }
}
```