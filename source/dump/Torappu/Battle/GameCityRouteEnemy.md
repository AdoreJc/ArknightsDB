# GameCityRouteEnemy

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 m_cursorIndex`

- `PeriodicTimer m_waitTimer`


## Methods

- `Void _TriggerEnemyMove(Int32)`

- `Void <>xLuaBaseProxy_Init(EnemyData, EnemyHandBookData, SchedulerSnapshot, Route)`

- `Vector2 <>xLuaBaseProxy__MoveByRoute(Single, out)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GameCityRouteEnemy : Enemy
{
	private Int32 m_cursorIndex; // 0x4b8
	private PeriodicTimer m_waitTimer; // 0x4c0
	private List`1 m_checkpointDatas; // 0x4c8
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0__MoveByRoute; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0__TriggerEnemyMove; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1c277e4 VA: 0x759423f7e4
	protected override Void Init(EnemyData data, EnemyHandBookData handbookData, SchedulerSnapshot snapshot, Route route) { }
	// RVA: 0x1c27dac VA: 0x759423fdac
	protected override Vector2 _MoveByRoute(Single deltaTime, out Boolean isHanging) { }
	// RVA: 0x1c27fcc VA: 0x759423ffcc
	public override Void OnTick(FP fixedDeltaTime) { }
	// RVA: 0x1c278c8 VA: 0x759423f8c8
	private Void _TriggerEnemyMove(Int32 cursorIndex) { }
	// RVA: 0x1c280d0 VA: 0x75942400d0
	public Void .ctor() { }
	// RVA: 0x1c28200 VA: 0x7594240200
	private Void <>xLuaBaseProxy_Init(EnemyData P0, EnemyHandBookData P1, SchedulerSnapshot P2, Route P3) { }
	// RVA: 0x1c28230 VA: 0x7594240230
	private Vector2 <>xLuaBaseProxy__MoveByRoute(Single P0, out Boolean P1) { }
	// RVA: 0x1c28238 VA: 0x7594240238
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```