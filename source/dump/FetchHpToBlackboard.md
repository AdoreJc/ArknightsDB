# FetchHpToBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `DamageType _damageType`

- `String _blackboardStr`

- `String _buffNameOfBlackboard`

- `Boolean _isHpRatio`

- `Boolean _skipModifierEvent`


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`

- `Void PreprocessForProjectile(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FetchHpToBlackboard : ActionNode, IDamageOrHealSourceNode
{
	private ActionTargetType _targetType; // 0x10
	private DamageType _damageType; // 0x14
	private String _blackboardStr; // 0x18
	private String _buffNameOfBlackboard; // 0x20
	private Boolean _isHpRatio; // 0x28
	private Boolean _skipModifierEvent; // 0x29
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_PreprocessForProjectile; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f4d68c VA: 0x759456568c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4d6f4 VA: 0x75945656f4
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f4d75c VA: 0x759456575c
	public Void PreprocessForProjectile(Entity source) { }
	// RVA: 0x1f4d7d4 VA: 0x75945657d4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4db04 VA: 0x7594565b04
	public Void .ctor() { }
}
```