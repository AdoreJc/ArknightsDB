# FilterByTargetSpRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `CompareType _condType`

- `Single _spRatio`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByTargetSpRatio : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private CompareType _condType; // 0x14
	private Single _spRatio; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f17810 VA: 0x759452f810
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f17878 VA: 0x759452f878
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f17a7c VA: 0x759452fa7c
	public Void .ctor() { }
}
```