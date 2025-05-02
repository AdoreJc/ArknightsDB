# NarantS3Movement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _speed`

- `Single _curveHeight`

- `Single _pitchOffsetBound`

- `Single _timeWhenReachMaxHeight`

- `Boolean _delayAfterReached`

- `Single _delayTime`

- `Boolean _updateDelayTimeOnlyOnce`

- `Single _noCurveHeightThreshold`

- `Boolean _comeBack`

- `Single _comeBackSpeedScale`

- `Boolean _clockwiseOffset`

- `Boolean m_clockwiseOffset`

- `Boolean m_reachedLimit`

- `Single m_delayAfterReached`

- `Single m_velocityPitchRise`

- `Single m_velocityPitchFall`

- `Single m_pitchProgress`

- `Single m_speed`

- `Boolean m_isComeBack`

- `Boolean m_alreadyUpdateAfterDelay`


## Properties

- `Boolean comeBack`

- `Single speed`


## Methods

- `Boolean get_comeBack()`

- `Single get_speed()`

- `Void set_speed(Single)`

- `Void _UpdateAfterReach()`

- `Void Comeback()`

- `Vector3 _CalculateNextPosition(Single, Boolean)`

- `Void <_UpdateAfterReach>b__35_0()`

- `Single <>xLuaBaseProxy_get_realSpeed()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnInitPose()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Boolean <>xLuaBaseProxy_DoCheckReachedInternal()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class NarantS3Movement : BasicMovement
{
	private const Single DIRECTION_ZERO_TOLERANCE; // 0x0
	private Single _speed; // 0x94
	private Single _curveHeight; // 0x98
	private Single _pitchOffsetBound; // 0x9c
	private Single _timeWhenReachMaxHeight; // 0xa0
	private Boolean _delayAfterReached; // 0xa4
	private Single _delayTime; // 0xa8
	private Boolean _updateDelayTimeOnlyOnce; // 0xac
	private Single _noCurveHeightThreshold; // 0xb0
	private Boolean _comeBack; // 0xb4
	private Single _comeBackSpeedScale; // 0xb8
	private Boolean _clockwiseOffset; // 0xbc
	private Boolean m_clockwiseOffset; // 0xbd
	private Boolean m_reachedLimit; // 0xbe
	private Single m_delayAfterReached; // 0xc0
	private Single m_velocityPitchRise; // 0xc4
	private Single m_velocityPitchFall; // 0xc8
	private Single m_pitchProgress; // 0xcc
	private Single m_speed; // 0xd0
	private Boolean m_isComeBack; // 0xd4
	private Boolean m_alreadyUpdateAfterDelay; // 0xd5
	private static DelegateBridge __Hotfix0_get_comeBack; // 0x0
	private static DelegateBridge __Hotfix0_get_speed; // 0x8
	private static DelegateBridge __Hotfix0_set_speed; // 0x10
	private static DelegateBridge __Hotfix0_get_realSpeed; // 0x18
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0_OnInitPose; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0_DoCheckReached; // 0x48
	private static DelegateBridge __Hotfix0__UpdateAfterReach; // 0x50
	private static DelegateBridge __Hotfix0_Comeback; // 0x58
	private static DelegateBridge __Hotfix0_DoCheckReachedInternal; // 0x60
	private static DelegateBridge __Hotfix0__CalculateNextPosition; // 0x68
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Boolean comeBack { get; }
	protected Single speed { get; set; }
	protected override Single realSpeed { get; }
	public override Boolean movementAdjustable { get; }

	// RVA: 0x1da63f8 VA: 0x75943be3f8
	public Boolean get_comeBack() { }
	// RVA: 0x1da6460 VA: 0x75943be460
	protected Single get_speed() { }
	// RVA: 0x1da64c8 VA: 0x75943be4c8
	protected Void set_speed(Single value) { }
	// RVA: 0x1da6544 VA: 0x75943be544
	protected override Single get_realSpeed() { }
	// RVA: 0x1da6604 VA: 0x75943be604
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1da666c VA: 0x75943be66c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1da6720 VA: 0x75943be720
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1da6a10 VA: 0x75943bea10
	protected override Void OnInitPose() { }
	// RVA: 0x1da6f90 VA: 0x75943bef90
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1da70b8 VA: 0x75943bf0b8
	protected virtual Void DoCheckReached() { }
	// RVA: 0x1da7248 VA: 0x75943bf248
	private Void _UpdateAfterReach() { }
	// RVA: 0x1da731c VA: 0x75943bf31c
	protected Void Comeback() { }
	// RVA: 0x1da7770 VA: 0x75943bf770
	protected override Boolean DoCheckReachedInternal() { }
	// RVA: 0x1da6a90 VA: 0x75943bea90
	private Vector3 _CalculateNextPosition(Single deltaTime, Boolean forceToResetDir) { }
	// RVA: 0x1da786c VA: 0x75943bf86c
	public override Void OnProjectileStop() { }
	// RVA: 0x1da7940 VA: 0x75943bf940
	public Void .ctor() { }
	// RVA: 0x1da79dc VA: 0x75943bf9dc
	private Void <_UpdateAfterReach>b__35_0() { }
	// RVA: 0x1da79f8 VA: 0x75943bf9f8
	private Single <>xLuaBaseProxy_get_realSpeed() { }
	// RVA: 0x1da7a00 VA: 0x75943bfa00
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1da7a08 VA: 0x75943bfa08
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1da7a10 VA: 0x75943bfa10
	private Void <>xLuaBaseProxy_OnInitPose() { }
	// RVA: 0x1da7a18 VA: 0x75943bfa18
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1da7a20 VA: 0x75943bfa20
	private Boolean <>xLuaBaseProxy_DoCheckReachedInternal() { }
	// RVA: 0x1da7a28 VA: 0x75943bfa28
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```