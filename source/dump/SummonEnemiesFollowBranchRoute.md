# SummonEnemiesFollowBranchRoute

**Namespace:** ` `


## Fields

- `Boolean _unharmful`

- `Boolean _managedByScheduler`

- `Boolean _alwaysCountAsKilled`

- `Boolean _disableBornTweenColor`

- `BuffData _buffToEnemy`

- `String _overrideEnemyKey`

- `Boolean _setHostUid`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SummonEnemiesFollowBranchRoute : ActionNode, IBuffSource, ICreateBuffNode
{
	private Boolean _unharmful; // 0x10
	private Boolean _managedByScheduler; // 0x11
	private Boolean _alwaysCountAsKilled; // 0x12
	private Boolean _disableBornTweenColor; // 0x13
	private BuffData _buffToEnemy; // 0x18
	private String _overrideEnemyKey; // 0x20
	private Boolean _setHostUid; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1fdb558 VA: 0x75945f3558
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fdb5c0 VA: 0x75945f35c0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fdb888 VA: 0x75945f3888
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1fdb9a4 VA: 0x75945f39a4
	public Void .ctor() { }
}
```