# AssignDirectionToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isReverse`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignDirectionToBB : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _isReverse; // 0x14
	private String _blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef2ad8 VA: 0x759450aad8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef2b40 VA: 0x759450ab40
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef2cd4 VA: 0x759450acd4
	public Void .ctor() { }
}
```