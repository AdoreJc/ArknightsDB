# RoguelikeInheritEnemyHp

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoguelikeInheritEnemyHp : ActionNode
{
	private ActionTargetType _target; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f80e8c VA: 0x7594598e8c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f80ef4 VA: 0x7594598ef4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f812c4 VA: 0x75945992c4
	public Void .ctor() { }
}
```