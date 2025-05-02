# AbilityParallelGroup

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Category m_category`

- `FP m_cooldown`

- `Int32 m_remainingJobCnt`

- `Int32 m_jobCntThisTime`

- `Boolean _alsoInterruptSubAbilities`

- `Boolean _useEscaptime`

- `Boolean _alsoCheckChildrenAffecting`

- `Boolean _finishAllAbilitiesIfOneFinish`

- `Ability _mainAbility`

- `TimeMode _timeMode`

- `FP m_escapeTime`


## Properties

- `Boolean finishAllAbilitiesIfOneFinish`


## Methods

- `Boolean get_finishAllAbilitiesIfOneFinish()`

- `Void _OnSubAbilityFinished(Ability, FinishReason, Boolean)`

- `Boolean <>xLuaBaseProxy_get_isAffecting()`

- `FP <>xLuaBaseProxy_get_escapeTime()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Void <>xLuaBaseProxy_Awake()`

- `Boolean <>xLuaBaseProxy_CheckAtPreCastPhase()`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`

- `Void <>xLuaBaseProxy_OnAttackTimeChanged(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AbilityParallelGroup : AbilityStandard
{
	protected Ability[] _abilities; // 0x108
	private Category m_category; // 0x110
	private FP m_cooldown; // 0x118
	private Int32 m_remainingJobCnt; // 0x120
	private Int32 m_jobCntThisTime; // 0x124
	private Boolean _alsoInterruptSubAbilities; // 0x128
	private Boolean _useEscaptime; // 0x129
	private Boolean _alsoCheckChildrenAffecting; // 0x12a
	private Boolean _finishAllAbilitiesIfOneFinish; // 0x12b
	private Ability _mainAbility; // 0x130
	private TimeMode _timeMode; // 0x138
	private FP m_escapeTime; // 0x140
	private static DelegateBridge __Hotfix0_get_finishAllAbilitiesIfOneFinish; // 0x0
	private static DelegateBridge __Hotfix0_get_isAffecting; // 0x8
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x10
	private static DelegateBridge __Hotfix0_get_escapeTime; // 0x18
	private static DelegateBridge __Hotfix0_get_category; // 0x20
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x28
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x30
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x38
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x40
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x48
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x50
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x58
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x60
	private static DelegateBridge __Hotfix0_DoSetData; // 0x68
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x70
	private static DelegateBridge __Hotfix0_CastDirectly; // 0x78
	private static DelegateBridge __Hotfix0_DoAttach; // 0x80
	private static DelegateBridge __Hotfix0_DoDetach; // 0x88
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x90
	private static DelegateBridge __Hotfix0_Awake; // 0x98
	private static DelegateBridge __Hotfix0__OnSubAbilityFinished; // 0xa0
	private static DelegateBridge __Hotfix0_CheckAtPreCastPhase; // 0xa8
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0xb0
	private static DelegateBridge __Hotfix0_OnAttackTimeChanged; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public Boolean finishAllAbilitiesIfOneFinish { get; }
	public override Boolean isAffecting { get; }
	public override FP cooldown { get; }
	public override FP escapeTime { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }

	// RVA: 0x1e32698 VA: 0x759444a698
	public Boolean get_finishAllAbilitiesIfOneFinish() { }
	// RVA: 0x1e32700 VA: 0x759444a700
	public override Boolean get_isAffecting() { }
	// RVA: 0x1e327f0 VA: 0x759444a7f0
	public override FP get_cooldown() { }
	// RVA: 0x1e32908 VA: 0x759444a908
	public override FP get_escapeTime() { }
	// RVA: 0x1e32970 VA: 0x759444a970
	public override Category get_category() { }
	// RVA: 0x1e329d8 VA: 0x759444a9d8
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e32a3c VA: 0x759444aa3c
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e32aa0 VA: 0x759444aaa0
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e32b18 VA: 0x759444ab18
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e32b98 VA: 0x759444ab98
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e32bfc VA: 0x759444abfc
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e32c60 VA: 0x759444ac60
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e32d24 VA: 0x759444ad24
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e32de8 VA: 0x759444ade8
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e330bc VA: 0x759444b0bc
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e332f0 VA: 0x759444b2f0
	public override Boolean CastDirectly(FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e33518 VA: 0x759444b518
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e33614 VA: 0x759444b614
	protected override Void DoDetach() { }
	// RVA: 0x1e336cc VA: 0x759444b6cc
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e337e8 VA: 0x759444b7e8
	protected override Void Awake() { }
	// RVA: 0x1e338d0 VA: 0x759444b8d0
	private Void _OnSubAbilityFinished(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x1e33ab4 VA: 0x759444bab4
	public override Boolean CheckAtPreCastPhase() { }
	// RVA: 0x1e33bac VA: 0x759444bbac
	public override Void PreloadSpecialAudioSignals(String abilityId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1e33d84 VA: 0x759444bd84
	public override Void OnAttackTimeChanged(FP newValue) { }
	// RVA: 0x1e33e2c VA: 0x759444be2c
	public Void .ctor() { }
	// RVA: 0x1e33f14 VA: 0x759444bf14
	private Boolean <>xLuaBaseProxy_get_isAffecting() { }
	// RVA: 0x1e33f1c VA: 0x759444bf1c
	private FP <>xLuaBaseProxy_get_escapeTime() { }
	// RVA: 0x1e33f24 VA: 0x759444bf24
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e33f4c VA: 0x759444bf4c
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e33f58 VA: 0x759444bf58
	private Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate P0, Boolean P1) { }
	// RVA: 0x1e33f64 VA: 0x759444bf64
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e33f6c VA: 0x759444bf6c
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e33f74 VA: 0x759444bf74
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e33f7c VA: 0x759444bf7c
	private Void <>xLuaBaseProxy_Awake() { }
	// RVA: 0x1e33f84 VA: 0x759444bf84
	private Boolean <>xLuaBaseProxy_CheckAtPreCastPhase() { }
	// RVA: 0x1e33f8c VA: 0x759444bf8c
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
	// RVA: 0x1e33f94 VA: 0x759444bf94
	private Void <>xLuaBaseProxy_OnAttackTimeChanged(FP P0) { }
}
```