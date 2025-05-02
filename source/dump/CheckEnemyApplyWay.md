# CheckEnemyApplyWay

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `SourceApplyWay _applyWay`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyApplyWay : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private SourceApplyWay _applyWay; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f94858 VA: 0x75945ac858
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f948c0 VA: 0x75945ac8c0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f94a88 VA: 0x75945aca88
	public Void .ctor() { }
}
```