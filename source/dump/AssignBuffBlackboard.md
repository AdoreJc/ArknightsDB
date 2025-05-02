# AssignBuffBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _blackboardKey`

- `String _valueKey`

- `String _buffKey`

- `Boolean _assignString`

- `Single _defaultValue`


## Properties

- `String calculationStr`


## Methods

- `String get_calculationStr()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignBuffBlackboard : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _blackboardKey; // 0x18
	private String _valueKey; // 0x20
	private String _buffKey; // 0x28
	private Boolean _assignString; // 0x30
	private Single _defaultValue; // 0x34
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_calculationStr; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	public String calculationStr { get; }

	// RVA: 0x1eeda68 VA: 0x7594505a68
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eedad0 VA: 0x7594505ad0
	public String get_calculationStr() { }
	// RVA: 0x1eedbc4 VA: 0x7594505bc4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eeddd8 VA: 0x7594505dd8
	public Void .ctor() { }
}
```