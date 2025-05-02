# ParacurveMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _speed`

- `Single _raiseHeight`

- `Boolean _delayAfterReached`

- `Single _delayTime`

- `Boolean _updateDelayTimeOnlyOnce`

- `Single _noRaiseHeightThreshold`

- `Boolean _comeBack`

- `Single _comeBackSpeedScale`

- `Boolean _inverseParacurve`

- `Boolean _useRandomHeight`

- `Vector2 _randomHeightRange`

- `Boolean _randomInverseParacurve`

- `Boolean m_isComeBack`

- `Single m_gravity`

- `Single m_velocityN`

- `Boolean m_reachedTop`

- `Single m_delayAfterReached`

- `Boolean m_alreadyUpdateAfterDelay`

- `Boolean m_inverseParacurve`

- `Single m_speed`


## Properties

- `Boolean comeBack`

- `Single speed`

- `Boolean useRandomHeight`


## Methods

- `Boolean get_comeBack()`

- `Single get_speed()`

- `Void set_speed(Single)`

- `Boolean get_useRandomHeight()`

- `Void _UpdateAfterReach()`

- `Void Comeback()`

- `Vector3 _CalculateNextPosition(Single, Boolean)`

- `Void <_UpdateAfterReach>b__40_0()`

- `Single <>xLuaBaseProxy_get_realSpeed()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnInitPose()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Boolean <>xLuaBaseProxy_DoCheckReachedInternal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class ParacurveMovement : BasicMovement
{
	private const Single MIN_FULL_HEIGHT; // 0x0
	private const Single DIRECTION_ZERO_TOLERANCE; // 0x0
	private const Single TOO_CLOSE_THRESHOLD; // 0x0
	private const Single LEFT_TIME_MIN_VALUE; // 0x0
	private Single _speed; // 0x94
	private Single _raiseHeight; // 0x98
	protected Boolean _delayAfterReached; // 0x9c
	private Single _delayTime; // 0xa0
	private Boolean _updateDelayTimeOnlyOnce; // 0xa4
	private Single _noRaiseHeightThreshold; // 0xa8
	protected Boolean _comeBack; // 0xac
	private Single _comeBackSpeedScale; // 0xb0
	private Boolean _inverseParacurve; // 0xb4
	private Boolean _useRandomHeight; // 0xb5
	private Vector2 _randomHeightRange; // 0xb8
	private Boolean _randomInverseParacurve; // 0xc0
	protected Boolean m_isComeBack; // 0xc1
	private Single m_gravity; // 0xc4
	private Single m_velocityN; // 0xc8
	private Boolean m_reachedTop; // 0xcc
	protected Single m_delayAfterReached; // 0xd0
	private Boolean m_alreadyUpdateAfterDelay; // 0xd4
	private Boolean m_inverseParacurve; // 0xd5
	private Single m_speed; // 0xd8
	private static DelegateBridge __Hotfix0_get_comeBack; // 0x0
	private static DelegateBridge __Hotfix0_get_speed; // 0x8
	private static DelegateBridge __Hotfix0_set_speed; // 0x10
	private static DelegateBridge __Hotfix0_get_realSpeed; // 0x18
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x20
	private static DelegateBridge __Hotfix0_get_useRandomHeight; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x30
	private static DelegateBridge __Hotfix0_OnInit; // 0x38
	private static DelegateBridge __Hotfix0_OnInitPose; // 0x40
	private static DelegateBridge __Hotfix0_OnTick; // 0x48
	private static DelegateBridge __Hotfix0_DoCheckReached; // 0x50
	private static DelegateBridge __Hotfix0__UpdateAfterReach; // 0x58
	private static DelegateBridge __Hotfix0_Comeback; // 0x60
	private static DelegateBridge __Hotfix0_DoCheckReachedInternal; // 0x68
	private static DelegateBridge __Hotfix0__CalculateNextPosition; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Boolean comeBack { get; }
	protected Single speed { get; set; }
	protected override Single realSpeed { get; }
	public override Boolean movementAdjustable { get; }
	private Boolean useRandomHeight { get; }

	// RVA: 0x1da9298 VA: 0x75943c1298
	public Boolean get_comeBack() { }
	// RVA: 0x1da9300 VA: 0x75943c1300
	protected Single get_speed() { }
	// RVA: 0x1da9368 VA: 0x75943c1368
	protected Void set_speed(Single value) { }
	// RVA: 0x1da93e4 VA: 0x75943c13e4
	protected override Single get_realSpeed() { }
	// RVA: 0x1da94a4 VA: 0x75943c14a4
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1da950c VA: 0x75943c150c
	private Boolean get_useRandomHeight() { }
	// RVA: 0x1d9fa2c VA: 0x75943b7a2c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1da85ac VA: 0x75943c05ac
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1da9574 VA: 0x75943c1574
	protected override Void OnInitPose() { }
	// RVA: 0x1d9fb6c VA: 0x75943b7b6c
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1da0700 VA: 0x75943b8700
	protected virtual Void DoCheckReached() { }
	// RVA: 0x1da9b68 VA: 0x75943c1b68
	private Void _UpdateAfterReach() { }
	// RVA: 0x1da01a8 VA: 0x75943b81a8
	protected Void Comeback() { }
	// RVA: 0x1da9c3c VA: 0x75943c1c3c
	protected override Boolean DoCheckReachedInternal() { }
	// RVA: 0x1da95f4 VA: 0x75943c15f4
	private Vector3 _CalculateNextPosition(Single deltaTime, Boolean forceToResetDir) { }
	// RVA: 0x1da0668 VA: 0x75943b8668
	public Void .ctor() { }
	// RVA: 0x1da9d38 VA: 0x75943c1d38
	private Void <_UpdateAfterReach>b__40_0() { }
	// RVA: 0x1da9d54 VA: 0x75943c1d54
	private Single <>xLuaBaseProxy_get_realSpeed() { }
	// RVA: 0x1da9d5c VA: 0x75943c1d5c
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1da9d64 VA: 0x75943c1d64
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1da9d6c VA: 0x75943c1d6c
	private Void <>xLuaBaseProxy_OnInitPose() { }
	// RVA: 0x1da9d74 VA: 0x75943c1d74
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1da9d7c VA: 0x75943c1d7c
	private Boolean <>xLuaBaseProxy_DoCheckReachedInternal() { }
}
```