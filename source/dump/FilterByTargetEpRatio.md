# FilterByTargetEpRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `CompareType _condType`

- `Single _epRatio`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByTargetEpRatio : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private CompareType _condType; // 0x14
	private Single _epRatio; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f16f80 VA: 0x759452ef80
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f16fe8 VA: 0x759452efe8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f172cc VA: 0x759452f2cc
	public Void .ctor() { }
}
```