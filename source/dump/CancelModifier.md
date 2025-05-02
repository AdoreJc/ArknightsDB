# CancelModifier

**Namespace:** ` `


## Fields

- `CancelReason _reason`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CancelModifier : ActionNode
{
	private CancelReason _reason; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7438c VA: 0x759458c38c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f743f4 VA: 0x759458c3f4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f744c8 VA: 0x759458c4c8
	public Void .ctor() { }
}
```