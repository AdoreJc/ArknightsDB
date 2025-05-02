# RacingSchedulerPreprocessor

**Namespace:** `Torappu.Battle`


## Fields

- `RacingInput m_racingInput`


## Methods

- `Void <>xLuaBaseProxy_DoPreprocess(LevelData)`

- `Void <>xLuaBaseProxy_Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RacingSchedulerPreprocessor : RandomGroupSchedulerPreprocessor
{
	private const String RACING_WAVE_NAME; // 0x0
	private RacingInput m_racingInput; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_DoPreprocess; // 0x8
	private static DelegateBridge __Hotfix0_Dispose; // 0x10


	// RVA: 0x40ba100 VA: 0x75966d2100
	public Void .ctor(RacingInput input) { }
	// RVA: 0x40ba194 VA: 0x75966d2194
	public override Void DoPreprocess(LevelData levelData) { }
	// RVA: 0x40ba588 VA: 0x75966d2588
	public override Void Dispose() { }
	// RVA: 0x40ba604 VA: 0x75966d2604
	private Void <>xLuaBaseProxy_DoPreprocess(LevelData P0) { }
	// RVA: 0x40ba60c VA: 0x75966d260c
	private Void <>xLuaBaseProxy_Dispose() { }
}
```