# RecordAbilityRemainingTime

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `String _abilityName`

- `String _recordKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RecordAbilityRemainingTime : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private String _abilityName; // 0x18
	private String _recordKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc79f4 VA: 0x75945df9f4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc7a5c VA: 0x75945dfa5c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc7c54 VA: 0x75945dfc54
	public Void .ctor() { }
}
```