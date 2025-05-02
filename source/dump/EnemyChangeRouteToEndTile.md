# EnemyChangeRouteToEndTile

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyChangeRouteToEndTile : ActionNode
{
	private ActionTargetType _target; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f58a2c VA: 0x7594570a2c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f58a94 VA: 0x7594570a94
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f58ce4 VA: 0x7594570ce4
	public Void .ctor() { }
}
```