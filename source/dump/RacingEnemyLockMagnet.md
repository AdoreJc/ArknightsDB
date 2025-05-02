# RacingEnemyLockMagnet

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`

- `Boolean _unlock`

- `Single _magnetSpeed`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RacingEnemyLockMagnet : ActionNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private Boolean _unlock; // 0x18
	private Single _magnetSpeed; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7b360 VA: 0x7594593360
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7b3c8 VA: 0x75945933c8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7b68c VA: 0x759459368c
	public Void .ctor() { }
}
```