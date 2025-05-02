# SummonEnemiesOnTargetTile

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `String _enemyKey`

- `Int32 _summonCount`

- `FP _randomOffsetBound`

- `Boolean _selectTileInSnapshot`

- `Boolean _useProjectileTraceTargetMapPos`

- `Single _delayTime`

- `Boolean _addBuffToEnemy`

- `Boolean _unharmful`

- `BuffData _buffToEnemy`

- `MotionMask _checkMotionMode`

- `Boolean _managedByScheduler`

- `Boolean _excludeRootTile`


## Properties

- `Boolean addBuffToEnemy`


## Methods

- `Boolean get_addBuffToEnemy()`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SummonEnemiesOnTargetTile : ActionNode, IBuffSource
{
	private ActionTargetType _source; // 0x10
	private String _enemyKey; // 0x18
	private Int32 _summonCount; // 0x20
	private FP _randomOffsetBound; // 0x28
	private Boolean _selectTileInSnapshot; // 0x30
	private Boolean _useProjectileTraceTargetMapPos; // 0x31
	private Single _delayTime; // 0x34
	private Boolean _addBuffToEnemy; // 0x38
	private Boolean _unharmful; // 0x39
	private BuffData _buffToEnemy; // 0x40
	private MotionMask _checkMotionMode; // 0x48
	private Boolean _managedByScheduler; // 0x4c
	private Boolean _excludeRootTile; // 0x4d
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_addBuffToEnemy; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	private Boolean addBuffToEnemy { get; }

	// RVA: 0x1fdf140 VA: 0x75945f7140
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fdf1a8 VA: 0x75945f71a8
	private Boolean get_addBuffToEnemy() { }
	// RVA: 0x1fdf210 VA: 0x75945f7210
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1fdf32c VA: 0x75945f732c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fdfaa8 VA: 0x75945f7aa8
	public Void .ctor() { }
}
```