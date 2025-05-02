# ScoreAGoal

**Namespace:** ` `


## Fields

- `SideTypeIndex _sideType`

- `Int32 value`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ScoreAGoal : ActionNode
{
	private SideTypeIndex _sideType; // 0x10
	private Int32 value; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f504cc VA: 0x75945684cc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f50534 VA: 0x7594568534
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f50658 VA: 0x7594568658
	public Void .ctor() { }
}
```