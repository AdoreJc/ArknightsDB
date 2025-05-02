# SandboxRecordUsingConstructItem

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxRecordUsingConstructItem : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f892d0 VA: 0x75945a12d0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f89338 VA: 0x75945a1338
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f894fc VA: 0x75945a14fc
	public Void .ctor() { }
}
```