# Act33SideEmitManagedProjectile

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `MountPointType _mountPoint`

- `Event _ev`

- `Boolean _overwriteActions`

- `ActionTargetType _targetType`

- `String _projectileKey`


## Methods

- `Void GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act33SideEmitManagedProjectile : ActionNode, IActionNodeSource
{
	private ActionTargetType _sourceType; // 0x10
	private MountPointType _mountPoint; // 0x14
	private Event _ev; // 0x18
	public ActionNode[] _actions; // 0x20
	private Boolean _overwriteActions; // 0x28
	private ActionTargetType _targetType; // 0x2c
	private String _projectileKey; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1edd828 VA: 0x75944f5828
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edd890 VA: 0x75944f5890
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eddda0 VA: 0x75944f5da0
	public Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1edde28 VA: 0x75944f5e28
	public Void .ctor() { }
}
```