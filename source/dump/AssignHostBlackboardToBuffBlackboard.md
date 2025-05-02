# AssignHostBlackboardToBuffBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _hostTargetType`

- `String _hostBuffKey`

- `String _fromBlackboardKey`

- `String _toBlackboardKey`

- `Single _defaultValue`


## Properties

- `String calculationStr`


## Methods

- `String get_calculationStr()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignHostBlackboardToBuffBlackboard : ActionNode
{
	private ActionTargetType _hostTargetType; // 0x10
	private String _hostBuffKey; // 0x18
	private String _fromBlackboardKey; // 0x20
	private String _toBlackboardKey; // 0x28
	private Single _defaultValue; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_calculationStr; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	public String calculationStr { get; }

	// RVA: 0x1ef09d8 VA: 0x75945089d8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef0a40 VA: 0x7594508a40
	public String get_calculationStr() { }
	// RVA: 0x1ef0b1c VA: 0x7594508b1c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef0d50 VA: 0x7594508d50
	public Void .ctor() { }
}
```