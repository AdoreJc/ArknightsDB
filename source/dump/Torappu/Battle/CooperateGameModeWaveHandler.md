# CooperateGameModeWaveHandler

**Namespace:** `Torappu.Battle`


## Fields

- `CooperateGameMode m_gameMode`


## Properties

- `CooperateGameMode gameMode`


## Methods

- `CooperateGameMode get_gameMode()`

- `Boolean ReplaceAllActionKeyForLastWave(String)`

- `Boolean <>xLuaBaseProxy_get_skipCurWave()`

- `IEnumerator <>xLuaBaseProxy_WaitForPredelay(WaveData)`

- `IEnumerator <>xLuaBaseProxy_WaitForPostDelay(WaveData)`

- `IEnumerator <>xLuaBaseProxy_ExecuteActionQueue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CooperateGameModeWaveHandler : DefaultWaveHandler
{
	private const String STAGE_JUDGE_TRAP; // 0x0
	private const String LAST_WAVE_KEY; // 0x0
	private CooperateGameMode m_gameMode; // 0x18
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x0
	private static DelegateBridge __Hotfix0_get_skipCurWave; // 0x8
	private static DelegateBridge __Hotfix0_WaitForPredelay; // 0x10
	private static DelegateBridge __Hotfix0_WaitForPostDelay; // 0x18
	private static DelegateBridge __Hotfix0_ExecuteActionQueue; // 0x20
	private static DelegateBridge __Hotfix0_ReplaceAllActionKeyForLastWave; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected CooperateGameMode gameMode { get; }
	public override Boolean skipCurWave { get; }

	// RVA: 0x40e3e34 VA: 0x75966fbe34
	protected CooperateGameMode get_gameMode() { }
	// RVA: 0x40e3f2c VA: 0x75966fbf2c
	public override Boolean get_skipCurWave() { }
	// RVA: 0x40e3fa4 VA: 0x75966fbfa4
	public override IEnumerator WaitForPredelay(WaveData wave) { }
	// RVA: 0x40e409c VA: 0x75966fc09c
	public override IEnumerator WaitForPostDelay(WaveData wave) { }
	// RVA: 0x40e4194 VA: 0x75966fc194
	public override IEnumerator ExecuteActionQueue() { }
	// RVA: 0x40e4268 VA: 0x75966fc268
	public Boolean ReplaceAllActionKeyForLastWave(String key) { }
	// RVA: 0x40e4430 VA: 0x75966fc430
	public Void .ctor() { }
	// RVA: 0x40e44a0 VA: 0x75966fc4a0
	private Boolean <>xLuaBaseProxy_get_skipCurWave() { }
	// RVA: 0x40e44a8 VA: 0x75966fc4a8
	private IEnumerator <>xLuaBaseProxy_WaitForPredelay(WaveData P0) { }
	// RVA: 0x40e44b0 VA: 0x75966fc4b0
	private IEnumerator <>xLuaBaseProxy_WaitForPostDelay(WaveData P0) { }
	// RVA: 0x40e44b8 VA: 0x75966fc4b8
	private IEnumerator <>xLuaBaseProxy_ExecuteActionQueue() { }
}
```