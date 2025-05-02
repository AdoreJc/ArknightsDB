# NarantS2Movement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `String _moveAheadTimeKey`

- `Single _moveAheadTime`

- `Single _moveAheadSpeed`

- `Single m_moveAheadTime`

- `MoveState m_moveState`

- `PeriodicTimer m_aheadStateTimer`

- `PeriodicTimer m_aheadBackStateTimer`

- `NarantS2HitBehaviour m_hitBehaviour`

- `Animator m_mainEffectAnimator`


## Methods

- `Void _SwitchToNextMoveState(MoveState)`

- `Vector3 _CalculateNextPosition(Single, Boolean)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileBorn()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_DoCheckReached()`

- `Boolean <>xLuaBaseProxy_DoCheckReachedInternal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class NarantS2Movement : AdvancedMovement
{
	private const Single DIRECTION_ZERO_TOLERANCE; // 0x0
	private const String COMEBACK_AUDIO; // 0x0
	private String _moveAheadTimeKey; // 0x118
	private Single _moveAheadTime; // 0x120
	private Single _moveAheadSpeed; // 0x124
	private Single m_moveAheadTime; // 0x128
	private MoveState m_moveState; // 0x12c
	private PeriodicTimer m_aheadStateTimer; // 0x130
	private PeriodicTimer m_aheadBackStateTimer; // 0x138
	private NarantS2HitBehaviour m_hitBehaviour; // 0x140
	private Animator m_mainEffectAnimator; // 0x148
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnProjectileBorn; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_DoCheckReached; // 0x18
	private static DelegateBridge __Hotfix0_DoCheckReachedInternal; // 0x20
	private static DelegateBridge __Hotfix0__SwitchToNextMoveState; // 0x28
	private static DelegateBridge __Hotfix0__CalculateNextPosition; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1da56a0 VA: 0x75943bd6a0
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1da584c VA: 0x75943bd84c
	public override Void OnProjectileBorn() { }
	// RVA: 0x1da5910 VA: 0x75943bd910
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1da6120 VA: 0x75943be120
	protected override Void DoCheckReached() { }
	// RVA: 0x1da61c8 VA: 0x75943be1c8
	protected override Boolean DoCheckReachedInternal() { }
	// RVA: 0x1da5e6c VA: 0x75943bde6c
	private Void _SwitchToNextMoveState(MoveState newState) { }
	// RVA: 0x1da5aec VA: 0x75943bdaec
	private Vector3 _CalculateNextPosition(Single deltaTime, Boolean forceToResetDir) { }
	// RVA: 0x1da62d0 VA: 0x75943be2d0
	public Void .ctor() { }
	// RVA: 0x1da63e0 VA: 0x75943be3e0
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1da63e4 VA: 0x75943be3e4
	private Void <>xLuaBaseProxy_OnProjectileBorn() { }
	// RVA: 0x1da63ec VA: 0x75943be3ec
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1da63f0 VA: 0x75943be3f0
	private Void <>xLuaBaseProxy_DoCheckReached() { }
	// RVA: 0x1da63f4 VA: 0x75943be3f4
	private Boolean <>xLuaBaseProxy_DoCheckReachedInternal() { }
}
```