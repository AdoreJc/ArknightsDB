# IceCornerTile

**Namespace:** `Torappu.Battle`


## Fields

- `Transform _orbitCenter`


## Properties

- `Vector2 orbitCenter`

- `Vector2 tileCenter`

- `Vector2 exitDirectionX`

- `Vector2 exitDirectionY`


## Methods

- `Vector2 get_orbitCenter()`

- `Vector2 get_tileCenter()`

- `Vector2 get_exitDirectionX()`

- `Vector2 get_exitDirectionY()`

- `Boolean _NormalDirectionDamping(Enemy)`

- `Void _AddCentripetalForce(Enemy)`

- `Void _DoOrbitInternal(Enemy)`

- `Boolean _CheckWithinRange(Vector2)`

- `Void _DoOrbit(Object)`

- `Void _StopOrbit(Enemy)`

- `Void <>xLuaBaseProxy_OnEnemyEnter(Enemy)`

- `Void <>xLuaBaseProxy_OnEnemyLeave(Enemy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class IceCornerTile : BuffTile
{
	private const Single TILE_WIDTH; // 0x0
	private const Single DAMPING_MAX_RADIUS; // 0x0
	private const Single DAMPING_MIN_RADIUS; // 0x0
	private const Single REFLECT_FACTOR; // 0x0
	private const Single CENTRIPETAL_FORCE_MAX_RADIUS; // 0x0
	private const Single FRICTION_FACTOR; // 0x0
	private Transform _orbitCenter; // 0x198
	private static DelegateBridge __Hotfix0_get_orbitCenter; // 0x0
	private static DelegateBridge __Hotfix0_get_tileCenter; // 0x8
	private static DelegateBridge __Hotfix0_get_exitDirectionX; // 0x10
	private static DelegateBridge __Hotfix0_get_exitDirectionY; // 0x18
	private static DelegateBridge __Hotfix0__NormalDirectionDamping; // 0x20
	private static DelegateBridge __Hotfix0__AddCentripetalForce; // 0x28
	private static DelegateBridge __Hotfix0__DoOrbitInternal; // 0x30
	private static DelegateBridge __Hotfix0__CheckWithinRange; // 0x38
	private static DelegateBridge __Hotfix0__DoOrbit; // 0x40
	private static DelegateBridge __Hotfix0__StopOrbit; // 0x48
	private static DelegateBridge __Hotfix0_OnEnemyEnter; // 0x50
	private static DelegateBridge __Hotfix0_OnEnemyLeave; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Vector2 orbitCenter { get; }
	private Vector2 tileCenter { get; }
	private Vector2 exitDirectionX { get; }
	private Vector2 exitDirectionY { get; }

	// RVA: 0x409140c VA: 0x75966a940c
	private Vector2 get_orbitCenter() { }
	// RVA: 0x4091480 VA: 0x75966a9480
	private Vector2 get_tileCenter() { }
	// RVA: 0x40914fc VA: 0x75966a94fc
	private Vector2 get_exitDirectionX() { }
	// RVA: 0x4091618 VA: 0x75966a9618
	private Vector2 get_exitDirectionY() { }
	// RVA: 0x4091734 VA: 0x75966a9734
	private Boolean _NormalDirectionDamping(Enemy target) { }
	// RVA: 0x4091c04 VA: 0x75966a9c04
	private Void _AddCentripetalForce(Enemy target) { }
	// RVA: 0x4091e94 VA: 0x75966a9e94
	private Void _DoOrbitInternal(Enemy aliveTarget) { }
	// RVA: 0x4091fac VA: 0x75966a9fac
	private Boolean _CheckWithinRange(Vector2 targetPos) { }
	// RVA: 0x40920ac VA: 0x75966aa0ac
	private Void _DoOrbit(Object rawTarget) { }
	// RVA: 0x40921e8 VA: 0x75966aa1e8
	private Void _StopOrbit(Enemy enemy) { }
	// RVA: 0x40922f8 VA: 0x75966aa2f8
	protected override Void OnEnemyEnter(Enemy enemy) { }
	// RVA: 0x4092474 VA: 0x75966aa474
	protected override Void OnEnemyLeave(Enemy enemy) { }
	// RVA: 0x4092500 VA: 0x75966aa500
	public Void .ctor() { }
	// RVA: 0x4092590 VA: 0x75966aa590
	private Void <>xLuaBaseProxy_OnEnemyEnter(Enemy P0) { }
	// RVA: 0x4092594 VA: 0x75966aa594
	private Void <>xLuaBaseProxy_OnEnemyLeave(Enemy P0) { }
}
```