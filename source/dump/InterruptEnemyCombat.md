# InterruptEnemyCombat

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InterruptEnemyCombat : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f94038 VA: 0x75945ac038
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f940a0 VA: 0x75945ac0a0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f94270 VA: 0x75945ac270
	public Void .ctor() { }
}
```