# SandboxMarkTraceReached

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxMarkTraceReached : ActionNode
{
	private ActionTargetType _target; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f84c5c VA: 0x759459cc5c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f84cc4 VA: 0x759459ccc4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f84e80 VA: 0x759459ce80
	public Void .ctor() { }
}
```