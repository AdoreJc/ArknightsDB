# TraceTargetEnemy

**Namespace:** `Torappu.Battle`


## Fields

- `Ability _searchTargetAbility`

- `Boolean _searchAroundBall`

- `Ability _searchBallAbility`


## Properties

- `Boolean searchAroundBall`


## Methods

- `Boolean get_searchAroundBall()`

- `Vector2 _MoveToTarget(Single, out, Unit)`

- `Vector2 <>xLuaBaseProxy__MoveByRoute(Single, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TraceTargetEnemy : Enemy
{
	private Ability _searchTargetAbility; // 0x4b8
	private Boolean _searchAroundBall; // 0x4c0
	private Ability _searchBallAbility; // 0x4c8
	private static DelegateBridge __Hotfix0_get_searchAroundBall; // 0x0
	private static DelegateBridge __Hotfix0__MoveByRoute; // 0x8
	private static DelegateBridge __Hotfix0__MoveToTarget; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected Boolean searchAroundBall { get; }

	// RVA: 0x1c29fbc VA: 0x7594241fbc
	protected Boolean get_searchAroundBall() { }
	// RVA: 0x1c2a024 VA: 0x7594242024
	protected override Vector2 _MoveByRoute(Single deltaTime, out Boolean isHanging) { }
	// RVA: 0x1c2a5d8 VA: 0x75942425d8
	private Vector2 _MoveToTarget(Single deltaTime, out Boolean isHanging, Unit target) { }
	// RVA: 0x1c2aacc VA: 0x7594242acc
	public Void .ctor() { }
	// RVA: 0x1c2ab60 VA: 0x7594242b60
	private Vector2 <>xLuaBaseProxy__MoveByRoute(Single P0, out Boolean P1) { }
}
```