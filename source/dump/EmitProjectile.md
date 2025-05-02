# EmitProjectile

**Namespace:** ` `


## Fields

- `MountPointType _mountPoint`

- `Boolean _emitOnRootTile`

- `Event _ev`

- `Boolean _overwriteActions`

- `Boolean _overwriteBuffs`

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `String _projectileKey`

- `Boolean _useProjectileAsTarget`

- `Boolean _extraBlackboard`

- `Boolean _overwriteBlackboard`

- `Boolean _useTileAsTarget`

- `Boolean _useAbilityTileSelector`

- `String _abilityName`


## Methods

- `Void GatherActionNodes(List`1)`

- `Boolean _TryGetProjectileTarget(Entity, ref, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EmitProjectile : ActionNode, IActionNodeSource
{
	private MountPointType _mountPoint; // 0x10
	private Boolean _emitOnRootTile; // 0x14
	private Event _ev; // 0x18
	public ActionNode[] _actions; // 0x20
	private Boolean _overwriteActions; // 0x28
	private List`1 _buffDataList; // 0x30
	private Boolean _overwriteBuffs; // 0x38
	private ActionTargetType _sourceType; // 0x3c
	private ActionTargetType _targetType; // 0x40
	private String _projectileKey; // 0x48
	private Boolean _useProjectileAsTarget; // 0x50
	private Boolean _extraBlackboard; // 0x51
	private Boolean _overwriteBlackboard; // 0x52
	private Boolean _useTileAsTarget; // 0x53
	private Boolean _useAbilityTileSelector; // 0x54
	private String _abilityName; // 0x58
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x10
	private static DelegateBridge __Hotfix0__TryGetProjectileTarget; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }

	// RVA: 0x1f76c0c VA: 0x759458ec0c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f76c74 VA: 0x759458ec74
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f77378 VA: 0x759458f378
	public Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1f7705c VA: 0x759458f05c
	private Boolean _TryGetProjectileTarget(Entity source, ref Snapshot snapshot, out ILocatable projetileTarget) { }
	// RVA: 0x1f77400 VA: 0x759458f400
	public Void .ctor() { }
}
```