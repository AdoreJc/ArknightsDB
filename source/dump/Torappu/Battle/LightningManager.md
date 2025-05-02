# LightningManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _readyToLightningStatus`

- `String _lightningStatus`

- `PeriodicTimer m_intervalTicker`

- `Int32 m_tileCount`

- `FP m_interval`

- `FP m_delayToDamage`


## Methods

- `Void TryTriggerLightning()`

- `Void EmitEvnet(String)`

- `Void <TryTriggerLightning>b__13_0()`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class LightningManager : EnvManager
{
	private String _readyToLightningStatus; // 0x28
	private String _lightningStatus; // 0x30
	private List`1 _effectSettings; // 0x38
	private List`1 _prioritizedTargetId; // 0x40
	private PeriodicTimer m_intervalTicker; // 0x48
	private List`1 m_tiles; // 0x50
	private List`1 m_targeTiles; // 0x58
	private Int32 m_tileCount; // 0x60
	private FP m_interval; // 0x68
	private FP m_delayToDamage; // 0x70
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_TryTriggerLightning; // 0x10
	private static DelegateBridge __Hotfix0__GetPrioritizedTargets; // 0x18
	private static DelegateBridge __Hotfix0_EmitEvnet; // 0x20
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x404c904 VA: 0x7596664904
	public override Void Init(GlobalEnvSystem system) { }
	// RVA: 0x404cda0 VA: 0x7596664da0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x404ce88 VA: 0x7596664e88
	private Void TryTriggerLightning() { }
	// RVA: 0x404d054 VA: 0x7596665054
	private List`1 _GetPrioritizedTargets() { }
	// RVA: 0x404d4f8 VA: 0x75966654f8
	private Void EmitEvnet(String value) { }
	// RVA: 0x404d590 VA: 0x7596665590
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x404d79c VA: 0x759666579c
	public Void .ctor() { }
	// RVA: 0x404d920 VA: 0x7596665920
	private Void <TryTriggerLightning>b__13_0() { }
	// RVA: 0x404d928 VA: 0x7596665928
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x404d930 VA: 0x7596665930
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x404d938 VA: 0x7596665938
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```