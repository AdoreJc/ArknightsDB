# AbilitySelectableGroup

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Category _category`

- `Int32 _coolDownAbilityIndex`

- `Boolean _clearInternalCooldownWhenFinish`

- `Boolean _updateCooldownBySubAbilityCooldownDuringCasting`

- `TimeMode _timeMode`

- `Boolean _selectAbilitySequentially`

- `Boolean _useSubAbilityEscapeTime`

- `Int32 _escapeTimeAbilityIndex`

- `Boolean _firstAttackIfAbilityChanged`

- `Boolean _resetSubAbilities`

- `Boolean _resetSubAbilityCooldown`

- `Boolean _useCurAbCheckAtPreCastPhase`

- `Int32 m_curAbilityIndex`

- `Int32 m_lastAbilityIndex`

- `FP m_cooldown`


## Properties

- `Boolean useSubAbilityEscapeTime`

- `Boolean needUpdateAttackTime`


## Methods

- `Boolean get_useSubAbilityEscapeTime()`

- `Boolean get_needUpdateAttackTime()`

- `Boolean _DoCastInternal(Boolean, FinishCallbackDelegate, Boolean)`

- `Void _OnSubAbilityFinished(Ability, FinishReason, Boolean)`

- `Boolean _IsFirstAttack(Int32, Boolean)`

- `Void _SyncCooldownOnCastStartByOption()`

- `FP <>xLuaBaseProxy_get_escapeTime()`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_CastToTarget(Entity, FinishCallbackDelegate, Boolean)`

- `Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate, Boolean)`

- `Void <>xLuaBaseProxy_ResetCooldown(Boolean)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Void <>xLuaBaseProxy_OnAttackTimeChanged(FP)`

- `Boolean <>xLuaBaseProxy_CheckAtPreCastPhase()`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AbilitySelectableGroup : AbilityStandard
{
	private Category _category; // 0x108
	private Int32 _coolDownAbilityIndex; // 0x10c
	private Boolean _clearInternalCooldownWhenFinish; // 0x110
	private Boolean _updateCooldownBySubAbilityCooldownDuringCasting; // 0x111
	private AbilityConfigs[] _abilityConfigs; // 0x118
	private TimeMode _timeMode; // 0x120
	private Boolean _selectAbilitySequentially; // 0x124
	private Boolean _useSubAbilityEscapeTime; // 0x125
	private Int32 _escapeTimeAbilityIndex; // 0x128
	private Boolean _firstAttackIfAbilityChanged; // 0x12c
	private Boolean _resetSubAbilities; // 0x12d
	private Boolean _resetSubAbilityCooldown; // 0x12e
	private Boolean _useCurAbCheckAtPreCastPhase; // 0x12f
	private Int32 m_curAbilityIndex; // 0x130
	private Int32 m_lastAbilityIndex; // 0x134
	private FP m_cooldown; // 0x138
	private static DelegateBridge __Hotfix0_get_useSubAbilityEscapeTime; // 0x0
	private static DelegateBridge __Hotfix0_get_escapeTime; // 0x8
	private static DelegateBridge __Hotfix0_get_category; // 0x10
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x18
	private static DelegateBridge __Hotfix0_get_cooldown; // 0x20
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x28
	private static DelegateBridge __Hotfix0_get_needUpdateAttackTime; // 0x30
	private static DelegateBridge __Hotfix0_GetActiveBuffs; // 0x38
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x40
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x48
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x50
	private static DelegateBridge __Hotfix0_Reset; // 0x58
	private static DelegateBridge __Hotfix0_DoSetData; // 0x60
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x68
	private static DelegateBridge __Hotfix0_CastDirectly; // 0x70
	private static DelegateBridge __Hotfix0__DoCastInternal; // 0x78
	private static DelegateBridge __Hotfix0_ResetCooldown; // 0x80
	private static DelegateBridge __Hotfix0_DoAttach; // 0x88
	private static DelegateBridge __Hotfix0_DoDetach; // 0x90
	private static DelegateBridge __Hotfix0_OnWaitForPreDelay; // 0x98
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0xa0
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0xa8
	private static DelegateBridge __Hotfix0_OnAttackTimeChanged; // 0xb0
	private static DelegateBridge __Hotfix0__OnSubAbilityFinished; // 0xb8
	private static DelegateBridge __Hotfix0_CheckAtPreCastPhase; // 0xc0
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0xc8
	private static DelegateBridge __Hotfix0__IsFirstAttack; // 0xd0
	private static DelegateBridge __Hotfix0__SyncCooldownOnCastStartByOption; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe0

	private Boolean useSubAbilityEscapeTime { get; }
	public override FP escapeTime { get; }
	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	public override FP cooldown { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	public Boolean needUpdateAttackTime { get; }

	// RVA: 0x1e636e0 VA: 0x759447b6e0
	private Boolean get_useSubAbilityEscapeTime() { }
	// RVA: 0x1e63748 VA: 0x759447b748
	public override FP get_escapeTime() { }
	// RVA: 0x1e63870 VA: 0x759447b870
	public override Category get_category() { }
	// RVA: 0x1e638d8 VA: 0x759447b8d8
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e6393c VA: 0x759447b93c
	public override FP get_cooldown() { }
	// RVA: 0x1e639a4 VA: 0x759447b9a4
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e63a08 VA: 0x759447ba08
	public Boolean get_needUpdateAttackTime() { }
	// RVA: 0x1e63a88 VA: 0x759447ba88
	public override IList`1 GetActiveBuffs() { }
	// RVA: 0x1e63aec VA: 0x759447baec
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e63b6c VA: 0x759447bb6c
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e63be4 VA: 0x759447bbe4
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e63c48 VA: 0x759447bc48
	protected override Void Reset() { }
	// RVA: 0x1e63d08 VA: 0x759447bd08
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e63f40 VA: 0x759447bf40
	public override Boolean CastToTarget(Entity target, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e64274 VA: 0x759447c274
	public override Boolean CastDirectly(FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e63fe4 VA: 0x759447bfe4
	private Boolean _DoCastInternal(Boolean isCastToTarget, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1e643bc VA: 0x759447c3bc
	public override Void ResetCooldown(Boolean waitFirstPeriod) { }
	// RVA: 0x1e64584 VA: 0x759447c584
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e646b8 VA: 0x759447c6b8
	protected override Void DoDetach() { }
	// RVA: 0x1e64784 VA: 0x759447c784
	protected override IEnumerator OnWaitForPreDelay() { }
	// RVA: 0x1e64820 VA: 0x759447c820
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e648bc VA: 0x759447c8bc
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e64a04 VA: 0x759447ca04
	public override Void OnAttackTimeChanged(FP newValue) { }
	// RVA: 0x1e64b3c VA: 0x759447cb3c
	private Void _OnSubAbilityFinished(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x1e64be8 VA: 0x759447cbe8
	public override Boolean CheckAtPreCastPhase() { }
	// RVA: 0x1e64ca8 VA: 0x759447cca8
	public override Void PreloadSpecialAudioSignals(String abilityId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1e64304 VA: 0x759447c304
	private Boolean _IsFirstAttack(Int32 currentAbilityIndex, Boolean isFirstAttack) { }
	// RVA: 0x1e644b0 VA: 0x759447c4b0
	private Void _SyncCooldownOnCastStartByOption() { }
	// RVA: 0x1e64e80 VA: 0x759447ce80
	public Void .ctor() { }
	// RVA: 0x1e64f00 VA: 0x759447cf00
	private FP <>xLuaBaseProxy_get_escapeTime() { }
	// RVA: 0x1e64f08 VA: 0x759447cf08
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e64f10 VA: 0x759447cf10
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e64f38 VA: 0x759447cf38
	private Boolean <>xLuaBaseProxy_CastToTarget(Entity P0, FinishCallbackDelegate P1, Boolean P2) { }
	// RVA: 0x1e64f44 VA: 0x759447cf44
	private Boolean <>xLuaBaseProxy_CastDirectly(FinishCallbackDelegate P0, Boolean P1) { }
	// RVA: 0x1e64f50 VA: 0x759447cf50
	private Void <>xLuaBaseProxy_ResetCooldown(Boolean P0) { }
	// RVA: 0x1e64f5c VA: 0x759447cf5c
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e64f64 VA: 0x759447cf64
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e64f6c VA: 0x759447cf6c
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e64f74 VA: 0x759447cf74
	private Void <>xLuaBaseProxy_OnAttackTimeChanged(FP P0) { }
	// RVA: 0x1e64f7c VA: 0x759447cf7c
	private Boolean <>xLuaBaseProxy_CheckAtPreCastPhase() { }
	// RVA: 0x1e64f84 VA: 0x759447cf84
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
}
```