# ChargeRangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _maxChargeTimes`

- `Int32 m_chargeTimes`

- `Boolean m_isChargeAction`

- `Int32 m_maxChargeTimes`

- `IChargeableAbilityCounter <chargeCounter>k__BackingField`


## Properties

- `Boolean isChargeAction`

- `Int32 maxChargeTimes`

- `IChargeableAbilityCounter chargeCounter`


## Methods

- `Boolean get_isChargeAction()`

- `Int32 get_maxChargeTimes()`

- `Void set_maxChargeTimes(Int32)`

- `Boolean BaseCastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Void OnChargeCastEvent(Event)`

- `Void FinishAbility(FinishReason)`

- `Int32 GetChargeTimes()`

- `Boolean GetIsChargeAction()`

- `Void MergeAtkScale(FP)`

- `Void ResetAtkScale()`

- `IChargeableAbilityCounter get_chargeCounter()`

- `Void set_chargeCounter(IChargeableAbilityCounter)`

- `Void SetChargeCounter(IChargeableAbilityCounter)`

- `Void SetChargeTimes(Int32)`

- `Boolean <>xLuaBaseProxy_get_isReady()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable, out)`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay()`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ChargeRangedAttack : RangedAttack, IChargeableAttackAbilityReactor, IChargeableAbilityReactor, IChargeableAbility, IMultiChargeUberEffectEmitterAbility, IChargeableSource
{
	private Int32 _maxChargeTimes; // 0x25c
	private List`1 _mountPointForProjectiles; // 0x260
	private Int32 m_chargeTimes; // 0x268
	private Boolean m_isChargeAction; // 0x26c
	private Int32 m_maxChargeTimes; // 0x270
	private IChargeableAbilityCounter <chargeCounter>k__BackingField; // 0x278
	private static DelegateBridge __Hotfix0_get_isReady; // 0x0
	private static DelegateBridge __Hotfix0_get_isChargeAction; // 0x8
	private static DelegateBridge __Hotfix0_get_chargeTimes; // 0x10
	private static DelegateBridge __Hotfix0_set_chargeTimes; // 0x18
	private static DelegateBridge __Hotfix0_get_maxChargeTimes; // 0x20
	private static DelegateBridge __Hotfix0_set_maxChargeTimes; // 0x28
	private static DelegateBridge __Hotfix0_DoSetData; // 0x30
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x38
	private static DelegateBridge __Hotfix0_BaseCastToTarget; // 0x40
	private static DelegateBridge __Hotfix0_CreateProjectile; // 0x48
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x50
	private static DelegateBridge __Hotfix0_AddChargeTimes; // 0x58
	private static DelegateBridge __Hotfix0_CanCharge; // 0x60
	private static DelegateBridge __Hotfix0_SetIsChargeAction; // 0x68
	private static DelegateBridge __Hotfix0_OnChargeCastEvent; // 0x70
	private static DelegateBridge __Hotfix0_FinishAbility; // 0x78
	private static DelegateBridge __Hotfix0_GetChargeTimes; // 0x80
	private static DelegateBridge __Hotfix0_GetIsChargeAction; // 0x88
	private static DelegateBridge __Hotfix0_MergeAtkScale; // 0x90
	private static DelegateBridge __Hotfix0_ResetAtkScale; // 0x98
	private static DelegateBridge __Hotfix0_get_chargeCounter; // 0xa0
	private static DelegateBridge __Hotfix0_set_chargeCounter; // 0xa8
	private static DelegateBridge __Hotfix0_SetChargeCounter; // 0xb0
	private static DelegateBridge __Hotfix0_SetChargeTimes; // 0xb8
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public override Boolean isReady { get; }
	protected Boolean isChargeAction { get; }
	protected virtual Int32 chargeTimes { get; set; }
	protected Int32 maxChargeTimes { get; set; }
	public IChargeableAbilityCounter chargeCounter { get; set; }

	// RVA: 0x1e08d7c VA: 0x7594420d7c
	public override Boolean get_isReady() { }
	// RVA: 0x1e08de4 VA: 0x7594420de4
	protected Boolean get_isChargeAction() { }
	// RVA: 0x1e08e4c VA: 0x7594420e4c
	protected virtual Int32 get_chargeTimes() { }
	// RVA: 0x1e08eb4 VA: 0x7594420eb4
	protected virtual Void set_chargeTimes(Int32 value) { }
	// RVA: 0x1e08f30 VA: 0x7594420f30
	protected Int32 get_maxChargeTimes() { }
	// RVA: 0x1e08f98 VA: 0x7594420f98
	protected Void set_maxChargeTimes(Int32 value) { }
	// RVA: 0x1e09014 VA: 0x7594421014
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e09114 VA: 0x7594421114
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e091e8 VA: 0x75944211e8
	protected Boolean BaseCastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e09290 VA: 0x7594421290
	protected override Projectile CreateProjectile(ILocatable target, out Projectile fakeProjectile) { }
	// RVA: 0x1e096e4 VA: 0x75944216e4
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e09780 VA: 0x7594421780
	public virtual Void AddChargeTimes() { }
	// RVA: 0x1e097f0 VA: 0x75944217f0
	public virtual Boolean CanCharge() { }
	// RVA: 0x1e09864 VA: 0x7594421864
	public virtual Void SetIsChargeAction(Boolean isChargeAttack) { }
	// RVA: 0x1e098e4 VA: 0x75944218e4
	public Void OnChargeCastEvent(Event ev) { }
	// RVA: 0x1e09974 VA: 0x7594421974
	public Void FinishAbility(FinishReason reason) { }
	// RVA: 0x1e09a04 VA: 0x7594421a04
	public Int32 GetChargeTimes() { }
	// RVA: 0x1e09a6c VA: 0x7594421a6c
	public Boolean GetIsChargeAction() { }
	// RVA: 0x1e09ad4 VA: 0x7594421ad4
	public Void MergeAtkScale(FP atkScale) { }
	// RVA: 0x1e09ca8 VA: 0x7594421ca8
	public Void ResetAtkScale() { }
	// RVA: 0x1e09e5c VA: 0x7594421e5c
	public IChargeableAbilityCounter get_chargeCounter() { }
	// RVA: 0x1e09ec4 VA: 0x7594421ec4
	public Void set_chargeCounter(IChargeableAbilityCounter value) { }
	// RVA: 0x1e09f48 VA: 0x7594421f48
	public Void SetChargeCounter(IChargeableAbilityCounter counter) { }
	// RVA: 0x1e095cc VA: 0x75944215cc
	public Void SetChargeTimes(Int32 times) { }
	// RVA: 0x1e09fc8 VA: 0x7594421fc8
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e0a120 VA: 0x7594422120
	public Void .ctor() { }
	// RVA: 0x1e0a1e4 VA: 0x75944221e4
	private Boolean <>xLuaBaseProxy_get_isReady() { }
	// RVA: 0x1e0a1ec VA: 0x75944221ec
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e0a210 VA: 0x7594422210
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e0a21c VA: 0x759442221c
	private Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable P0, out Projectile P1) { }
	// RVA: 0x1e0a224 VA: 0x7594422224
	private IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay() { }
	// RVA: 0x1e0a22c VA: 0x759442222c
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
}
```