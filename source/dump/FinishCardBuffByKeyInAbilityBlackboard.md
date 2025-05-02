# FinishCardBuffByKeyInAbilityBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _abilityName`

- `InfoType _infoType`

- `String _cardBuffKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishCardBuffByKeyInAbilityBlackboard : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _abilityName; // 0x18
	private InfoType _infoType; // 0x20
	private String _cardBuffKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f089c4 VA: 0x75945209c4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f08a2c VA: 0x7594520a2c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f08db0 VA: 0x7594520db0
	public Void .ctor() { }
}
```