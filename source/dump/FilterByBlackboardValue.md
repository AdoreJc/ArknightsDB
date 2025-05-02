# FilterByBlackboardValue

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _anotherBuff`

- `String _buffKey`

- `String _blackboardKey`

- `Int32 _valueToCompare`

- `String _anotherKeyToCompare`

- `CompareType _condType`


## Properties

- `String calculationStr`


## Methods

- `String get_calculationStr()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByBlackboardValue : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _anotherBuff; // 0x14
	private String _buffKey; // 0x18
	private String _blackboardKey; // 0x20
	private Int32 _valueToCompare; // 0x28
	private String _anotherKeyToCompare; // 0x30
	private CompareType _condType; // 0x38
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_calculationStr; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	public String calculationStr { get; }

	// RVA: 0x1f17f4c VA: 0x759452ff4c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f17fb4 VA: 0x759452ffb4
	public String get_calculationStr() { }
	// RVA: 0x1f181e8 VA: 0x75945301e8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f18464 VA: 0x7594530464
	public Void .ctor() { }
}
```