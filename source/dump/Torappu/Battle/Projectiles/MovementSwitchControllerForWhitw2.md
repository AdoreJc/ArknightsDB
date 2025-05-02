# MovementSwitchControllerForWhitw2

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `TargetOptions _targetOptions`

- `BuffData _traceTargetBuff`

- `String _traceTargetBuffManagerBuffKey`

- `Vector3 _randomOffsetMin`

- `Vector3 _randomOffsetMax`

- `PeriodicTimer m_timer`

- `MovementType m_curMovementType`

- `ILocatable m_curTargetLocation`

- `Entity m_curTarget`

- `Vector3 m_randomOffsetAfterAttach`


## Methods

- `Void _SwitchToMovementType(MovementType)`

- `Void _AddTraceTargetBuff()`

- `Boolean _CheckProjectileMissTarget()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile, GroupedMovement)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Boolean <>xLuaBaseProxy_UpdateTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class MovementSwitchControllerForWhitw2 : MovementSwitchController
{
	private TargetOptions _targetOptions; // 0x40
	private List`1 _periodTimeBBKeys; // 0xa0
	private List`1 _movementTypes; // 0xa8
	private BuffData _traceTargetBuff; // 0xb0
	private String _traceTargetBuffManagerBuffKey; // 0xb8
	private Vector3 _randomOffsetMin; // 0xc0
	private Vector3 _randomOffsetMax; // 0xcc
	private List`1 m_timeSlots; // 0xd8
	private PeriodicTimer m_timer; // 0xe0
	private MovementType m_curMovementType; // 0xe8
	private ILocatable m_curTargetLocation; // 0xf0
	private Entity m_curTarget; // 0xf8
	private Vector3 m_randomOffsetAfterAttach; // 0x100
	private const Single LARGE_VALUE; // 0x0
	private const String PROJECTILE_EFFECT_APPEAR; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0__SwitchToMovementType; // 0x10
	private static DelegateBridge __Hotfix0_UpdateTarget; // 0x18
	private static DelegateBridge __Hotfix0__AddTraceTargetBuff; // 0x20
	private static DelegateBridge __Hotfix0__CheckProjectileMissTarget; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1da4010 VA: 0x75943bc010
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile, GroupedMovement groupedMovement) { }
	// RVA: 0x1da458c VA: 0x75943bc58c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1da4b40 VA: 0x75943bcb40
	private Void _SwitchToMovementType(MovementType targetMovementType) { }
	// RVA: 0x1da5050 VA: 0x75943bd050
	public override Boolean UpdateTarget() { }
	// RVA: 0x1da4c24 VA: 0x75943bcc24
	private Void _AddTraceTargetBuff() { }
	// RVA: 0x1da4ec4 VA: 0x75943bcec4
	private Boolean _CheckProjectileMissTarget() { }
	// RVA: 0x1da5548 VA: 0x75943bd548
	public Void .ctor() { }
	// RVA: 0x1da5694 VA: 0x75943bd694
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2, GroupedMovement P3) { }
	// RVA: 0x1da5698 VA: 0x75943bd698
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1da569c VA: 0x75943bd69c
	private Boolean <>xLuaBaseProxy_UpdateTarget() { }
}
```