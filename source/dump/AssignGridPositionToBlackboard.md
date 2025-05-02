# AssignGridPositionToBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _gridRowKey`

- `String _gridColKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignGridPositionToBlackboard : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _gridRowKey; // 0x18
	private String _gridColKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f942e0 VA: 0x75945ac2e0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f94348 VA: 0x75945ac348
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f944a8 VA: 0x75945ac4a8
	public Void .ctor() { }
}
```