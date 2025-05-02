# AdvancedMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `MoveType _moveType`

- `Single _speed`

- `Single _distance`

- `Boolean _comeBack`

- `Single _comeBackSpeedScale`

- `Single _delayToStart`

- `Single _delayAfterReached`

- `Single _delayToReachAfterHit`

- `Boolean _clearTraceTargetWhenReached`

- `Boolean _updateDelayTimeOnlyOnce`

- `Boolean _skipSmoothLerpDirection`

- `Boolean _addInertia`

- `Single _turnSpeed`

- `Boolean _useDynamicSpeed`

- `Single _deltaSpeedPerSec`

- `Single _finalSpeed`

- `Vector3 _randomOffset`

- `Boolean _forceUseTargetMountPoint`

- `Boolean m_hasTarget`

- `Single m_delayToStart`

- `Single m_estimatedTime`

- `FP m_delayAfterReached`

- `Boolean m_isComeBack`

- `FP m_turnSpeed`

- `Boolean m_alreadyUpdateAfterDelay`

- `CoroutineId m_reachAfterDelayId`

- `Single m_speed`


## Properties

- `Boolean needSpeed`

- `Boolean ableAddInertia`

- `Boolean addInertia`

- `Boolean ableDynamicSpeed`

- `Boolean useDynamicSpeed`

- `Boolean needDistance`

- `Boolean isTwoPoint`

- `Boolean clearTraceTargetWhenReached`

- `Boolean updateDelayTimeOnlyOnce`

- `FP delayAfterReached`

- `Boolean isComeBack`

- `Boolean alreadyUpdateAfterDelay`

- `Single estimateRatio`

- `Single speed`

- `MoveType moveType`


## Methods

- `Boolean get_needSpeed()`

- `Boolean get_ableAddInertia()`

- `Boolean get_addInertia()`

- `Boolean get_ableDynamicSpeed()`

- `Boolean get_useDynamicSpeed()`

- `Boolean get_needDistance()`

- `Boolean get_isTwoPoint()`

- `Boolean get_clearTraceTargetWhenReached()`

- `Boolean get_updateDelayTimeOnlyOnce()`

- `FP get_delayAfterReached()`

- `Boolean get_isComeBack()`

- `Boolean get_alreadyUpdateAfterDelay()`

- `Void set_alreadyUpdateAfterDelay(Boolean)`

- `Single get_estimateRatio()`

- `Single get_speed()`

- `Void set_speed(Single)`

- `MoveType get_moveType()`

- `Void _UpdateAfterReach()`

- `Void Comeback()`

- `Boolean CheckStartTick(Single)`

- `Void SetUnReached()`

- `Void ResetMoveSpeed()`

- `Single _UpdateDynamicSpeed(Single, Single, Single, Single)`

- `Void <_UpdateAfterReach>b__69_0()`

- `Single <>xLuaBaseProxy_get_realSpeed()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_DoCheckReached()`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Boolean <>xLuaBaseProxy_DoCheckReachedInternal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class AdvancedMovement : BasicMovement
{
	private MoveType _moveType; // 0x94
	private Single _speed; // 0x98
	private Single _distance; // 0x9c
	private Boolean _comeBack; // 0xa0
	private Single _comeBackSpeedScale; // 0xa4
	private Single _delayToStart; // 0xa8
	private Single _delayAfterReached; // 0xac
	private Single _delayToReachAfterHit; // 0xb0
	private Boolean _clearTraceTargetWhenReached; // 0xb4
	private Boolean _updateDelayTimeOnlyOnce; // 0xb5
	private Boolean _skipSmoothLerpDirection; // 0xb6
	private Boolean _addInertia; // 0xb7
	private Single _turnSpeed; // 0xb8
	private Boolean _useDynamicSpeed; // 0xbc
	private Single _deltaSpeedPerSec; // 0xc0
	private Single _finalSpeed; // 0xc4
	private Vector3 _randomOffset; // 0xc8
	private Boolean _forceUseTargetMountPoint; // 0xd4
	private Boolean m_hasTarget; // 0xd5
	private Single m_delayToStart; // 0xd8
	private Single m_estimatedTime; // 0xdc
	private FP m_delayAfterReached; // 0xe0
	private Boolean m_isComeBack; // 0xe8
	private FP m_turnSpeed; // 0xf0
	private Boolean m_alreadyUpdateAfterDelay; // 0xf8
	private CoroutineId m_reachAfterDelayId; // 0x100
	private Single m_speed; // 0x110
	private static DelegateBridge __Hotfix0_get_needSpeed; // 0x0
	private static DelegateBridge __Hotfix0_get_ableAddInertia; // 0x8
	private static DelegateBridge __Hotfix0_get_addInertia; // 0x10
	private static DelegateBridge __Hotfix0_get_ableDynamicSpeed; // 0x18
	private static DelegateBridge __Hotfix0_get_useDynamicSpeed; // 0x20
	private static DelegateBridge __Hotfix0_get_needDistance; // 0x28
	private static DelegateBridge __Hotfix0_get_isTwoPoint; // 0x30
	private static DelegateBridge __Hotfix0_get_comeBack; // 0x38
	private static DelegateBridge __Hotfix0_get_clearTraceTargetWhenReached; // 0x40
	private static DelegateBridge __Hotfix0_get_updateDelayTimeOnlyOnce; // 0x48
	private static DelegateBridge __Hotfix0_get_delayAfterReached; // 0x50
	private static DelegateBridge __Hotfix0_get_isComeBack; // 0x58
	private static DelegateBridge __Hotfix0_get_alreadyUpdateAfterDelay; // 0x60
	private static DelegateBridge __Hotfix0_set_alreadyUpdateAfterDelay; // 0x68
	private static DelegateBridge __Hotfix0_get_estimateRatio; // 0x70
	private static DelegateBridge __Hotfix0_get_speed; // 0x78
	private static DelegateBridge __Hotfix0_set_speed; // 0x80
	private static DelegateBridge __Hotfix0_get_realSpeed; // 0x88
	private static DelegateBridge __Hotfix0_get_moveType; // 0x90
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x98
	private static DelegateBridge __Hotfix0_Init; // 0xa0
	private static DelegateBridge __Hotfix0_OnTick; // 0xa8
	private static DelegateBridge __Hotfix0_DoCheckReached; // 0xb0
	private static DelegateBridge __Hotfix0__UpdateAfterReach; // 0xb8
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0xc0
	private static DelegateBridge __Hotfix0_OnInit; // 0xc8
	private static DelegateBridge __Hotfix0_DoCheckReachedInternal; // 0xd0
	private static DelegateBridge __Hotfix0_GetLerpRatio; // 0xd8
	private static DelegateBridge __Hotfix0_GetSpeed; // 0xe0
	private static DelegateBridge __Hotfix0_Comeback; // 0xe8
	private static DelegateBridge __Hotfix0_CheckStartTick; // 0xf0
	private static DelegateBridge __Hotfix0_SetUnReached; // 0xf8
	private static DelegateBridge __Hotfix0_ResetMoveSpeed; // 0x100
	private static DelegateBridge __Hotfix0__UpdateDynamicSpeed; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110

	public Boolean needSpeed { get; }
	public Boolean ableAddInertia { get; }
	public Boolean addInertia { get; }
	public Boolean ableDynamicSpeed { get; }
	public Boolean useDynamicSpeed { get; }
	public Boolean needDistance { get; }
	public Boolean isTwoPoint { get; }
	public virtual Boolean comeBack { get; }
	protected Boolean clearTraceTargetWhenReached { get; }
	protected Boolean updateDelayTimeOnlyOnce { get; }
	protected FP delayAfterReached { get; }
	protected Boolean isComeBack { get; }
	protected Boolean alreadyUpdateAfterDelay { get; set; }
	protected Single estimateRatio { get; }
	protected Single speed { get; set; }
	protected override Single realSpeed { get; }
	protected MoveType moveType { get; }
	public override Boolean movementAdjustable { get; }

	// RVA: 0x1d9844c VA: 0x75943b044c
	public Boolean get_needSpeed() { }
	// RVA: 0x1d984c8 VA: 0x75943b04c8
	public Boolean get_ableAddInertia() { }
	// RVA: 0x1d98538 VA: 0x75943b0538
	public Boolean get_addInertia() { }
	// RVA: 0x1d985a0 VA: 0x75943b05a0
	public Boolean get_ableDynamicSpeed() { }
	// RVA: 0x1d9861c VA: 0x75943b061c
	public Boolean get_useDynamicSpeed() { }
	// RVA: 0x1d98684 VA: 0x75943b0684
	public Boolean get_needDistance() { }
	// RVA: 0x1d986f4 VA: 0x75943b06f4
	public Boolean get_isTwoPoint() { }
	// RVA: 0x1d98764 VA: 0x75943b0764
	public virtual Boolean get_comeBack() { }
	// RVA: 0x1d987cc VA: 0x75943b07cc
	protected Boolean get_clearTraceTargetWhenReached() { }
	// RVA: 0x1d98834 VA: 0x75943b0834
	protected Boolean get_updateDelayTimeOnlyOnce() { }
	// RVA: 0x1d9889c VA: 0x75943b089c
	protected FP get_delayAfterReached() { }
	// RVA: 0x1d98904 VA: 0x75943b0904
	protected Boolean get_isComeBack() { }
	// RVA: 0x1d9896c VA: 0x75943b096c
	protected Boolean get_alreadyUpdateAfterDelay() { }
	// RVA: 0x1d989d4 VA: 0x75943b09d4
	protected Void set_alreadyUpdateAfterDelay(Boolean value) { }
	// RVA: 0x1d98a54 VA: 0x75943b0a54
	protected Single get_estimateRatio() { }
	// RVA: 0x1d98b9c VA: 0x75943b0b9c
	protected Single get_speed() { }
	// RVA: 0x1d98c04 VA: 0x75943b0c04
	protected Void set_speed(Single value) { }
	// RVA: 0x1d98c80 VA: 0x75943b0c80
	protected override Single get_realSpeed() { }
	// RVA: 0x1d98d40 VA: 0x75943b0d40
	protected MoveType get_moveType() { }
	// RVA: 0x1d98da8 VA: 0x75943b0da8
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1d98e10 VA: 0x75943b0e10
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d99038 VA: 0x75943b1038
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1d999a0 VA: 0x75943b19a0
	protected override Void DoCheckReached() { }
	// RVA: 0x1d99b0c VA: 0x75943b1b0c
	protected Void _UpdateAfterReach() { }
	// RVA: 0x1d99c1c VA: 0x75943b1c1c
	public override Void OnHitTarget(Entity target) { }
	// RVA: 0x1d99da8 VA: 0x75943b1da8
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1d9a2ac VA: 0x75943b22ac
	protected override Boolean DoCheckReachedInternal() { }
	// RVA: 0x1d9a3cc VA: 0x75943b23cc
	protected virtual Single GetLerpRatio(Single ratio) { }
	// RVA: 0x1d9a448 VA: 0x75943b2448
	protected virtual Single GetSpeed(Single ratio, Single speed) { }
	// RVA: 0x1d9a4cc VA: 0x75943b24cc
	protected Void Comeback() { }
	// RVA: 0x1d9975c VA: 0x75943b175c
	protected Boolean CheckStartTick(Single deltaTime) { }
	// RVA: 0x1d9a9d0 VA: 0x75943b29d0
	public Void SetUnReached() { }
	// RVA: 0x1d9aa58 VA: 0x75943b2a58
	public Void ResetMoveSpeed() { }
	// RVA: 0x1d99838 VA: 0x75943b1838
	private Single _UpdateDynamicSpeed(Single lastSpeed, Single deltaSpeedPerSec, Single finalSpeed, Single deltaTime) { }
	// RVA: 0x1d9aac4 VA: 0x75943b2ac4
	public Void .ctor() { }
	// RVA: 0x1d9abcc VA: 0x75943b2bcc
	private Void <_UpdateAfterReach>b__69_0() { }
	// RVA: 0x1d9abe8 VA: 0x75943b2be8
	private Single <>xLuaBaseProxy_get_realSpeed() { }
	// RVA: 0x1d9abf0 VA: 0x75943b2bf0
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d9abf8 VA: 0x75943b2bf8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d9ac00 VA: 0x75943b2c00
	private Void <>xLuaBaseProxy_DoCheckReached() { }
	// RVA: 0x1d9ac08 VA: 0x75943b2c08
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
	// RVA: 0x1d9ac10 VA: 0x75943b2c10
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1d9ac18 VA: 0x75943b2c18
	private Boolean <>xLuaBaseProxy_DoCheckReachedInternal() { }
}
```