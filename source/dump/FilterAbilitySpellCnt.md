# FilterAbilitySpellCnt

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `CompareType _condType`

- `Single _compareValue`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterAbilitySpellCnt : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private CompareType _condType; // 0x14
	private Single _compareValue; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2fa24 VA: 0x7594547a24
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2fa8c VA: 0x7594547a8c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2fc5c VA: 0x7594547c5c
	public Void .ctor() { }
}
```