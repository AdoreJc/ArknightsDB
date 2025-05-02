# FilterChargeTimes

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _times`

- `Boolean _isExCharge`

- `CompareType _compareType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterChargeTimes : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _times; // 0x14
	private Boolean _isExCharge; // 0x18
	private CompareType _compareType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcf564 VA: 0x75945e7564
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcf5cc VA: 0x75945e75cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcf918 VA: 0x75945e7918
	public Void .ctor() { }
}
```