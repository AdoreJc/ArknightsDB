# RotateAroundMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _aroundSpeed`

- `Boolean _stopIfTargetDead`

- `Boolean _rotateAndMoving`

- `Boolean _rotateWithWorldPosition`

- `Single _projectileAroundRadius`

- `Boolean _clockwise`

- `Boolean _pointYAxisToTraceTarget`

- `Vector3 m_direction`

- `Boolean m_pointYAxisToTraceTarget`

- `Single m_finalRadius`

- `Single m_defaultRadius`

- `Single m_curRadius`

- `Single m_progress`

- `Single m_aroundSpeed`


## Properties

- `Boolean rotateAndMoving`

- `Boolean dynamicChangeProjectileAroundRadius`


## Methods

- `Boolean get_rotateAndMoving()`

- `Boolean get_dynamicChangeProjectileAroundRadius()`

- `Void _CalculateProjectileRadiusAndRotate(FP)`

- `Void <>xLuaBaseProxy_OnProjectileBorn()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnInitPose()`

- `Void <>xLuaBaseProxy_DealReached()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class RotateAroundMovement : BasicMovement
{
	private const Int32 MAX_DEGREES; // 0x0
	private const Single RADIUS_CHANGE_RATE; // 0x0
	private const String FINAL_RADIUS; // 0x0
	private const String DEFAULT_RADIUS; // 0x0
	private Single _aroundSpeed; // 0x94
	private Boolean _stopIfTargetDead; // 0x98
	private Boolean _rotateAndMoving; // 0x99
	private Boolean _rotateWithWorldPosition; // 0x9a
	private Single _projectileAroundRadius; // 0x9c
	private Boolean _clockwise; // 0xa0
	private Boolean _pointYAxisToTraceTarget; // 0xa1
	private Vector3 m_direction; // 0xa4
	private Boolean m_pointYAxisToTraceTarget; // 0xb0
	private Single m_finalRadius; // 0xb4
	private Single m_defaultRadius; // 0xb8
	private Single m_curRadius; // 0xbc
	private Single m_progress; // 0xc0
	private Single m_aroundSpeed; // 0xc4
	private static DelegateBridge __Hotfix0_get_rotateAndMoving; // 0x0
	private static DelegateBridge __Hotfix0_get_dynamicChangeProjectileAroundRadius; // 0x8
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileBorn; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnInitPose; // 0x30
	private static DelegateBridge __Hotfix0_DealReached; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0__CalculateProjectileRadiusAndRotate; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Boolean rotateAndMoving { get; }
	private Boolean dynamicChangeProjectileAroundRadius { get; }
	public override Boolean movementAdjustable { get; }

	// RVA: 0x1daad84 VA: 0x75943c2d84
	private Boolean get_rotateAndMoving() { }
	// RVA: 0x1daadec VA: 0x75943c2dec
	private Boolean get_dynamicChangeProjectileAroundRadius() { }
	// RVA: 0x1daae7c VA: 0x75943c2e7c
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1daaee4 VA: 0x75943c2ee4
	public override Void OnProjectileBorn() { }
	// RVA: 0x1daaff4 VA: 0x75943c2ff4
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1dab26c VA: 0x75943c326c
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1dab2ec VA: 0x75943c32ec
	protected override Void OnInitPose() { }
	// RVA: 0x1dab350 VA: 0x75943c3350
	protected override Void DealReached() { }
	// RVA: 0x1dab3b4 VA: 0x75943c33b4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1dab92c VA: 0x75943c392c
	private Void _CalculateProjectileRadiusAndRotate(FP deltaTime) { }
	// RVA: 0x1dabb74 VA: 0x75943c3b74
	public Void .ctor() { }
	// RVA: 0x1dabbf0 VA: 0x75943c3bf0
	private Void <>xLuaBaseProxy_OnProjectileBorn() { }
	// RVA: 0x1dabbf8 VA: 0x75943c3bf8
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1dabc00 VA: 0x75943c3c00
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1dabc08 VA: 0x75943c3c08
	private Void <>xLuaBaseProxy_OnInitPose() { }
	// RVA: 0x1dabc10 VA: 0x75943c3c10
	private Void <>xLuaBaseProxy_DealReached() { }
	// RVA: 0x1dabc18 VA: 0x75943c3c18
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```