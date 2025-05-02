# SetMagicCircuitLikeObstacleInRange

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isLikeObstacle`

- `String _rangeId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetMagicCircuitLikeObstacleInRange : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _isLikeObstacle; // 0x14
	private String _rangeId; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6e16c VA: 0x759458616c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6e1d4 VA: 0x75945861d4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6e464 VA: 0x7594586464
	public Void .ctor() { }
}
```