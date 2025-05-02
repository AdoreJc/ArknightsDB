# CheckTargetSkillDurationType

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTargetSkillDurationType : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private SkillDurationType[] _checkTypes; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8e968 VA: 0x75945a6968
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8e9d0 VA: 0x75945a69d0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8ebe0 VA: 0x75945a6be0
	public Void .ctor() { }
}
```