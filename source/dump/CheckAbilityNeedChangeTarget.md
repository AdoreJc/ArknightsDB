# CheckAbilityNeedChangeTarget

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `String _abilityName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckAbilityNeedChangeTarget : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private String _abilityName; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2583c VA: 0x759453d83c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f258a4 VA: 0x759453d8a4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f25d78 VA: 0x759453dd78
	public Void .ctor() { }
}
```