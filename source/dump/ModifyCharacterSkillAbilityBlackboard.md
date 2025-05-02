# ModifyCharacterSkillAbilityBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyCharacterSkillAbilityBlackboard : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcefe4 VA: 0x75945e6fe4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcf04c VA: 0x75945e704c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcf218 VA: 0x75945e7218
	public Void .ctor() { }
}
```