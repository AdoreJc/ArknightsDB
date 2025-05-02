# EmitProjectileUseAbilitySelector

**Namespace:** ` `


## Fields

- `MountPointType _mountPoint`

- `Event _ev`

- `Boolean _overwriteActions`

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Boolean _hookStartPoint`

- `ActionTargetType _startPointTarget`

- `String _abilityName`

- `String _projectileKey`

- `Boolean _useAbilityFromOther`

- `ActionTargetType _abilityOwner`

- `Boolean _overwriteBuffs`

- `Boolean _extraBlackboard`

- `Boolean _overwriteBlackboard`

- `Boolean _useMountPointGroup`

- `MountPointGroup _mountPointGroup`

- `Boolean _cacheAtkToActions`

- `Int32 _emitCount`


## Methods

- `Void GatherActionNodes(List`1)`

- `Boolean _CreateProjectileInternal(String, Entity, Entity, Entity, SourceType, Blackboard, ref)`

- `MountPointType _GetMountPointType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EmitProjectileUseAbilitySelector : ActionNode, IActionNodeSource
{
	private MountPointType _mountPoint; // 0x10
	private Event _ev; // 0x14
	public ActionNode[] _actions; // 0x18
	private Boolean _overwriteActions; // 0x20
	private ActionTargetType _sourceType; // 0x24
	private ActionTargetType _targetType; // 0x28
	private Boolean _hookStartPoint; // 0x2c
	private ActionTargetType _startPointTarget; // 0x30
	private String _abilityName; // 0x38
	private String _projectileKey; // 0x40
	private Boolean _useAbilityFromOther; // 0x48
	private ActionTargetType _abilityOwner; // 0x4c
	private List`1 _buffDataList; // 0x50
	private Boolean _overwriteBuffs; // 0x58
	private Boolean _extraBlackboard; // 0x59
	private Boolean _overwriteBlackboard; // 0x5a
	private Boolean _useMountPointGroup; // 0x5b
	private MountPointGroup _mountPointGroup; // 0x60
	private Boolean _cacheAtkToActions; // 0x68
	private Int32 _emitCount; // 0x6c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x10
	private static DelegateBridge __Hotfix0__CreateProjectileInternal; // 0x18
	private static DelegateBridge __Hotfix0__GetMountPointType; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override SourceType allowedSource { get; }

	// RVA: 0x1f78568 VA: 0x7594590568
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f785d0 VA: 0x75945905d0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f78ec4 VA: 0x7594590ec4
	public Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1f78c5c VA: 0x7594590c5c
	private Boolean _CreateProjectileInternal(String projectileKey, Entity source, Entity target, Entity startMountTarget, SourceType sourceType, Blackboard blackboard, ref Snapshot snapshot) { }
	// RVA: 0x1f78f4c VA: 0x7594590f4c
	private MountPointType _GetMountPointType() { }
	// RVA: 0x1f78fd8 VA: 0x7594590fd8
	public Void .ctor() { }
}
```