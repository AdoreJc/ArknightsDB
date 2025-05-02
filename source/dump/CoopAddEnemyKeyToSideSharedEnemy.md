# CoopAddEnemyKeyToSideSharedEnemy

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CoopAddEnemyKeyToSideSharedEnemy : ActionNode
{
	private ActionTargetType _target; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f39248 VA: 0x7594551248
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f392b0 VA: 0x75945512b0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f394a8 VA: 0x75945514a8
	public Void .ctor() { }
}
```