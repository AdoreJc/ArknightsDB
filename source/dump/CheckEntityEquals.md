# CheckEntityEquals

**Namespace:** ` `


## Fields

- `ActionTargetType _lhsType`

- `ActionTargetType _rhsType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEntityEquals : ActionNode
{
	private ActionTargetType _lhsType; // 0x10
	private ActionTargetType _rhsType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f15514 VA: 0x759452d514
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1557c VA: 0x759452d57c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f15694 VA: 0x759452d694
	public Void .ctor() { }
}
```