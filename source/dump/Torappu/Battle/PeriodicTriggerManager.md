# PeriodicTriggerManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _triggerEvent`

- `Single _defaultInterval`

- `Int32 _maxTarget`

- `Boolean _waitFirstPeriod`

- `String _triggerEventBB`

- `String _delayTriggerIntervalBB`

- `String _delayTriggerEventBB`

- `Int32 maxTarget`

- `Single m_interval`

- `String m_triggerEvent`

- `Single m_delayTriggerInterval`

- `String m_delayTriggerEvent`


## Methods

- `Void <OnTrigger>b__21_0()`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class PeriodicTriggerManager : EnvManager
{
	private String _triggerEvent; // 0x28
	private Single _defaultInterval; // 0x30
	private Int32 _maxTarget; // 0x34
	private Boolean _waitFirstPeriod; // 0x38
	private String _triggerEventBB; // 0x40
	private String _delayTriggerIntervalBB; // 0x48
	private String _delayTriggerEventBB; // 0x50
	protected readonly List`1 candidateTiles; // 0x58
	protected readonly List`1 targetTiles; // 0x60
	protected readonly List`1 candidateEntities; // 0x68
	protected readonly List`1 targetEntities; // 0x70
	protected Int32 maxTarget; // 0x78
	private readonly PeriodicTimer m_intervalTicker; // 0x80
	private Single m_interval; // 0x88
	private String m_triggerEvent; // 0x90
	private Single m_delayTriggerInterval; // 0x98
	private String m_delayTriggerEvent; // 0xa0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_InitCandidates; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_UpdateCandidates; // 0x18
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x20
	private static DelegateBridge __Hotfix0_FilterTargets; // 0x28
	private static DelegateBridge __Hotfix0_EmitEvent; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x405a848 VA: 0x7596672848
	public override Void Init(GlobalEnvSystem envSystem) { }
	// RVA: 0x405aa48 VA: 0x7596672a48
	public virtual Void InitCandidates() { }
	// RVA: 0x405aaac VA: 0x7596672aac
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x405abfc VA: 0x7596672bfc
	public virtual Void UpdateCandidates() { }
	// RVA: 0x405ac60 VA: 0x7596672c60
	public virtual Void OnTrigger() { }
	// RVA: 0x405add0 VA: 0x7596672dd0
	public virtual Void FilterTargets() { }
	// RVA: 0x405ae34 VA: 0x7596672e34
	public virtual Void EmitEvent(String value) { }
	// RVA: 0x405aeec VA: 0x7596672eec
	public Void .ctor() { }
	// RVA: 0x405b0d8 VA: 0x75966730d8
	private Void <OnTrigger>b__21_0() { }
	// RVA: 0x405b0ec VA: 0x75966730ec
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x405b0f4 VA: 0x75966730f4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```