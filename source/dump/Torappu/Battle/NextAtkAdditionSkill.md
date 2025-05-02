# NextAtkAdditionSkill

**Namespace:** `Torappu.Battle`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class NextAtkAdditionSkill : NextAttackOrCombatSkill
{
	private static DelegateBridge __Hotfix0_CheckIfToModify; // 0x0
	private static DelegateBridge __Hotfix0_ApplyModification; // 0x8
	private static DelegateBridge __Hotfix0_CancelAfterAttack; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1b703b0 VA: 0x75941883b0
	protected override Boolean CheckIfToModify(Ability atkOrCbt, Boolean isCombat) { }
	// RVA: 0x1b70454 VA: 0x7594188454
	protected override Void ApplyModification() { }
	// RVA: 0x1b704e8 VA: 0x75941884e8
	protected override Boolean CancelAfterAttack(Ability atkOrCbt, Boolean isCombat, FinishReason reason) { }
	// RVA: 0x1b705c0 VA: 0x75941885c0
	public Void .ctor() { }
}
```