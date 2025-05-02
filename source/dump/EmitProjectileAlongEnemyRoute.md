# EmitProjectileAlongEnemyRoute

**Namespace:** ` `


## Fields

- `MountPointType _mountPoint`

- `Event _ev`

- `Boolean _overwriteActions`

- `ActionTargetType _sourceType`

- `String _projectileKey`

- `Boolean _overwriteBuffs`


## Methods

- `Void GatherActionNodes(List`1)`

- `Boolean _CreateProjectileInternal(String, Enemy, Single, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EmitProjectileAlongEnemyRoute : ActionNode, IActionNodeSource
{
	private MountPointType _mountPoint; // 0x10
	private Event _ev; // 0x14
	private ActionNode[] _actions; // 0x18
	private Boolean _overwriteActions; // 0x20
	private ActionTargetType _sourceType; // 0x24
	private List`1 _distList; // 0x28
	private String _projectileKey; // 0x30
	private List`1 _buffDataList; // 0x38
	private Boolean _overwriteBuffs; // 0x40
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x10
	private static DelegateBridge __Hotfix0__CreateProjectileInternal; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }

	// RVA: 0x1f79110 VA: 0x7594591110
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f79178 VA: 0x7594591178
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f79780 VA: 0x7594591780
	public Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1f79454 VA: 0x7594591454
	private Boolean _CreateProjectileInternal(String projectileKey, Enemy enemy, Single distance, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f79808 VA: 0x7594591808
	public Void .ctor() { }
}
```