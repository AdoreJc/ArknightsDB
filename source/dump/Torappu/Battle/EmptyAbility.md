# EmptyAbility

**Namespace:** `Torappu.Battle`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EmptyAbility : AbilityStandard
{
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x0
	private static DelegateBridge __Hotfix0_get_category; // 0x8
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x10
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x18
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x20
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x28
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x30
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x38
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x40
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override FP cooldown { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x3f1d90c VA: 0x759653590c
	public override FP get_cooldown() { }
	// RVA: 0x3f1d99c VA: 0x759653599c
	public override Category get_category() { }
	// RVA: 0x3f1da04 VA: 0x7596535a04
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x3f1da68 VA: 0x7596535a68
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x3f1dacc VA: 0x7596535acc
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x3f1db44 VA: 0x7596535b44
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x3f1dbc4 VA: 0x7596535bc4
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x3f1dc28 VA: 0x7596535c28
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x3f1dc8c VA: 0x7596535c8c
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x3f1dd50 VA: 0x7596535d50
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x3f1de14 VA: 0x7596535e14
	public Void .ctor() { }
}
```