# AddBuffBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _blackboardKey`

- `String _buffKey`

- `Single _addition`

- `String _additionKey`

- `String _maxValueKey`

- `Boolean _isMinus`

- `Boolean _checkBuffSource`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddBuffBlackboard : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _blackboardKey; // 0x18
	private String _buffKey; // 0x20
	private Single _addition; // 0x28
	private String _additionKey; // 0x30
	private String _maxValueKey; // 0x38
	private Boolean _isMinus; // 0x40
	private Boolean _checkBuffSource; // 0x41
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eed318 VA: 0x7594505318
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eed380 VA: 0x7594505380
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eed6a4 VA: 0x75945056a4
	public Void .ctor() { }
}
```