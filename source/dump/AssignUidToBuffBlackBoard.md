# AssignUidToBuffBlackBoard

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `String _buffKey`

- `String _blackBoardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignUidToBuffBlackBoard : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _buffKey; // 0x18
	private String _blackBoardKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eee474 VA: 0x7594506474
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eee4dc VA: 0x75945064dc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eee6b0 VA: 0x75945066b0
	public Void .ctor() { }
}
```