# LegionModeOnlyAssignStatusStackCntToBB

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyAssignStatusStackCntToBB : ActionNode
{
	private String _blackboardKey; // 0x10
	private ActionTargetType _sourceType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6a490 VA: 0x7594582490
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6a4f8 VA: 0x75945824f8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6a700 VA: 0x7594582700
	public Void .ctor() { }
}
```