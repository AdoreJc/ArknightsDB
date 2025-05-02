# FilterByTargetHp

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByTargetHp : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private CompareType _condType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1733c VA: 0x759452f33c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f173a4 VA: 0x759452f3a4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f17594 VA: 0x759452f594
	public Void .ctor() { }
}
```