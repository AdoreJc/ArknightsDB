# AbilityFirstSucceedGroup

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Category _category`

- `Int32 _coolDownAbilityIndex`

- `Boolean _fixAffectingAbilityParam`

- `Boolean _alsoInterruptCurrentSubAbility`

- `Boolean _clearInternalCooldownWhenFinish`

- `Boolean _useEscaptime`

- `TimeMode _timeMode`

- `FP m_cooldown`

- `FP m_escapeTime`

- `Int32 m_affectingAbilityIndex`


## Properties

- `Boolean needUpdateAttackTime`


## Methods

- `Boolean get_needUpdateAttackTime()`

- `Void _OnSubAbilityFinished(Ability, FinishReason, Boolean)`

- `Void _OnSubAbilityCasted(Int32)`

- `FP <>xLuaBaseProxy_get_escapeTime()`

- `Boolean <>xLuaBaseProxy_get_isAffecting()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Void <>xLuaBaseProxy_OnAttackTimeChanged(FP)`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AbilityFirstSucceedGroup : AbilityStandard
{
	private Category _category; // 0x108
	private Int32 _coolDownAbilityIndex; // 0x10c
	private Boolean _fixAffectingAbilityParam; // 0x110
	private Boolean _alsoInterruptCurrentSubAbility; // 0x111
	private Boolean _clearInternalCooldownWhenFinish; // 0x112
	private Boolean _useEscaptime; // 0x113
	private Ability[] _abilities; // 0x118
	private TimeMode _timeMode; // 0x120
	private FP m_cooldown; // 0x128
	private FP m_escapeTime; // 0x130
	private Int32 m_affectingAbilityIndex; // 0x138
	private static DelegateBridge __Hotfix0_get_category; // 0x0
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x8
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x10
	private static DelegateBridge __Hotfix0_get_escapeTime; // 0x18
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x20
	private static DelegateBridge __Hotfix0_get_isAffecting; // 0x28
	private static DelegateBridge __Hotfix0_get_needUpdateAttackTime; // 0x30
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x38
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x40
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x48
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x50
	private static DelegateBridge __Hotfix0_DoSetData; // 0x58
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x60
	private static DelegateBridge __Hotfix0_CastDirectly; // 0x68
	private static DelegateBridge __Hotfix0_DoAttach; // 0x70
	private static DelegateBridge __Hotfix0_DoDetach; // 0x78
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x80
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x88
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x90
	private static DelegateBridge __Hotfix0_OnAttackTimeChanged; // 0x98
	private static DelegateBridge __Hotfix0__OnSubAbilityFinished; // 0xa0
	private static DelegateBridge __Hotfix0__OnSubAbilityCasted; // 0xa8
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	public override FP cooldown { get; }
	public override FP escapeTime { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	public override Boolean isAffecting { get; }
	public Boolean needUpdateAttackTime { get; }

	// RVA: 0x1e30fac VA: 0x7594448fac
	public override Category get_category() { }
	// RVA: 0x1e31014 VA: 0x7594449014
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e31078 VA: 0x7594449078
	public override FP get_cooldown() { }
	// RVA: 0x1e310e0 VA: 0x75944490e0
	public override FP get_escapeTime() { }
	// RVA: 0x1e31148 VA: 0x7594449148
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e311ac VA: 0x75944491ac
	public override Boolean get_isAffecting() { }
	// RVA: 0x1e31260 VA: 0x7594449260
	public Boolean get_needUpdateAttackTime() { }
	// RVA: 0x1e312e0 VA: 0x75944492e0
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e31344 VA: 0x7594449344
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e313c4 VA: 0x75944493c4
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e3143c VA: 0x759444943c
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e314a0 VA: 0x75944494a0
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e3174c VA: 0x759444974c
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e319ec VA: 0x75944499ec
	public override Boolean CastDirectly(FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e31b90 VA: 0x7594449b90
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e31ca0 VA: 0x7594449ca0
	protected override Void DoDetach() { }
	// RVA: 0x1e31d58 VA: 0x7594449d58
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e31e1c VA: 0x7594449e1c
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e31ee0 VA: 0x7594449ee0
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e32020 VA: 0x759444a020
	public override Void OnAttackTimeChanged(FP newValue) { }
	// RVA: 0x1e320cc VA: 0x759444a0cc
	private Void _OnSubAbilityFinished(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x1e31908 VA: 0x7594449908
	private Void _OnSubAbilityCasted(Int32 abilityIndex) { }
	// RVA: 0x1e32178 VA: 0x759444a178
	public override Void PreloadSpecialAudioSignals(String abilityId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1e32350 VA: 0x759444a350
	public Void .ctor() { }
	// RVA: 0x1e32448 VA: 0x759444a448
	private FP <>xLuaBaseProxy_get_escapeTime() { }
	// RVA: 0x1e32450 VA: 0x759444a450
	private Boolean <>xLuaBaseProxy_get_isAffecting() { }
	// RVA: 0x1e32458 VA: 0x759444a458
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e32480 VA: 0x759444a480
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e3248c VA: 0x759444a48c
	private Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate P0, Boolean P1) { }
	// RVA: 0x1e32498 VA: 0x759444a498
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e324a0 VA: 0x759444a4a0
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e324a8 VA: 0x759444a4a8
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e324b0 VA: 0x759444a4b0
	private Void <>xLuaBaseProxy_OnAttackTimeChanged(FP P0) { }
	// RVA: 0x1e324b8 VA: 0x759444a4b8
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
}
```