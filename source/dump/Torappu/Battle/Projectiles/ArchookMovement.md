# ArchookMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _speed`

- `Single _acceleration`

- `Boolean _stayWhenReached`

- `Boolean _needBack`

- `Single _hitOffset`

- `Single m_speed`

- `Single m_offset`

- `ArchookTraitAbility m_trait`

- `Boolean m_isBack`


## Methods

- `Void _UpdateSpeed(Single)`

- `Void _ComeBack()`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class ArchookMovement : BasicMovement
{
	private const Single FARTHEST_DISTANCE; // 0x0
	private Single _speed; // 0x94
	private Single _acceleration; // 0x98
	private Boolean _stayWhenReached; // 0x9c
	private Boolean _needBack; // 0x9d
	private Single _hitOffset; // 0xa0
	private Single m_speed; // 0xa4
	private Single m_offset; // 0xa8
	private ArchookTraitAbility m_trait; // 0xb0
	private Boolean m_isBack; // 0xb8
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0__UpdateSpeed; // 0x20
	private static DelegateBridge __Hotfix0__ComeBack; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override Boolean movementAdjustable { get; }

	// RVA: 0x1d9c3ec VA: 0x75943b43ec
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1d9c450 VA: 0x75943b4450
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1d9c724 VA: 0x75943b4724
	public override Void OnHitTarget(Entity target) { }
	// RVA: 0x1d9c7d4 VA: 0x75943b47d4
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1d9cd24 VA: 0x75943b4d24
	private Void _UpdateSpeed(Single deltaTime) { }
	// RVA: 0x1d9cdb0 VA: 0x75943b4db0
	private Void _ComeBack() { }
	// RVA: 0x1d9d16c VA: 0x75943b516c
	public Void .ctor() { }
	// RVA: 0x1d9d1e8 VA: 0x75943b51e8
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1d9d1f0 VA: 0x75943b51f0
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
	// RVA: 0x1d9d1f8 VA: 0x75943b51f8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```