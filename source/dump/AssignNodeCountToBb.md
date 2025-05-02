# AssignNodeCountToBb

**Namespace:** ` `


## Fields

- `String _assignKey`

- `NodeState _state`

- `Boolean _isMainMap`

- `Boolean _isNotChoosedState`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignNodeCountToBb : ActionNode
{
	private String _assignKey; // 0x10
	private NodeState _state; // 0x18
	private Boolean _isMainMap; // 0x1c
	private Boolean _isNotChoosedState; // 0x1d
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8b348 VA: 0x75945a3348
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8b3b0 VA: 0x75945a33b0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8b630 VA: 0x75945a3630
	public Void .ctor() { }
}
```