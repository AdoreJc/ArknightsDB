# IfSourceFromEnemyDirection

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Direction _direction`


## Methods

- `Vector2 _GetRowRange(Enemy)`

- `Vector2 _GetColRange(Enemy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IfSourceFromEnemyDirection : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Direction _direction; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__GetRowRange; // 0x10
	private static DelegateBridge __Hotfix0__GetColRange; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }

	// RVA: 0x1f147d8 VA: 0x759452c7d8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f14840 VA: 0x759452c840
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f14af0 VA: 0x759452caf0
	private Vector2 _GetRowRange(Enemy enemy) { }
	// RVA: 0x1f14d84 VA: 0x759452cd84
	private Vector2 _GetColRange(Enemy enemy) { }
	// RVA: 0x1f15024 VA: 0x759452d024
	public Void .ctor() { }
}
```