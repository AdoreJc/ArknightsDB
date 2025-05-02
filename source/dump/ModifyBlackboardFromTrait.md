# ModifyBlackboardFromTrait

**Namespace:** ` `


## Fields

- `String _blackboardKeys`

- `String _fromBlackboardKeys`

- `Single _value`

- `Boolean _addBasedOriginValue`

- `Boolean _checkFromBlackboardValue`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyBlackboardFromTrait : ActionNode
{
	private String _blackboardKeys; // 0x10
	private String _fromBlackboardKeys; // 0x18
	private Single _value; // 0x20
	private Boolean _addBasedOriginValue; // 0x24
	private Boolean _checkFromBlackboardValue; // 0x25
	private ActionTargetType _targetType; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f99580 VA: 0x75945b1580
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f995e8 VA: 0x75945b15e8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f998e4 VA: 0x75945b18e4
	public Void .ctor() { }
}
```