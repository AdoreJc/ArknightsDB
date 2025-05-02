# Act20SideGameMode

**Namespace:** ` `


## Fields

- `Act20SideUIPlugin m_uiPlugin`

- `FP m_maxPlayTime`

- `Int32 m_score`


## Properties

- `FP maxPlayTime`

- `Int32 score`


## Methods

- `FP get_maxPlayTime()`

- `Int32 get_score()`

- `Void IncreaseScore(Int32)`

- `Void AssignUIPlugin(Act20SideUIPlugin)`

- `Void _CheckGameFinish()`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `Void <>xLuaBaseProxy_Tick(Action)`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act20SideGameMode : DefaultGameMode
{
	public const String BATTLE_UI_PLUGIN_PATH; // 0x0
	private Act20SideUIPlugin m_uiPlugin; // 0x20
	private FP m_maxPlayTime; // 0x28
	private Int32 m_score; // 0x30
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x0
	private static DelegateBridge __Hotfix0_get_maxPlayTime; // 0x8
	private static DelegateBridge __Hotfix0_get_score; // 0x10
	private static DelegateBridge __Hotfix0_IncreaseScore; // 0x18
	private static DelegateBridge __Hotfix0_AssignUIPlugin; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_Tick; // 0x30
	private static DelegateBridge __Hotfix0__CheckGameFinish; // 0x38
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override GameModeType gameModeType { get; }
	public FP maxPlayTime { get; }
	public Int32 score { get; }

	// RVA: 0x1c8d154 VA: 0x75942a5154
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1c8d1bc VA: 0x75942a51bc
	public FP get_maxPlayTime() { }
	// RVA: 0x1c8d224 VA: 0x75942a5224
	public Int32 get_score() { }
	// RVA: 0x1c8d28c VA: 0x75942a528c
	public Void IncreaseScore(Int32 value) { }
	// RVA: 0x1c8d374 VA: 0x75942a5374
	public Void AssignUIPlugin(Act20SideUIPlugin uiPlugin) { }
	// RVA: 0x1c8d3f8 VA: 0x75942a53f8
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1c8d4fc VA: 0x75942a54fc
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1c8d590 VA: 0x75942a5590
	private Void _CheckGameFinish() { }
	// RVA: 0x1c8d74c VA: 0x75942a574c
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1c8b8c8 VA: 0x75942a38c8
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1c8d7e4 VA: 0x75942a57e4
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1c8d7ec VA: 0x75942a57ec
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1c8d7f4 VA: 0x75942a57f4
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
	// RVA: 0x1c8d7fc VA: 0x75942a57fc
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
}
```