# CheckUnitInAttackState

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `Boolean _isUnset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckUnitInAttackState : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private Boolean _isUnset; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f28d44 VA: 0x7594540d44
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f28dac VA: 0x7594540dac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f28f34 VA: 0x7594540f34
	public Void .ctor() { }
}
```