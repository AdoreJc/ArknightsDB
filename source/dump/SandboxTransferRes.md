# SandboxTransferRes

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxTransferRes : ActionNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8676c VA: 0x759459e76c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f867d4 VA: 0x759459e7d4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f86984 VA: 0x759459e984
	public Void .ctor() { }
}
```