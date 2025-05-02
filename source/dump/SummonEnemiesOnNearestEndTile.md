# SummonEnemiesOnNearestEndTile

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `MotionMode _motionMode`

- `String _enemyKey`

- `Int32 _summonCount`

- `Single _randomOffsetBound`

- `Boolean _unharmful`

- `Boolean _alwaysCountAsKilled`

- `Single _waitTime`

- `Boolean _managedByScheduler`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SummonEnemiesOnNearestEndTile : ActionNode
{
	private ActionTargetType _source; // 0x10
	private MotionMode _motionMode; // 0x14
	private String _enemyKey; // 0x18
	private Int32 _summonCount; // 0x20
	private Single _randomOffsetBound; // 0x24
	private Boolean _unharmful; // 0x28
	private Boolean _alwaysCountAsKilled; // 0x29
	private Single _waitTime; // 0x2c
	private Boolean _managedByScheduler; // 0x30
	private List`1 _buffs; // 0x38
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe0a24 VA: 0x75945f8a24
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe0a8c VA: 0x75945f8a8c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe0e44 VA: 0x75945f8e44
	public Void .ctor() { }
}
```