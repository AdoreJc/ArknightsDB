# SummonEnemiesOnAttackRange

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `Boolean _useTargetAbilitySelector`

- `ActionTargetType _target`

- `String _abilityName`

- `Boolean _selectTheNearestTileToSource`

- `Boolean _meanwhileNearestTileToTarget`

- `String _enemyKey`

- `Int32 _summonCount`

- `MotionMode _motionMode`

- `Boolean _unharmful`

- `Boolean _alwaysCountAsKilled`

- `Single _waitTime`

- `Single _spawnOffset`


## Methods

- `Tile _GetTheNearestTileToSouece(List`1, Unit)`

- `Tile _GetTheNearestTileToSourceThenTarget(List`1, Unit, Unit)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SummonEnemiesOnAttackRange : ActionNode
{
	private ActionTargetType _source; // 0x10
	private Boolean _useTargetAbilitySelector; // 0x14
	private ActionTargetType _target; // 0x18
	private String _abilityName; // 0x20
	private Boolean _selectTheNearestTileToSource; // 0x28
	private Boolean _meanwhileNearestTileToTarget; // 0x29
	private String _enemyKey; // 0x30
	private Int32 _summonCount; // 0x38
	private MotionMode _motionMode; // 0x3c
	private Boolean _unharmful; // 0x40
	private Boolean _alwaysCountAsKilled; // 0x41
	private Single _waitTime; // 0x44
	private Single _spawnOffset; // 0x48
	private List`1 _buffs; // 0x50
	private const Int32 MAX_DISTANCE; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__GetTheNearestTileToSouece; // 0x10
	private static DelegateBridge __Hotfix0__GetTheNearestTileToSourceThenTarget; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }

	// RVA: 0x1fdfb5c VA: 0x75945f7b5c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fdfbc4 VA: 0x75945f7bc4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe02f4 VA: 0x75945f82f4
	private Tile _GetTheNearestTileToSouece(List`1 tiles, Unit unit) { }
	// RVA: 0x1fe05c8 VA: 0x75945f85c8
	private Tile _GetTheNearestTileToSourceThenTarget(List`1 tiles, Unit source, Unit target) { }
	// RVA: 0x1fe09ac VA: 0x75945f89ac
	public Void .ctor() { }
}
```