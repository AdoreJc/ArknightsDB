# CheckEnemyAbilityName

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _abilityName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyAbilityName : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _abilityName; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f3048c VA: 0x759454848c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f304f4 VA: 0x75945484f4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f306f0 VA: 0x75945486f0
	public Void .ctor() { }
}
```