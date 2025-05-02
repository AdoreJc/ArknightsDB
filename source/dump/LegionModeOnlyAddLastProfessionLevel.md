# LegionModeOnlyAddLastProfessionLevel

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _levelCnt`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyAddLastProfessionLevel : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _levelCnt; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f66634 VA: 0x759457e634
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6669c VA: 0x759457e69c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f668f0 VA: 0x759457e8f0
	public Void .ctor() { }
}
```