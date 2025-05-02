# SetIgnoreCancelReasonMask

**Namespace:** ` `


## Fields

- `CancelReasonMask _ignoreCancelReasonMask`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetIgnoreCancelReasonMask : ActionNode
{
	private CancelReasonMask _ignoreCancelReasonMask; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f73e38 VA: 0x759458be38
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f73ea0 VA: 0x759458bea0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f73f78 VA: 0x759458bf78
	public Void .ctor() { }
}
```