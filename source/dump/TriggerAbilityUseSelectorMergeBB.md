# TriggerAbilityUseSelectorMergeBB

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `String _abilityName`

- `Boolean _excludeTarget`

- `ActionTargetType _excludeTargetType`

- `Boolean _castDirectly`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerAbilityUseSelectorMergeBB : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _abilityName; // 0x18
	private Boolean _excludeTarget; // 0x20
	private ActionTargetType _excludeTargetType; // 0x24
	private Boolean _castDirectly; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f930b8 VA: 0x75945ab0b8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f93120 VA: 0x75945ab120
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f9391c VA: 0x75945ab91c
	public Void .ctor() { }
}
```