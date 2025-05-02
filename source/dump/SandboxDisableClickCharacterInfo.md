# SandboxDisableClickCharacterInfo

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _enabled`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxDisableClickCharacterInfo : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _enabled; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f84a04 VA: 0x759459ca04
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f84a6c VA: 0x759459ca6c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f84bec VA: 0x759459cbec
	public Void .ctor() { }
}
```