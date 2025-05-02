# AssignEntityEsIntoBlackboard

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignEntityEsIntoBlackboard : ActionNode
{
	private String _blackboardKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eee728 VA: 0x7594506728
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eee790 VA: 0x7594506790
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eee8d8 VA: 0x75945068d8
	public Void .ctor() { }
}
```