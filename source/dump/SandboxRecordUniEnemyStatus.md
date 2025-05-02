# SandboxRecordUniEnemyStatus

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxRecordUniEnemyStatus : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8c6c8 VA: 0x75945a46c8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8c730 VA: 0x75945a4730
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8ca0c VA: 0x75945a4a0c
	public Void .ctor() { }
}
```