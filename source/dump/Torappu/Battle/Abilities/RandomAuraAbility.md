# RandomAuraAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _maxNum`

- `Int32 m_affectTargetNum`

- `Boolean m_waitForFirstBatch`

- `Boolean m_isDuringFirstBatch`

- `CoroutineId m_coroutine`


## Methods

- `Void _DealWithPendingTask()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Boolean <>xLuaBaseProxy_DealTargetTouched(Entity, TargetMeta)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RandomAuraAbility : AuraAbility
{
	private Int32 _maxNum; // 0x178
	private Int32 m_affectTargetNum; // 0x17c
	private List`1 m_pendingTargets; // 0x180
	private Boolean m_waitForFirstBatch; // 0x188
	private Boolean m_isDuringFirstBatch; // 0x189
	private CoroutineId m_coroutine; // 0x190
	private static DelegateBridge __Hotfix0_OnAttached; // 0x0
	private static DelegateBridge __Hotfix0_OnDetached; // 0x8
	private static DelegateBridge __Hotfix0_DealTargetTouched; // 0x10
	private static DelegateBridge __Hotfix0__DealWithPendingTask; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1e45274 VA: 0x759445d274
	protected override Void OnAttached() { }
	// RVA: 0x1e452f0 VA: 0x759445d2f0
	protected override Void OnDetached() { }
	// RVA: 0x1e457e0 VA: 0x759445d7e0
	protected override Boolean DealTargetTouched(Entity target, TargetMeta meta) { }
	// RVA: 0x1e45400 VA: 0x759445d400
	private Void _DealWithPendingTask() { }
	// RVA: 0x1e45b4c VA: 0x759445db4c
	public Void .ctor() { }
	// RVA: 0x1e45c58 VA: 0x759445dc58
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e45c60 VA: 0x759445dc60
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e45c68 VA: 0x759445dc68
	private Boolean <>xLuaBaseProxy_DealTargetTouched(Entity P0, TargetMeta P1) { }
}
```