# CheckAbnormalFlags

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckAbnormalFlags : ActionNode
{
	private List`1 _abnormalFlags; // 0x10
	private ActionTargetType _targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f18c88 VA: 0x7594530c88
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f18cf0 VA: 0x7594530cf0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f18f78 VA: 0x7594530f78
	public Void .ctor() { }
}
```