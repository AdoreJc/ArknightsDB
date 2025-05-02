# AssignBuffBlackboardFromOthers

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _blackboardKey`

- `String _valueKey`

- `String _buffKey`

- `Boolean _filterBuffSource`

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignBuffBlackboardFromOthers : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _blackboardKey; // 0x18
	private String _valueKey; // 0x20
	private String _buffKey; // 0x28
	private Boolean _filterBuffSource; // 0x30
	private ActionTargetType _sourceType; // 0x34
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eede48 VA: 0x7594505e48
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eedeb0 VA: 0x7594505eb0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eee144 VA: 0x7594506144
	public Void .ctor() { }
}
```