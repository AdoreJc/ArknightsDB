# AssignHostAttributeToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `AttributeType _attributeType`

- `Boolean _setCurrentHp`

- `String _scaleVar`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignHostAttributeToBB : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private AttributeType _attributeType; // 0x14
	private Boolean _setCurrentHp; // 0x18
	private String _scaleVar; // 0x20
	private String _blackboardKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef0dc0 VA: 0x7594508dc0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef0e28 VA: 0x7594508e28
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef10d4 VA: 0x75945090d4
	public Void .ctor() { }
}
```