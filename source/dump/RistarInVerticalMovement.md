# RistarInVerticalMovement

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `Single _ignoredOffset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RistarInVerticalMovement : ActionNode
{
	private ActionTargetType _source; // 0x10
	private Single _ignoredOffset; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f5a23c VA: 0x759457223c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5a2a4 VA: 0x75945722a4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5a4f4 VA: 0x75945724f4
	public Void .ctor() { }
}
```