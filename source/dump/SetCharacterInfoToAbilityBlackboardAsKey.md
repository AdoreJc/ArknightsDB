# SetCharacterInfoToAbilityBlackboardAsKey

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `String _abilityName`

- `InfoType _infoType`

- `Single _value`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetCharacterInfoToAbilityBlackboardAsKey : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _abilityName; // 0x18
	private InfoType _infoType; // 0x20
	private Single _value; // 0x24
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcd3b8 VA: 0x75945e53b8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcd420 VA: 0x75945e5420
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcd71c VA: 0x75945e571c
	public Void .ctor() { }
}
```