# AssignAttributeAsDynamicVarToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `AttributeType _attributeType`

- `String _scaleVar`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignAttributeAsDynamicVarToBB : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private AttributeType _attributeType; // 0x14
	private String _scaleVar; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef0394 VA: 0x7594508394
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef03fc VA: 0x75945083fc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef060c VA: 0x759450860c
	public Void .ctor() { }
}
```