# SummonEnemiesFollowMyRouteWithBuff

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

- `Boolean _ignoreOffset`

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

- `Boolean _addNoSourceBuffImmediately`

- `BuffData _noSourceBuff`

- `MotionMask _checkMotionMode`

- `ActionTargetType _buffSource`

- `Boolean _skipCheckPoint`


## Properties

- `Boolean notUseMapPosition`


## Methods

- `Boolean get_notUseMapPosition()`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SummonEnemiesFollowMyRouteWithBuff : ActionNode, IBuffSource, ICreateBuffNode
{
	private ActionTargetType _source; // 0x10
	private String _enemyKey; // 0x18
	private Int32 _summonCount; // 0x20
	private Single _delayTime; // 0x24
	private Boolean _managedByScheduler; // 0x28
	private Boolean _dontBlockWave; // 0x29
	private Boolean _trySummonOutsideWhenInObstacle; // 0x2a
	private Single _randomOffsetBound; // 0x2c
	private Boolean _ignoreOffset; // 0x30
	private MotionMask _passableMask; // 0x34
	private Boolean _onlySummonOneInTheSamePlace; // 0x38
	private Boolean _useOffsetInBB; // 0x39
	private String _offsetXKey; // 0x40
	private String _offsetYKey; // 0x48
	private Vector2 _offset; // 0x50
	private Boolean _useLocalUnharmfulFlag; // 0x58
	private Boolean _unharmful; // 0x59
	private Boolean _useMapPosition; // 0x5a
	private Boolean _spawnOnHostRootTile; // 0x5b
	private Boolean _useTargetPosition; // 0x5c
	private ActionTargetType _targetType; // 0x60
	private Boolean _useRandomDelay; // 0x64
	private Single _randomDelayRange; // 0x68
	private Boolean _stopSummonIfHostDead; // 0x6c
	private Boolean _useOffsetForEach; // 0x6d
	private Boolean _addNoSourceBuffImmediately; // 0x6e
	private BuffData _noSourceBuff; // 0x70
	private MotionMask _checkMotionMode; // 0x78
	private ActionTargetType _buffSource; // 0x7c
	private List`1 _additionalBuff; // 0x80
	private Boolean _skipCheckPoint; // 0x88
	private static DelegateBridge __Hotfix0_get_notUseMapPosition; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Boolean notUseMapPosition { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fdc650 VA: 0x75945f4650
	private Boolean get_notUseMapPosition() { }
	// RVA: 0x1fdc6c0 VA: 0x75945f46c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fdc728 VA: 0x75945f4728
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fdcfb4 VA: 0x75945f4fb4
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1fdd0d0 VA: 0x75945f50d0
	public Void .ctor() { }
}
```