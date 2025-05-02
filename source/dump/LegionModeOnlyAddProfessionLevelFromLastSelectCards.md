# LegionModeOnlyAddProfessionLevelFromLastSelectCards

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyAddProfessionLevelFromLastSelectCards : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f66968 VA: 0x759457e968
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f669d0 VA: 0x759457e9d0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f66bc8 VA: 0x759457ebc8
	public Void .ctor() { }
}
```