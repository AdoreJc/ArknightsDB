# FilterModifierCancelReason

**Namespace:** ` `


## Fields

- `CancelReason _reason`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterModifierCancelReason : ActionNode
{
	private CancelReason _reason; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f74538 VA: 0x759458c538
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f745a0 VA: 0x759458c5a0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7469c VA: 0x759458c69c
	public Void .ctor() { }
}
```