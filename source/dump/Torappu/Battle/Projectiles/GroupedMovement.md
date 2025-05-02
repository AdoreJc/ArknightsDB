# GroupedMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `MovementSwitchController _controller`

- `Boolean m_movementAdjustable`


## Properties

- `Behaviour curMovement`

- `BasicMovement curBasicMovement`


## Methods

- `Behaviour get_curMovement()`

- `BasicMovement get_curBasicMovement()`

- `Void _CalcMovementAdjustable()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnInitPose()`

- `Void <>xLuaBaseProxy_DealReached()`

- `Void <>xLuaBaseProxy_OnProjectileBorn()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_SwitchTraceTarget(ILocatable)`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class GroupedMovement : BasicMovement
{
	private List`1 _movements; // 0x98
	private MovementSwitchController _controller; // 0xa0
	private Boolean m_movementAdjustable; // 0xa8
	private static DelegateBridge __Hotfix0_get_curMovement; // 0x0
	private static DelegateBridge __Hotfix0_get_curBasicMovement; // 0x8
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnInitPose; // 0x28
	private static DelegateBridge __Hotfix0_DealReached; // 0x30
	private static DelegateBridge __Hotfix0_OnProjectileBorn; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0_SwitchTraceTarget; // 0x48
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x50
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x58
	private static DelegateBridge __Hotfix0__CalcMovementAdjustable; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Behaviour curMovement { get; }
	public BasicMovement curBasicMovement { get; }
	public override Boolean movementAdjustable { get; }

	// RVA: 0x1da1574 VA: 0x75943b9574
	public Behaviour get_curMovement() { }
	// RVA: 0x1da1678 VA: 0x75943b9678
	public BasicMovement get_curBasicMovement() { }
	// RVA: 0x1da1730 VA: 0x75943b9730
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1da1798 VA: 0x75943b9798
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1da1b70 VA: 0x75943b9b70
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1da1bf0 VA: 0x75943b9bf0
	protected override Void OnInitPose() { }
	// RVA: 0x1da1c54 VA: 0x75943b9c54
	protected override Void DealReached() { }
	// RVA: 0x1da1cb8 VA: 0x75943b9cb8
	public override Void OnProjectileBorn() { }
	// RVA: 0x1da1e3c VA: 0x75943b9e3c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1da1ee8 VA: 0x75943b9ee8
	public override Void SwitchTraceTarget(ILocatable newTarget) { }
	// RVA: 0x1da1fd8 VA: 0x75943b9fd8
	public override Void OnHitTarget(Entity target) { }
	// RVA: 0x1da206c VA: 0x75943ba06c
	public override Void OnProjectileStop() { }
	// RVA: 0x1da1a64 VA: 0x75943b9a64
	private Void _CalcMovementAdjustable() { }
	// RVA: 0x1da20f4 VA: 0x75943ba0f4
	public Void .ctor() { }
	// RVA: 0x1da21b8 VA: 0x75943ba1b8
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1da21c0 VA: 0x75943ba1c0
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1da21c8 VA: 0x75943ba1c8
	private Void <>xLuaBaseProxy_OnInitPose() { }
	// RVA: 0x1da21d0 VA: 0x75943ba1d0
	private Void <>xLuaBaseProxy_DealReached() { }
	// RVA: 0x1da21d8 VA: 0x75943ba1d8
	private Void <>xLuaBaseProxy_OnProjectileBorn() { }
	// RVA: 0x1da21e0 VA: 0x75943ba1e0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1da21e8 VA: 0x75943ba1e8
	private Void <>xLuaBaseProxy_SwitchTraceTarget(ILocatable P0) { }
	// RVA: 0x1da21f0 VA: 0x75943ba1f0
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
	// RVA: 0x1da21f8 VA: 0x75943ba1f8
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```