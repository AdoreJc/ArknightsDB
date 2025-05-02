# LegionModeOnlyCheckCardLastDrawTag

**Namespace:** ` `


## Fields

- `String _targetGroupId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyCheckCardLastDrawTag : ActionNode
{
	private String _targetGroupId; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f64c44 VA: 0x759457cc44
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f64cac VA: 0x759457ccac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f64df4 VA: 0x759457cdf4
	public Void .ctor() { }
}
```