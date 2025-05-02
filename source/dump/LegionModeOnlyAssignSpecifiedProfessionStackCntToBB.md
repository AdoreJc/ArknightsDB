# LegionModeOnlyAssignSpecifiedProfessionStackCntToBB

**Namespace:** ` `


## Fields

- `String _assignBlackboardKey`

- `ProfessionCategory _queryProfessionCategory`

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyAssignSpecifiedProfessionStackCntToBB : ActionNode
{
	private String _assignBlackboardKey; // 0x10
	private ProfessionCategory _queryProfessionCategory; // 0x18
	private ActionTargetType _sourceType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6a7a8 VA: 0x75945827a8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6a810 VA: 0x7594582810
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6aa18 VA: 0x7594582a18
	public Void .ctor() { }
}
```