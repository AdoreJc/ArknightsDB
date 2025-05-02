# InterruptCharacterSkill

**Namespace:** ` `


## Fields

- `Boolean _switchOutFromSkillState`

- `Boolean _interruptSkillSelf`

- `ActionTargetType _charFrom`

- `Boolean _resetAbilityCooldown`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InterruptCharacterSkill : ActionNode
{
	private Boolean _switchOutFromSkillState; // 0x10
	private Boolean _interruptSkillSelf; // 0x11
	private ActionTargetType _charFrom; // 0x14
	private Boolean _resetAbilityCooldown; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0e518 VA: 0x7594526518
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0e580 VA: 0x7594526580
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0e7b4 VA: 0x75945267b4
	public Void .ctor() { }
}
```