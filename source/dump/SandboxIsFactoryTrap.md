# SandboxIsFactoryTrap

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxIsFactoryTrap : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f86ed0 VA: 0x759459eed0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f86f38 VA: 0x759459ef38
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f870f0 VA: 0x759459f0f0
	public Void .ctor() { }
}
```