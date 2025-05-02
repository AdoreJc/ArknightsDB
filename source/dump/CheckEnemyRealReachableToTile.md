# CheckEnemyRealReachableToTile

**Namespace:** ` `


## Fields

- `ActionTargetType _targetEnemyType`

- `String _colKey`

- `String _rowKey`

- `Boolean _avoidObstacleLike`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyRealReachableToTile : ActionNode
{
	private ActionTargetType _targetEnemyType; // 0x10
	private String _colKey; // 0x18
	private String _rowKey; // 0x20
	private Boolean _avoidObstacleLike; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f27860 VA: 0x759453f860
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f278c8 VA: 0x759453f8c8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f27b18 VA: 0x759453fb18
	public Void .ctor() { }
}
```