# Act31SideTriggerRebuildAreas

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act31SideTriggerRebuildAreas : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edb068 VA: 0x75944f3068
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edb0d0 VA: 0x75944f30d0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edb334 VA: 0x75944f3334
	public Void .ctor() { }
}
```