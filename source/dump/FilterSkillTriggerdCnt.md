# FilterSkillTriggerdCnt

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `CompareType _compareType`

- `Int32 _count`

- `Boolean _useCurTriggerCnt`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterSkillTriggerdCnt : ActionNode
{
	private ActionTargetType _target; // 0x10
	private CompareType _compareType; // 0x14
	private Int32 _count; // 0x18
	private Boolean _useCurTriggerCnt; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f31104 VA: 0x7594549104
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3116c VA: 0x759454916c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f313e0 VA: 0x75945493e0
	public Void .ctor() { }
}
```