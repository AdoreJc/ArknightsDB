# AssignCurrentBlockNumToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignCurrentBlockNumToBB : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eeee28 VA: 0x7594506e28
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eeee90 VA: 0x7594506e90
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eef0a0 VA: 0x75945070a0
	public Void .ctor() { }
}
```