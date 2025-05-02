# ControllableEnemy

**Namespace:** `Torappu.Battle`


## Fields

- `Act6FunEmptyCursor m_emptyCursor`


## Methods

- `Vector2 _MoveByController(Single, out)`

- `Void <>xLuaBaseProxy_Init(EnemyData, EnemyHandBookData, SchedulerSnapshot, Route)`

- `DirectionCursor <>xLuaBaseProxy_get_cursor()`

- `DirectionCursor <>xLuaBaseProxy_get_moveCursor()`

- `Boolean <>xLuaBaseProxy_get_onlyCollideWhenUnbalance()`

- `Vector2 <>xLuaBaseProxy__MoveByRoute(Single, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ControllableEnemy : Enemy
{
	private Act6FunEmptyCursor m_emptyCursor; // 0x4b8
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_get_cursor; // 0x8
	private static DelegateBridge __Hotfix0_get_moveCursor; // 0x10
	private static DelegateBridge __Hotfix0_get_onlyCollideWhenUnbalance; // 0x18
	private static DelegateBridge __Hotfix0__MoveByRoute; // 0x20
	private static DelegateBridge __Hotfix0__MoveByController; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override DirectionCursor cursor { get; }
	public override DirectionCursor moveCursor { get; }
	protected override Boolean onlyCollideWhenUnbalance { get; }

	// RVA: 0x1c271c0 VA: 0x759423f1c0
	protected override Void Init(EnemyData data, EnemyHandBookData handbookData, SchedulerSnapshot snapshot, Route route) { }
	// RVA: 0x1c27334 VA: 0x759423f334
	public override DirectionCursor get_cursor() { }
	// RVA: 0x1c2739c VA: 0x759423f39c
	public override DirectionCursor get_moveCursor() { }
	// RVA: 0x1c27404 VA: 0x759423f404
	protected override Boolean get_onlyCollideWhenUnbalance() { }
	// RVA: 0x1c27468 VA: 0x759423f468
	protected override Vector2 _MoveByRoute(Single deltaTime, out Boolean isHanging) { }
	// RVA: 0x1c27500 VA: 0x759423f500
	private Vector2 _MoveByController(Single deltaTime, out Boolean isHanging) { }
	// RVA: 0x1c27700 VA: 0x759423f700
	public Void .ctor() { }
	// RVA: 0x1c27794 VA: 0x759423f794
	private Void <>xLuaBaseProxy_Init(EnemyData P0, EnemyHandBookData P1, SchedulerSnapshot P2, Route P3) { }
	// RVA: 0x1c277c4 VA: 0x759423f7c4
	private DirectionCursor <>xLuaBaseProxy_get_cursor() { }
	// RVA: 0x1c277cc VA: 0x759423f7cc
	private DirectionCursor <>xLuaBaseProxy_get_moveCursor() { }
	// RVA: 0x1c277d4 VA: 0x759423f7d4
	private Boolean <>xLuaBaseProxy_get_onlyCollideWhenUnbalance() { }
	// RVA: 0x1c277dc VA: 0x759423f7dc
	private Vector2 <>xLuaBaseProxy__MoveByRoute(Single P0, out Boolean P1) { }
}
```