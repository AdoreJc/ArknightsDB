# AbilitySequenceGroup

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _alwaysNext`

- `Boolean _forceNextIfCastFail`

- `Boolean _checkCanUseSubAbility`

- `Boolean _useLongestAbilityCooldown`

- `Boolean _fireCastStartEventWhenCast`

- `Boolean m_isCastDirectly`

- `Boolean m_cachedFirstAttack`

- `Category m_category`

- `FP m_cooldown`

- `Int32 m_currentIndex`

- `Int32 m_remainingJobCnt`

- `Boolean _alsoInterruptCurrentSubAbility`

- `Boolean _alsoStopSubAbilityAffect`

- `Boolean _alsoResetSubAbilityCooldown`

- `Boolean _setDataExceptRedundance`

- `Boolean _interruptIfTargetDead`

- `TimeMode _timeMode`

- `Boolean _enableLoop`


## Properties

- `Boolean alwaysNext`

- `Boolean alsoInterruptCurrentSubAbility`

- `Boolean enableLoop`


## Methods

- `Boolean get_alwaysNext()`

- `Boolean get_alsoInterruptCurrentSubAbility()`

- `Boolean get_enableLoop()`

- `Void _OnSubAbilityFinished(Ability, FinishReason, Boolean)`

- `Boolean _LoopValid()`

- `Boolean _MoveToNextActiveAbility(out)`

- `Void _OnCastStart()`

- `Boolean <OnWaitForPostDelay>b__45_0()`

- `Boolean <>xLuaBaseProxy_get_isAffecting()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Void <>xLuaBaseProxy_Awake()`

- `Boolean <>xLuaBaseProxy_CheckAtPreCastPhase()`

- `Void <>xLuaBaseProxy_StopAffect()`

- `Void <>xLuaBaseProxy_ResetCooldown(Boolean)`

- `Void <>xLuaBaseProxy_OnAttackTimeChanged(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AbilitySequenceGroup : AbilityStandard
{
	private const Int32 MAX_CASTING_TIME; // 0x0
	private Ability[] _abilities; // 0x108
	private Boolean _alwaysNext; // 0x110
	private Boolean _forceNextIfCastFail; // 0x111
	private Boolean _checkCanUseSubAbility; // 0x112
	private Boolean _useLongestAbilityCooldown; // 0x113
	private Boolean _fireCastStartEventWhenCast; // 0x114
	private Boolean m_isCastDirectly; // 0x115
	private ObjectPtr`1 m_cachedTarget; // 0x118
	private Boolean m_cachedFirstAttack; // 0x128
	private Category m_category; // 0x12c
	private FP m_cooldown; // 0x130
	private Int32 m_currentIndex; // 0x138
	private Int32 m_remainingJobCnt; // 0x13c
	private Boolean _alsoInterruptCurrentSubAbility; // 0x140
	private List`1 _interruptableSubAbilityIndice; // 0x148
	private Boolean _alsoStopSubAbilityAffect; // 0x150
	private Boolean _alsoResetSubAbilityCooldown; // 0x151
	private Boolean _setDataExceptRedundance; // 0x152
	private Boolean _interruptIfTargetDead; // 0x153
	private TimeMode _timeMode; // 0x154
	private Boolean _enableLoop; // 0x158
	private AbilityLoopGroup[] _abilityLoopSettings; // 0x160
	private static DelegateBridge __Hotfix0_get_alwaysNext; // 0x0
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x8
	private static DelegateBridge __Hotfix0_get_category; // 0x10
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x18
	private static DelegateBridge __Hotfix0_get_isAffecting; // 0x20
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x28
	private static DelegateBridge __Hotfix0_get_alsoInterruptCurrentSubAbility; // 0x30
	private static DelegateBridge __Hotfix0_get_enableLoop; // 0x38
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x40
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x48
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x50
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x58
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x60
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x68
	private static DelegateBridge __Hotfix0_DoSetData; // 0x70
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x78
	private static DelegateBridge __Hotfix0_CastDirectly; // 0x80
	private static DelegateBridge __Hotfix0_DoAttach; // 0x88
	private static DelegateBridge __Hotfix0_DoDetach; // 0x90
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0x98
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0xa0
	private static DelegateBridge __Hotfix0_Awake; // 0xa8
	private static DelegateBridge __Hotfix0_CheckAtPreCastPhase; // 0xb0
	private static DelegateBridge __Hotfix0__OnSubAbilityFinished; // 0xb8
	private static DelegateBridge __Hotfix0__LoopValid; // 0xc0
	private static DelegateBridge __Hotfix0__MoveToNextActiveAbility; // 0xc8
	private static DelegateBridge __Hotfix0__OnCastStart; // 0xd0
	private static DelegateBridge __Hotfix0_StopAffect; // 0xd8
	private static DelegateBridge __Hotfix0_ResetCooldown; // 0xe0
	private static DelegateBridge __Hotfix0_OnAttackTimeChanged; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	private Boolean alwaysNext { get; }
	public override FP cooldown { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	public override Boolean isAffecting { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	protected Boolean alsoInterruptCurrentSubAbility { get; }
	protected Boolean enableLoop { get; }

	// RVA: 0x1e374d0 VA: 0x759444f4d0
	private Boolean get_alwaysNext() { }
	// RVA: 0x1e37538 VA: 0x759444f538
	public override FP get_cooldown() { }
	// RVA: 0x1e37650 VA: 0x759444f650
	public override Category get_category() { }
	// RVA: 0x1e376b8 VA: 0x759444f6b8
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e3771c VA: 0x759444f71c
	public override Boolean get_isAffecting() { }
	// RVA: 0x1e377f8 VA: 0x759444f7f8
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e3785c VA: 0x759444f85c
	protected Boolean get_alsoInterruptCurrentSubAbility() { }
	// RVA: 0x1e378c4 VA: 0x759444f8c4
	protected Boolean get_enableLoop() { }
	// RVA: 0x1e3792c VA: 0x759444f92c
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e379a4 VA: 0x759444f9a4
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e37a24 VA: 0x759444fa24
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e37a88 VA: 0x759444fa88
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e37aec VA: 0x759444faec
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e37bb0 VA: 0x759444fbb0
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e37c84 VA: 0x759444fc84
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e3806c VA: 0x759445006c
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e3840c VA: 0x759445040c
	public override Boolean CastDirectly(FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e385c4 VA: 0x75944505c4
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e386c0 VA: 0x75944506c0
	protected override Void DoDetach() { }
	// RVA: 0x1e38778 VA: 0x7594450778
	public override Void PreloadSpecialAudioSignals(String abilityId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1e38950 VA: 0x7594450950
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e38a9c VA: 0x7594450a9c
	protected override Void Awake() { }
	// RVA: 0x1e38b84 VA: 0x7594450b84
	public override Boolean CheckAtPreCastPhase() { }
	// RVA: 0x1e38bf4 VA: 0x7594450bf4
	private Void _OnSubAbilityFinished(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x1e38e78 VA: 0x7594450e78
	private Boolean _LoopValid() { }
	// RVA: 0x1e3822c VA: 0x759445022c
	private Boolean _MoveToNextActiveAbility(out Ability ability) { }
	// RVA: 0x1e38344 VA: 0x7594450344
	private Void _OnCastStart() { }
	// RVA: 0x1e39004 VA: 0x7594451004
	public override Void StopAffect() { }
	// RVA: 0x1e390cc VA: 0x75944510cc
	public override Void ResetCooldown(Boolean waitFirstPeriod) { }
	// RVA: 0x1e391b0 VA: 0x75944511b0
	public override Void OnAttackTimeChanged(FP newValue) { }
	// RVA: 0x1e39258 VA: 0x7594451258
	public Void .ctor() { }
	// RVA: 0x1e39390 VA: 0x7594451390
	private Boolean <OnWaitForPostDelay>b__45_0() { }
	// RVA: 0x1e39398 VA: 0x7594451398
	private Boolean <>xLuaBaseProxy_get_isAffecting() { }
	// RVA: 0x1e393a0 VA: 0x75944513a0
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e393c8 VA: 0x75944513c8
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e393d4 VA: 0x75944513d4
	private Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate P0, Boolean P1) { }
	// RVA: 0x1e393e0 VA: 0x75944513e0
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e393e8 VA: 0x75944513e8
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e393f0 VA: 0x75944513f0
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
	// RVA: 0x1e393f8 VA: 0x75944513f8
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e39400 VA: 0x7594451400
	private Void <>xLuaBaseProxy_Awake() { }
	// RVA: 0x1e39408 VA: 0x7594451408
	private Boolean <>xLuaBaseProxy_CheckAtPreCastPhase() { }
	// RVA: 0x1e39410 VA: 0x7594451410
	private Void <>xLuaBaseProxy_StopAffect() { }
	// RVA: 0x1e39418 VA: 0x7594451418
	private Void <>xLuaBaseProxy_ResetCooldown(Boolean P0) { }
	// RVA: 0x1e39424 VA: 0x7594451424
	private Void <>xLuaBaseProxy_OnAttackTimeChanged(FP P0) { }
}
```