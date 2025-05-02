# BattleVerboseRecorder

**Namespace:** `Torappu.Battle`


## Fields

- `DebugPrinter m_debugPrinter`

- `FileLogger m_logger`


## Methods

- `Void _OnAppliedModifier(Object)`

- `Void _OnSkillCast(Object)`

- `Void _OnUnitBorn(Object)`

- `Void _OnRallyPointReborn(Object)`

- `Void _OnUnitFinish(Object)`

- `Void _OnBuffStart(Object)`

- `Void _OnBuffFinish(Object)`

- `Void _OnSnapShot(Object)`

- `Void _OnPlayerOperation(Object)`

- `Void _OnGiveUpGame(Object)`

- `Void OnGameReady()`

- `Void OnGameReset(BattleController)`

- `Void OnGameInit(Options)`

- `Void OnGameStart()`

- `Void OnGameOver(GameResult)`

- `Void _AppendLog(LogItem)`

- `SourceOrTargetRef _AnalyzeComplexSource(ref, ref)`

- `Void _ResetLogger()`

- `Void _ReleaseLogger()`

- `String _GetFileFormat()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleVerboseRecorder : IBattleModule
{
	private const String SAVE_DIR; // 0x0
	private const String FILENAME_FORMAT; // 0x0
	private const String MULTIPLAYER_SIDE_A_FILENAME_FORMAT; // 0x0
	private const String MULTIPLAYER_SIDE_B_FILENAME_FORMAT; // 0x0
	private List`1 m_detailLogs; // 0x10
	private DebugPrinter m_debugPrinter; // 0x18
	private FileLogger m_logger; // 0x20


	// RVA: 0x3fe3334 VA: 0x75965fb334
	public static String GetLogDirPath() { }
	// RVA: 0x3fe3378 VA: 0x75965fb378
	private Void _OnAppliedModifier(Object arg) { }
	// RVA: 0x3fe4194 VA: 0x75965fc194
	private Void _OnSkillCast(Object arg) { }
	// RVA: 0x3fe440c VA: 0x75965fc40c
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x3fe4770 VA: 0x75965fc770
	private Void _OnRallyPointReborn(Object arg) { }
	// RVA: 0x3fe49bc VA: 0x75965fc9bc
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x3fe4c58 VA: 0x75965fcc58
	private Void _OnBuffStart(Object arg) { }
	// RVA: 0x3fe4ec8 VA: 0x75965fcec8
	private Void _OnBuffFinish(Object arg) { }
	// RVA: 0x3fe5138 VA: 0x75965fd138
	private Void _OnSnapShot(Object arg) { }
	// RVA: 0x3fe5194 VA: 0x75965fd194
	private Void _OnPlayerOperation(Object arg) { }
	// RVA: 0x3fe51f0 VA: 0x75965fd1f0
	private Void _OnGiveUpGame(Object arg) { }
	// RVA: 0x3fe524c VA: 0x75965fd24c
	public Void OnGameReady() { }
	// RVA: 0x3fe5250 VA: 0x75965fd250
	public Void OnGameReset(BattleController controller) { }
	// RVA: 0x3fe56b8 VA: 0x75965fd6b8
	public Void OnGameInit(Options levelOptions) { }
	// RVA: 0x3fe5728 VA: 0x75965fd728
	public Void OnGameStart() { }
	// RVA: 0x3fe5754 VA: 0x75965fd754
	public Void OnGameOver(GameResult result) { }
	// RVA: 0x3fe400c VA: 0x75965fc00c
	private Void _AppendLog(LogItem log) { }
	// RVA: 0x3fe3c98 VA: 0x75965fbc98
	private SourceOrTargetRef _AnalyzeComplexSource(ref Modifier modifier, ref Snapshot snapshot) { }
	// RVA: 0x3fe5514 VA: 0x75965fd514
	private Void _ResetLogger() { }
	// RVA: 0x3fe580c VA: 0x75965fd80c
	private Void _ReleaseLogger() { }
	// RVA: 0x3fe5e8c VA: 0x75965fde8c
	private String _GetFileFormat() { }
	// RVA: 0x3fdb5a8 VA: 0x75965f35a8
	public Void .ctor() { }
}
```