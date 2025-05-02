# FilterRootTileOffset

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _colKey`

- `String _rowKey`

- `Int32 _valueToCompare`

- `String _anotherKeyToCompare`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterRootTileOffset : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _colKey; // 0x18
	private String _rowKey; // 0x20
	private Int32 _valueToCompare; // 0x28
	private String _anotherKeyToCompare; // 0x30
	private CompareType _condType; // 0x38
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f91844 VA: 0x75945a9844
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f918ac VA: 0x75945a98ac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f91bc8 VA: 0x75945a9bc8
	public Void .ctor() { }
}
```