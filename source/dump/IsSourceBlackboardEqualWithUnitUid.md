# IsSourceBlackboardEqualWithUnitUid

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `String _blackboardKey`

- `String _buffKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IsSourceBlackboardEqualWithUnitUid : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _blackboardKey; // 0x18
	private String _buffKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eec49c VA: 0x759450449c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eec504 VA: 0x7594504504
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eec708 VA: 0x7594504708
	public Void .ctor() { }
}
```