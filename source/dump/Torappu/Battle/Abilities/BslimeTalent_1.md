# BslimeTalent_1

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `ActionArray _projectileActions`


## Methods

- `Void GatherProjectileFromBuffs(BuffData[], List`1)`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BslimeTalent_1 : AbilityStandard, IActionNodeSource, IBuffSource
{
	protected BuffData[] _buffs; // 0x108
	protected ActionArray _projectileActions; // 0x110
	protected BuffData[] _projectileBuffs; // 0x118
	protected Event[] _ignoredProjectileEvents; // 0x120
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x0
	private static DelegateBridge __Hotfix0_get_category; // 0x8
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x10
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x18
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x20
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x28
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x30
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x38
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x40
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x48
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x50
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x58
	private static DelegateBridge __Hotfix0_GatherProjectileFromBuffs; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override FP cooldown { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x1e6c0a8 VA: 0x75944840a8
	public override FP get_cooldown() { }
	// RVA: 0x1e6c138 VA: 0x7594484138
	public override Category get_category() { }
	// RVA: 0x1e6c1a0 VA: 0x75944841a0
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e6c204 VA: 0x7594484204
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e6c268 VA: 0x7594484268
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1e6c30c VA: 0x759448430c
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e6c384 VA: 0x7594484384
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e6c4a0 VA: 0x75944844a0
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e6c508 VA: 0x7594484508
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e6c570 VA: 0x7594484570
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e6c634 VA: 0x7594484634
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e6c6f8 VA: 0x75944846f8
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e6c79c VA: 0x759448479c
	private Void GatherProjectileFromBuffs(BuffData[] buffs, List`1 projectiles) { }
	// RVA: 0x1e6ca8c VA: 0x7594484a8c
	public Void .ctor() { }
	// RVA: 0x1e6cb78 VA: 0x7594484b78
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
	// RVA: 0x1e6cb80 VA: 0x7594484b80
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
}
```