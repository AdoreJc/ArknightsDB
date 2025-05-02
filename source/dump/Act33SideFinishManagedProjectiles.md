# Act33SideFinishManagedProjectiles

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _projectileKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act33SideFinishManagedProjectiles : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _projectileKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eddedc VA: 0x75944f5edc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eddf44 VA: 0x75944f5f44
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ede1cc VA: 0x75944f61cc
	public Void .ctor() { }
}
```