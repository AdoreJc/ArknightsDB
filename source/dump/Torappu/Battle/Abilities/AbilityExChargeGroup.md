# AbilityExChargeGroup

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 m_chargeTimes`

- `Int32 m_exChargeTimes`


## Methods

- `Int32 GetChargeTimes()`

- `Int32 GetExChargeTimes()`

- `Void SyncChargeTimes(Int32, Int32)`

- `Int32 GetTotalChargeTimes()`

- `Void GetBothChargeTimes(out, out)`

- `Boolean <>xLuaBaseProxy_get_isReady()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AbilityExChargeGroup : AbilityStandard, IExChargeableSource, IChargeableSource
{
	private ExChargeRangedAttack[] _abilities; // 0x108
	private Int32 m_chargeTimes; // 0x110
	private Int32 m_exChargeTimes; // 0x114
	private static DelegateBridge __Hotfix0_get_category; // 0x0
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x8
	private static DelegateBridge __Hotfix0_get_isReady; // 0x10
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x18
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x20
	private static DelegateBridge __Hotfix0_DoSetData; // 0x28
	private static DelegateBridge __Hotfix0_GetChargeTimes; // 0x30
	private static DelegateBridge __Hotfix0_GetExChargeTimes; // 0x38
	private static DelegateBridge __Hotfix0_SyncChargeTimes; // 0x40
	private static DelegateBridge __Hotfix0_GetTotalChargeTimes; // 0x48
	private static DelegateBridge __Hotfix0_GetBothChargeTimes; // 0x50
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x58
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x60
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x68
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x70
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x78
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public override Category category { get; }
	public override FP cooldown { get; }
	public override Boolean isReady { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x1e30244 VA: 0x7594448244
	public override Category get_category() { }
	// RVA: 0x1e302ac VA: 0x75944482ac
	public override FP get_cooldown() { }
	// RVA: 0x1e3033c VA: 0x759444833c
	public override Boolean get_isReady() { }
	// RVA: 0x1e303a4 VA: 0x75944483a4
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e30408 VA: 0x7594448408
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e3046c VA: 0x759444846c
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e30594 VA: 0x7594448594
	public Int32 GetChargeTimes() { }
	// RVA: 0x1e306fc VA: 0x75944486fc
	public Int32 GetExChargeTimes() { }
	// RVA: 0x1e30864 VA: 0x7594448864
	public Void SyncChargeTimes(Int32 chargeTimes, Int32 exChargeTimes) { }
	// RVA: 0x1e308ec VA: 0x75944488ec
	public Int32 GetTotalChargeTimes() { }
	// RVA: 0x1e3095c VA: 0x759444895c
	public Void GetBothChargeTimes(out Int32 chargeTimes, out Int32 exChargeTimes) { }
	// RVA: 0x1e309ec VA: 0x75944489ec
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e30a64 VA: 0x7594448a64
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e30ae4 VA: 0x7594448ae4
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e30b48 VA: 0x7594448b48
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e30bac VA: 0x7594448bac
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e30c70 VA: 0x7594448c70
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e30d34 VA: 0x7594448d34
	public Void .ctor() { }
	// RVA: 0x1e30da4 VA: 0x7594448da4
	private Boolean <>xLuaBaseProxy_get_isReady() { }
	// RVA: 0x1e30dac VA: 0x7594448dac
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
}
```