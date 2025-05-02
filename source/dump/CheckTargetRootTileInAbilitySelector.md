# CheckTargetRootTileInAbilitySelector

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `ActionTargetType _abilityOwnerType`

- `String _abilityName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTargetRootTileInAbilitySelector : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private ActionTargetType _abilityOwnerType; // 0x14
	private String _abilityName; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2d420 VA: 0x7594545420
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2d488 VA: 0x7594545488
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2d76c VA: 0x759454576c
	public Void .ctor() { }
}
```