# ExChargeRangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _exProjectileKey`

- `Int32 _maxExChargeTimes`

- `TargetValidator _targetValidator`

- `Boolean _forceExCharge`

- `Boolean _refreshBlackboardOnAttached`

- `Int32 m_exChargeTimes`

- `Int32 m_maxExChargeTimes`

- `Boolean m_isExChargeAction`

- `AbilityExChargeGroup m_syncGroup`


## Properties

- `Int32 exChargeTimes`


## Methods

- `Int32 get_exChargeTimes()`

- `Void SetChargeGroup(AbilityExChargeGroup)`

- `Boolean ConsumeChargeTimes()`

- `Void SetExChargeTimes(Int32)`

- `Int32 GetExChargeTimes()`

- `Boolean IsExChargeAction()`

- `Boolean ValidateTarget(Entity)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable, out)`

- `Void <>xLuaBaseProxy_AddChargeTimes()`

- `Void <>xLuaBaseProxy_SetIsChargeAction(Boolean)`

- `Boolean <>xLuaBaseProxy_CanCharge()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ExChargeRangedAttack : ChargeRangedAttack, IExChargeableSource, IChargeableSource
{
	private String _exProjectileKey; // 0x280
	private Int32 _maxExChargeTimes; // 0x288
	private TargetValidator _targetValidator; // 0x290
	private Boolean _forceExCharge; // 0x298
	private Boolean _refreshBlackboardOnAttached; // 0x299
	private List`1 _exMounts; // 0x2a0
	private Int32 m_exChargeTimes; // 0x2a8
	private Int32 m_maxExChargeTimes; // 0x2ac
	private Boolean m_isExChargeAction; // 0x2b0
	private ObjectPtr`1 m_castTarget; // 0x2b8
	private AbilityExChargeGroup m_syncGroup; // 0x2c8
	private static DelegateBridge __Hotfix0_get_exChargeTimes; // 0x0
	private static DelegateBridge __Hotfix0_DoSetData; // 0x8
	private static DelegateBridge __Hotfix0_SetChargeGroup; // 0x10
	private static DelegateBridge __Hotfix0_OnAttached; // 0x18
	private static DelegateBridge __Hotfix0_OnDetached; // 0x20
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x28
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x30
	private static DelegateBridge __Hotfix0_CreateProjectile; // 0x38
	private static DelegateBridge __Hotfix0_ConsumeChargeTimes; // 0x40
	private static DelegateBridge __Hotfix0_AddChargeTimes; // 0x48
	private static DelegateBridge __Hotfix0_SetIsChargeAction; // 0x50
	private static DelegateBridge __Hotfix0_CanCharge; // 0x58
	private static DelegateBridge __Hotfix0_SetExChargeTimes; // 0x60
	private static DelegateBridge __Hotfix0_GetExChargeTimes; // 0x68
	private static DelegateBridge __Hotfix0_IsExChargeAction; // 0x70
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public Int32 exChargeTimes { get; }

	// RVA: 0x1e0d370 VA: 0x7594425370
	public Int32 get_exChargeTimes() { }
	// RVA: 0x1e0d3d8 VA: 0x75944253d8
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e0d564 VA: 0x7594425564
	public Void SetChargeGroup(AbilityExChargeGroup group) { }
	// RVA: 0x1e0d5e8 VA: 0x75944255e8
	protected override Void OnAttached() { }
	// RVA: 0x1e0d808 VA: 0x7594425808
	protected override Void OnDetached() { }
	// RVA: 0x1e0d904 VA: 0x7594425904
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e0daec VA: 0x7594425aec
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e0dbd8 VA: 0x7594425bd8
	protected override Projectile CreateProjectile(ILocatable target, out Projectile fakeProjectile) { }
	// RVA: 0x1e0df68 VA: 0x7594425f68
	public Boolean ConsumeChargeTimes() { }
	// RVA: 0x1e0e1f4 VA: 0x75944261f4
	public override Void AddChargeTimes() { }
	// RVA: 0x1e0e2c4 VA: 0x75944262c4
	public override Void SetIsChargeAction(Boolean isChargeAttack) { }
	// RVA: 0x1e0e38c VA: 0x759442638c
	public override Boolean CanCharge() { }
	// RVA: 0x1e0e434 VA: 0x7594426434
	public Void SetExChargeTimes(Int32 exTimes) { }
	// RVA: 0x1e0e4b0 VA: 0x75944264b0
	public Int32 GetExChargeTimes() { }
	// RVA: 0x1e0e518 VA: 0x7594426518
	public Boolean IsExChargeAction() { }
	// RVA: 0x1e0da0c VA: 0x7594425a0c
	public Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1e0e580 VA: 0x7594426580
	public Void .ctor() { }
	// RVA: 0x1e0e644 VA: 0x7594426644
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e0e66c VA: 0x759442666c
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e0e674 VA: 0x7594426674
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e0e67c VA: 0x759442667c
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e0e688 VA: 0x7594426688
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e0e690 VA: 0x7594426690
	private Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable P0, out Projectile P1) { }
	// RVA: 0x1e0e698 VA: 0x7594426698
	private Void <>xLuaBaseProxy_AddChargeTimes() { }
	// RVA: 0x1e0e6a0 VA: 0x75944266a0
	private Void <>xLuaBaseProxy_SetIsChargeAction(Boolean P0) { }
	// RVA: 0x1e0e6ac VA: 0x75944266ac
	private Boolean <>xLuaBaseProxy_CanCharge() { }
}
```