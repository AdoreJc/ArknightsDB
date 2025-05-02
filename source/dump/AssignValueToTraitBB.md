# AssignValueToTraitBB

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `Single _value`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignValueToTraitBB : ActionNode
{
	private String _blackboardKey; // 0x10
	private Single _value; // 0x18
	private ActionTargetType _targetType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef1944 VA: 0x7594509944
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef19ac VA: 0x75945099ac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef1bb8 VA: 0x7594509bb8
	public Void .ctor() { }
}
```