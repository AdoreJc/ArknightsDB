# CalculateBlackboardValueViaParams

**Namespace:** ` `


## Fields

- `String _inputKey`

- `String _outputKey`

- `String _multiplyParamKey`

- `String _dividedParamKey`

- `String _addParamKey`

- `String _minusParamKey`

- `String _minValueKey`

- `String _maxValueKey`

- `Boolean _finalAbs`

- `Boolean _finalCeil`

- `Boolean _finalFloor`

- `Boolean _useAbilityBlackboard`

- `String _abilityName`


## Properties

- `String calculationStr`


## Methods

- `String get_calculationStr()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CalculateBlackboardValueViaParams : ActionNode
{
	private String _inputKey; // 0x10
	private String _outputKey; // 0x18
	private String _multiplyParamKey; // 0x20
	private String _dividedParamKey; // 0x28
	private String _addParamKey; // 0x30
	private String _minusParamKey; // 0x38
	private String _minValueKey; // 0x40
	private String _maxValueKey; // 0x48
	private Boolean _finalAbs; // 0x50
	private Boolean _finalCeil; // 0x51
	private Boolean _finalFloor; // 0x52
	private Boolean _useAbilityBlackboard; // 0x53
	private String _abilityName; // 0x58
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_calculationStr; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	public String calculationStr { get; }

	// RVA: 0x1eef608 VA: 0x7594507608
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eef670 VA: 0x7594507670
	public String get_calculationStr() { }
	// RVA: 0x1eef9d0 VA: 0x75945079d0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eefd60 VA: 0x7594507d60
	public Void .ctor() { }
}
```