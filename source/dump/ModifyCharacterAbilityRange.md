# ModifyCharacterAbilityRange

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `ActionTargetType _source`

- `String _abilityName`

- `String _rangeId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyCharacterAbilityRange : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ActionTargetType _source; // 0x14
	private String _abilityName; // 0x18
	private String _rangeId; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc5fa8 VA: 0x75945ddfa8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc6010 VA: 0x75945de010
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc6458 VA: 0x75945de458
	public Void .ctor() { }
}
```