# Act27SideGameMode

**Namespace:** ` `


## Fields

- `Int32 m_totalTargetTilesCnt`

- `Int32 m_finishedTilesCnt`

- `FP m_maxPlayTime`


## Properties

- `Int32 totalTargetTilesCnt`

- `Int32 finishedTilesCnt`


## Methods

- `Int32 get_totalTargetTilesCnt()`

- `Int32 get_finishedTilesCnt()`

- `Void OnFinishedTileCntChanged(MechanismSideType, MechanismSideType)`

- `Void _CheckGameFinish()`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `Void <>xLuaBaseProxy_Tick(Action)`

- `Boolean <>xLuaBaseProxy_HookBattleFinishAudio(GameResult)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act27SideGameMode : DefaultGameMode
{
	public static readonly String ACT27SIDE_TILE_KEY; // 0x0
	public const String BATTLE_UI_PLUGIN_PATH; // 0x0
	private const String ACT27SIDE_BATTLE_WIN_SIGNAL; // 0x0
	private const String ACT27SIDE_BATTLE_LOSE_SIGNAL; // 0x0
	private Int32 m_totalTargetTilesCnt; // 0x20
	private Int32 m_finishedTilesCnt; // 0x24
	private FP m_maxPlayTime; // 0x28
	private static DelegateBridge __Hotfix0_get_totalTargetTilesCnt; // 0x8
	private static DelegateBridge __Hotfix0_get_finishedTilesCnt; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_Tick; // 0x30
	private static DelegateBridge __Hotfix0_HookBattleFinishAudio; // 0x38
	private static DelegateBridge __Hotfix0_OnFinishedTileCntChanged; // 0x40
	private static DelegateBridge __Hotfix0__CheckGameFinish; // 0x48

	public Int32 totalTargetTilesCnt { get; }
	public Int32 finishedTilesCnt { get; }
	public override GameModeType gameModeType { get; }

	// RVA: 0x1c8d804 VA: 0x75942a5804
	public Int32 get_totalTargetTilesCnt() { }
	// RVA: 0x1c8d87c VA: 0x75942a587c
	public Int32 get_finishedTilesCnt() { }
	// RVA: 0x1c8b950 VA: 0x75942a3950
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1c8d8f4 VA: 0x75942a58f4
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1c8d96c VA: 0x75942a596c
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1c8dbb4 VA: 0x75942a5bb4
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1c8de1c VA: 0x75942a5e1c
	public override Boolean HookBattleFinishAudio(GameResult result) { }
	// RVA: 0x1c8df24 VA: 0x75942a5f24
	public Void OnFinishedTileCntChanged(MechanismSideType prevSideType, MechanismSideType targetSideType) { }
	// RVA: 0x1c8dc50 VA: 0x75942a5c50
	private Void _CheckGameFinish() { }
	// RVA: 0x1c8e020 VA: 0x75942a6020
	private static Void .cctor() { }
	// RVA: 0x1c8e08c VA: 0x75942a608c
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1c8e094 VA: 0x75942a6094
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1c8e09c VA: 0x75942a609c
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
	// RVA: 0x1c8e0a4 VA: 0x75942a60a4
	private Boolean <>xLuaBaseProxy_HookBattleFinishAudio(GameResult P0) { }
}
```