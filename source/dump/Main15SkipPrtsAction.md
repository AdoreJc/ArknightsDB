# Main15SkipPrtsAction

**Namespace:** ` `


## Fields

- `PrtsActionType _actionType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Main15SkipPrtsAction : ActionNode
{
	private PrtsActionType _actionType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f70270 VA: 0x7594588270
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f702d8 VA: 0x75945882d8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7048c VA: 0x759458848c
	public Void .ctor() { }
}
```