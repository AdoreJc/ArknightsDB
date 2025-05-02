# AssignEnemyRouteDistToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `ActionTargetType _buffTarget`

- `String _buffkey`

- `String _blackBoardkey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignEnemyRouteDistToBB : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ActionTargetType _buffTarget; // 0x14
	private String _buffkey; // 0x18
	private String _blackBoardkey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f31b4c VA: 0x7594549b4c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f31bb4 VA: 0x7594549bb4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f31dbc VA: 0x7594549dbc
	public Void .ctor() { }
}
```