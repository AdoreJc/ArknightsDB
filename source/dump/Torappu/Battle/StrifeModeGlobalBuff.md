# StrifeModeGlobalBuff

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 m_curWaveIndex`

- `Int32 m_curWaveDuration`

- `FP m_remaningDuration`

- `Boolean m_hasSwitchedWave`

- `Boolean m_killAllOneWaveMode`

- `StrifeUIPlugin m_strifePlugin`

- `StrifeGameMode m_gameMode`


## Methods

- `Void _OnWaveWillFinish(Single)`

- `Void _FinishCurWaveBecauseTimeUp()`

- `Void <OnInit>b__10_0(Object)`

- `Void <>xLuaBaseProxy_OnInit(GlobalBuffData)`

- `Void <>xLuaBaseProxy_TryAddBuff(Unit, Boolean)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class StrifeModeGlobalBuff : GlobalBuff
{
	private List`1 _initBlackboard; // 0xe0
	private readonly List`1 m_buffs; // 0xe8
	private Int32 m_curWaveIndex; // 0xf0
	private Int32 m_curWaveDuration; // 0xf4
	private FP m_remaningDuration; // 0xf8
	private Boolean m_hasSwitchedWave; // 0x100
	private Boolean m_killAllOneWaveMode; // 0x101
	private List`1 m_durationEachWave; // 0x108
	private StrifeUIPlugin m_strifePlugin; // 0x110
	private StrifeGameMode m_gameMode; // 0x118
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_TryAddBuff; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0__OnWaveWillFinish; // 0x18
	private static DelegateBridge __Hotfix0__FinishCurWaveBecauseTimeUp; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x401d13c VA: 0x759663513c
	public override Void OnInit(GlobalBuffData data) { }
	// RVA: 0x401d82c VA: 0x759663582c
	public override Void TryAddBuff(Unit unit, Boolean isInit) { }
	// RVA: 0x401d9f0 VA: 0x75966359f0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x401ddf4 VA: 0x7596635df4
	private Void _OnWaveWillFinish(Single showTime) { }
	// RVA: 0x401dc18 VA: 0x7596635c18
	private Void _FinishCurWaveBecauseTimeUp() { }
	// RVA: 0x401de8c VA: 0x7596635e8c
	public Void .ctor() { }
	// RVA: 0x401dfe8 VA: 0x7596635fe8
	private Void <OnInit>b__10_0(Object arg) { }
	// RVA: 0x401e05c VA: 0x759663605c
	private Void <>xLuaBaseProxy_OnInit(GlobalBuffData P0) { }
	// RVA: 0x401e060 VA: 0x7596636060
	private Void <>xLuaBaseProxy_TryAddBuff(Unit P0, Boolean P1) { }
	// RVA: 0x401e068 VA: 0x7596636068
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```