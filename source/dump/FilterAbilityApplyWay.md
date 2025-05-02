# FilterAbilityApplyWay

**Namespace:** ` `


## Fields

- `SourceApplyWay _applyWayFilter`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterAbilityApplyWay : ActionNode
{
	private SourceApplyWay _applyWayFilter; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f21b6c VA: 0x7594539b6c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f21bd4 VA: 0x7594539bd4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f21cd4 VA: 0x7594539cd4
	public Void .ctor() { }
}
```