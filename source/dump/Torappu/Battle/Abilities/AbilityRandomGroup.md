# AbilityRandomGroup

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Category _category`

- `Int32 _coolDownAbilityIndex`

- `Boolean _clearInternalCooldownWhenFinish`

- `SelectMethod _selectMethod`

- `Boolean _alsoInterruptCurrentSubAbility`

- `TimeMode _timeMode`

- `Boolean _isConfigurableProb`

- `Boolean _diffFromLastOneIfNotFirst`

- `Int32 m_loopIndex`

- `Int32 m_randomRangeNum`

- `FP m_cooldown`


## Properties

- `Boolean isConfigurableProb`

- `Boolean isRandom`

- `Boolean needUpdateAttackTime`


## Methods

- `Boolean get_isConfigurableProb()`

- `Boolean get_isRandom()`

- `Boolean get_needUpdateAttackTime()`

- `Ability _SelectAbilityDifferentFromLastOne()`

- `Ability _SelectAbilityForRandom()`

- `Ability _SelectAbilityForRandomWithConfigurableProb()`

- `Ability _GetAbilityInternal()`

- `Void _OnSubAbilityFinished(Ability, FinishReason, Boolean)`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_UpdateBlackboard(Blackboard)`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Void <>xLuaBaseProxy_OnAttackTimeChanged(FP)`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`

- `Boolean <>xLuaBaseProxy_InterruptIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AbilityRandomGroup : AbilityStandard
{
	private Category _category; // 0x108
	private Int32 _coolDownAbilityIndex; // 0x10c
	private Boolean _clearInternalCooldownWhenFinish; // 0x110
	private SelectMethod _selectMethod; // 0x114
	private Boolean _alsoInterruptCurrentSubAbility; // 0x118
	private Ability[] _abilities; // 0x120
	private TimeMode _timeMode; // 0x128
	private Boolean _isConfigurableProb; // 0x12c
	private List`1 _probKeyList; // 0x130
	private Boolean _diffFromLastOneIfNotFirst; // 0x138
	private ObjectPtr`1 m_lastCastAbilitySinceFirstAttack; // 0x140
	private List`1 m_abilityGroupThisTime; // 0x150
	private Int32 m_loopIndex; // 0x158
	private Int32 m_randomRangeNum; // 0x15c
	private List`1 m_probList; // 0x160
	private FP m_cooldown; // 0x168
	private static DelegateBridge __Hotfix0_get_isConfigurableProb; // 0x0
	private static DelegateBridge __Hotfix0_get_category; // 0x8
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x10
	private static DelegateBridge __Hotfix0_get_isRandom; // 0x18
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x20
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x28
	private static DelegateBridge __Hotfix0_get_needUpdateAttackTime; // 0x30
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x38
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x40
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x48
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x50
	private static DelegateBridge __Hotfix0_Reset; // 0x58
	private static DelegateBridge __Hotfix0_DoSetData; // 0x60
	private static DelegateBridge __Hotfix0_UpdateBlackboard; // 0x68
	private static DelegateBridge __Hotfix0__SelectAbilityDifferentFromLastOne; // 0x70
	private static DelegateBridge __Hotfix0__SelectAbilityForRandom; // 0x78
	private static DelegateBridge __Hotfix0__SelectAbilityForRandomWithConfigurableProb; // 0x80
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x88
	private static DelegateBridge __Hotfix0_CastDirectly; // 0x90
	private static DelegateBridge __Hotfix0__GetAbilityInternal; // 0x98
	private static DelegateBridge __Hotfix0_DoAttach; // 0xa0
	private static DelegateBridge __Hotfix0_DoDetach; // 0xa8
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0xb0
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0xb8
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0xc0
	private static DelegateBridge __Hotfix0_OnAttackTimeChanged; // 0xc8
	private static DelegateBridge __Hotfix0__OnSubAbilityFinished; // 0xd0
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0xd8
	private static DelegateBridge __Hotfix0_InterruptIfNot; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	public Boolean isConfigurableProb { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected Boolean isRandom { get; }
	public override FP cooldown { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	public Boolean needUpdateAttackTime { get; }

	// RVA: 0x1e34174 VA: 0x759444c174
	public Boolean get_isConfigurableProb() { }
	// RVA: 0x1e341dc VA: 0x759444c1dc
	public override Category get_category() { }
	// RVA: 0x1e34244 VA: 0x759444c244
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e342a8 VA: 0x759444c2a8
	protected Boolean get_isRandom() { }
	// RVA: 0x1e34318 VA: 0x759444c318
	public override FP get_cooldown() { }
	// RVA: 0x1e34430 VA: 0x759444c430
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e34494 VA: 0x759444c494
	public Boolean get_needUpdateAttackTime() { }
	// RVA: 0x1e34514 VA: 0x759444c514
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e34578 VA: 0x759444c578
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e345f8 VA: 0x759444c5f8
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e34670 VA: 0x759444c670
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e346d4 VA: 0x759444c6d4
	protected override Void Reset() { }
	// RVA: 0x1e34850 VA: 0x759444c850
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e34c2c VA: 0x759444cc2c
	public override Void UpdateBlackboard(Blackboard extraBlackboard) { }
	// RVA: 0x1e34d08 VA: 0x759444cd08
	private Ability _SelectAbilityDifferentFromLastOne() { }
	// RVA: 0x1e35078 VA: 0x759444d078
	private Ability _SelectAbilityForRandom() { }
	// RVA: 0x1e351e0 VA: 0x759444d1e0
	private Ability _SelectAbilityForRandomWithConfigurableProb() { }
	// RVA: 0x1e35334 VA: 0x759444d334
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e3562c VA: 0x759444d62c
	public override Boolean CastDirectly(FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e35510 VA: 0x759444d510
	private Ability _GetAbilityInternal() { }
	// RVA: 0x1e357f0 VA: 0x759444d7f0
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e358ec VA: 0x759444d8ec
	protected override Void DoDetach() { }
	// RVA: 0x1e359a4 VA: 0x759444d9a4
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e35a68 VA: 0x759444da68
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e35b04 VA: 0x759444db04
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e35c44 VA: 0x759444dc44
	public override Void OnAttackTimeChanged(FP newValue) { }
	// RVA: 0x1e35cf0 VA: 0x759444dcf0
	private Void _OnSubAbilityFinished(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x1e35d9c VA: 0x759444dd9c
	public override Void PreloadSpecialAudioSignals(String abilityId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1e35f74 VA: 0x759444df74
	public override Boolean InterruptIfNot() { }
	// RVA: 0x1e36090 VA: 0x759444e090
	public Void .ctor() { }
	// RVA: 0x1e36240 VA: 0x759444e240
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e36248 VA: 0x759444e248
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e36270 VA: 0x759444e270
	private Void <>xLuaBaseProxy_UpdateBlackboard(Blackboard P0) { }
	// RVA: 0x1e36278 VA: 0x759444e278
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e36284 VA: 0x759444e284
	private Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate P0, Boolean P1) { }
	// RVA: 0x1e36290 VA: 0x759444e290
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e36298 VA: 0x759444e298
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e362a0 VA: 0x759444e2a0
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e362a8 VA: 0x759444e2a8
	private Void <>xLuaBaseProxy_OnAttackTimeChanged(FP P0) { }
	// RVA: 0x1e362b0 VA: 0x759444e2b0
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
	// RVA: 0x1e362b8 VA: 0x759444e2b8
	private Boolean <>xLuaBaseProxy_InterruptIfNot() { }
}
```