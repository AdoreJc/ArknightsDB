# LegionModeOnlyAssignDangerLevelToBB

**Namespace:** ` `


## Fields

- `String _dangerLevelKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyAssignDangerLevelToBB : ActionNode
{
	private String _dangerLevelKey; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f69f10 VA: 0x7594581f10
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f69f78 VA: 0x7594581f78
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6a0b4 VA: 0x75945820b4
	public Void .ctor() { }
}
```