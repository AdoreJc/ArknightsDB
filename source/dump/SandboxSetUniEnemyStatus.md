# SandboxSetUniEnemyStatus

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxSetUniEnemyStatus : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8ca7c VA: 0x75945a4a7c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8cae4 VA: 0x75945a4ae4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8ce34 VA: 0x75945a4e34
	public Void .ctor() { }
}
```