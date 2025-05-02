# CheckCharSkillAvailable

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckCharSkillAvailable : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f24508 VA: 0x759453c508
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f24570 VA: 0x759453c570
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f24738 VA: 0x759453c738
	public Void .ctor() { }
}
```