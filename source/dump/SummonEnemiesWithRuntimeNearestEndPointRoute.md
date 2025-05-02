# SummonEnemiesWithRuntimeNearestEndPointRoute

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `String _enemyKey`

- `Int32 _summonCount`

- `MotionMode _motionMode`

- `Boolean _unharmful`

- `Boolean _alwaysCountAsKilled`

- `Single _waitTime`

- `Boolean _summonOnNearestPassableTile`

- `Single _spawnOffset`

- `Boolean _managedByScheduler`

- `Boolean _ignoreMissEndPoint`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SummonEnemiesWithRuntimeNearestEndPointRoute : ActionNode, IBuffSource, ICreateBuffNode
{
	private ActionTargetType _source; // 0x10
	private String _enemyKey; // 0x18
	private Int32 _summonCount; // 0x20
	private MotionMode _motionMode; // 0x24
	private Boolean _unharmful; // 0x28
	private Boolean _alwaysCountAsKilled; // 0x29
	private Single _waitTime; // 0x2c
	private Boolean _summonOnNearestPassableTile; // 0x30
	private Single _spawnOffset; // 0x34
	private Boolean _managedByScheduler; // 0x38
	private Boolean _ignoreMissEndPoint; // 0x39
	private List`1 _buffs; // 0x40
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1fde664 VA: 0x75945f6664
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fde6cc VA: 0x75945f66cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fdec08 VA: 0x75945f6c08
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1fdeca8 VA: 0x75945f6ca8
	public Void .ctor() { }
}
```