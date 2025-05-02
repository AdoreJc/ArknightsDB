# CooperateFortressGlobalBuff

**Namespace:** `Torappu.Battle`


## Fields

- `FP m_waveTime`

- `FP m_waveTimeLast`

- `Int32 m_waveLifePoint`

- `FP m_waveReadyTime`

- `Int32 m_reviveLifePoint`

- `Boolean m_inPlayState`

- `Int32 m_waveAddime`

- `FP m_remaningDuration`

- `CooperateGameMode m_gameMode`

- `CooperateUIPlugin m_cooperatePlugin`


## Methods

- `Void _OnWaveWillStart()`

- `Void _BeforeResting(Object)`

- `Void _BeforeWaveFinish(Object)`

- `Void _FinishCurWaveBecauseTimeUp()`

- `Void <OnInit>b__15_0(Object)`

- `Void <>xLuaBaseProxy_OnInit(GlobalBuffData)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CooperateFortressGlobalBuff : GlobalBuff
{
	private const String REST_TIME; // 0x0
	private const String WAVE_TIME; // 0x0
	private const String WAVE_TIME_LAST; // 0x0
	private const String LIFE_POINT; // 0x0
	private const String REST_TIME_ADD; // 0x0
	private FP m_waveTime; // 0xe0
	private FP m_waveTimeLast; // 0xe8
	private Int32 m_waveLifePoint; // 0xf0
	private FP m_waveReadyTime; // 0xf8
	private Int32 m_reviveLifePoint; // 0x100
	private Boolean m_inPlayState; // 0x104
	private Int32 m_waveAddime; // 0x108
	private FP m_remaningDuration; // 0x110
	private CooperateGameMode m_gameMode; // 0x118
	private CooperateUIPlugin m_cooperatePlugin; // 0x120
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0__OnWaveWillStart; // 0x8
	private static DelegateBridge __Hotfix0__BeforeResting; // 0x10
	private static DelegateBridge __Hotfix0__BeforeWaveFinish; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge __Hotfix0__FinishCurWaveBecauseTimeUp; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x401595c VA: 0x759662d95c
	public override Void OnInit(GlobalBuffData data) { }
	// RVA: 0x4015e08 VA: 0x759662de08
	private Void _OnWaveWillStart() { }
	// RVA: 0x4015e90 VA: 0x759662de90
	private Void _BeforeResting(Object args) { }
	// RVA: 0x4016230 VA: 0x759662e230
	private Void _BeforeWaveFinish(Object args) { }
	// RVA: 0x4016684 VA: 0x759662e684
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x4016350 VA: 0x759662e350
	private Void _FinishCurWaveBecauseTimeUp() { }
	// RVA: 0x4016868 VA: 0x759662e868
	public Void .ctor() { }
	// RVA: 0x4016940 VA: 0x759662e940
	private Void <OnInit>b__15_0(Object arg) { }
	// RVA: 0x4016944 VA: 0x759662e944
	private Void <>xLuaBaseProxy_OnInit(GlobalBuffData P0) { }
	// RVA: 0x4016948 VA: 0x759662e948
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```