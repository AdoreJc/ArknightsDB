# SandboxHunterKillEnemy

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `ActionTargetType _owner`

- `String _huntBuffKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxHunterKillEnemy : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ActionTargetType _owner; // 0x14
	private String _huntBuffKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f857c0 VA: 0x759459d7c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f85828 VA: 0x759459d828
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f85a04 VA: 0x759459da04
	public Void .ctor() { }
}
```