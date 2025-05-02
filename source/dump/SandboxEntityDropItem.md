# SandboxEntityDropItem

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `ResDropSourceType _type`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxEntityDropItem : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ResDropSourceType _type; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f86524 VA: 0x759459e524
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8658c VA: 0x759459e58c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f866fc VA: 0x759459e6fc
	public Void .ctor() { }
}
```