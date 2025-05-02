# MultiChargeRangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _useChargeableGroup`

- `AbilityChargeableGroup _chargeableGroup`

- `ChargeRangedAttack _chargeAbility`

- `String _chargeAnimKey`

- `String _chargeDownAnimKey`

- `String _chargeUpAnimKey`

- `Boolean _attachAndDetach`

- `Boolean m_isChargeAction`


## Properties

- `Boolean isUseChargeableGroup`


## Methods

- `Boolean get_isUseChargeableGroup()`

- `Void _SetIsChargeAction(Boolean)`

- `Boolean GetIsChargeAction()`

- `Int32 GetChargeTimes()`

- `Boolean _CheckCanCharge()`

- `Boolean CanAlwaysTrigger()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable, out)`

- `Void <>xLuaBaseProxy_DoEmitAudioSignalForSpellOn()`

- `String <>xLuaBaseProxy_GetAnimKey()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiChargeRangedAttack : RangedAttack, IMultiChargeUberEffectEmitterAbility, IChargeableSource, IAlwaysTrigger
{
	private Boolean _useChargeableGroup; // 0x25c
	protected AbilityChargeableGroup _chargeableGroup; // 0x260
	protected ChargeRangedAttack _chargeAbility; // 0x268
	private String _chargeAnimKey; // 0x270
	private String _chargeDownAnimKey; // 0x278
	private String _chargeUpAnimKey; // 0x280
	private Boolean _attachAndDetach; // 0x288
	private Boolean m_isChargeAction; // 0x289
	private static DelegateBridge __Hotfix0_get_isUseChargeableGroup; // 0x0
	private static DelegateBridge __Hotfix0_OnAttached; // 0x8
	private static DelegateBridge __Hotfix0_OnDetached; // 0x10
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x18
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x20
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x28
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x30
	private static DelegateBridge __Hotfix0_CreateProjectile; // 0x38
	private static DelegateBridge __Hotfix0_DoEmitAudioSignalForSpellOn; // 0x40
	private static DelegateBridge __Hotfix0_GetAnimKey; // 0x48
	private static DelegateBridge __Hotfix0__SetIsChargeAction; // 0x50
	private static DelegateBridge __Hotfix0_GetIsChargeAction; // 0x58
	private static DelegateBridge __Hotfix0_GetChargeTimes; // 0x60
	private static DelegateBridge __Hotfix0__CheckCanCharge; // 0x68
	private static DelegateBridge __Hotfix0_CanAlwaysTrigger; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	private Boolean isUseChargeableGroup { get; }

	// RVA: 0x1e12088 VA: 0x759442a088
	private Boolean get_isUseChargeableGroup() { }
	// RVA: 0x1e120f0 VA: 0x759442a0f0
	protected override Void OnAttached() { }
	// RVA: 0x1e121c8 VA: 0x759442a1c8
	protected override Void OnDetached() { }
	// RVA: 0x1e122a0 VA: 0x759442a2a0
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e125c8 VA: 0x759442a5c8
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e126e4 VA: 0x759442a6e4
	protected override Void OnCastStart() { }
	// RVA: 0x1e12954 VA: 0x759442a954
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e12a34 VA: 0x759442aa34
	protected override Projectile CreateProjectile(ILocatable target, out Projectile fakeProjectile) { }
	// RVA: 0x1e12aec VA: 0x759442aaec
	protected override Void DoEmitAudioSignalForSpellOn() { }
	// RVA: 0x1e12cc0 VA: 0x759442acc0
	public override String GetAnimKey() { }
	// RVA: 0x1e1245c VA: 0x759442a45c
	private Void _SetIsChargeAction(Boolean isChargeAction) { }
	// RVA: 0x1e12da4 VA: 0x759442ada4
	public Boolean GetIsChargeAction() { }
	// RVA: 0x1e12e0c VA: 0x759442ae0c
	public Int32 GetChargeTimes() { }
	// RVA: 0x1e12520 VA: 0x759442a520
	private Boolean _CheckCanCharge() { }
	// RVA: 0x1e12e74 VA: 0x759442ae74
	public Boolean CanAlwaysTrigger() { }
	// RVA: 0x1e12edc VA: 0x759442aedc
	public Void .ctor() { }
	// RVA: 0x1e12f48 VA: 0x759442af48
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e12f50 VA: 0x759442af50
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e12f58 VA: 0x759442af58
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e12f64 VA: 0x759442af64
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e12f68 VA: 0x759442af68
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e12f6c VA: 0x759442af6c
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e12f70 VA: 0x759442af70
	private Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable P0, out Projectile P1) { }
	// RVA: 0x1e12f74 VA: 0x759442af74
	private Void <>xLuaBaseProxy_DoEmitAudioSignalForSpellOn() { }
	// RVA: 0x1e12f7c VA: 0x759442af7c
	private String <>xLuaBaseProxy_GetAnimKey() { }
}
```