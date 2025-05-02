# UnitSummonApopsisEnemy

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `String _enemyKey`

- `MotionMode _motionMode`

- `Boolean _unharmful`

- `Boolean _alwaysCountAsKilled`

- `Boolean _addBuffToEnemy`

- `BuffData _buffToEnemy`


## Properties

- `Boolean addBuffToEnemy`


## Methods

- `Boolean get_addBuffToEnemy()`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UnitSummonApopsisEnemy : ActionNode, IBuffSource
{
	private ActionTargetType _source; // 0x10
	private String _enemyKey; // 0x18
	private MotionMode _motionMode; // 0x20
	private Boolean _unharmful; // 0x24
	private Boolean _alwaysCountAsKilled; // 0x25
	private Boolean _addBuffToEnemy; // 0x26
	private BuffData _buffToEnemy; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_addBuffToEnemy; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	private Boolean addBuffToEnemy { get; }

	// RVA: 0x1f7f82c VA: 0x759459782c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7f894 VA: 0x7594597894
	private Boolean get_addBuffToEnemy() { }
	// RVA: 0x1f7f8fc VA: 0x75945978fc
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f7fa18 VA: 0x7594597a18
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7ff5c VA: 0x7594597f5c
	public Void .ctor() { }
}
```