# ChangeAnimatorMeshBySandboxKilledBoss

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `Boolean _enable`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ChangeAnimatorMeshBySandboxKilledBoss : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private Boolean _enable; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f832f8 VA: 0x759459b2f8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f83360 VA: 0x759459b360
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f836a8 VA: 0x759459b6a8
	public Void .ctor() { }
}
```