# SetMultiAppearSkillPendingToCast

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetMultiAppearSkillPendingToCast : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f58ff0 VA: 0x7594570ff0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f59058 VA: 0x7594571058
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f59280 VA: 0x7594571280
	public Void .ctor() { }
}
```