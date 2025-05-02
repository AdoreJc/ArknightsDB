# AssignCharacterSkillBlackboardToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _sourceBlackboardKey`

- `String _targetBlackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignCharacterSkillBlackboardToBB : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _sourceBlackboardKey; // 0x18
	private String _targetBlackboardKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef0074 VA: 0x7594508074
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef00dc VA: 0x75945080dc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef031c VA: 0x759450831c
	public Void .ctor() { }
}
```