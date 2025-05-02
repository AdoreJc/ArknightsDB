# FilterEnemyAbilityInSnapshot

**Namespace:** ` `


## Fields

- `Boolean _filterAbilityKey`

- `String _abilityKey`

- `Boolean _filterAbilityOwnerKey`

- `String _abilityOwnerKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterEnemyAbilityInSnapshot : ActionNode
{
	private Boolean _filterAbilityKey; // 0x10
	private String _abilityKey; // 0x18
	private Boolean _filterAbilityOwnerKey; // 0x20
	private String _abilityOwnerKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f61ec4 VA: 0x7594579ec4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f61f2c VA: 0x7594579f2c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f620f4 VA: 0x759457a0f4
	public Void .ctor() { }
}
```