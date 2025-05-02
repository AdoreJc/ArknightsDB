# CheckDistanceToTileCenter

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Single _distance`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckDistanceToTileCenter : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Single _distance; // 0x14
	private CompareType _condType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2bea8 VA: 0x7594543ea8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2bf10 VA: 0x7594543f10
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2c110 VA: 0x7594544110
	public Void .ctor() { }
}
```