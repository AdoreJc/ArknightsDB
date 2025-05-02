# StrifeGameMode

**Namespace:** ` `


## Fields

- `StrifeInput m_input`

- `Int32 m_finishedWave`

- `Int32 m_totalWave`

- `Int32 m_remainingCntLastWave`

- `Boolean m_killAllModeInOneWave`


## Methods

- `Void InitWaveInfo(Int32, Boolean)`

- `Void FinishCurrentWave(Int32)`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`

- `Void <>xLuaBaseProxy_OnGameOver(ref)`

- `Void <>xLuaBaseProxy_OnWaveWillStart(WaveData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StrifeGameMode : DefaultGameMode
{
	public const String STRIFE_UI_PLUGIN_PATH; // 0x0
	private StrifeInput m_input; // 0x20
	private Int32 m_finishedWave; // 0x28
	private Int32 m_totalWave; // 0x2c
	private Int32 m_remainingCntLastWave; // 0x30
	private Boolean m_killAllModeInOneWave; // 0x34
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x10
	private static DelegateBridge __Hotfix0_InitWaveInfo; // 0x18
	private static DelegateBridge __Hotfix0_FinishCurrentWave; // 0x20
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x28
	private static DelegateBridge __Hotfix0_OnWaveWillStart; // 0x30

	public override GameModeType gameModeType { get; }

	// RVA: 0x1cfa2ec VA: 0x75943122ec
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1cfa354 VA: 0x7594312354
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1cfa470 VA: 0x7594312470
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1cfa508 VA: 0x7594312508
	public Void InitWaveInfo(Int32 totalWave, Boolean isKillAll) { }
	// RVA: 0x1cfa594 VA: 0x7594312594
	public Void FinishCurrentWave(Int32 finishedWave) { }
	// RVA: 0x1cfa9f4 VA: 0x75943129f4
	public override Void OnGameOver(ref GameResult result) { }
	// RVA: 0x1cfabac VA: 0x7594312bac
	public override Void OnWaveWillStart(WaveData waveData) { }
	// RVA: 0x1cfac5c VA: 0x7594312c5c
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1cfac64 VA: 0x7594312c64
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
	// RVA: 0x1cfac6c VA: 0x7594312c6c
	private Void <>xLuaBaseProxy_OnGameOver(ref GameResult P0) { }
	// RVA: 0x1cfac74 VA: 0x7594312c74
	private Void <>xLuaBaseProxy_OnWaveWillStart(WaveData P0) { }
}
```