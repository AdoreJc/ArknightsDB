# LegionModeOnlyForceRecycleUsingCard

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyForceRecycleUsingCard : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f67e50 VA: 0x759457fe50
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f67eb8 VA: 0x759457feb8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f680c8 VA: 0x75945800c8
	public Void .ctor() { }
}
```