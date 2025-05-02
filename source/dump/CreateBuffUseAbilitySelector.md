# CreateBuffUseAbilitySelector

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `String _abilityName`

- `Boolean _excludeTarget`

- `ActionTargetType _excludeTargetType`

- `BuffData _buff`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffUseAbilitySelector : ActionNode, ICreateBuffNode, IBuffSource
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _abilityName; // 0x18
	private Boolean _excludeTarget; // 0x20
	private ActionTargetType _excludeTargetType; // 0x24
	private BuffData _buff; // 0x28
	private Boolean _isDerivedBuff; // 0x30
	private Boolean _finishDerivedBuffIfParentFinish; // 0x31
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f02278 VA: 0x759451a278
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f022e0 VA: 0x759451a2e0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f02c28 VA: 0x759451ac28
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f02d1c VA: 0x759451ad1c
	public Void .ctor() { }
}
```