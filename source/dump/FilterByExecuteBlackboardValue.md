# FilterByExecuteBlackboardValue

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `Int32 _valueToCompare`

- `String _anotherKeyToCompare`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByExecuteBlackboardValue : ActionNode
{
	private String _blackboardKey; // 0x10
	private Int32 _valueToCompare; // 0x18
	private String _anotherKeyToCompare; // 0x20
	private CompareType _condType; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eeebac VA: 0x7594506bac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eeec14 VA: 0x7594506c14
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eeedb8 VA: 0x7594506db8
	public Void .ctor() { }
}
```