# LegionModeOnlyShowStatusMessage

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyShowStatusMessage : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f62578 VA: 0x759457a578
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f625e0 VA: 0x759457a5e0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f627c0 VA: 0x759457a7c0
	public Void .ctor() { }
}
```