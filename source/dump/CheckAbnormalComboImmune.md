# CheckAbnormalComboImmune

**Namespace:** ` `


## Fields

- `AbnormalCombo _abnormalCombo`

- `ActionTargetType _targetType`

- `Boolean _isUnset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckAbnormalComboImmune : ActionNode
{
	private AbnormalCombo _abnormalCombo; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Boolean _isUnset; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2a430 VA: 0x7594542430
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2a498 VA: 0x7594542498
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2a5e0 VA: 0x75945425e0
	public Void .ctor() { }
}
```