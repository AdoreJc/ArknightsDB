# FilterSubProfessionAttackType

**Namespace:** ` `


## Fields

- `SubProfessionAttackType _targetAttackType`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterSubProfessionAttackType : ActionNode
{
	private SubProfessionAttackType _targetAttackType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2f1a8 VA: 0x75945471a8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2f210 VA: 0x7594547210
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2f43c VA: 0x759454743c
	public Void .ctor() { }
}
```