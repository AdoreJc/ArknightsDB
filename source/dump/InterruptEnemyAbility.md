# InterruptEnemyAbility

**Namespace:** ` `


## Fields

- `ActionTargetType _enemyFrom`

- `Boolean _resetCooldown`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InterruptEnemyAbility : ActionNode
{
	private ActionTargetType _enemyFrom; // 0x10
	private Boolean _resetCooldown; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0dfc0 VA: 0x7594525fc0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0e028 VA: 0x7594526028
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0e19c VA: 0x759452619c
	public Void .ctor() { }
}
```