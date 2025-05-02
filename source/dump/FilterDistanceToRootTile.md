# FilterDistanceToRootTile

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Single _distance`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterDistanceToRootTile : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Single _distance; // 0x14
	private CompareType _condType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f91c40 VA: 0x75945a9c40
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f91ca8 VA: 0x75945a9ca8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f91f00 VA: 0x75945a9f00
	public Void .ctor() { }
}
```