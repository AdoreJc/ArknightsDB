# InterruptCharacterAbility

**Namespace:** ` `


## Fields

- `ActionTargetType _charFrom`

- `String _abilityName`

- `Boolean _needStopAffect`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InterruptCharacterAbility : ActionNode
{
	private ActionTargetType _charFrom; // 0x10
	private String _abilityName; // 0x18
	private Boolean _needStopAffect; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0e82c VA: 0x759452682c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0e894 VA: 0x7594526894
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0ea90 VA: 0x7594526a90
	public Void .ctor() { }
}
```