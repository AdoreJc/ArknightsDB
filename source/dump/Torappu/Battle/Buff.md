# Buff

**Namespace:** `Torappu.Battle`


## Fields

- `BuffContainer m_container`

- `BuffData m_data`

- `FP m_lifeTime`

- `FP m_remainingTime`

- `FP m_existingTime`

- `Int32 m_triggerCnt`

- `Int32 m_stackCnt`

- `Int32 m_maxValidStackCnt`

- `Boolean m_refreshRemainingTimeWhenStackMax`

- `Boolean m_clearAllStackCntWhenTimeUp`

- `PrecisePeriodicTimer m_triggerTimer`

- `Blackboard m_blackboard`

- `RuntimeAttributesSnapshot m_runtimeAttributesSnapshot`

- `Boolean m_isDurableBuff`

- `Boolean m_isDamageMissable`

- `Boolean m_isSilenceable`

- `Boolean m_isStunnable`

- `Boolean m_isFreezable`

- `Boolean m_isStatusResistable`

- `Boolean m_isLevitatable`

- `Boolean m_started`

- `Boolean m_isFinished`

- `Boolean m_isActuallyFinished`

- `Boolean m_needRemove`

- `Boolean m_isActuallyEnabled`

- `Boolean m_isLateEnabled`

- `Boolean m_isManuallyEnabled`

- `Boolean m_isValid`

- `String <key>k__BackingField`

- `String <overrideKey>k__BackingField`

- `UInt32 <instanceUid>k__BackingField`

- `Int32 <priority>k__BackingField`

- `Int64 <attributeMask>k__BackingField`

- `Int64 <abnormalFlagMask>k__BackingField`

- `Int64 <abnormalImmuneMask>k__BackingField`

- `Int64 <abnormalAntiMask>k__BackingField`

- `Int64 <abnormalComboMask>k__BackingField`

- `Int64 <abnormalComboImmuneMask>k__BackingField`

- `String <effectKey>k__BackingField`

- `OnEventPriority <onEventPriority>k__BackingField`

- `String <audioSignal>k__BackingField`

- `Boolean <triggerable>k__BackingField`

- `DamageTypeMask m_shieldMask`

- `Boolean <hasShield>k__BackingField`


## Properties

- `String key`

- `String overrideKey`

- `UInt32 instanceUid`

- `Int32 priority`

- `Int32 triggerCnt`

- `Entity owner`

- `Entity source`

- `Projectile sourceProjectile`

- `Context context`

- `Int64 attributeMask`

- `Int64 abnormalFlagMask`

- `Int64 abnormalImmuneMask`

- `Int64 abnormalAntiMask`

- `Int64 abnormalComboMask`

- `Int64 abnormalComboImmuneMask`

- `Blackboard blackboard`

- `RuntimeAttributesSnapshot runtimeAttributesSnapshot`

- `FP lifeTime`

- `FP remainingTime`

- `FP existingTime`

- `FP remainingRatio`

- `FP triggerInterval`

- `PrecisePeriodicTimer triggerTimer`

- `String effectKey`

- `OnEventPriority onEventPriority`

- `String audioSignal`

- `Ability ability`

- `Boolean triggerable`

- `Boolean isEnabled`

- `Boolean isFinished`

- `Boolean needRemove`

- `Boolean isFinishedOrDisabled`

- `Int32 stackCnt`

- `Int32 validStackCnt`

- `Int32 overridableStackCnt`

- `Boolean isValid`

- `Boolean isStatusResistable`

- `Boolean hasShield`


## Methods

- `String get_key()`

- `Void set_key(String)`

- `String get_overrideKey()`

- `Void set_overrideKey(String)`

- `UInt32 get_instanceUid()`

- `Void set_instanceUid(UInt32)`

- `Int32 get_priority()`

- `Void set_priority(Int32)`

- `Int32 get_triggerCnt()`

- `Entity get_owner()`

- `Entity get_source()`

- `Projectile get_sourceProjectile()`

- `Context get_context()`

- `Int64 get_attributeMask()`

- `Void set_attributeMask(Int64)`

- `Int64 get_abnormalFlagMask()`

- `Void set_abnormalFlagMask(Int64)`

- `Int64 get_abnormalImmuneMask()`

- `Void set_abnormalImmuneMask(Int64)`

- `Int64 get_abnormalAntiMask()`

- `Void set_abnormalAntiMask(Int64)`

- `Int64 get_abnormalComboMask()`

- `Void set_abnormalComboMask(Int64)`

- `Int64 get_abnormalComboImmuneMask()`

- `Void set_abnormalComboImmuneMask(Int64)`

- `Blackboard get_blackboard()`

- `RuntimeAttributesSnapshot get_runtimeAttributesSnapshot()`

- `FP get_lifeTime()`

- `FP get_remainingTime()`

- `FP get_existingTime()`

- `FP get_remainingRatio()`

- `FP get_triggerInterval()`

- `PrecisePeriodicTimer get_triggerTimer()`

- `String get_effectKey()`

- `Void set_effectKey(String)`

- `OnEventPriority get_onEventPriority()`

- `Void set_onEventPriority(OnEventPriority)`

- `String get_audioSignal()`

- `Void set_audioSignal(String)`

- `Ability get_ability()`

- `Boolean get_triggerable()`

- `Void set_triggerable(Boolean)`

- `Boolean get_isEnabled()`

- `Void set_isEnabled(Boolean)`

- `Boolean get_isFinished()`

- `Boolean get_needRemove()`

- `Void set_needRemove(Boolean)`

- `Boolean get_isFinishedOrDisabled()`

- `Int32 get_stackCnt()`

- `Int32 get_validStackCnt()`

- `Int32 get_overridableStackCnt()`

- `Boolean get_isValid()`

- `Boolean get_isStatusResistable()`

- `Int32 CompareTo(Buff)`

- `Boolean _IsActionValid(Event)`

- `Void Reset(BuffConfig, BuffContainer, Entity, Ability, Blackboard, Blackboard, Projectile)`

- `Boolean GetValue(AttributeType, out, out, out, out)`

- `Void _ResetTriggerTimer()`

- `Boolean Trigger(Boolean)`

- `Boolean OverrideEffectKey(String)`

- `Void MarkFinish(Boolean)`

- `Void DecStackCntOrMarkFinish(Boolean, Boolean)`

- `Void _SetAttributeModifier(AttributeType, FP, FP, FP, FP)`

- `Void _SetAttributeModifier(AttributeType, FormulaItemType, FP)`

- `Void TryUpdateAttributeModifier(AttributeType, FP, FP, FP, FP)`

- `Void TryUpdateAttributeModifier(AttributeType, FP, FP, FP)`

- `Void TryUpdateAttributeModifier(AttributeType, FP, FP)`

- `Void TryUpdateAttributeModifier(AttributeType, FP)`

- `Void TryUpdateAttributeModifier(AttributeType, FormulaItemType, FP)`

- `Boolean CheckAttributeModifier(AttributeType, FormulaItemType, FP)`

- `Void OnAllocate()`

- `Void OnRecycle()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnStart()`

- `Boolean OnFinish(Boolean)`

- `Void OnTrigger()`

- `Void OnTick(FP)`

- `Void OnLateTick()`

- `Void AddDerivedBuff(ObjectPtr`1)`

- `Boolean ContainsAnyDerivedBuff()`

- `Boolean ContainsDerivedBuff(String)`

- `Void OnOwnerBorn()`

- `Void OnOwnerPostBorn()`

- `Void OnOwnerLocate()`

- `Void OnOwnerFinish(FinishReason, Entity)`

- `Void OnOwnerDying()`

- `Void OnGameOver()`

- `Void OnBeforeApplyingModifier(ref)`

- `Void OnApplyingModifier(ref)`

- `Void OnAppliedModifier(ref)`

- `Void OnApplyingSkippedModifier(ref)`

- `Void OnOutputModifier(ref)`

- `Void OnBeforeTargetApplyModifier(ref)`

- `Void OnAfterOutputDamage(ref)`

- `Void OnCalculateCachedProjectileDamage(ref)`

- `Void OnCalculateDamage(ref)`

- `Void OnAfterCalculateDamage()`

- `Void OnBeingCalculateDamage(ref)`

- `Void OnTakeDamage(ref)`

- `Void OnTakeEPDamage(ref)`

- `Void OnOutputDamage(ref)`

- `Void OnOutputAtkOrHeal()`

- `Void OnEvadeDamage(ref)`

- `Void OnBlockDamage(ref)`

- `Void OnTargetKilled(Entity)`

- `Void OnAbilityStart()`

- `Void OnOtherBuffStart()`

- `Void OnAbilityFinish()`

- `Void OnAbilitySpellOn()`

- `Void OnAbilityCastOnTarget()`

- `Void OnSkillStart()`

- `Void OnToggleSkillStart()`

- `Void OnSkillCastSucceed()`

- `Void OnSkillFinish()`

- `Void OnBeforeAttack()`

- `Void OnAfterAttack()`

- `Void OnBeforeTrySetHpZero()`

- `Void OnBeforeTrySetEpZero()`

- `Void OnBeforeDisappear()`

- `Void OnBeforeAppear()`

- `Void OnOwnerAbnormalFlagDirty()`

- `Void OnOwnerBlockeeChanged()`

- `Void OnCollideWithHighLand()`

- `Void OnBeforeExitUnbalancedState()`

- `Void OnEnterUnbalancedState()`

- `Void OnEnterMagicCircuit()`

- `Void OnLeaveMagicCircuit()`

- `Void OnAbilityInterrupted()`

- `Void OnOwnerRootTileChanged()`

- `Void OnOtherResistableBuffStart()`

- `Void OnEsOverZero()`

- `Void OnMotionModeChanged()`

- `Void OnDirectionChanged()`

- `Void OnBeforeDirectionChange()`

- `Void OnMakeEnemyUnbalanced()`

- `Void OnEnterLevitateState()`

- `Void OnEPBreakStart()`

- `Void OnBeforeEPBreakStart()`

- `Void OnEPBreakFinish()`

- `Void OnBeforeEPBreakFinish()`

- `Void OnBeforeExitLevitateState()`

- `Void OnEndPulling()`

- `Void OnBeforeFallDown()`

- `Void OnOwnerOverlapped()`

- `Void OnBossWaveWillStart()`

- `Void OnStageEnd()`

- `Void OnLegionModeDrawCard()`

- `Void OnLegionModeRefreshCard()`

- `Void OnSandboxOwnerResChanged()`

- `Void OnEntityWillOverlap()`

- `Void OnOwnerBeforeDead()`

- `Void OnUnitSwitchMode()`

- `Void CooperatePlayerDying()`

- `Void CooperatePlayerRevive()`

- `Snapshot _RunActions(Event, Boolean)`

- `Void _LoadAttributesModifier(AttributeModifierData, Int32)`

- `Boolean CheckAbnormalFlagAnti(Int64)`

- `Void TakeSnapshotToBuffAttribute()`

- `Void _ModifyLifeTimeFinally()`

- `Void _LoadActions(EventToActionMap)`

- `Void _MarkAttributeDirty(AttributeType)`

- `Int64 _CalcAbnormalMask(IList`1)`

- `Int64 _CalcAbnormalCombo(IList`1)`

- `Int32 _CalculatePriority(BuffConfig)`

- `Void _DoUpdateStack()`

- `Void _AddStack(Buff)`

- `Void _FillRemainingTimeWhenStackMax(Buff)`

- `Void _FillRemainingTime(Buff)`

- `Void _ExtendRemainingTime(Buff)`

- `Void _UpdateIsEnabledIfNotFinished()`

- `Boolean _InitIsStatusResistable()`

- `Boolean _AutoCalcIsStatusResistable()`

- `Void _PreprocessDeltaTime(ref)`

- `Void FinishDerivedBuff(String, Boolean, Boolean)`

- `Void ClearDerivedBuffsIfNot(Boolean)`

- `Void _UpdateOverrideMap()`

- `Boolean get_hasShield()`

- `Void set_hasShield(Boolean)`

- `ShieldData CalculateShieldData()`

- `Void _InitShieldSource()`

- `String <>xLuaBaseProxy_ToString()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Buff : IAttributesModifier, IShieldSource, IReusableObject, IReusable, IPtrObject, IComparable`1, IHotfixable
{
	private static UInt32 s_globalCounter; // 0x0
	private static readonly AbnormalFlag[] ABFLAGS_IS_AUTO_STATUS_RESISTABLE; // 0x8
	private static readonly AbnormalFlag[] ABFLAGS_ABLE_TO_BE_RESISTED; // 0x10
	public static readonly FP INFINITY_TIME; // 0x18
	public const Int32 EVENT_NUM; // 0x0
	private BuffContainer m_container; // 0x10
	private ObjectPtr`1 m_source; // 0x18
	private ObjectPtr`1 m_ability; // 0x28
	private ObjectPtr`1 m_sourceProjectile; // 0x38
	private FP[] m_attributeMultipliers; // 0x48
	private FP[] m_attributeAdditions; // 0x50
	private FP[] m_attributeFinalAdditions; // 0x58
	private FP[] m_attributeFinalScalers; // 0x60
	private BuffData m_data; // 0x68
	private FP m_lifeTime; // 0x70
	private FP m_remainingTime; // 0x78
	private FP m_existingTime; // 0x80
	private Int32 m_triggerCnt; // 0x88
	private Int32 m_stackCnt; // 0x8c
	private Int32 m_maxValidStackCnt; // 0x90
	private Boolean m_refreshRemainingTimeWhenStackMax; // 0x94
	private Boolean m_clearAllStackCntWhenTimeUp; // 0x95
	private PrecisePeriodicTimer m_triggerTimer; // 0x98
	private ActionNode[][] m_actions; // 0xa0
	private Blackboard m_blackboard; // 0xa8
	private RuntimeAttributesSnapshot m_runtimeAttributesSnapshot; // 0xb0
	private Boolean m_isDurableBuff; // 0x1e0
	private Boolean m_isDamageMissable; // 0x1e1
	private Boolean m_isSilenceable; // 0x1e2
	private Boolean m_isStunnable; // 0x1e3
	private Boolean m_isFreezable; // 0x1e4
	private Boolean m_isStatusResistable; // 0x1e5
	private Boolean m_isLevitatable; // 0x1e6
	private Boolean m_started; // 0x1e7
	private Boolean m_isFinished; // 0x1e8
	private Boolean m_isActuallyFinished; // 0x1e9
	private Boolean m_needRemove; // 0x1ea
	private Boolean m_isActuallyEnabled; // 0x1eb
	private Boolean m_isLateEnabled; // 0x1ec
	private Boolean m_isManuallyEnabled; // 0x1ed
	private Boolean m_isValid; // 0x1ee
	private String <key>k__BackingField; // 0x1f0
	private String <overrideKey>k__BackingField; // 0x1f8
	private UInt32 <instanceUid>k__BackingField; // 0x200
	private Int32 <priority>k__BackingField; // 0x204
	private Int64 <attributeMask>k__BackingField; // 0x208
	private Int64 <abnormalFlagMask>k__BackingField; // 0x210
	private Int64 <abnormalImmuneMask>k__BackingField; // 0x218
	private Int64 <abnormalAntiMask>k__BackingField; // 0x220
	private Int64 <abnormalComboMask>k__BackingField; // 0x228
	private Int64 <abnormalComboImmuneMask>k__BackingField; // 0x230
	private String <effectKey>k__BackingField; // 0x238
	private OnEventPriority <onEventPriority>k__BackingField; // 0x240
	private String <audioSignal>k__BackingField; // 0x248
	private Boolean <triggerable>k__BackingField; // 0x250
	private List`1 m_derivedBuffs; // 0x258
	private DamageTypeMask m_shieldMask; // 0x260
	private Boolean <hasShield>k__BackingField; // 0x264
	private static DelegateBridge __Hotfix0_get_key; // 0x20
	private static DelegateBridge __Hotfix0_set_key; // 0x28
	private static DelegateBridge __Hotfix0_get_overrideKey; // 0x30
	private static DelegateBridge __Hotfix0_set_overrideKey; // 0x38
	private static DelegateBridge __Hotfix0_get_instanceUid; // 0x40
	private static DelegateBridge __Hotfix0_set_instanceUid; // 0x48
	private static DelegateBridge __Hotfix0_get_priority; // 0x50
	private static DelegateBridge __Hotfix0_set_priority; // 0x58
	private static DelegateBridge __Hotfix0_get_triggerCnt; // 0x60
	private static DelegateBridge __Hotfix0_get_owner; // 0x68
	private static DelegateBridge __Hotfix0_get_source; // 0x70
	private static DelegateBridge __Hotfix0_get_sourceProjectile; // 0x78
	private static DelegateBridge __Hotfix0_get_context; // 0x80
	private static DelegateBridge __Hotfix0_get_attributeMask; // 0x88
	private static DelegateBridge __Hotfix0_set_attributeMask; // 0x90
	private static DelegateBridge __Hotfix0_get_abnormalFlagMask; // 0x98
	private static DelegateBridge __Hotfix0_set_abnormalFlagMask; // 0xa0
	private static DelegateBridge __Hotfix0_get_abnormalImmuneMask; // 0xa8
	private static DelegateBridge __Hotfix0_set_abnormalImmuneMask; // 0xb0
	private static DelegateBridge __Hotfix0_get_abnormalAntiMask; // 0xb8
	private static DelegateBridge __Hotfix0_set_abnormalAntiMask; // 0xc0
	private static DelegateBridge __Hotfix0_get_abnormalComboMask; // 0xc8
	private static DelegateBridge __Hotfix0_set_abnormalComboMask; // 0xd0
	private static DelegateBridge __Hotfix0_get_abnormalComboImmuneMask; // 0xd8
	private static DelegateBridge __Hotfix0_set_abnormalComboImmuneMask; // 0xe0
	private static DelegateBridge __Hotfix0_get_blackboard; // 0xe8
	private static DelegateBridge __Hotfix0_get_runtimeAttributesSnapshot; // 0xf0
	private static DelegateBridge __Hotfix0_get_lifeTime; // 0xf8
	private static DelegateBridge __Hotfix0_get_remainingTime; // 0x100
	private static DelegateBridge __Hotfix0_get_existingTime; // 0x108
	private static DelegateBridge __Hotfix0_get_remainingRatio; // 0x110
	private static DelegateBridge __Hotfix0_get_triggerInterval; // 0x118
	private static DelegateBridge __Hotfix0_get_triggerTimer; // 0x120
	private static DelegateBridge __Hotfix0_get_effectKey; // 0x128
	private static DelegateBridge __Hotfix0_set_effectKey; // 0x130
	private static DelegateBridge __Hotfix0_get_onEventPriority; // 0x138
	private static DelegateBridge __Hotfix0_set_onEventPriority; // 0x140
	private static DelegateBridge __Hotfix0_get_audioSignal; // 0x148
	private static DelegateBridge __Hotfix0_set_audioSignal; // 0x150
	private static DelegateBridge __Hotfix0_get_ability; // 0x158
	private static DelegateBridge __Hotfix0_get_triggerable; // 0x160
	private static DelegateBridge __Hotfix0_set_triggerable; // 0x168
	private static DelegateBridge __Hotfix0_get_derivedBuffs; // 0x170
	private static DelegateBridge __Hotfix0_get_isEnabled; // 0x178
	private static DelegateBridge __Hotfix0_set_isEnabled; // 0x180
	private static DelegateBridge __Hotfix0_get_isFinished; // 0x188
	private static DelegateBridge __Hotfix0_get_needRemove; // 0x190
	private static DelegateBridge __Hotfix0_set_needRemove; // 0x198
	private static DelegateBridge __Hotfix0_get_isFinishedOrDisabled; // 0x1a0
	private static DelegateBridge __Hotfix0_get_stackCnt; // 0x1a8
	private static DelegateBridge __Hotfix0_get_validStackCnt; // 0x1b0
	private static DelegateBridge __Hotfix0_get_overridableStackCnt; // 0x1b8
	private static DelegateBridge __Hotfix0_get_isValid; // 0x1c0
	private static DelegateBridge __Hotfix0_get_isStatusResistable; // 0x1c8
	private static DelegateBridge __Hotfix0_CompareTo; // 0x1d0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1d8
	private static DelegateBridge __Hotfix0__IsActionValid; // 0x1e0
	private static DelegateBridge __Hotfix0_Reset; // 0x1e8
	private static DelegateBridge __Hotfix0_GetValue; // 0x1f0
	private static DelegateBridge __Hotfix0__ResetTriggerTimer; // 0x1f8
	private static DelegateBridge __Hotfix0_Trigger; // 0x200
	private static DelegateBridge __Hotfix0_OverrideEffectKey; // 0x208
	private static DelegateBridge __Hotfix0_MarkFinish; // 0x210
	private static DelegateBridge __Hotfix0_DecStackCntOrMarkFinish; // 0x218
	private static DelegateBridge __Hotfix0__SetAttributeModifier; // 0x220
	private static DelegateBridge __Hotfix1__SetAttributeModifier; // 0x228
	private static DelegateBridge __Hotfix0_TryUpdateAttributeModifier; // 0x230
	private static DelegateBridge __Hotfix1_TryUpdateAttributeModifier; // 0x238
	private static DelegateBridge __Hotfix2_TryUpdateAttributeModifier; // 0x240
	private static DelegateBridge __Hotfix3_TryUpdateAttributeModifier; // 0x248
	private static DelegateBridge __Hotfix4_TryUpdateAttributeModifier; // 0x250
	private static DelegateBridge __Hotfix0_CheckAttributeModifier; // 0x258
	private static DelegateBridge __Hotfix0_ToString; // 0x260
	private static DelegateBridge __Hotfix0_FetchDuration; // 0x268
	private static DelegateBridge __Hotfix0_AddDerivedBuffSafe; // 0x270
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x278
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x280
	private static DelegateBridge __Hotfix0_OnEnable; // 0x288
	private static DelegateBridge __Hotfix0_OnDisable; // 0x290
	private static DelegateBridge __Hotfix0_OnStart; // 0x298
	private static DelegateBridge __Hotfix0_OnFinish; // 0x2a0
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x2a8
	private static DelegateBridge __Hotfix0_OnTick; // 0x2b0
	private static DelegateBridge __Hotfix0_OnLateTick; // 0x2b8
	private static DelegateBridge __Hotfix0_AddDerivedBuff; // 0x2c0
	private static DelegateBridge __Hotfix0_ContainsAnyDerivedBuff; // 0x2c8
	private static DelegateBridge __Hotfix0_ContainsDerivedBuff; // 0x2d0
	private static DelegateBridge __Hotfix0_OnOwnerBorn; // 0x2d8
	private static DelegateBridge __Hotfix0_OnOwnerPostBorn; // 0x2e0
	private static DelegateBridge __Hotfix0_OnOwnerLocate; // 0x2e8
	private static DelegateBridge __Hotfix0_OnOwnerFinish; // 0x2f0
	private static DelegateBridge __Hotfix0_OnOwnerDying; // 0x2f8
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x300
	private static DelegateBridge __Hotfix0_OnBeforeApplyingModifier; // 0x308
	private static DelegateBridge __Hotfix0_OnApplyingModifier; // 0x310
	private static DelegateBridge __Hotfix0_OnAppliedModifier; // 0x318
	private static DelegateBridge __Hotfix0_OnApplyingSkippedModifier; // 0x320
	private static DelegateBridge __Hotfix0_OnOutputModifier; // 0x328
	private static DelegateBridge __Hotfix0_OnBeforeTargetApplyModifier; // 0x330
	private static DelegateBridge __Hotfix0_OnAfterOutputDamage; // 0x338
	private static DelegateBridge __Hotfix0_OnCalculateCachedProjectileDamage; // 0x340
	private static DelegateBridge __Hotfix0_OnCalculateDamage; // 0x348
	private static DelegateBridge __Hotfix0_OnAfterCalculateDamage; // 0x350
	private static DelegateBridge __Hotfix0_OnBeingCalculateDamage; // 0x358
	private static DelegateBridge __Hotfix0_OnTakeDamage; // 0x360
	private static DelegateBridge __Hotfix0_OnTakeEPDamage; // 0x368
	private static DelegateBridge __Hotfix0_OnOutputDamage; // 0x370
	private static DelegateBridge __Hotfix0_OnOutputAtkOrHeal; // 0x378
	private static DelegateBridge __Hotfix0_OnEvadeDamage; // 0x380
	private static DelegateBridge __Hotfix0_OnBlockDamage; // 0x388
	private static DelegateBridge __Hotfix0_OnTargetKilled; // 0x390
	private static DelegateBridge __Hotfix0_OnAbilityStart; // 0x398
	private static DelegateBridge __Hotfix0_OnOtherBuffStart; // 0x3a0
	private static DelegateBridge __Hotfix0_OnAbilityFinish; // 0x3a8
	private static DelegateBridge __Hotfix0_OnAbilitySpellOn; // 0x3b0
	private static DelegateBridge __Hotfix0_OnAbilityCastOnTarget; // 0x3b8
	private static DelegateBridge __Hotfix0_OnSkillStart; // 0x3c0
	private static DelegateBridge __Hotfix0_OnToggleSkillStart; // 0x3c8
	private static DelegateBridge __Hotfix0_OnSkillCastSucceed; // 0x3d0
	private static DelegateBridge __Hotfix0_OnSkillFinish; // 0x3d8
	private static DelegateBridge __Hotfix0_OnBeforeAttack; // 0x3e0
	private static DelegateBridge __Hotfix0_OnAfterAttack; // 0x3e8
	private static DelegateBridge __Hotfix0_OnBeforeTrySetHpZero; // 0x3f0
	private static DelegateBridge __Hotfix0_OnBeforeTrySetEpZero; // 0x3f8
	private static DelegateBridge __Hotfix0_OnBeforeDisappear; // 0x400
	private static DelegateBridge __Hotfix0_OnBeforeAppear; // 0x408
	private static DelegateBridge __Hotfix0_OnOwnerAbnormalFlagDirty; // 0x410
	private static DelegateBridge __Hotfix0_OnOwnerBlockeeChanged; // 0x418
	private static DelegateBridge __Hotfix0_OnCollideWithHighLand; // 0x420
	private static DelegateBridge __Hotfix0_OnBeforeExitUnbalancedState; // 0x428
	private static DelegateBridge __Hotfix0_OnEnterUnbalancedState; // 0x430
	private static DelegateBridge __Hotfix0_OnEnterMagicCircuit; // 0x438
	private static DelegateBridge __Hotfix0_OnLeaveMagicCircuit; // 0x440
	private static DelegateBridge __Hotfix0_OnAbilityInterrupted; // 0x448
	private static DelegateBridge __Hotfix0_OnOwnerRootTileChanged; // 0x450
	private static DelegateBridge __Hotfix0_OnOtherResistableBuffStart; // 0x458
	private static DelegateBridge __Hotfix0_OnEsOverZero; // 0x460
	private static DelegateBridge __Hotfix0_OnMotionModeChanged; // 0x468
	private static DelegateBridge __Hotfix0_OnDirectionChanged; // 0x470
	private static DelegateBridge __Hotfix0_OnBeforeDirectionChange; // 0x478
	private static DelegateBridge __Hotfix0_OnMakeEnemyUnbalanced; // 0x480
	private static DelegateBridge __Hotfix0_OnEnterLevitateState; // 0x488
	private static DelegateBridge __Hotfix0_OnEPBreakStart; // 0x490
	private static DelegateBridge __Hotfix0_OnBeforeEPBreakStart; // 0x498
	private static DelegateBridge __Hotfix0_OnEPBreakFinish; // 0x4a0
	private static DelegateBridge __Hotfix0_OnBeforeEPBreakFinish; // 0x4a8
	private static DelegateBridge __Hotfix0_OnBeforeExitLevitateState; // 0x4b0
	private static DelegateBridge __Hotfix0_OnEndPulling; // 0x4b8
	private static DelegateBridge __Hotfix0_OnBeforeFallDown; // 0x4c0
	private static DelegateBridge __Hotfix0_OnOwnerOverlapped; // 0x4c8
	private static DelegateBridge __Hotfix0_OnBossWaveWillStart; // 0x4d0
	private static DelegateBridge __Hotfix0_OnStageEnd; // 0x4d8
	private static DelegateBridge __Hotfix0_OnLegionModeDrawCard; // 0x4e0
	private static DelegateBridge __Hotfix0_OnLegionModeRefreshCard; // 0x4e8
	private static DelegateBridge __Hotfix0_OnSandboxOwnerResChanged; // 0x4f0
	private static DelegateBridge __Hotfix0_OnEntityWillOverlap; // 0x4f8
	private static DelegateBridge __Hotfix0_OnOwnerBeforeDead; // 0x500
	private static DelegateBridge __Hotfix0_OnUnitSwitchMode; // 0x508
	private static DelegateBridge __Hotfix0_CooperatePlayerDying; // 0x510
	private static DelegateBridge __Hotfix0_CooperatePlayerRevive; // 0x518
	private static DelegateBridge __Hotfix0__RunActions; // 0x520
	private static DelegateBridge __Hotfix0__LoadAttributesModifier; // 0x528
	private static DelegateBridge __Hotfix0_CheckAbnormalFlagAnti; // 0x530
	private static DelegateBridge __Hotfix0_TakeSnapshotToBuffAttribute; // 0x538
	private static DelegateBridge __Hotfix0__ModifyLifeTimeFinally; // 0x540
	private static DelegateBridge __Hotfix0__LoadActions; // 0x548
	private static DelegateBridge __Hotfix0__MarkAttributeDirty; // 0x550
	private static DelegateBridge __Hotfix0__CalcAbnormalMask; // 0x558
	private static DelegateBridge __Hotfix0__CalcAbnormalCombo; // 0x560
	private static DelegateBridge __Hotfix0__CalculatePriority; // 0x568
	private static DelegateBridge __Hotfix0__DoUpdateStack; // 0x570
	private static DelegateBridge __Hotfix0__AddStack; // 0x578
	private static DelegateBridge __Hotfix0__FillRemainingTimeWhenStackMax; // 0x580
	private static DelegateBridge __Hotfix0__FillRemainingTime; // 0x588
	private static DelegateBridge __Hotfix0__ExtendRemainingTime; // 0x590
	private static DelegateBridge __Hotfix0__UpdateIsEnabledIfNotFinished; // 0x598
	private static DelegateBridge __Hotfix0__InitIsStatusResistable; // 0x5a0
	private static DelegateBridge __Hotfix0__AutoCalcIsStatusResistable; // 0x5a8
	private static DelegateBridge __Hotfix0__PreprocessDeltaTime; // 0x5b0
	private static DelegateBridge __Hotfix0_FinishDerivedBuff; // 0x5b8
	private static DelegateBridge __Hotfix0_ClearDerivedBuffsIfNot; // 0x5c0
	private static DelegateBridge __Hotfix0__UpdateOverrideMap; // 0x5c8
	private static DelegateBridge __Hotfix0_get_hasShield; // 0x5d0
	private static DelegateBridge __Hotfix0_set_hasShield; // 0x5d8
	private static DelegateBridge __Hotfix0_CalculateShieldData; // 0x5e0
	private static DelegateBridge __Hotfix0__InitShieldSource; // 0x5e8

	public String key { get; set; }
	public String overrideKey { get; set; }
	public UInt32 instanceUid { get; set; }
	public Int32 priority { get; set; }
	public Int32 triggerCnt { get; }
	public Entity owner { get; }
	public Entity source { get; }
	public Projectile sourceProjectile { get; }
	public Context context { get; }
	public Int64 attributeMask { get; set; }
	public Int64 abnormalFlagMask { get; set; }
	public Int64 abnormalImmuneMask { get; set; }
	public Int64 abnormalAntiMask { get; set; }
	public Int64 abnormalComboMask { get; set; }
	public Int64 abnormalComboImmuneMask { get; set; }
	public Blackboard blackboard { get; }
	public RuntimeAttributesSnapshot runtimeAttributesSnapshot { get; }
	public FP lifeTime { get; }
	public FP remainingTime { get; }
	public FP existingTime { get; }
	public FP remainingRatio { get; }
	public FP triggerInterval { get; }
	public PrecisePeriodicTimer triggerTimer { get; }
	public String effectKey { get; set; }
	public OnEventPriority onEventPriority { get; set; }
	public String audioSignal { get; set; }
	public Ability ability { get; }
	public Boolean triggerable { get; set; }
	public List`1 derivedBuffs { get; }
	public Boolean isEnabled { get; set; }
	public Boolean isFinished { get; }
	public Boolean needRemove { get; set; }
	public Boolean isFinishedOrDisabled { get; }
	public Int32 stackCnt { get; }
	public Int32 validStackCnt { get; }
	public Int32 overridableStackCnt { get; }
	public Boolean isValid { get; }
	public Boolean isStatusResistable { get; }
	public Boolean hasShield { get; set; }

	// RVA: 0x3f74254 VA: 0x759658c254
	public String get_key() { }
	// RVA: 0x3f742cc VA: 0x759658c2cc
	private Void set_key(String value) { }
	// RVA: 0x3f74360 VA: 0x759658c360
	public String get_overrideKey() { }
	// RVA: 0x3f743d8 VA: 0x759658c3d8
	private Void set_overrideKey(String value) { }
	// RVA: 0x3f7446c VA: 0x759658c46c
	public UInt32 get_instanceUid() { }
	// RVA: 0x3f744e4 VA: 0x759658c4e4
	private Void set_instanceUid(UInt32 value) { }
	// RVA: 0x3f74570 VA: 0x759658c570
	public Int32 get_priority() { }
	// RVA: 0x3f745e8 VA: 0x759658c5e8
	private Void set_priority(Int32 value) { }
	// RVA: 0x3f74674 VA: 0x759658c674
	public Int32 get_triggerCnt() { }
	// RVA: 0x3f746ec VA: 0x759658c6ec
	public Entity get_owner() { }
	// RVA: 0x3f747d4 VA: 0x759658c7d4
	public Entity get_source() { }
	// RVA: 0x3f74864 VA: 0x759658c864
	public Projectile get_sourceProjectile() { }
	// RVA: 0x3f748f4 VA: 0x759658c8f4
	public Context get_context() { }
	// RVA: 0x3f74a00 VA: 0x759658ca00
	public Int64 get_attributeMask() { }
	// RVA: 0x3f74a78 VA: 0x759658ca78
	private Void set_attributeMask(Int64 value) { }
	// RVA: 0x3f74b04 VA: 0x759658cb04
	public Int64 get_abnormalFlagMask() { }
	// RVA: 0x3f74b7c VA: 0x759658cb7c
	private Void set_abnormalFlagMask(Int64 value) { }
	// RVA: 0x3f74c08 VA: 0x759658cc08
	public Int64 get_abnormalImmuneMask() { }
	// RVA: 0x3f74c80 VA: 0x759658cc80
	private Void set_abnormalImmuneMask(Int64 value) { }
	// RVA: 0x3f74d0c VA: 0x759658cd0c
	public Int64 get_abnormalAntiMask() { }
	// RVA: 0x3f74d84 VA: 0x759658cd84
	private Void set_abnormalAntiMask(Int64 value) { }
	// RVA: 0x3f74e10 VA: 0x759658ce10
	public Int64 get_abnormalComboMask() { }
	// RVA: 0x3f74e88 VA: 0x759658ce88
	private Void set_abnormalComboMask(Int64 value) { }
	// RVA: 0x3f74f14 VA: 0x759658cf14
	public Int64 get_abnormalComboImmuneMask() { }
	// RVA: 0x3f74f8c VA: 0x759658cf8c
	private Void set_abnormalComboImmuneMask(Int64 value) { }
	// RVA: 0x3f75018 VA: 0x759658d018
	public Blackboard get_blackboard() { }
	// RVA: 0x3f75090 VA: 0x759658d090
	public RuntimeAttributesSnapshot get_runtimeAttributesSnapshot() { }
	// RVA: 0x3f75144 VA: 0x759658d144
	public FP get_lifeTime() { }
	// RVA: 0x3f751bc VA: 0x759658d1bc
	public FP get_remainingTime() { }
	// RVA: 0x3f75234 VA: 0x759658d234
	public FP get_existingTime() { }
	// RVA: 0x3f752ac VA: 0x759658d2ac
	public FP get_remainingRatio() { }
	// RVA: 0x3f753ac VA: 0x759658d3ac
	public FP get_triggerInterval() { }
	// RVA: 0x3f75430 VA: 0x759658d430
	public PrecisePeriodicTimer get_triggerTimer() { }
	// RVA: 0x3f754a8 VA: 0x759658d4a8
	public String get_effectKey() { }
	// RVA: 0x3f75520 VA: 0x759658d520
	private Void set_effectKey(String value) { }
	// RVA: 0x3f755b4 VA: 0x759658d5b4
	public OnEventPriority get_onEventPriority() { }
	// RVA: 0x3f7562c VA: 0x759658d62c
	public Void set_onEventPriority(OnEventPriority value) { }
	// RVA: 0x3f756b8 VA: 0x759658d6b8
	public String get_audioSignal() { }
	// RVA: 0x3f75730 VA: 0x759658d730
	private Void set_audioSignal(String value) { }
	// RVA: 0x3f757c4 VA: 0x759658d7c4
	public Ability get_ability() { }
	// RVA: 0x3f75854 VA: 0x759658d854
	public Boolean get_triggerable() { }
	// RVA: 0x3f758cc VA: 0x759658d8cc
	private Void set_triggerable(Boolean value) { }
	// RVA: 0x3f7595c VA: 0x759658d95c
	public List`1 get_derivedBuffs() { }
	// RVA: 0x3f759d4 VA: 0x759658d9d4
	public Boolean get_isEnabled() { }
	// RVA: 0x3f75a4c VA: 0x759658da4c
	private Void set_isEnabled(Boolean value) { }
	// RVA: 0x3f75d08 VA: 0x759658dd08
	public Boolean get_isFinished() { }
	// RVA: 0x3f75dd4 VA: 0x759658ddd4
	public Boolean get_needRemove() { }
	// RVA: 0x3f75e60 VA: 0x759658de60
	public Void set_needRemove(Boolean value) { }
	// RVA: 0x3f75ef0 VA: 0x759658def0
	public Boolean get_isFinishedOrDisabled() { }
	// RVA: 0x3f75f88 VA: 0x759658df88
	public Int32 get_stackCnt() { }
	// RVA: 0x3f76000 VA: 0x759658e000
	public Int32 get_validStackCnt() { }
	// RVA: 0x3f760bc VA: 0x759658e0bc
	public Int32 get_overridableStackCnt() { }
	// RVA: 0x3f76208 VA: 0x759658e208
	public Boolean get_isValid() { }
	// RVA: 0x3f76280 VA: 0x759658e280
	public Boolean get_isStatusResistable() { }
	// RVA: 0x3f762f8 VA: 0x759658e2f8
	public Int32 CompareTo(Buff another) { }
	// RVA: 0x3f763f0 VA: 0x759658e3f0
	private Void .ctor() { }
	// RVA: 0x3f76600 VA: 0x759658e600
	private Boolean _IsActionValid(Event ev) { }
	// RVA: 0x3f766d0 VA: 0x759658e6d0
	protected Void Reset(BuffConfig config, BuffContainer container, Entity source, Ability ability, Blackboard extraBlackboard, Blackboard extraBlackboard2, Projectile sourceProjectile) { }
	// RVA: 0x3f782b8 VA: 0x75965902b8
	public Boolean GetValue(AttributeType attribute, out FP addition, out FP multiplier, out FP finalAddition, out FP finalScaler) { }
	// RVA: 0x3f78468 VA: 0x7596590468
	private Void _ResetTriggerTimer() { }
	// RVA: 0x3f78510 VA: 0x7596590510
	public Boolean Trigger(Boolean force) { }
	// RVA: 0x3f786b0 VA: 0x75965906b0
	public Boolean OverrideEffectKey(String effectKey) { }
	// RVA: 0x3f78760 VA: 0x7596590760
	public Void MarkFinish(Boolean updateOverrideMap) { }
	// RVA: 0x3f78a7c VA: 0x7596590a7c
	public Void DecStackCntOrMarkFinish(Boolean updateOverrideMap, Boolean isTimeUp) { }
	// RVA: 0x3f78c6c VA: 0x7596590c6c
	private Void _SetAttributeModifier(AttributeType attribute, FP addition, FP scale, FP finalAddition, FP finalScaler) { }
	// RVA: 0x3f78e98 VA: 0x7596590e98
	private Void _SetAttributeModifier(AttributeType attribute, FormulaItemType formula, FP value) { }
	// RVA: 0x3f78fac VA: 0x7596590fac
	public Void TryUpdateAttributeModifier(AttributeType attribute, FP addition, FP scale, FP finalAddition, FP finalScaler) { }
	// RVA: 0x3f791bc VA: 0x75965911bc
	public Void TryUpdateAttributeModifier(AttributeType attribute, FP addition, FP scale, FP finalAddition) { }
	// RVA: 0x3f792ac VA: 0x75965912ac
	public Void TryUpdateAttributeModifier(AttributeType attribute, FP addition, FP scale) { }
	// RVA: 0x3f79394 VA: 0x7596591394
	public Void TryUpdateAttributeModifier(AttributeType attribute, FP addition) { }
	// RVA: 0x3f79468 VA: 0x7596591468
	public Void TryUpdateAttributeModifier(AttributeType attribute, FormulaItemType formula, FP value) { }
	// RVA: 0x3f79548 VA: 0x7596591548
	public Boolean CheckAttributeModifier(AttributeType attribute, FormulaItemType type, FP value) { }
	// RVA: 0x3f7969c VA: 0x759659169c
	public override String ToString() { }
	// RVA: 0x3f79a04 VA: 0x7596591a04
	public static FP FetchDuration(BuffData data, Blackboard extraBlackboard, Blackboard extraBlackboard2) { }
	// RVA: 0x3f79d30 VA: 0x7596591d30
	public static Void AddDerivedBuffSafe(Buff parentBuff, Buff derivedBuff, Boolean finishDerivedBuffIfParentFinish) { }
	// RVA: 0x3f7a018 VA: 0x7596592018
	public Void OnAllocate() { }
	// RVA: 0x3f7a0c0 VA: 0x75965920c0
	public Void OnRecycle() { }
	// RVA: 0x3f7a144 VA: 0x7596592144
	protected Void OnEnable() { }
	// RVA: 0x3f7a530 VA: 0x7596592530
	protected Void OnDisable() { }
	// RVA: 0x3f7a5f8 VA: 0x75965925f8
	protected Void OnStart() { }
	// RVA: 0x3f7a6ec VA: 0x75965926ec
	protected Boolean OnFinish(Boolean immediatelyFinishEffect) { }
	// RVA: 0x3f785c4 VA: 0x75965905c4
	protected Void OnTrigger() { }
	// RVA: 0x3f7a800 VA: 0x7596592800
	protected Void OnTick(FP deltaTime) { }
	// RVA: 0x3f7abe4 VA: 0x7596592be4
	protected Void OnLateTick() { }
	// RVA: 0x3f79e40 VA: 0x7596591e40
	public Void AddDerivedBuff(ObjectPtr`1 buff) { }
	// RVA: 0x3f7aca8 VA: 0x7596592ca8
	public Boolean ContainsAnyDerivedBuff() { }
	// RVA: 0x3f7add4 VA: 0x7596592dd4
	public Boolean ContainsDerivedBuff(String buffKey) { }
	// RVA: 0x3f7af4c VA: 0x7596592f4c
	protected Void OnOwnerBorn() { }
	// RVA: 0x3f7affc VA: 0x7596592ffc
	protected Void OnOwnerPostBorn() { }
	// RVA: 0x3f7b0ac VA: 0x75965930ac
	protected Void OnOwnerLocate() { }
	// RVA: 0x3f7b15c VA: 0x759659315c
	protected Void OnOwnerFinish(FinishReason reason, Entity source) { }
	// RVA: 0x3f7b3c8 VA: 0x75965933c8
	protected Void OnOwnerDying() { }
	// RVA: 0x3f7b478 VA: 0x7596593478
	protected Void OnGameOver() { }
	// RVA: 0x3f7b528 VA: 0x7596593528
	protected Void OnBeforeApplyingModifier(ref Modifier modifier) { }
	// RVA: 0x3f7b600 VA: 0x7596593600
	protected Void OnApplyingModifier(ref Modifier modifier) { }
	// RVA: 0x3f7b6d8 VA: 0x75965936d8
	protected Void OnAppliedModifier(ref Modifier modifier) { }
	// RVA: 0x3f7b7b0 VA: 0x75965937b0
	protected Void OnApplyingSkippedModifier(ref Modifier modifier) { }
	// RVA: 0x3f7b888 VA: 0x7596593888
	protected Void OnOutputModifier(ref Modifier modifier) { }
	// RVA: 0x3f7b960 VA: 0x7596593960
	protected Void OnBeforeTargetApplyModifier(ref Modifier modifier) { }
	// RVA: 0x3f7ba38 VA: 0x7596593a38
	protected Void OnAfterOutputDamage(ref Modifier modifier) { }
	// RVA: 0x3f7baf0 VA: 0x7596593af0
	protected Void OnCalculateCachedProjectileDamage(ref AttackInfo atkInfo) { }
	// RVA: 0x3f7bbc0 VA: 0x7596593bc0
	protected Void OnCalculateDamage(ref AttackInfo atkInfo) { }
	// RVA: 0x3f7bc90 VA: 0x7596593c90
	protected Void OnAfterCalculateDamage() { }
	// RVA: 0x3f7bd40 VA: 0x7596593d40
	protected Void OnBeingCalculateDamage(ref AttackInfo atkInfo) { }
	// RVA: 0x3f7be10 VA: 0x7596593e10
	protected Void OnTakeDamage(ref Modifier modifier) { }
	// RVA: 0x3f7bee8 VA: 0x7596593ee8
	protected Void OnTakeEPDamage(ref Modifier modifier) { }
	// RVA: 0x3f7bfc0 VA: 0x7596593fc0
	protected Void OnOutputDamage(ref Modifier modifier) { }
	// RVA: 0x3f7c098 VA: 0x7596594098
	protected Void OnOutputAtkOrHeal() { }
	// RVA: 0x3f7c148 VA: 0x7596594148
	protected Void OnEvadeDamage(ref Modifier modifier) { }
	// RVA: 0x3f7c220 VA: 0x7596594220
	protected Void OnBlockDamage(ref Modifier modifier) { }
	// RVA: 0x3f7c2f8 VA: 0x75965942f8
	protected Void OnTargetKilled(Entity target) { }
	// RVA: 0x3f7c3b0 VA: 0x75965943b0
	protected Void OnAbilityStart() { }
	// RVA: 0x3f7c460 VA: 0x7596594460
	protected Void OnOtherBuffStart() { }
	// RVA: 0x3f7c510 VA: 0x7596594510
	protected Void OnAbilityFinish() { }
	// RVA: 0x3f7c5c0 VA: 0x75965945c0
	protected Void OnAbilitySpellOn() { }
	// RVA: 0x3f7c670 VA: 0x7596594670
	protected Void OnAbilityCastOnTarget() { }
	// RVA: 0x3f7c720 VA: 0x7596594720
	protected Void OnSkillStart() { }
	// RVA: 0x3f7c7d0 VA: 0x75965947d0
	protected Void OnToggleSkillStart() { }
	// RVA: 0x3f7c880 VA: 0x7596594880
	protected Void OnSkillCastSucceed() { }
	// RVA: 0x3f7c930 VA: 0x7596594930
	protected Void OnSkillFinish() { }
	// RVA: 0x3f7c9e0 VA: 0x75965949e0
	protected Void OnBeforeAttack() { }
	// RVA: 0x3f7ca90 VA: 0x7596594a90
	protected Void OnAfterAttack() { }
	// RVA: 0x3f7cb40 VA: 0x7596594b40
	protected Void OnBeforeTrySetHpZero() { }
	// RVA: 0x3f7cbf0 VA: 0x7596594bf0
	protected Void OnBeforeTrySetEpZero() { }
	// RVA: 0x3f7cca0 VA: 0x7596594ca0
	protected Void OnBeforeDisappear() { }
	// RVA: 0x3f7cd50 VA: 0x7596594d50
	protected Void OnBeforeAppear() { }
	// RVA: 0x3f7ce00 VA: 0x7596594e00
	protected Void OnOwnerAbnormalFlagDirty() { }
	// RVA: 0x3f7ceb0 VA: 0x7596594eb0
	protected Void OnOwnerBlockeeChanged() { }
	// RVA: 0x3f7cf60 VA: 0x7596594f60
	protected Void OnCollideWithHighLand() { }
	// RVA: 0x3f7d010 VA: 0x7596595010
	protected Void OnBeforeExitUnbalancedState() { }
	// RVA: 0x3f7d0c0 VA: 0x75965950c0
	protected Void OnEnterUnbalancedState() { }
	// RVA: 0x3f7d170 VA: 0x7596595170
	protected Void OnEnterMagicCircuit() { }
	// RVA: 0x3f7d220 VA: 0x7596595220
	protected Void OnLeaveMagicCircuit() { }
	// RVA: 0x3f7d2d0 VA: 0x75965952d0
	protected Void OnAbilityInterrupted() { }
	// RVA: 0x3f7d380 VA: 0x7596595380
	protected Void OnOwnerRootTileChanged() { }
	// RVA: 0x3f7d430 VA: 0x7596595430
	protected Void OnOtherResistableBuffStart() { }
	// RVA: 0x3f7d4e0 VA: 0x75965954e0
	protected Void OnEsOverZero() { }
	// RVA: 0x3f7d590 VA: 0x7596595590
	protected Void OnMotionModeChanged() { }
	// RVA: 0x3f7d640 VA: 0x7596595640
	protected Void OnDirectionChanged() { }
	// RVA: 0x3f7d6f0 VA: 0x75965956f0
	protected Void OnBeforeDirectionChange() { }
	// RVA: 0x3f7d7a0 VA: 0x75965957a0
	protected Void OnMakeEnemyUnbalanced() { }
	// RVA: 0x3f7d850 VA: 0x7596595850
	protected Void OnEnterLevitateState() { }
	// RVA: 0x3f7d900 VA: 0x7596595900
	protected Void OnEPBreakStart() { }
	// RVA: 0x3f7d9b0 VA: 0x75965959b0
	protected Void OnBeforeEPBreakStart() { }
	// RVA: 0x3f7da60 VA: 0x7596595a60
	protected Void OnEPBreakFinish() { }
	// RVA: 0x3f7db10 VA: 0x7596595b10
	protected Void OnBeforeEPBreakFinish() { }
	// RVA: 0x3f7dbc0 VA: 0x7596595bc0
	protected Void OnBeforeExitLevitateState() { }
	// RVA: 0x3f7dc70 VA: 0x7596595c70
	protected Void OnEndPulling() { }
	// RVA: 0x3f7dd20 VA: 0x7596595d20
	protected Void OnBeforeFallDown() { }
	// RVA: 0x3f7ddd0 VA: 0x7596595dd0
	protected Void OnOwnerOverlapped() { }
	// RVA: 0x3f7de80 VA: 0x7596595e80
	protected Void OnBossWaveWillStart() { }
	// RVA: 0x3f7df30 VA: 0x7596595f30
	protected Void OnStageEnd() { }
	// RVA: 0x3f7dfe0 VA: 0x7596595fe0
	protected Void OnLegionModeDrawCard() { }
	// RVA: 0x3f7e090 VA: 0x7596596090
	protected Void OnLegionModeRefreshCard() { }
	// RVA: 0x3f7e140 VA: 0x7596596140
	protected Void OnSandboxOwnerResChanged() { }
	// RVA: 0x3f7e1f0 VA: 0x75965961f0
	protected Void OnEntityWillOverlap() { }
	// RVA: 0x3f7e2a0 VA: 0x75965962a0
	protected Void OnOwnerBeforeDead() { }
	// RVA: 0x3f7e350 VA: 0x7596596350
	protected Void OnUnitSwitchMode() { }
	// RVA: 0x3f7e400 VA: 0x7596596400
	protected Void CooperatePlayerDying() { }
	// RVA: 0x3f7e4b0 VA: 0x75965964b0
	protected Void CooperatePlayerRevive() { }
	// RVA: 0x3f7a20c VA: 0x759659220c
	private Snapshot _RunActions(Event ev, Boolean setMeAsTarget) { }
	// RVA: 0x3f772d4 VA: 0x759658f2d4
	private Void _LoadAttributesModifier(AttributeModifierData data, Int32 stackCnt) { }
	// RVA: 0x3f7e9a4 VA: 0x75965969a4
	public Boolean CheckAbnormalFlagAnti(Int64 antiMask) { }
	// RVA: 0x3f7e8a0 VA: 0x75965968a0
	private Void TakeSnapshotToBuffAttribute() { }
	// RVA: 0x3f770fc VA: 0x759658f0fc
	private Void _ModifyLifeTimeFinally() { }
	// RVA: 0x3f778a4 VA: 0x759658f8a4
	private Void _LoadActions(EventToActionMap eventToActions) { }
	// RVA: 0x3f78db0 VA: 0x7596590db0
	private Void _MarkAttributeDirty(AttributeType attribute) { }
	// RVA: 0x3f7e560 VA: 0x7596596560
	private Int64 _CalcAbnormalMask(IList`1 flags) { }
	// RVA: 0x3f7e700 VA: 0x7596596700
	private Int64 _CalcAbnormalCombo(IList`1 combos) { }
	// RVA: 0x3f77a74 VA: 0x759658fa74
	private Int32 _CalculatePriority(BuffConfig config) { }
	// RVA: 0x3f78b8c VA: 0x7596590b8c
	private Void _DoUpdateStack() { }
	// RVA: 0x3f7ea4c VA: 0x7596596a4c
	private Void _AddStack(Buff buff) { }
	// RVA: 0x3f7eb38 VA: 0x7596596b38
	private Void _FillRemainingTimeWhenStackMax(Buff buff) { }
	// RVA: 0x3f7ec14 VA: 0x7596596c14
	private Void _FillRemainingTime(Buff buff) { }
	// RVA: 0x3f7ee00 VA: 0x7596596e00
	private Void _ExtendRemainingTime(Buff buff) { }
	// RVA: 0x3f75afc VA: 0x759658dafc
	private Void _UpdateIsEnabledIfNotFinished() { }
	// RVA: 0x3f78080 VA: 0x7596590080
	private Boolean _InitIsStatusResistable() { }
	// RVA: 0x3f7eff4 VA: 0x7596596ff4
	private Boolean _AutoCalcIsStatusResistable() { }
	// RVA: 0x3f7aa20 VA: 0x7596592a20
	private Void _PreprocessDeltaTime(ref FP deltaTime) { }
	// RVA: 0x3f7f110 VA: 0x7596597110
	public Void FinishDerivedBuff(String buffKey, Boolean decCntIfStack, Boolean updateOverrideMap) { }
	// RVA: 0x3f78828 VA: 0x7596590828
	public Void ClearDerivedBuffsIfNot(Boolean updateOverrideMap) { }
	// RVA: 0x3f789d8 VA: 0x75965909d8
	private Void _UpdateOverrideMap() { }
	// RVA: 0x3f7f410 VA: 0x7596597410
	public Boolean get_hasShield() { }
	// RVA: 0x3f7f488 VA: 0x7596597488
	private Void set_hasShield(Boolean value) { }
	// RVA: 0x3f7f518 VA: 0x7596597518
	public ShieldData CalculateShieldData() { }
	// RVA: 0x3f78130 VA: 0x7596590130
	private Void _InitShieldSource() { }
	// RVA: 0x3f7f60c VA: 0x759659760c
	private static Void .cctor() { }
	// RVA: 0x3f7f72c VA: 0x759659772c
	private String <>xLuaBaseProxy_ToString() { }
}
```