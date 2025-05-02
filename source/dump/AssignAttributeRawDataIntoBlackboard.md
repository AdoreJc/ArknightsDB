# AssignAttributeRawDataIntoBlackboard

**Namespace:** ` `


## Fields

- `String _blackBoardKey`

- `ActionTargetType _targetType`

- `AttributeType _attributeType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignAttributeRawDataIntoBlackboard : ActionNode
{
	private String _blackBoardKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private AttributeType _attributeType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef1364 VA: 0x7594509364
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef13cc VA: 0x75945093cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef1534 VA: 0x7594509534
	public Void .ctor() { }
}
```