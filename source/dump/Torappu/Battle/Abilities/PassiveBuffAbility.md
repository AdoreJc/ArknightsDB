# PassiveBuffAbility

**Namespace:** `Torappu.Battle.Abilities`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class PassiveBuffAbility : AbilityStandard
{
	protected BuffData[] _buffs; // 0x108
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

	// RVA: 0x1e54cdc VA: 0x759446ccdc
	public override FP get_cooldown() { }
	// RVA: 0x1e54d6c VA: 0x759446cd6c
	public override Category get_category() { }
	// RVA: 0x1e54dd4 VA: 0x759446cdd4
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e54e38 VA: 0x759446ce38
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e54e9c VA: 0x759446ce9c
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e54f14 VA: 0x759446cf14
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e54f94 VA: 0x759446cf94
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e54ffc VA: 0x759446cffc
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e55060 VA: 0x759446d060
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e55124 VA: 0x759446d124
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e515a4 VA: 0x75944695a4
	public Void .ctor() { }
}
```