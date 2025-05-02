# AbilityChargeableGroup

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _maxChargeTimes`

- `Boolean _feedData`

- `Boolean _attachAndDetach`

- `Int32 m_chargeTimes`

- `Int32 m_maxChargeTimes`

- `Boolean m_isChargeAction`

- `Ability m_activatedAbility`

- `IChargeableAbilityReactor m_activatedAbilityReactor`


## Properties

- `Boolean IsFullCharge`


## Methods

- `Void FinishAbility(FinishReason)`

- `Void OnCastOnTargetBehaviours(Entity)`

- `Boolean get_IsFullCharge()`

- `Void Charge(Int32)`

- `Void SetChargeTimes(Int32)`

- `Void SetIsChargeAction(Boolean)`

- `Void OnChargeCastEvent(Event)`

- `Void SetActivateAbility(Ability)`

- `Int32 GetChargeTimes()`

- `Boolean GetIsChargeAction()`

- `Boolean <>xLuaBaseProxy_get_isReady()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AbilityChargeableGroup : AbilityStandard, IChargeableAbilityCounter, IChargeableAbility, IMultiChargeUberEffectEmitterAbility, IChargeableSource
{
	private Int32 _maxChargeTimes; // 0x108
	private AbilityStandard[] _abilities; // 0x110
	private Boolean _feedData; // 0x118
	private Boolean _attachAndDetach; // 0x119
	private Int32 m_chargeTimes; // 0x11c
	private Int32 m_maxChargeTimes; // 0x120
	private Boolean m_isChargeAction; // 0x124
	private Ability m_activatedAbility; // 0x128
	private IChargeableAbilityReactor m_activatedAbilityReactor; // 0x130
	private static DelegateBridge __Hotfix0_get_category; // 0x0
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x8
	private static DelegateBridge __Hotfix0_get_isReady; // 0x10
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x18
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x20
	private static DelegateBridge __Hotfix0_DoSetData; // 0x28
	private static DelegateBridge __Hotfix0_DoAttach; // 0x30
	private static DelegateBridge __Hotfix0_DoDetach; // 0x38
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x40
	private static DelegateBridge __Hotfix0_FinishAbility; // 0x48
	private static DelegateBridge __Hotfix0_OnCastOnTargetBehaviours; // 0x50
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x58
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x60
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x68
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x70
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x78
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x80
	private static DelegateBridge __Hotfix0_get_IsFullCharge; // 0x88
	private static DelegateBridge __Hotfix0_Charge; // 0x90
	private static DelegateBridge __Hotfix0_SetChargeTimes; // 0x98
	private static DelegateBridge __Hotfix0_SetIsChargeAction; // 0xa0
	private static DelegateBridge __Hotfix0_OnChargeCastEvent; // 0xa8
	private static DelegateBridge __Hotfix0_SetActivateAbility; // 0xb0
	private static DelegateBridge __Hotfix0_GetChargeTimes; // 0xb8
	private static DelegateBridge __Hotfix0_GetIsChargeAction; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public override Category category { get; }
	public override FP cooldown { get; }
	public override Boolean isReady { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	public Boolean IsFullCharge { get; }

	// RVA: 0x1e2ed30 VA: 0x7594446d30
	public override Category get_category() { }
	// RVA: 0x1e2ed98 VA: 0x7594446d98
	public override FP get_cooldown() { }
	// RVA: 0x1e2ee28 VA: 0x7594446e28
	public override Boolean get_isReady() { }
	// RVA: 0x1e2ee90 VA: 0x7594446e90
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e2eef4 VA: 0x7594446ef4
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e2ef58 VA: 0x7594446f58
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e2f160 VA: 0x7594447160
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e2f240 VA: 0x7594447240
	protected override Void DoDetach() { }
	// RVA: 0x1e2f304 VA: 0x7594447304
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e2f4ac VA: 0x75944474ac
	public Void FinishAbility(FinishReason reason) { }
	// RVA: 0x1e2f5c8 VA: 0x75944475c8
	public Void OnCastOnTargetBehaviours(Entity target) { }
	// RVA: 0x1e2f690 VA: 0x7594447690
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e2f708 VA: 0x7594447708
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e2f788 VA: 0x7594447788
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e2f7ec VA: 0x75944477ec
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e2f850 VA: 0x7594447850
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e2f914 VA: 0x7594447914
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e2f9d8 VA: 0x75944479d8
	public Boolean get_IsFullCharge() { }
	// RVA: 0x1e2fa4c VA: 0x7594447a4c
	public Void Charge(Int32 times) { }
	// RVA: 0x1e2fad0 VA: 0x7594447ad0
	public Void SetChargeTimes(Int32 times) { }
	// RVA: 0x1e2fb9c VA: 0x7594447b9c
	public Void SetIsChargeAction(Boolean isChargeAction) { }
	// RVA: 0x1e2fca4 VA: 0x7594447ca4
	public Void OnChargeCastEvent(Event ev) { }
	// RVA: 0x1e2fdc0 VA: 0x7594447dc0
	public Void SetActivateAbility(Ability ability) { }
	// RVA: 0x1e2fee0 VA: 0x7594447ee0
	public Int32 GetChargeTimes() { }
	// RVA: 0x1e2ff48 VA: 0x7594447f48
	public Boolean GetIsChargeAction() { }
	// RVA: 0x1e2ffb0 VA: 0x7594447fb0
	public Void .ctor() { }
	// RVA: 0x1e30020 VA: 0x7594448020
	private Boolean <>xLuaBaseProxy_get_isReady() { }
	// RVA: 0x1e30028 VA: 0x7594448028
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e30050 VA: 0x7594448050
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e30058 VA: 0x7594448058
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e30060 VA: 0x7594448060
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
}
```