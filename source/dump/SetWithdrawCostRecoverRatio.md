# SetWithdrawCostRecoverRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Single _ratio`

- `Boolean _isReset`

- `Boolean _dontLimitMaxWithdrawCost`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetWithdrawCostRecoverRatio : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Single _ratio; // 0x14
	private Boolean _isReset; // 0x18
	private Boolean _dontLimitMaxWithdrawCost; // 0x19
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc4514 VA: 0x75945dc514
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc457c VA: 0x75945dc57c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc4724 VA: 0x75945dc724
	public Void .ctor() { }
}
```