# SandboxCheckEnemyCanTraceTarget

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _checkHasTraceTarget`

- `Boolean _checkHasTraceTargetNow`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxCheckEnemyCanTraceTarget : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _checkHasTraceTarget; // 0x14
	private Boolean _checkHasTraceTargetNow; // 0x15
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8956c VA: 0x75945a156c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f895d4 VA: 0x75945a15d4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f89844 VA: 0x75945a1844
	public Void .ctor() { }
}
```