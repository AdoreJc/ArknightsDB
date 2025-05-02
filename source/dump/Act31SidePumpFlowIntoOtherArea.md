# Act31SidePumpFlowIntoOtherArea

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _rangeId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act31SidePumpFlowIntoOtherArea : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _rangeId; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edb6bc VA: 0x75944f36bc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edb724 VA: 0x75944f3724
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edbad4 VA: 0x75944f3ad4
	public Void .ctor() { }
}
```