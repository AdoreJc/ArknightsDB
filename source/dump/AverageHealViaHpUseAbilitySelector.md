# AverageHealViaHpUseAbilitySelector

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Boolean _getMaxHpFromTarget`

- `Boolean _ignoreHealFree`

- `Boolean _skipModifierEvent`

- `Boolean _alsoEpHeal`

- `Boolean _useCurHp`

- `String _abilityName`

- `Boolean _excludeTarget`

- `String _effectKey`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AverageHealViaHpUseAbilitySelector : ActionNode, IEffectSource
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Boolean _getMaxHpFromTarget; // 0x18
	private Boolean _ignoreHealFree; // 0x19
	private Boolean _skipModifierEvent; // 0x1a
	private Boolean _alsoEpHeal; // 0x1b
	private Boolean _useCurHp; // 0x1c
	private String _abilityName; // 0x20
	private Boolean _excludeTarget; // 0x28
	private String _effectKey; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f5fa10 VA: 0x7594577a10
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5fa78 VA: 0x7594577a78
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f5fae0 VA: 0x7594577ae0
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1f5fbf4 VA: 0x7594577bf4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f60534 VA: 0x7594578534
	public Void .ctor() { }
}
```