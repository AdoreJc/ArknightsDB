# SummonEnemyWithRuntimeRoute

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`

- `Boolean _useSpecialHost`

- `ActionTargetType _host`

- `Boolean _useRandomEnemy`

- `String _enemyKey`

- `MotionMode _motionMode`

- `Boolean _unharmful`

- `Boolean _alwaysCountAsKilled`

- `Single _waitTime`

- `Single _spawnOffset`

- `Boolean _selectTileInSnapshot`

- `Boolean _useSourceEndPosition`

- `Boolean _avoidHighland`


## Properties

- `Boolean useSpecialHost`


## Methods

- `Boolean get_useSpecialHost()`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SummonEnemyWithRuntimeRoute : ActionNode, IBuffSource, ICreateBuffNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private Boolean _useSpecialHost; // 0x18
	private ActionTargetType _host; // 0x1c
	private Boolean _useRandomEnemy; // 0x20
	private String _enemyKey; // 0x28
	private MotionMode _motionMode; // 0x30
	private Boolean _unharmful; // 0x34
	private Boolean _alwaysCountAsKilled; // 0x35
	private Single _waitTime; // 0x38
	private Single _spawnOffset; // 0x3c
	private Boolean _selectTileInSnapshot; // 0x40
	private List`1 _buffs; // 0x48
	private Boolean _useSourceEndPosition; // 0x50
	private Boolean _avoidHighland; // 0x51
	private static DelegateBridge __Hotfix0_get_useSpecialHost; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean useSpecialHost { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fdd1f0 VA: 0x75945f51f0
	public Boolean get_useSpecialHost() { }
	// RVA: 0x1fdd258 VA: 0x75945f5258
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fdd2c0 VA: 0x75945f52c0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fdd940 VA: 0x75945f5940
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1fdd9e0 VA: 0x75945f59e0
	public Void .ctor() { }
}
```