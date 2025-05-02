# CreepTileLogAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _tileMode`


## Methods

- `Void _LogOnGameOver(Object)`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class CreepTileLogAbility : AbilityStandard
{
	private Int32 _tileMode; // 0x108
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
	private static DelegateBridge __Hotfix0_OnAttached; // 0x50
	private static DelegateBridge __Hotfix0_OnDetached; // 0x58
	private static DelegateBridge __Hotfix0__LogOnGameOver; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override FP cooldown { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x1e702b4 VA: 0x75944882b4
	public override FP get_cooldown() { }
	// RVA: 0x1e70344 VA: 0x7594488344
	public override Category get_category() { }
	// RVA: 0x1e703ac VA: 0x75944883ac
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e70410 VA: 0x7594488410
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e70474 VA: 0x7594488474
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e704ec VA: 0x75944884ec
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e7056c VA: 0x759448856c
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e705d0 VA: 0x75944885d0
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e70634 VA: 0x7594488634
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e706f8 VA: 0x75944886f8
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e707bc VA: 0x75944887bc
	protected override Void OnAttached() { }
	// RVA: 0x1e708d0 VA: 0x75944888d0
	protected override Void OnDetached() { }
	// RVA: 0x1e709e4 VA: 0x75944889e4
	private Void _LogOnGameOver(Object arg) { }
	// RVA: 0x1e70d14 VA: 0x7594488d14
	public Void .ctor() { }
	// RVA: 0x1e70d84 VA: 0x7594488d84
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e70d8c VA: 0x7594488d8c
	private Void <>xLuaBaseProxy_OnDetached() { }
}
```