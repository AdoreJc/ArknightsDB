# BuffContainer

**Namespace:** ` `


## Fields

- `Entity <owner>k__BackingField`

- `SortedDoubleBufferedBuffList m_buffs`


## Properties

- `Entity owner`

- `Attributes attributes`

- `Context context`

- `Int32 buffCnt`


## Methods

- `Entity get_owner()`

- `Void set_owner(Entity)`

- `Attributes get_attributes()`

- `Context get_context()`

- `Int32 get_buffCnt()`

- `Buff NewBuff(BuffConfig, Entity, Ability, Blackboard, Blackboard, Projectile)`

- `Boolean RemoveBuff(UInt32)`

- `Void RemoveBuffs(IList`1)`

- `Void RemoveBuffs(String)`

- `Void RemoveOneBuffByKey(String, Boolean)`

- `Void RemoveBuffsByBuffSource(Entity, String, Boolean)`

- `Void RemoveAllStatusResistableBuffs()`

- `Void RemoveAllBuffsWithCertainAbnormalFlag(AbnormalFlag)`

- `Void ForceRefreshFinishedBuffs()`

- `Void ResetAllBuffsTriggerTimer()`

- `Void DecStackCntBuffsOrMarkFinish(String, Boolean)`

- `Buff GetBuffByUid(UInt32)`

- `Buff GetFirstBuffByKey(String)`

- `Buff GetFirstBuffByKeyAndSource(String, Entity)`

- `Boolean CheckTriggerableBuffByKeys(String[], Buff)`

- `Boolean TriggerBuffByKeys(String[], Buff, Boolean)`

- `Boolean TriggerAllBuffsByKeys(String[], Buff, Boolean)`

- `Boolean TryGetOverrideGroup(String, out)`

- `String GetOverrideKeyCandidate(String)`

- `Void EnsureOverrideIndependentKey(String, String)`

- `Boolean TryGetOverrideGroup(Buff, out)`

- `Boolean ContainsBuff(String)`

- `Boolean ContainsBuffFromCertainSource(String, Entity)`

- `Boolean ContainsStatusResistableBuff()`

- `Boolean ContainsResistableAbnormalFlagsBuff()`

- `Boolean ContainsIrresistibleAbnormalFlagsBuff()`

- `Boolean TryGetFirstBuffStackCount(String, out)`

- `Boolean TryGetFirstBuffStackCountFromCertainSource(String, Entity, out)`

- `Boolean TryGetFirstBuffValidStackCount(String, out)`

- `Int32 GetOverridableBuffStackCount(String)`

- `Boolean TryGetBuffCountByKeyFromAllBuffs(String, out)`

- `Boolean TryGetBuffCountByKeyFromAllBuffsWithCertainSource(String, Entity, out)`

- `Boolean TryGetBuffCountByBlackboardFromAll(String, String, Int32, out)`

- `Boolean TryGetBuffBlackboardValueByBlackboardFromAll(String, String, Int32, String, out)`

- `Void Tick(FP)`

- `Void Clear(Boolean)`

- `Void ClearWithWhiteList(List`1, Boolean)`

- `Void _ClearBuffOverrideMapWithWhiteList(List`1)`

- `Void _ClearBuffUidMapWithWhiteList(List`1)`

- `Void _CheckFinishedBuffs()`

- `Boolean _CheckBuffsActionValid(Event)`

- `Boolean _CheckThroughBuffAbnormalAnti(BuffData)`

- `Boolean _CheckThroughBuffStatusResistableAnti(Buff)`

- `Boolean _CheckThroughLevitateBuffCondition(BuffData)`

- `Void _FilterBuffAbnormalAnti(Int64)`

- `Void _FinishAndRemoveBuff(Buff)`

- `Void _FinishBuff(Buff, Boolean, Boolean, Boolean)`

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

- `Void OnEvadeDamage(ref)`

- `Void OnBlockDamage(ref)`

- `Void OnTakeDamage(ref)`

- `Void OnTakeEPDamage(ref)`

- `Void OnEPBreakStart()`

- `Void OnBeforeEPBreakStart()`

- `Void OnEPBreakFinish()`

- `Void OnBeforeEPBreakFinish()`

- `Void OnOutputDamage(ref)`

- `Void OnOutputAtkOrHeal(Ability)`

- `Void OnTargetKilled(Entity)`

- `Void OnCalculateCachedProjectileDamage(Entity, ref)`

- `Void OnCalculateDamage(Entity, ref)`

- `Void OnAfterCalculateDamage(Entity)`

- `Void OnBeingCalculateDamage(ref)`

- `Void OnAbilityStart(Ability)`

- `Void OnMakeEnemyUnbalanced(Entity)`

- `Void OnEnterLevitateState()`

- `Void OnBeforeExitLevitateState()`

- `Void OnEndPulling(Entity)`

- `Void OnBeforeFallDown()`

- `Void OnOwnerOverlapped(Entity)`

- `Void OnBossWaveWillStart()`

- `Void OnStageEnd()`

- `Void OnOtherBuffStart(Buff)`

- `Void OnOtherResistableBuffStart(Buff)`

- `Void OnAbilityFinish(Ability)`

- `Void OnAbilityInterrupted(Ability)`

- `Void OnAbilitySpellOn(Ability)`

- `Void OnAbilityCastOnTarget(Ability, Entity)`

- `Void OnSkillStart(BasicSkill)`

- `Void OnToggleSkillStart(BasicSkill)`

- `Void OnSkillCastSucceed(BasicSkill)`

- `Void OnSkillFinish(BasicSkill)`

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

- `Void OnOwnerRootTileChanged(Tile)`

- `Void OnMotionModeChanged()`

- `Void OnDirectionChanged()`

- `Void OnBeforeDirectionChange()`

- `Void OnEsOverZero()`

- `Void OnLegionModeDrawCard()`

- `Void OnLegionModeRefreshCard()`

- `Void OnSandboxOwnerResChanged()`

- `Void OnEntityWillOverlap(Entity, Direction)`

- `Void OnOwnerBeforeDead()`

- `Void OnUnitSwitchMode()`

- `Void CooperatePlayerDying()`

- `Void CooperatePlayerRevive()`

- `FP CalculateShieldValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BuffContainer : IHotfixable
{
	private Entity <owner>k__BackingField; // 0x10
	private SortedDoubleBufferedBuffList m_buffs; // 0x18
	private Dictionary`2 m_buffOverrideMap; // 0x20
	private Dictionary`2 m_buffUidMap; // 0x28
	private static DelegateBridge __Hotfix0_get_owner; // 0x0
	private static DelegateBridge __Hotfix0_set_owner; // 0x8
	private static DelegateBridge __Hotfix0_get_attributes; // 0x10
	private static DelegateBridge __Hotfix0_get_context; // 0x18
	private static DelegateBridge __Hotfix0_get_buffCnt; // 0x20
	private static DelegateBridge __Hotfix0_get_pool; // 0x28
	private static DelegateBridge __Hotfix0_CreateBuff; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38
	private static DelegateBridge __Hotfix0_NewBuff; // 0x40
	private static DelegateBridge __Hotfix0_RemoveBuff; // 0x48
	private static DelegateBridge __Hotfix0_RemoveBuffs; // 0x50
	private static DelegateBridge __Hotfix1_RemoveBuffs; // 0x58
	private static DelegateBridge __Hotfix0_RemoveOneBuffByKey; // 0x60
	private static DelegateBridge __Hotfix0_RemoveBuffsByBuffSource; // 0x68
	private static DelegateBridge __Hotfix0_CollectBuffSourceByBuffKey_DISPOSE; // 0x70
	private static DelegateBridge __Hotfix0_RemoveAllStatusResistableBuffs; // 0x78
	private static DelegateBridge __Hotfix0_RemoveAllBuffsWithCertainAbnormalFlag; // 0x80
	private static DelegateBridge __Hotfix0_ForceRefreshFinishedBuffs; // 0x88
	private static DelegateBridge __Hotfix0_ResetAllBuffsTriggerTimer; // 0x90
	private static DelegateBridge __Hotfix0_DecStackCntBuffsOrMarkFinish; // 0x98
	private static DelegateBridge __Hotfix0_GetBuffByUid; // 0xa0
	private static DelegateBridge __Hotfix0_GetFirstBuffByKey; // 0xa8
	private static DelegateBridge __Hotfix0_GetFirstBuffByKeyAndSource; // 0xb0
	private static DelegateBridge __Hotfix0_CheckTriggerableBuffByKeys; // 0xb8
	private static DelegateBridge __Hotfix0_TriggerBuffByKeys; // 0xc0
	private static DelegateBridge __Hotfix0_TriggerAllBuffsByKeys; // 0xc8
	private static DelegateBridge __Hotfix0_TryGetOverrideGroup; // 0xd0
	private static DelegateBridge __Hotfix0_GetOverrideKeyCandidate; // 0xd8
	private static DelegateBridge __Hotfix0_EnsureOverrideIndependentKey; // 0xe0
	private static DelegateBridge __Hotfix1_TryGetOverrideGroup; // 0xe8
	private static DelegateBridge __Hotfix0_ContainsBuff; // 0xf0
	private static DelegateBridge __Hotfix0_ContainsBuffFromCertainSource; // 0xf8
	private static DelegateBridge __Hotfix0_ContainsStatusResistableBuff; // 0x100
	private static DelegateBridge __Hotfix0_ContainsResistableAbnormalFlagsBuff; // 0x108
	private static DelegateBridge __Hotfix0_ContainsIrresistibleAbnormalFlagsBuff; // 0x110
	private static DelegateBridge __Hotfix0_TryGetFirstBuffStackCount; // 0x118
	private static DelegateBridge __Hotfix0_TryGetFirstBuffStackCountFromCertainSource; // 0x120
	private static DelegateBridge __Hotfix0_TryGetFirstBuffValidStackCount; // 0x128
	private static DelegateBridge __Hotfix0_GetOverridableBuffStackCount; // 0x130
	private static DelegateBridge __Hotfix0_TryGetBuffCountByKeyFromAllBuffs; // 0x138
	private static DelegateBridge __Hotfix0_TryGetBuffCountByKeyFromAllBuffsWithCertainSource; // 0x140
	private static DelegateBridge __Hotfix0_TryGetBuffCountByBlackboardFromAll; // 0x148
	private static DelegateBridge __Hotfix0_TryGetBuffBlackboardValueByBlackboardFromAll; // 0x150
	private static DelegateBridge __Hotfix0_Tick; // 0x158
	private static DelegateBridge __Hotfix0_Clear; // 0x160
	private static DelegateBridge __Hotfix0_ClearWithWhiteList; // 0x168
	private static DelegateBridge __Hotfix0__ClearBuffOverrideMapWithWhiteList; // 0x170
	private static DelegateBridge __Hotfix0__ClearBuffUidMapWithWhiteList; // 0x178
	private static DelegateBridge __Hotfix0__CheckFinishedBuffs; // 0x180
	private static DelegateBridge __Hotfix0__CheckBuffsActionValid; // 0x188
	private static DelegateBridge __Hotfix0__CheckThroughBuffAbnormalAnti; // 0x190
	private static DelegateBridge __Hotfix0__CheckThroughBuffStatusResistableAnti; // 0x198
	private static DelegateBridge __Hotfix0__CheckThroughLevitateBuffCondition; // 0x1a0
	private static DelegateBridge __Hotfix0__FilterBuffAbnormalAnti; // 0x1a8
	private static DelegateBridge __Hotfix0__FinishAndRemoveBuff; // 0x1b0
	private static DelegateBridge __Hotfix0__FinishBuff; // 0x1b8
	private static DelegateBridge __Hotfix0_OnOwnerBorn; // 0x1c0
	private static DelegateBridge __Hotfix0_OnOwnerPostBorn; // 0x1c8
	private static DelegateBridge __Hotfix0_OnOwnerLocate; // 0x1d0
	private static DelegateBridge __Hotfix0_OnOwnerFinish; // 0x1d8
	private static DelegateBridge __Hotfix0_OnOwnerDying; // 0x1e0
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x1e8
	private static DelegateBridge __Hotfix0_OnBeforeApplyingModifier; // 0x1f0
	private static DelegateBridge __Hotfix0_OnApplyingModifier; // 0x1f8
	private static DelegateBridge __Hotfix0_OnAppliedModifier; // 0x200
	private static DelegateBridge __Hotfix0_OnApplyingSkippedModifier; // 0x208
	private static DelegateBridge __Hotfix0_OnOutputModifier; // 0x210
	private static DelegateBridge __Hotfix0_OnBeforeTargetApplyModifier; // 0x218
	private static DelegateBridge __Hotfix0_OnAfterOutputDamage; // 0x220
	private static DelegateBridge __Hotfix0_OnEvadeDamage; // 0x228
	private static DelegateBridge __Hotfix0_OnBlockDamage; // 0x230
	private static DelegateBridge __Hotfix0_OnTakeDamage; // 0x238
	private static DelegateBridge __Hotfix0_OnTakeEPDamage; // 0x240
	private static DelegateBridge __Hotfix0_OnEPBreakStart; // 0x248
	private static DelegateBridge __Hotfix0_OnBeforeEPBreakStart; // 0x250
	private static DelegateBridge __Hotfix0_OnEPBreakFinish; // 0x258
	private static DelegateBridge __Hotfix0_OnBeforeEPBreakFinish; // 0x260
	private static DelegateBridge __Hotfix0_OnOutputDamage; // 0x268
	private static DelegateBridge __Hotfix0_OnOutputAtkOrHeal; // 0x270
	private static DelegateBridge __Hotfix0_OnTargetKilled; // 0x278
	private static DelegateBridge __Hotfix0_OnCalculateCachedProjectileDamage; // 0x280
	private static DelegateBridge __Hotfix0_OnCalculateDamage; // 0x288
	private static DelegateBridge __Hotfix0_OnAfterCalculateDamage; // 0x290
	private static DelegateBridge __Hotfix0_OnBeingCalculateDamage; // 0x298
	private static DelegateBridge __Hotfix0_OnAbilityStart; // 0x2a0
	private static DelegateBridge __Hotfix0_OnMakeEnemyUnbalanced; // 0x2a8
	private static DelegateBridge __Hotfix0_OnEnterLevitateState; // 0x2b0
	private static DelegateBridge __Hotfix0_OnBeforeExitLevitateState; // 0x2b8
	private static DelegateBridge __Hotfix0_OnEndPulling; // 0x2c0
	private static DelegateBridge __Hotfix0_OnBeforeFallDown; // 0x2c8
	private static DelegateBridge __Hotfix0_OnOwnerOverlapped; // 0x2d0
	private static DelegateBridge __Hotfix0_OnBossWaveWillStart; // 0x2d8
	private static DelegateBridge __Hotfix0_OnStageEnd; // 0x2e0
	private static DelegateBridge __Hotfix0_OnOtherBuffStart; // 0x2e8
	private static DelegateBridge __Hotfix0_OnOtherResistableBuffStart; // 0x2f0
	private static DelegateBridge __Hotfix0_OnAbilityFinish; // 0x2f8
	private static DelegateBridge __Hotfix0_OnAbilityInterrupted; // 0x300
	private static DelegateBridge __Hotfix0_OnAbilitySpellOn; // 0x308
	private static DelegateBridge __Hotfix0_OnAbilityCastOnTarget; // 0x310
	private static DelegateBridge __Hotfix0_OnSkillStart; // 0x318
	private static DelegateBridge __Hotfix0_OnToggleSkillStart; // 0x320
	private static DelegateBridge __Hotfix0_OnSkillCastSucceed; // 0x328
	private static DelegateBridge __Hotfix0_OnSkillFinish; // 0x330
	private static DelegateBridge __Hotfix0_OnBeforeAttack; // 0x338
	private static DelegateBridge __Hotfix0_OnAfterAttack; // 0x340
	private static DelegateBridge __Hotfix0_OnBeforeTrySetHpZero; // 0x348
	private static DelegateBridge __Hotfix0_OnBeforeTrySetEpZero; // 0x350
	private static DelegateBridge __Hotfix0_OnBeforeDisappear; // 0x358
	private static DelegateBridge __Hotfix0_OnBeforeAppear; // 0x360
	private static DelegateBridge __Hotfix0_OnOwnerAbnormalFlagDirty; // 0x368
	private static DelegateBridge __Hotfix0_OnOwnerBlockeeChanged; // 0x370
	private static DelegateBridge __Hotfix0_OnCollideWithHighLand; // 0x378
	private static DelegateBridge __Hotfix0_OnBeforeExitUnbalancedState; // 0x380
	private static DelegateBridge __Hotfix0_OnEnterUnbalancedState; // 0x388
	private static DelegateBridge __Hotfix0_OnEnterMagicCircuit; // 0x390
	private static DelegateBridge __Hotfix0_OnLeaveMagicCircuit; // 0x398
	private static DelegateBridge __Hotfix0_OnOwnerRootTileChanged; // 0x3a0
	private static DelegateBridge __Hotfix0_OnMotionModeChanged; // 0x3a8
	private static DelegateBridge __Hotfix0_OnDirectionChanged; // 0x3b0
	private static DelegateBridge __Hotfix0_OnBeforeDirectionChange; // 0x3b8
	private static DelegateBridge __Hotfix0_OnEsOverZero; // 0x3c0
	private static DelegateBridge __Hotfix0_OnLegionModeDrawCard; // 0x3c8
	private static DelegateBridge __Hotfix0_OnLegionModeRefreshCard; // 0x3d0
	private static DelegateBridge __Hotfix0_OnSandboxOwnerResChanged; // 0x3d8
	private static DelegateBridge __Hotfix0_OnEntityWillOverlap; // 0x3e0
	private static DelegateBridge __Hotfix0_OnOwnerBeforeDead; // 0x3e8
	private static DelegateBridge __Hotfix0_OnUnitSwitchMode; // 0x3f0
	private static DelegateBridge __Hotfix0_CooperatePlayerDying; // 0x3f8
	private static DelegateBridge __Hotfix0_CooperatePlayerRevive; // 0x400
	private static DelegateBridge __Hotfix0_CalculateShieldValue; // 0x408

	public Entity owner { get; set; }
	public Attributes attributes { get; }
	public Context context { get; }
	public Int32 buffCnt { get; }
	private ObjectPool`1 pool { get; }

	// RVA: 0x3f7476c VA: 0x759658c76c
	public Entity get_owner() { }
	// RVA: 0x3f80690 VA: 0x7596598690
	private Void set_owner(Entity value) { }
	// RVA: 0x3f80714 VA: 0x7596598714
	public Attributes get_attributes() { }
	// RVA: 0x3f74974 VA: 0x759658c974
	public Context get_context() { }
	// RVA: 0x3f8078c VA: 0x759659878c
	public Int32 get_buffCnt() { }
	// RVA: 0x3f80814 VA: 0x7596598814
	private ObjectPool`1 get_pool() { }
	// RVA: 0x3f808a0 VA: 0x75965988a0
	public static Buff CreateBuff() { }
	// RVA: 0x3f8092c VA: 0x759659892c
	public Void .ctor(Entity owner) { }
	// RVA: 0x3f80a98 VA: 0x7596598a98
	public Buff NewBuff(BuffConfig input, Entity source, Ability ability, Blackboard extraBlackboard, Blackboard extraBlackboard2, Projectile sourceProjectile) { }
	// RVA: 0x3f81a14 VA: 0x7596599a14
	public Boolean RemoveBuff(UInt32 instanceUid) { }
	// RVA: 0x3f81ae0 VA: 0x7596599ae0
	public Void RemoveBuffs(IList`1 instanceUids) { }
	// RVA: 0x3f81c5c VA: 0x7596599c5c
	public Void RemoveBuffs(String buffKey) { }
	// RVA: 0x3f81f90 VA: 0x7596599f90
	public Void RemoveOneBuffByKey(String buffKey, Boolean checkBuffFinished) { }
	// RVA: 0x3f822e4 VA: 0x759659a2e4
	public Void RemoveBuffsByBuffSource(Entity entity, String buffKey, Boolean alsoClearNullSource) { }
	// RVA: 0x3f826d8 VA: 0x759659a6d8
	public ReusableList`1 CollectBuffSourceByBuffKey_DISPOSE(String buffkey) { }
	// RVA: 0x3f82b1c VA: 0x759659ab1c
	public Void RemoveAllStatusResistableBuffs() { }
	// RVA: 0x3f82e14 VA: 0x759659ae14
	public Void RemoveAllBuffsWithCertainAbnormalFlag(AbnormalFlag abnormalFlag) { }
	// RVA: 0x3f83170 VA: 0x759659b170
	public Void ForceRefreshFinishedBuffs() { }
	// RVA: 0x3f831d8 VA: 0x759659b1d8
	public Void ResetAllBuffsTriggerTimer() { }
	// RVA: 0x3f834c4 VA: 0x759659b4c4
	public Void DecStackCntBuffsOrMarkFinish(String buffKey, Boolean updateOverrideMap) { }
	// RVA: 0x3f8380c VA: 0x759659b80c
	public Buff GetBuffByUid(UInt32 instanceUid) { }
	// RVA: 0x3f83938 VA: 0x759659b938
	public Buff GetFirstBuffByKey(String buffKey) { }
	// RVA: 0x3f83c94 VA: 0x759659bc94
	public Buff GetFirstBuffByKeyAndSource(String buffKey, Entity source) { }
	// RVA: 0x3f84058 VA: 0x759659c058
	public Boolean CheckTriggerableBuffByKeys(String[] buffKeys, Buff excludedBuff) { }
	// RVA: 0x3f843f8 VA: 0x759659c3f8
	public Boolean TriggerBuffByKeys(String[] buffKeys, Buff excludedBuff, Boolean force) { }
	// RVA: 0x3f84780 VA: 0x759659c780
	public Boolean TriggerAllBuffsByKeys(String[] buffKeys, Buff excludedBuff, Boolean force) { }
	// RVA: 0x3f84b04 VA: 0x759659cb04
	public Boolean TryGetOverrideGroup(String overrideKey, out OverrideGroup group) { }
	// RVA: 0x3f77d6c VA: 0x759658fd6c
	public String GetOverrideKeyCandidate(String independentKey) { }
	// RVA: 0x3f77f48 VA: 0x759658ff48
	public Void EnsureOverrideIndependentKey(String independentKey, String overrideKey) { }
	// RVA: 0x3f7f370 VA: 0x7596597370
	public Boolean TryGetOverrideGroup(Buff buff, out OverrideGroup group) { }
	// RVA: 0x3f84bb0 VA: 0x759659cbb0
	public Boolean ContainsBuff(String buffKey) { }
	// RVA: 0x3f84f18 VA: 0x759659cf18
	public Boolean ContainsBuffFromCertainSource(String buffKey, Entity source) { }
	// RVA: 0x3f852e0 VA: 0x759659d2e0
	public Boolean ContainsStatusResistableBuff() { }
	// RVA: 0x3f85600 VA: 0x759659d600
	public Boolean ContainsResistableAbnormalFlagsBuff() { }
	// RVA: 0x3f859cc VA: 0x759659d9cc
	public Boolean ContainsIrresistibleAbnormalFlagsBuff() { }
	// RVA: 0x3f85db4 VA: 0x759659ddb4
	public Boolean TryGetFirstBuffStackCount(String buffKey, out Int32 stackCnt) { }
	// RVA: 0x3f86148 VA: 0x759659e148
	public Boolean TryGetFirstBuffStackCountFromCertainSource(String buffKey, Entity source, out Int32 stackCnt) { }
	// RVA: 0x3f8653c VA: 0x759659e53c
	public Boolean TryGetFirstBuffValidStackCount(String buffKey, out Int32 validStackCnt) { }
	// RVA: 0x3f7614c VA: 0x759658e14c
	public Int32 GetOverridableBuffStackCount(String overrideKey) { }
	// RVA: 0x3f86948 VA: 0x759659e948
	public Boolean TryGetBuffCountByKeyFromAllBuffs(String buffKey, out Int32 count) { }
	// RVA: 0x3f86cc8 VA: 0x759659ecc8
	public Boolean TryGetBuffCountByKeyFromAllBuffsWithCertainSource(String buffKey, Entity source, out Int32 count) { }
	// RVA: 0x3f870a8 VA: 0x759659f0a8
	public Boolean TryGetBuffCountByBlackboardFromAll(String buffKey, String blackboardKey, Int32 blackboardValue, out Int32 count) { }
	// RVA: 0x3f874b8 VA: 0x759659f4b8
	public Boolean TryGetBuffBlackboardValueByBlackboardFromAll(String buffKey, String blackboardKey, Int32 blackboardValue, String resultBlackboardKey, out Int32 result) { }
	// RVA: 0x3f87910 VA: 0x759659f910
	public Void Tick(FP deltaTime) { }
	// RVA: 0x3f87e94 VA: 0x759659fe94
	public Void Clear(Boolean immediatelyFinishEffect) { }
	// RVA: 0x3f88638 VA: 0x75965a0638
	public Void ClearWithWhiteList(List`1 inPutWhiteList, Boolean alsoRemoveDurableBuff) { }
	// RVA: 0x3f89328 VA: 0x75965a1328
	private Void _ClearBuffOverrideMapWithWhiteList(List`1 whiteList) { }
	// RVA: 0x3f8970c VA: 0x75965a170c
	private Void _ClearBuffUidMapWithWhiteList(List`1 whiteList) { }
	// RVA: 0x3f80dd4 VA: 0x7596598dd4
	private Void _CheckFinishedBuffs() { }
	// RVA: 0x3f89ae4 VA: 0x75965a1ae4
	private Boolean _CheckBuffsActionValid(Event ev) { }
	// RVA: 0x3f811b8 VA: 0x75965991b8
	private Boolean _CheckThroughBuffAbnormalAnti(BuffData data) { }
	// RVA: 0x3f81564 VA: 0x7596599564
	private Boolean _CheckThroughBuffStatusResistableAnti(Buff buff) { }
	// RVA: 0x3f813a8 VA: 0x75965993a8
	private Boolean _CheckThroughLevitateBuffCondition(BuffData data) { }
	// RVA: 0x3f81618 VA: 0x7596599618
	private Void _FilterBuffAbnormalAnti(Int64 antiMask) { }
	// RVA: 0x3f8193c VA: 0x759659993c
	private Void _FinishAndRemoveBuff(Buff buff) { }
	// RVA: 0x3f884c8 VA: 0x75965a04c8
	private Void _FinishBuff(Buff buff, Boolean updateOverrideMap, Boolean delayToRecycle, Boolean immediatelyFinishEffect) { }
	// RVA: 0x3f89e34 VA: 0x75965a1e34
	public Void OnOwnerBorn() { }
	// RVA: 0x3f8a160 VA: 0x75965a2160
	public Void OnOwnerPostBorn() { }
	// RVA: 0x3f8a474 VA: 0x75965a2474
	public Void OnOwnerLocate() { }
	// RVA: 0x3f8a7a0 VA: 0x75965a27a0
	public Void OnOwnerFinish(FinishReason reason, Entity source) { }
	// RVA: 0x3f8aad4 VA: 0x75965a2ad4
	public Void OnOwnerDying() { }
	// RVA: 0x3f8ade8 VA: 0x75965a2de8
	public Void OnGameOver() { }
	// RVA: 0x3f8b0fc VA: 0x75965a30fc
	public Void OnBeforeApplyingModifier(ref Modifier modifier) { }
	// RVA: 0x3f8b5cc VA: 0x75965a35cc
	public Void OnApplyingModifier(ref Modifier modifier) { }
	// RVA: 0x3f8ba9c VA: 0x75965a3a9c
	public Void OnAppliedModifier(ref Modifier modifier) { }
	// RVA: 0x3f8bf6c VA: 0x75965a3f6c
	public Void OnApplyingSkippedModifier(ref Modifier modifier) { }
	// RVA: 0x3f8c44c VA: 0x75965a444c
	public Void OnOutputModifier(ref Modifier modifier) { }
	// RVA: 0x3f8c91c VA: 0x75965a491c
	public Void OnBeforeTargetApplyModifier(ref Modifier modifier) { }
	// RVA: 0x3f8cdfc VA: 0x75965a4dfc
	public Void OnAfterOutputDamage(ref Modifier modifier) { }
	// RVA: 0x3f8d2cc VA: 0x75965a52cc
	public Void OnEvadeDamage(ref Modifier modifier) { }
	// RVA: 0x3f8d79c VA: 0x75965a579c
	public Void OnBlockDamage(ref Modifier modifier) { }
	// RVA: 0x3f8dc7c VA: 0x75965a5c7c
	public Void OnTakeDamage(ref Modifier modifier) { }
	// RVA: 0x3f8e14c VA: 0x75965a614c
	public Void OnTakeEPDamage(ref Modifier modifier) { }
	// RVA: 0x3f8e62c VA: 0x75965a662c
	public Void OnEPBreakStart() { }
	// RVA: 0x3f8e968 VA: 0x75965a6968
	public Void OnBeforeEPBreakStart() { }
	// RVA: 0x3f8eca4 VA: 0x75965a6ca4
	public Void OnEPBreakFinish() { }
	// RVA: 0x3f8efe0 VA: 0x75965a6fe0
	public Void OnBeforeEPBreakFinish() { }
	// RVA: 0x3f8f31c VA: 0x75965a731c
	public Void OnOutputDamage(ref Modifier modifier) { }
	// RVA: 0x3f8f7ec VA: 0x75965a77ec
	public Void OnOutputAtkOrHeal(Ability ability) { }
	// RVA: 0x3f8fb84 VA: 0x75965a7b84
	public Void OnTargetKilled(Entity target) { }
	// RVA: 0x3f8ff28 VA: 0x75965a7f28
	public Void OnCalculateCachedProjectileDamage(Entity target, ref AttackInfo atkInfo) { }
	// RVA: 0x3f903fc VA: 0x75965a83fc
	public Void OnCalculateDamage(Entity target, ref AttackInfo atkInfo) { }
	// RVA: 0x3f908d0 VA: 0x75965a88d0
	public Void OnAfterCalculateDamage(Entity target) { }
	// RVA: 0x3f90d6c VA: 0x75965a8d6c
	public Void OnBeingCalculateDamage(ref AttackInfo atkInfo) { }
	// RVA: 0x3f91244 VA: 0x75965a9244
	public Void OnAbilityStart(Ability ability) { }
	// RVA: 0x3f915dc VA: 0x75965a95dc
	public Void OnMakeEnemyUnbalanced(Entity target) { }
	// RVA: 0x3f91984 VA: 0x75965a9984
	public Void OnEnterLevitateState() { }
	// RVA: 0x3f91cc0 VA: 0x75965a9cc0
	public Void OnBeforeExitLevitateState() { }
	// RVA: 0x3f91ffc VA: 0x75965a9ffc
	public Void OnEndPulling(Entity target) { }
	// RVA: 0x3f923a4 VA: 0x75965aa3a4
	public Void OnBeforeFallDown() { }
	// RVA: 0x3f926e0 VA: 0x75965aa6e0
	public Void OnOwnerOverlapped(Entity source) { }
	// RVA: 0x3f92a88 VA: 0x75965aaa88
	public Void OnBossWaveWillStart() { }
	// RVA: 0x3f92dc4 VA: 0x75965aadc4
	public Void OnStageEnd() { }
	// RVA: 0x3f93100 VA: 0x75965ab100
	public Void OnOtherBuffStart(Buff otherBuff) { }
	// RVA: 0x3f934c8 VA: 0x75965ab4c8
	public Void OnOtherResistableBuffStart(Buff otherBuff) { }
	// RVA: 0x3f938b8 VA: 0x75965ab8b8
	public Void OnAbilityFinish(Ability ability) { }
	// RVA: 0x3f93c50 VA: 0x75965abc50
	public Void OnAbilityInterrupted(Ability ability) { }
	// RVA: 0x3f93ff8 VA: 0x75965abff8
	public Void OnAbilitySpellOn(Ability ability) { }
	// RVA: 0x3f94390 VA: 0x75965ac390
	public Void OnAbilityCastOnTarget(Ability ability, Entity target) { }
	// RVA: 0x3f94794 VA: 0x75965ac794
	public Void OnSkillStart(BasicSkill skill) { }
	// RVA: 0x3f94b40 VA: 0x75965acb40
	public Void OnToggleSkillStart(BasicSkill skill) { }
	// RVA: 0x3f94eec VA: 0x75965aceec
	public Void OnSkillCastSucceed(BasicSkill skill) { }
	// RVA: 0x3f952a8 VA: 0x75965ad2a8
	public Void OnSkillFinish(BasicSkill skill) { }
	// RVA: 0x3f95654 VA: 0x75965ad654
	public Void OnBeforeAttack() { }
	// RVA: 0x3f95980 VA: 0x75965ad980
	public Void OnAfterAttack() { }
	// RVA: 0x3f95cac VA: 0x75965adcac
	public Void OnBeforeTrySetHpZero() { }
	// RVA: 0x3f95fd8 VA: 0x75965adfd8
	public Void OnBeforeTrySetEpZero() { }
	// RVA: 0x3f962f4 VA: 0x75965ae2f4
	public Void OnBeforeDisappear() { }
	// RVA: 0x3f96620 VA: 0x75965ae620
	public Void OnBeforeAppear() { }
	// RVA: 0x3f9695c VA: 0x75965ae95c
	public Void OnOwnerAbnormalFlagDirty() { }
	// RVA: 0x3f96c88 VA: 0x75965aec88
	public Void OnOwnerBlockeeChanged() { }
	// RVA: 0x3f96fb4 VA: 0x75965aefb4
	public Void OnCollideWithHighLand() { }
	// RVA: 0x3f972e0 VA: 0x75965af2e0
	public Void OnBeforeExitUnbalancedState() { }
	// RVA: 0x3f9760c VA: 0x75965af60c
	public Void OnEnterUnbalancedState() { }
	// RVA: 0x3f97948 VA: 0x75965af948
	public Void OnEnterMagicCircuit() { }
	// RVA: 0x3f97c74 VA: 0x75965afc74
	public Void OnLeaveMagicCircuit() { }
	// RVA: 0x3f97fa0 VA: 0x75965affa0
	public Void OnOwnerRootTileChanged(Tile newTile) { }
	// RVA: 0x3f98348 VA: 0x75965b0348
	public Void OnMotionModeChanged() { }
	// RVA: 0x3f98684 VA: 0x75965b0684
	public Void OnDirectionChanged() { }
	// RVA: 0x3f989c0 VA: 0x75965b09c0
	public Void OnBeforeDirectionChange() { }
	// RVA: 0x3f98cfc VA: 0x75965b0cfc
	public Void OnEsOverZero() { }
	// RVA: 0x3f99018 VA: 0x75965b1018
	public Void OnLegionModeDrawCard() { }
	// RVA: 0x3f99354 VA: 0x75965b1354
	public Void OnLegionModeRefreshCard() { }
	// RVA: 0x3f99690 VA: 0x75965b1690
	public Void OnSandboxOwnerResChanged() { }
	// RVA: 0x3f999ac VA: 0x75965b19ac
	public Void OnEntityWillOverlap(Entity entity, Direction direction) { }
	// RVA: 0x3f99db0 VA: 0x75965b1db0
	public Void OnOwnerBeforeDead() { }
	// RVA: 0x3f9a0ac VA: 0x75965b20ac
	public Void OnUnitSwitchMode() { }
	// RVA: 0x3f9a3e8 VA: 0x75965b23e8
	public Void CooperatePlayerDying() { }
	// RVA: 0x3f9a724 VA: 0x75965b2724
	public Void CooperatePlayerRevive() { }
	// RVA: 0x3f9aa60 VA: 0x75965b2a60
	public FP CalculateShieldValue() { }
}
```