# WithCooldownTargetValidator

**Namespace:** `Torappu.Battle`


## Fields

- `Single _cooldown`


## Methods

- `Boolean _CheckTargetValidateCooldown(Entity)`

- `Void _UpdateTargetValidateCooldown(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class WithCooldownTargetValidator : TargetValidator
{
	private Single _cooldown; // 0x8c
	private readonly ListDict`2 m_targetCooldownDict; // 0x90


	// RVA: 0x1bdc370 VA: 0x75941f4370
	private Boolean _CheckTargetValidateCooldown(Entity target) { }
	// RVA: 0x1bdc4c4 VA: 0x75941f44c4
	private Void _UpdateTargetValidateCooldown(Entity target) { }
	// RVA: 0x1bdc5d8 VA: 0x75941f45d8
	public override Boolean Validate(Entity target) { }
	// RVA: 0x1bdc624 VA: 0x75941f4624
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1bdc710 VA: 0x75941f4710
	public override Void SetData(Entity owner, Blackboard blackboard, Boolean ignoreTargetSide) { }
	// RVA: 0x1bdc7a4 VA: 0x75941f47a4
	public Void .ctor() { }
}
```