# GameCityGameModeWaveHandler

**Namespace:** `Torappu.Battle`


## Fields

- `GameCityGameMode m_gameMode`

- `Boolean isRestTimerSet`


## Properties

- `GameCityGameMode gameMode`


## Methods

- `GameCityGameMode get_gameMode()`

- `Boolean _CheckRestingIsFinish()`

- `IEnumerator <>xLuaBaseProxy_WaitForPostDelay(WaveData)`

- `Boolean <>xLuaBaseProxy_get_skipCurWave()`

- `IEnumerator <>xLuaBaseProxy_ExecuteActionQueue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GameCityGameModeWaveHandler : DefaultWaveHandler
{
	private GameCityGameMode m_gameMode; // 0x18
	private Boolean isRestTimerSet; // 0x20
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x0
	private static DelegateBridge __Hotfix0_WaitForPostDelay; // 0x8
	private static DelegateBridge __Hotfix0_get_skipCurWave; // 0x10
	private static DelegateBridge __Hotfix0_ExecuteActionQueue; // 0x18
	private static DelegateBridge __Hotfix0__CheckRestingIsFinish; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected GameCityGameMode gameMode { get; }
	public override Boolean skipCurWave { get; }

	// RVA: 0x40e4b58 VA: 0x75966fcb58
	protected GameCityGameMode get_gameMode() { }
	// RVA: 0x40e4c50 VA: 0x75966fcc50
	public override IEnumerator WaitForPostDelay(WaveData wave) { }
	// RVA: 0x40e4d38 VA: 0x75966fcd38
	public override Boolean get_skipCurWave() { }
	// RVA: 0x40e4db0 VA: 0x75966fcdb0
	public override IEnumerator ExecuteActionQueue() { }
	// RVA: 0x40e4e84 VA: 0x75966fce84
	private Boolean _CheckRestingIsFinish() { }
	// RVA: 0x40e4f90 VA: 0x75966fcf90
	public Void .ctor() { }
	// RVA: 0x40e5000 VA: 0x75966fd000
	private IEnumerator <>xLuaBaseProxy_WaitForPostDelay(WaveData P0) { }
	// RVA: 0x40e5008 VA: 0x75966fd008
	private Boolean <>xLuaBaseProxy_get_skipCurWave() { }
	// RVA: 0x40e5010 VA: 0x75966fd010
	private IEnumerator <>xLuaBaseProxy_ExecuteActionQueue() { }
}
```