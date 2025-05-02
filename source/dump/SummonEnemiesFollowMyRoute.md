# SummonEnemiesFollowMyRoute

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `String _enemyKey`

- `Int32 _summonCount`

- `Single _delayTime`

- `Boolean _managedByScheduler`

- `Boolean _dontBlockWave`

- `Boolean _trySummonOutsideWhenInObstacle`

- `Single _randomOffsetBound`

- `MotionMask _passableMask`

- `Boolean _onlySummonOneInTheSamePlace`

- `Boolean _useOffsetInBB`

- `String _offsetXKey`

- `String _offsetYKey`

- `Vector2 _offset`

- `Boolean _useLocalUnharmfulFlag`

- `Boolean _unharmful`

- `Boolean _useMapPosition`

- `Boolean _spawnOnHostRootTile`

- `Boolean _useTargetPosition`

- `ActionTargetType _targetType`

- `Boolean _useRandomDelay`

- `Single _randomDelayRange`

- `Boolean _stopSummonIfHostDead`

- `Boolean _useOffsetForEach`

- `Boolean _addBuffToEnemy`

- `BuffData _buffToEnemy`

- `MotionMask _checkMotionMode`

- `Boolean _skipCheckPoint`


## Properties

- `Boolean addBuffToEnemy`

- `Boolean notUseMapPosition`


## Methods

- `Boolean get_addBuffToEnemy()`

- `Boolean get_notUseMapPosition()`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SummonEnemiesFollowMyRoute : ActionNode, IBuffSource, ICreateBuffNode
{
	private ActionTargetType _source; // 0x10
	private String _enemyKey; // 0x18
	private Int32 _summonCount; // 0x20
	private Single _delayTime; // 0x24
	private Boolean _managedByScheduler; // 0x28
	private Boolean _dontBlockWave; // 0x29
	private Boolean _trySummonOutsideWhenInObstacle; // 0x2a
	private Single _randomOffsetBound; // 0x2c
	private MotionMask _passableMask; // 0x30
	private Boolean _onlySummonOneInTheSamePlace; // 0x34
	private Boolean _useOffsetInBB; // 0x35
	private String _offsetXKey; // 0x38
	private String _offsetYKey; // 0x40
	private Vector2 _offset; // 0x48
	private Boolean _useLocalUnharmfulFlag; // 0x50
	private Boolean _unharmful; // 0x51
	private Boolean _useMapPosition; // 0x52
	private Boolean _spawnOnHostRootTile; // 0x53
	private Boolean _useTargetPosition; // 0x54
	private ActionTargetType _targetType; // 0x58
	private Boolean _useRandomDelay; // 0x5c
	private Single _randomDelayRange; // 0x60
	private Boolean _stopSummonIfHostDead; // 0x64
	private Boolean _useOffsetForEach; // 0x65
	private Boolean _addBuffToEnemy; // 0x66
	private BuffData _buffToEnemy; // 0x68
	private MotionMask _checkMotionMode; // 0x70
	private Boolean _skipCheckPoint; // 0x74
	private static DelegateBridge __Hotfix0_get_addBuffToEnemy; // 0x0
	private static DelegateBridge __Hotfix0_get_notUseMapPosition; // 0x8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Boolean addBuffToEnemy { get; }
	private Boolean notUseMapPosition { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fdba54 VA: 0x75945f3a54
	private Boolean get_addBuffToEnemy() { }
	// RVA: 0x1fdbabc VA: 0x75945f3abc
	private Boolean get_notUseMapPosition() { }
	// RVA: 0x1fdbb2c VA: 0x75945f3b2c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fdbb94 VA: 0x75945f3b94
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fdc4ac VA: 0x75945f44ac
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1fdc5c8 VA: 0x75945f45c8
	public Void .ctor() { }
}
```