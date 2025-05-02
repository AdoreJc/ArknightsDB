# SandboxCheckHasFoodBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxCheckHasFoodBuff : ActionNode
{
	private ActionTargetType _target; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8bbb0 VA: 0x75945a3bb0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8bc18 VA: 0x75945a3c18
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8bdb8 VA: 0x75945a3db8
	public Void .ctor() { }
}
```