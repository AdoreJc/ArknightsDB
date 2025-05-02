# CheckSkillRemainingProgress

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `CompareType _condType`

- `Single _compareValue`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckSkillRemainingProgress : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private CompareType _condType; // 0x14
	private Single _compareValue; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2f6f0 VA: 0x75945476f0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2f758 VA: 0x7594547758
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2f9ac VA: 0x75945479ac
	public Void .ctor() { }
}
```