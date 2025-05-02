# InterruptAbility

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `String _abilityName`

- `Boolean _loadFromBlackboard`

- `Boolean _stopAffect`

- `Boolean _emitAttackFinishOnly`

- `Boolean _useCurrentAbility`


## Properties

- `Boolean useBlackboardAbility`


## Methods

- `Boolean get_useBlackboardAbility()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InterruptAbility : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private String _abilityName; // 0x18
	private Boolean _loadFromBlackboard; // 0x20
	private Boolean _stopAffect; // 0x21
	private Boolean _emitAttackFinishOnly; // 0x22
	private Boolean _useCurrentAbility; // 0x23
	private static DelegateBridge __Hotfix0_get_useBlackboardAbility; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected Boolean useBlackboardAbility { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fc72b8 VA: 0x75945df2b8
	protected Boolean get_useBlackboardAbility() { }
	// RVA: 0x1fc7328 VA: 0x75945df328
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc7390 VA: 0x75945df390
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc760c VA: 0x75945df60c
	public Void .ctor() { }
}
```