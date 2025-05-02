# SandboxCheckHasResource

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _checkFull`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxCheckHasResource : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _checkFull; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f84ef0 VA: 0x759459cef0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f84f58 VA: 0x759459cf58
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f850fc VA: 0x759459d0fc
	public Void .ctor() { }
}
```