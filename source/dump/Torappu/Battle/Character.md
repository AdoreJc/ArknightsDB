# Character

**Namespace:** `Torappu.Battle`


## Fields

- `Transform _skinHolder`

- `MotionMode _motionMode`

- `MotionMode _blockMode`

- `Boolean _isFixedRotation`

- `Boolean _occupiedRemainingCharacterCnt`

- `Boolean _useRealBornTimeFromAnim`

- `BuildCondition _buildCondition`

- `Ability _traitAbility`

- `Single _withdrawCostRecoverRatio`

- `Single _maxWithdrawCostRatioOfRawCost`

- `Transform _directionTransform`

- `Transform _directionIndicator`

- `String _startEffect`

- `String _deadEffect`

- `Boolean _playStartVocal`

- `Boolean _showDeadTweenColor`

- `Boolean _useSpecificDeadAnim`

- `Boolean _onlyPlayStartEffectOnce`

- `Boolean _dontMoveCameraWhenFocus`

- `Boolean _disableCharInfoPanel`

- `Boolean _disableRotateWhenDead`

- `Boolean _clearProjectileWhenDead`

- `UseIdForAudioSignalMask _useIdForAudioSignalMask`

- `Boolean _preprocessData`

- `Boolean _disableClickCharacterInfo`

- `Boolean m_isBuiltPredefined`

- `Boolean m_dontOccupyDeployCnt`

- `AdvancedBuildableMask m_additionalBuildableMask`

- `String m_defaultRangeId`

- `Int32 m_defaultModeIndex`

- `FP m_hatred`

- `FP m_createdTime`

- `FP m_deadTime`

- `String m_talentRange`

- `Tile m_rootTile`

- `BlockedEnemyManager m_blockedEnemyMgr`

- `PeriodicTicker m_findBlockeeTicker`

- `PeriodicTimer m_snapshotTimer`

- `IReplacement m_replacement`

- `BasicSkill m_skill`

- `SkillData m_skillData`

- `RebornData m_rebornData`

- `FP m_maxEsRatio`

- `UnitAnimator m_currentSkin`

- `Single m_delayToRecycle`

- `UnitDataFlowConfig m_dataFlowConfig`

- `BuildCondition m_buildCondition`

- `AdditionalBuildCondition m_additionalBuildCondition`

- `Ability m_traitAbility`

- `Single m_withdrawCostRecoverRatio`

- `Boolean m_limitMaxWithdrawCostByDeployUse`

- `Int32 m_deployCostThisTime`

- `Int32 m_originRemainingChrCntVolume`

- `Boolean m_externWithdrawGainCostFlag`

- `UInt32 <cardUid>k__BackingField`

- `MotionMode m_blockMode`

- `BattleCharacterData <data>k__BackingField`

- `Collider2D m_mainTriggerCollider`

- `FP m_mainTriggerColliderRadius`


## Properties

- `Transform skinHolder`

- `Boolean disableClickCharacterInfo`

- `Int32 defaultModeIndex`

- `UInt32 cardUid`

- `UInt32 tokenOrHostUid`

- `String characterId`

- `Boolean playStartVocal`

- `FP maxEsRatio`

- `BuildCondition originBuildCondition`

- `BuildCondition buildCondition`

- `BuildableType additionalBuildType`

- `AdvancedBuildableMask addtionalMask`

- `Ability rawAttackWithoutReplacement`

- `Ability rawCombatWithoutReplacement`

- `BasicSkill skill`

- `SkillData skillData`

- `Boolean hasSkill`

- `Ability traitAbility`

- `Boolean dontMoveCameraWhenFocus`

- `Boolean disableCharInfoPanel`

- `Ability traitOrTraitAsTalentAbility`

- `Boolean traitAsTalent`

- `Boolean isToken`

- `Boolean originOccupiedRemainingCharacterCnt`

- `Boolean overflowOccupiedCnt`

- `Boolean manuallyWithdrawable`

- `Boolean isBuiltPredefined`

- `Boolean isPlayerCharacter`

- `Int32 blockedTotalVolumn`

- `Transform directionIndicator`

- `Blackboard traitBlackboard`

- `MotionMode blockMode`

- `BattleCharacterData data`

- `SharedData sharedData`

- `FP deadTime`

- `Boolean hasReplacement`

- `Boolean isInIdletState`

- `Boolean canBeReplace`


## Methods

- `Transform get_skinHolder()`

- `Boolean get_disableClickCharacterInfo()`

- `Int32 get_defaultModeIndex()`

- `UInt32 get_cardUid()`

- `Void set_cardUid(UInt32)`

- `UInt32 get_tokenOrHostUid()`

- `String get_characterId()`

- `Boolean get_playStartVocal()`

- `FP get_maxEsRatio()`

- `BuildCondition get_originBuildCondition()`

- `BuildCondition get_buildCondition()`

- `BuildableType get_additionalBuildType()`

- `AdvancedBuildableMask get_addtionalMask()`

- `Ability get_rawAttackWithoutReplacement()`

- `Ability get_rawCombatWithoutReplacement()`

- `BasicSkill get_skill()`

- `SkillData get_skillData()`

- `Boolean get_hasSkill()`

- `Ability get_traitAbility()`

- `Boolean get_dontMoveCameraWhenFocus()`

- `Boolean get_disableCharInfoPanel()`

- `Ability get_traitOrTraitAsTalentAbility()`

- `Boolean get_traitAsTalent()`

- `Boolean get_isToken()`

- `Boolean get_originOccupiedRemainingCharacterCnt()`

- `Boolean get_overflowOccupiedCnt()`

- `Boolean get_manuallyWithdrawable()`

- `Boolean IsControllable(PlayerSide)`

- `Boolean get_isBuiltPredefined()`

- `Boolean get_isPlayerCharacter()`

- `Int32 get_blockedTotalVolumn()`

- `Transform get_directionIndicator()`

- `Blackboard get_traitBlackboard()`

- `VoiceQuery GetVoiceQuery()`

- `MotionMode get_blockMode()`

- `Void SetExternWithdrawGainCostFlag(Boolean)`

- `BattleCharacterData get_data()`

- `Void set_data(BattleCharacterData)`

- `SharedData get_sharedData()`

- `FP get_deadTime()`

- `Boolean get_hasReplacement()`

- `Boolean get_isInIdletState()`

- `Boolean get_canBeReplace()`

- `Void PlayBornAnimationAndEffect(ref, Action, Boolean)`

- `Void StopBornAnimationAndEffect(String)`

- `Void _PlayUniEquipEffect(Single)`

- `Void BuildAt(Card, Tile, Direction)`

- `Void BuildAsPredefined(BattleCharacterData, Tile, Direction)`

- `Void BuildAsRuntimeInst(BattleCharacterData, Tile, Direction, SideType, PlayerSide)`

- `Void MakeDummy(BattleCharacterData, Direction, AdditionalBuildCondition, PlayerSide)`

- `Boolean OpTrigSkill(PlayerSide)`

- `Boolean RemoteTrigSkill()`

- `Boolean SwitchToAttackState()`

- `Void SwitchToSkillState()`

- `Void SwitchOutFromSkillState()`

- `Boolean CheckIsBornState()`

- `Boolean CheckBuildable(Tile, Direction, Boolean, Boolean)`

- `Boolean CheckRespawnSelfBuildable(Tile, Direction, Boolean, Boolean)`

- `Boolean RechargeToken(Int32, RechargeTiming, Boolean)`

- `Boolean TryGetAtkAsHostBased(out)`

- `Void ResetSearchBlockeeTicker()`

- `Void SearchBlockeeImmediate()`

- `Void FetchTokenOrHost(Int32, List`1, Func`2)`

- `String GetCurrentModeRangeId()`

- `IDrawableRange GetRangeOfSkill()`

- `String _GetCharacterSignal(String)`

- `Boolean CheckUseIdForAudioSignal(String)`

- `Void ChangeBlockMode(MotionMode)`

- `Void ResetBlockMode()`

- `Void ForceDying()`

- `Void RespawnSelf(Tile, Direction, Boolean, PlayerSide, Boolean)`

- `Boolean MoveLikeRespawnSelf(Tile, Direction, Boolean, PlayerSide, Boolean)`

- `Boolean MoveLikeRespawnSelf(Tile, Direction, out, Boolean, PlayerSide, Boolean)`

- `Character RespawnSelfAsPredefined(String, Tile, Direction)`

- `Single GetDelayToRecycleTime()`

- `Void FinishWithReplace(Character)`

- `Void _ClearAbilityProjectilesIfNeeded()`

- `Void _BuildAtInternal(BuildParam)`

- `Void _InitAllModeDirection()`

- `Void LogSnapshotIfNot()`

- `Void SetAdditionalBuildCondition(BuildableType, AdvancedBuildableMask)`

- `Void AddOverlapSourceId(String)`

- `Void RemoveOverlapSourceId(String)`

- `Void RegisterReplacement(IReplacement)`

- `Void UnregisterReplacement(IReplacement)`

- `Boolean CheckIsCurrentReplacement(IReplacement)`

- `Void ClearReplacement()`

- `String GetStartEffect()`

- `String GetDeadEffect()`

- `Boolean _CheckCanSwithToAttackState()`

- `Boolean _SearchAttackTarget()`

- `Enemy _FetchCombatTarget()`

- `Void TryFaceToIdleDirection()`

- `Void _SearchBlockee(Boolean)`

- `Boolean _CheckBlockable(Entity, Entity, out, out)`

- `Boolean CheckBlockVolumeNotExceeded(Enemy)`

- `Void _ClearAllBlockees()`

- `Void _AddBlockee(Enemy)`

- `Void RemoveBlockee(Enemy)`

- `Void RecalculateBlockeesTotalVolume()`

- `Void UpdateBlockees()`

- `Void SetupSkin(UnitAnimator, String)`

- `Void RecycleSkinIfNot()`

- `Void _SpawnDeckBuffs()`

- `Boolean CheckModeChangeBeforeAttack(Int32)`

- `Boolean OnBeforeAttack(Ability, Boolean)`

- `Void OnAfterAttack(Ability, Boolean, FinishReason)`

- `Boolean OnBeforeSkill(BasicSkill)`

- `Void OnAfterSkill(BasicSkill, FinishReason)`

- `Void OnSkillStart()`

- `Void OnToggleSkillStart()`

- `Void OnSkillCastSucceed()`

- `Void OnSkillFinish()`

- `Void UpdateHatred()`

- `Void UpdateHatred(Single)`

- `Void EnsureSkillOnInAbnormalState()`

- `Void _AssignData(BattleCharacterData, SideType, PlayerSide)`

- `Void _PreprocessSkill(SkillData)`

- `Void _RecycleEquipIfNot()`

- `Void _AssignSkill(SkillData, Blackboard, Dictionary`2)`

- `Void _PreprocessSkin(CharSkinData)`

- `Void _PreprocessEquip()`

- `Void _PreprocessTalents(IList`1, TalentData, out, out)`

- `Void _AssignTalents(Dictionary`2)`

- `Void _AssignTrait(TraitData)`

- `Void _PreprocessTrait(TraitData, out)`

- `Void _EquipProcessTalents()`

- `Void _EquipProcessTrait()`

- `Int32 _GetDefaultModeIndex(Dictionary`2)`

- `String _GetDefaultRangeId(Dictionary`2)`

- `Void OnEquipProcessed(String, GameObject)`

- `TargetSelector GetCurrentModeSelector()`

- `Ability GetSpecialModeAttack(Int32)`

- `Void OnRallyPointLikeReborn()`

- `Void _ReactivateMainTriggerCollider()`

- `Void SetDontOccupyDeployCntFlag(Boolean)`

- `Void SetDisableClickCharacterInfo(Boolean, DisableClickCharacterInfoReasonMask)`

- `Void SetWithdrawCostRecoverRatio(Single, Boolean, Boolean)`

- `Void UpdateMaxEs(FP)`

- `Void OnEntityWillOverlap(Entity, Direction)`

- `Transform <>xLuaBaseProxy_get_graphicHolderTransform()`

- `Boolean <>xLuaBaseProxy_get_alive()`

- `Boolean <>xLuaBaseProxy_get_aliveOrDying()`

- `UnitMode <>xLuaBaseProxy_get_defaultMode()`

- `UnitAnimator <>xLuaBaseProxy_get_animator()`

- `FP <>xLuaBaseProxy_get_maxEs()`

- `String <>xLuaBaseProxy_get_talentRange()`

- `Ability <>xLuaBaseProxy_get_attack()`

- `Ability <>xLuaBaseProxy_get_combat()`

- `Boolean <>xLuaBaseProxy_get_hasCombat()`

- `TargetTrigger <>xLuaBaseProxy_get_attackTrigger()`

- `IDrawableRange <>xLuaBaseProxy_get_rangeToShow()`

- `String <>xLuaBaseProxy_get_defaultRangeId()`

- `Boolean <>xLuaBaseProxy_get_isMine()`

- `Transform <>xLuaBaseProxy_get_directionTransform()`

- `Int32 <>xLuaBaseProxy_get_initState()`

- `Single <>xLuaBaseProxy_get_delayToRecycle()`

- `Void <>xLuaBaseProxy_Born()`

- `Entity <>xLuaBaseProxy_FetchHost()`

- `String <>xLuaBaseProxy_GetModeRangeId(UnitMode, RangeIdUsage)`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_ChangeMotionMode(MotionMode)`

- `Void <>xLuaBaseProxy_ResetMotionMode()`

- `Void <>xLuaBaseProxy_FinishMe(FinishReason)`

- `Void <>xLuaBaseProxy_DoFakeDeath(RebornData)`

- `Void <>xLuaBaseProxy_DoReborn(RebornData)`

- `Void <>xLuaBaseProxy_ClearAbilities()`

- `Boolean <>xLuaBaseProxy_TryHookEffect(String, out)`

- `Boolean <>xLuaBaseProxy_TryHookAudio(String, String, out, out)`

- `Boolean <>xLuaBaseProxy_TryHookProjectile(String, out, out, out)`

- `Blackboard <>xLuaBaseProxy_GetAttackBlackboard(UnitMode)`

- `Boolean <>xLuaBaseProxy_isStillMotionTargetFreeWithImmuneFlag(AbnormalFlag, AbnormalCombo, MotionMode)`

- `Void <>xLuaBaseProxy_OnRecycle()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnAwake()`

- `Void <>xLuaBaseProxy_OnInit(Single)`

- `Void <>xLuaBaseProxy_OnBorn()`

- `Void <>xLuaBaseProxy_OnReborn(RebornData)`

- `Void <>xLuaBaseProxy_OnHpZero(Boolean, Boolean)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnLocate()`

- `Void <>xLuaBaseProxy_OnFinish(FinishReason)`

- `Void <>xLuaBaseProxy_OnAttributeDirty(AttributeType, FP)`

- `Void <>xLuaBaseProxy_OnDisappearChanged(Boolean)`

- `Void <>xLuaBaseProxy_PopulateSnapshotToHashBuilder(HashCodeBuilder)`

- `Void <>xLuaBaseProxy_PopulateSnapshotToStrBuilder(StringBuilder)`

- `AbstractBasicAttack <>xLuaBaseProxy_GetCurrentAttackOrCombatAbility()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Character : Unit, IBuildable, ILocatable
{
	private static readonly Vector2 LOG_SNAPSHOT_PERIOD_RANGE; // 0x0
	private const Int32 FIND_BLOCKEE_TICK; // 0x0
	private static readonly FP HATRED_VALUE_GAP; // 0x8
	private const Int32 DEFAULT_REMAINING_CHARACTER_CNT_VOLUME; // 0x0
	private Transform _skinHolder; // 0x250
	private MotionMode _motionMode; // 0x258
	private MotionMode _blockMode; // 0x25c
	private Boolean _isFixedRotation; // 0x260
	private Boolean _occupiedRemainingCharacterCnt; // 0x261
	private Boolean _useRealBornTimeFromAnim; // 0x262
	private BuildCondition _buildCondition; // 0x268
	private Ability _traitAbility; // 0x2b8
	private Single _withdrawCostRecoverRatio; // 0x2c0
	private Single _maxWithdrawCostRatioOfRawCost; // 0x2c4
	private Transform _directionTransform; // 0x2c8
	private Transform _directionIndicator; // 0x2d0
	protected String _startEffect; // 0x2d8
	protected String _deadEffect; // 0x2e0
	private Boolean _playStartVocal; // 0x2e8
	private Boolean _showDeadTweenColor; // 0x2e9
	private Boolean _useSpecificDeadAnim; // 0x2ea
	private Boolean _onlyPlayStartEffectOnce; // 0x2eb
	private Boolean _dontMoveCameraWhenFocus; // 0x2ec
	private Boolean _disableCharInfoPanel; // 0x2ed
	private Boolean _disableRotateWhenDead; // 0x2ee
	private Boolean _clearProjectileWhenDead; // 0x2ef
	private UseIdForAudioSignalMask _useIdForAudioSignalMask; // 0x2f0
	private Boolean _preprocessData; // 0x2f1
	private Boolean _disableClickCharacterInfo; // 0x2f2
	private Boolean m_isBuiltPredefined; // 0x2f3
	private Boolean m_dontOccupyDeployCnt; // 0x2f4
	private AdvancedBuildableMask m_additionalBuildableMask; // 0x2f8
	private String m_defaultRangeId; // 0x300
	private Int32 m_defaultModeIndex; // 0x308
	private FP m_hatred; // 0x310
	private FP m_createdTime; // 0x318
	private FP m_deadTime; // 0x320
	private String m_talentRange; // 0x328
	protected Tile m_rootTile; // 0x330
	private BlockedEnemyManager m_blockedEnemyMgr; // 0x338
	private PeriodicTicker m_findBlockeeTicker; // 0x340
	private PeriodicTimer m_snapshotTimer; // 0x348
	private IReplacement m_replacement; // 0x350
	private BasicSkill m_skill; // 0x358
	private SkillData m_skillData; // 0x360
	private RebornData m_rebornData; // 0x368
	private ObjectPtr`1 m_startEffect; // 0x3b0
	private FP m_maxEsRatio; // 0x3c0
	protected ListDict`2 m_effectOverrideMap; // 0x3c8
	private ListDict`2 m_equipObjects; // 0x3d0
	private UnitAnimator m_currentSkin; // 0x3d8
	private IList`1 m_deckBuffs; // 0x3e0
	private Single m_delayToRecycle; // 0x3e8
	private UnitDataFlowConfig m_dataFlowConfig; // 0x3f0
	private BuildCondition m_buildCondition; // 0x3f8
	private AdditionalBuildCondition m_additionalBuildCondition; // 0x448
	private Ability m_traitAbility; // 0x458
	private Single m_withdrawCostRecoverRatio; // 0x460
	private Boolean m_limitMaxWithdrawCostByDeployUse; // 0x464
	private Int32 m_deployCostThisTime; // 0x468
	private Int32 m_originRemainingChrCntVolume; // 0x46c
	private EnableStateWithKey`1 m_disableClickState; // 0x470
	private Boolean m_externWithdrawGainCostFlag; // 0x478
	private UInt32 <cardUid>k__BackingField; // 0x47c
	private MotionMode m_blockMode; // 0x480
	private BattleCharacterData <data>k__BackingField; // 0x488
	protected Collider2D m_mainTriggerCollider; // 0x490
	public FP m_mainTriggerColliderRadius; // 0x498
	private static DelegateBridge __Hotfix0_get_initSideType; // 0x10
	private static DelegateBridge __Hotfix0_get_skinHolder; // 0x18
	private static DelegateBridge __Hotfix0_get_graphicHolderTransform; // 0x20
	private static DelegateBridge __Hotfix0_get_alive; // 0x28
	private static DelegateBridge __Hotfix0_get_aliveOrDying; // 0x30
	private static DelegateBridge __Hotfix0_get_disableClickCharacterInfo; // 0x38
	private static DelegateBridge __Hotfix0_get_defaultMode; // 0x40
	private static DelegateBridge __Hotfix0_get_defaultModeIndex; // 0x48
	private static DelegateBridge __Hotfix0_get_cardUid; // 0x50
	private static DelegateBridge __Hotfix0_set_cardUid; // 0x58
	private static DelegateBridge __Hotfix0_get_tokenOrHostUid; // 0x60
	private static DelegateBridge __Hotfix0_get_characterId; // 0x68
	private static DelegateBridge __Hotfix0_get_playStartVocal; // 0x70
	private static DelegateBridge __Hotfix0_get_rootTile; // 0x78
	private static DelegateBridge __Hotfix0_get_oldTile; // 0x80
	private static DelegateBridge __Hotfix0_get_animator; // 0x88
	private static DelegateBridge __Hotfix0_get_isInCombat; // 0x90
	private static DelegateBridge __Hotfix0_get_hatred; // 0x98
	private static DelegateBridge __Hotfix0_get_maxEs; // 0xa0
	private static DelegateBridge __Hotfix0_get_maxEsRatio; // 0xa8
	private static DelegateBridge __Hotfix0_get_talentRange; // 0xb0
	private static DelegateBridge __Hotfix0_get_originBuildCondition; // 0xb8
	private static DelegateBridge __Hotfix0_get_buildCondition; // 0xc0
	private static DelegateBridge __Hotfix0_get_additionalBuildType; // 0xc8
	private static DelegateBridge __Hotfix0_get_addtionalMask; // 0xd0
	private static DelegateBridge __Hotfix0_get_attack; // 0xd8
	private static DelegateBridge __Hotfix0_get_rawAttackWithoutReplacement; // 0xe0
	private static DelegateBridge __Hotfix0_get_combat; // 0xe8
	private static DelegateBridge __Hotfix0_get_hasCombat; // 0xf0
	private static DelegateBridge __Hotfix0_get_rawCombatWithoutReplacement; // 0xf8
	private static DelegateBridge __Hotfix0_get_attackTrigger; // 0x100
	private static DelegateBridge __Hotfix0_get_skill; // 0x108
	private static DelegateBridge __Hotfix0_get_skillData; // 0x110
	private static DelegateBridge __Hotfix0_get_hideTileOption; // 0x118
	private static DelegateBridge __Hotfix0_get_hasSkill; // 0x120
	private static DelegateBridge __Hotfix0_get_traitAbility; // 0x128
	private static DelegateBridge __Hotfix0_get_dontMoveCameraWhenFocus; // 0x130
	private static DelegateBridge __Hotfix0_get_disableCharInfoPanel; // 0x138
	private static DelegateBridge __Hotfix0_get_traitOrTraitAsTalentAbility; // 0x140
	private static DelegateBridge __Hotfix0_get_traitAsTalent; // 0x148
	private static DelegateBridge __Hotfix0_get_rangeToShow; // 0x150
	private static DelegateBridge __Hotfix0_get_defaultRangeId; // 0x158
	private static DelegateBridge __Hotfix0_get_isToken; // 0x160
	private static DelegateBridge __Hotfix0_get_originOccupiedRemainingCharacterCnt; // 0x168
	private static DelegateBridge __Hotfix0_get_occupiedRemainingCharacterCnt; // 0x170
	private static DelegateBridge __Hotfix0_get_originRemainingCharacterCntVolume; // 0x178
	private static DelegateBridge __Hotfix0_set_originRemainingCharacterCntVolume; // 0x180
	private static DelegateBridge __Hotfix0_get_remainingCharacterCntVolume; // 0x188
	private static DelegateBridge __Hotfix0_get_overflowOccupiedCnt; // 0x190
	private static DelegateBridge __Hotfix0_get_withdrawable; // 0x198
	private static DelegateBridge __Hotfix0_get_manuallyWithdrawable; // 0x1a0
	private static DelegateBridge __Hotfix0_get_isMine; // 0x1a8
	private static DelegateBridge __Hotfix0_IsControllable; // 0x1b0
	private static DelegateBridge __Hotfix0_get_isBuiltPredefined; // 0x1b8
	private static DelegateBridge __Hotfix0_get_isPlayerCharacter; // 0x1c0
	private static DelegateBridge __Hotfix0_get_directionTransform; // 0x1c8
	private static DelegateBridge __Hotfix0_get_blockedEnemies; // 0x1d0
	private static DelegateBridge __Hotfix0_get_blockedTotalVolumn; // 0x1d8
	private static DelegateBridge __Hotfix0_get_directionIndicator; // 0x1e0
	private static DelegateBridge __Hotfix0_get_blockRadiusSquare; // 0x1e8
	private static DelegateBridge __Hotfix0_get_minBlockDistToTarget; // 0x1f0
	private static DelegateBridge __Hotfix0_get_traitBlackboard; // 0x1f8
	private static DelegateBridge __Hotfix0_GetVoiceQuery; // 0x200
	private static DelegateBridge __Hotfix0_get_blockMode; // 0x208
	private static DelegateBridge __Hotfix0_get_isFixedRotation; // 0x210
	private static DelegateBridge __Hotfix0_get_initState; // 0x218
	private static DelegateBridge __Hotfix0_get_delayToRecycle; // 0x220
	private static DelegateBridge __Hotfix0_get_allowWithdrawGainCost; // 0x228
	private static DelegateBridge __Hotfix0_SetExternWithdrawGainCostFlag; // 0x230
	private static DelegateBridge __Hotfix0_get_stateMachine; // 0x238
	private static DelegateBridge __Hotfix0_get_data; // 0x240
	private static DelegateBridge __Hotfix0_set_data; // 0x248
	private static DelegateBridge __Hotfix0_get_sharedData; // 0x250
	private static DelegateBridge __Hotfix0_get_managedProjectiles; // 0x258
	private static DelegateBridge __Hotfix0_get_createdTime; // 0x260
	private static DelegateBridge __Hotfix0_get_deadTime; // 0x268
	private static DelegateBridge __Hotfix0_get_startEffect; // 0x270
	private static DelegateBridge __Hotfix0_get_deadEffect; // 0x278
	private static DelegateBridge __Hotfix0_get_hasReplacement; // 0x280
	private static DelegateBridge __Hotfix0_get_isInAttackState; // 0x288
	private static DelegateBridge __Hotfix0_get_isInCombatState; // 0x290
	private static DelegateBridge __Hotfix0_get_isInRebornState; // 0x298
	private static DelegateBridge __Hotfix0_get_isInIdletState; // 0x2a0
	private static DelegateBridge __Hotfix0_get_isInDyingState; // 0x2a8
	private static DelegateBridge __Hotfix0_get_canBeReplace; // 0x2b0
	private static DelegateBridge __Hotfix0_PlayBornAnimationAndEffect; // 0x2b8
	private static DelegateBridge __Hotfix0_StopBornAnimationAndEffect; // 0x2c0
	private static DelegateBridge __Hotfix0__PlayUniEquipEffect; // 0x2c8
	private static DelegateBridge __Hotfix0_BuildAt; // 0x2d0
	private static DelegateBridge __Hotfix0_BuildAsPredefined; // 0x2d8
	private static DelegateBridge __Hotfix0_BuildAsRuntimeInst; // 0x2e0
	private static DelegateBridge __Hotfix0_Born; // 0x2e8
	private static DelegateBridge __Hotfix0_MakeDummy; // 0x2f0
	private static DelegateBridge __Hotfix0_OpTrigSkill; // 0x2f8
	private static DelegateBridge __Hotfix0_RemoteTrigSkill; // 0x300
	private static DelegateBridge __Hotfix0_SwitchToAttackState; // 0x308
	private static DelegateBridge __Hotfix0_SwitchToSkillState; // 0x310
	private static DelegateBridge __Hotfix0_SwitchOutFromSkillState; // 0x318
	private static DelegateBridge __Hotfix0_CheckIsBornState; // 0x320
	private static DelegateBridge __Hotfix0_Withdraw; // 0x328
	private static DelegateBridge __Hotfix0_CheckBuildable; // 0x330
	private static DelegateBridge __Hotfix0_CheckRespawnSelfBuildable; // 0x338
	private static DelegateBridge __Hotfix0_LocateOnTile; // 0x340
	private static DelegateBridge __Hotfix0_RechargeToken; // 0x348
	private static DelegateBridge __Hotfix0_FetchHost; // 0x350
	private static DelegateBridge __Hotfix0_TryGetAtkAsHostBased; // 0x358
	private static DelegateBridge __Hotfix0_ResetSearchBlockeeTicker; // 0x360
	private static DelegateBridge __Hotfix0_SearchBlockeeImmediate; // 0x368
	private static DelegateBridge __Hotfix0_FetchTokenOrHost; // 0x370
	private static DelegateBridge __Hotfix0_GetCurrentModeRangeId; // 0x378
	private static DelegateBridge __Hotfix0_GetModeRangeId; // 0x380
	private static DelegateBridge __Hotfix0_GetRangeOfSkill; // 0x388
	private static DelegateBridge __Hotfix0_PlayAudioSignal; // 0x390
	private static DelegateBridge __Hotfix0__GetCharacterSignal; // 0x398
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0x3a0
	private static DelegateBridge __Hotfix0_CheckUseIdForAudioSignal; // 0x3a8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x3b0
	private static DelegateBridge __Hotfix0_ChangeMotionMode; // 0x3b8
	private static DelegateBridge __Hotfix0_ResetMotionMode; // 0x3c0
	private static DelegateBridge __Hotfix0_ChangeBlockMode; // 0x3c8
	private static DelegateBridge __Hotfix0_ResetBlockMode; // 0x3d0
	private static DelegateBridge __Hotfix0_FinishMe; // 0x3d8
	private static DelegateBridge __Hotfix0_DoFakeDeath; // 0x3e0
	private static DelegateBridge __Hotfix0_DoReborn; // 0x3e8
	private static DelegateBridge __Hotfix0_ForceDying; // 0x3f0
	private static DelegateBridge __Hotfix0_RespawnSelf; // 0x3f8
	private static DelegateBridge __Hotfix0_MoveLikeRespawnSelf; // 0x400
	private static DelegateBridge __Hotfix1_MoveLikeRespawnSelf; // 0x408
	private static DelegateBridge __Hotfix0_RespawnSelfAsPredefined; // 0x410
	private static DelegateBridge __Hotfix0_GetDelayToRecycleTime; // 0x418
	private static DelegateBridge __Hotfix0_FinishWithReplace; // 0x420
	private static DelegateBridge __Hotfix0_ClearAbilities; // 0x428
	private static DelegateBridge __Hotfix0__ClearAbilityProjectilesIfNeeded; // 0x430
	private static DelegateBridge __Hotfix0__BuildAtInternal; // 0x438
	private static DelegateBridge __Hotfix0__InitAllModeDirection; // 0x440
	private static DelegateBridge __Hotfix0_LogSnapshotIfNot; // 0x448
	private static DelegateBridge __Hotfix0_CheckHasFilterTag; // 0x450
	private static DelegateBridge __Hotfix0_SetAdditionalBuildCondition; // 0x458
	private static DelegateBridge __Hotfix0_AddOverlapSourceId; // 0x460
	private static DelegateBridge __Hotfix0_RemoveOverlapSourceId; // 0x468
	private static DelegateBridge __Hotfix0_GetEffectReplacePairs; // 0x470
	private static DelegateBridge __Hotfix0_TryHookEffect; // 0x478
	private static DelegateBridge __Hotfix0_TryHookAudio; // 0x480
	private static DelegateBridge __Hotfix0_TryHookProjectile; // 0x488
	private static DelegateBridge __Hotfix0_RegisterReplacement; // 0x490
	private static DelegateBridge __Hotfix0_UnregisterReplacement; // 0x498
	private static DelegateBridge __Hotfix0_CheckIsCurrentReplacement; // 0x4a0
	private static DelegateBridge __Hotfix0_ClearReplacement; // 0x4a8
	private static DelegateBridge __Hotfix0_GetStartEffect; // 0x4b0
	private static DelegateBridge __Hotfix0_GetDeadEffect; // 0x4b8
	private static DelegateBridge __Hotfix0_GetAttackBlackboard; // 0x4c0
	private static DelegateBridge __Hotfix0__CheckCanSwithToAttackState; // 0x4c8
	private static DelegateBridge __Hotfix0__SearchAttackTarget; // 0x4d0
	private static DelegateBridge __Hotfix0__FetchCombatTarget; // 0x4d8
	private static DelegateBridge __Hotfix0_TryFaceToIdleDirection; // 0x4e0
	private static DelegateBridge __Hotfix0_isStillMotionTargetFreeWithImmuneFlag; // 0x4e8
	private static DelegateBridge __Hotfix0_CheckInBlockRange; // 0x4f0
	private static DelegateBridge __Hotfix0__SearchBlockee; // 0x4f8
	private static DelegateBridge __Hotfix0__CheckBlockable; // 0x500
	private static DelegateBridge __Hotfix0_CheckBlockVolumeNotExceeded; // 0x508
	private static DelegateBridge __Hotfix0__ClearAllBlockees; // 0x510
	private static DelegateBridge __Hotfix0__AddBlockee; // 0x518
	private static DelegateBridge __Hotfix0_RemoveBlockee; // 0x520
	private static DelegateBridge __Hotfix0_RecalculateBlockeesTotalVolume; // 0x528
	private static DelegateBridge __Hotfix0_UpdateBlockees; // 0x530
	private static DelegateBridge __Hotfix0_SetupSkin; // 0x538
	private static DelegateBridge __Hotfix0_RecycleSkinIfNot; // 0x540
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x548
	private static DelegateBridge __Hotfix0_OnTick; // 0x550
	private static DelegateBridge __Hotfix0_OnAwake; // 0x558
	private static DelegateBridge __Hotfix0_OnInit; // 0x560
	private static DelegateBridge __Hotfix0__SpawnDeckBuffs; // 0x568
	private static DelegateBridge __Hotfix0_OnBorn; // 0x570
	private static DelegateBridge __Hotfix0_OnReborn; // 0x578
	private static DelegateBridge __Hotfix0_OnHpZero; // 0x580
	private static DelegateBridge __Hotfix0_OnReset; // 0x588
	private static DelegateBridge __Hotfix0_OnLocate; // 0x590
	private static DelegateBridge __Hotfix0_OnFinish; // 0x598
	private static DelegateBridge __Hotfix0_ConstructStateMachine; // 0x5a0
	private static DelegateBridge __Hotfix0_OnAttributeDirty; // 0x5a8
	private static DelegateBridge __Hotfix0_OnDisappearChanged; // 0x5b0
	private static DelegateBridge __Hotfix0_CheckModeChangeBeforeAttack; // 0x5b8
	private static DelegateBridge __Hotfix0_OnBeforeAttack; // 0x5c0
	private static DelegateBridge __Hotfix0_OnAfterAttack; // 0x5c8
	private static DelegateBridge __Hotfix0_OnBeforeSkill; // 0x5d0
	private static DelegateBridge __Hotfix0_OnAfterSkill; // 0x5d8
	private static DelegateBridge __Hotfix0_OnSkillStart; // 0x5e0
	private static DelegateBridge __Hotfix0_OnToggleSkillStart; // 0x5e8
	private static DelegateBridge __Hotfix0_OnSkillCastSucceed; // 0x5f0
	private static DelegateBridge __Hotfix0_OnSkillFinish; // 0x5f8
	private static DelegateBridge __Hotfix0_PopulateSnapshotToHashBuilder; // 0x600
	private static DelegateBridge __Hotfix0_PopulateSnapshotToStrBuilder; // 0x608
	private static DelegateBridge __Hotfix0_CreateSkill; // 0x610
	private static DelegateBridge __Hotfix0_UpdateHatred; // 0x618
	private static DelegateBridge __Hotfix1_UpdateHatred; // 0x620
	private static DelegateBridge __Hotfix0_EnsureSkillOnInAbnormalState; // 0x628
	private static DelegateBridge __Hotfix0__AssignData; // 0x630
	private static DelegateBridge __Hotfix0__PreprocessSkill; // 0x638
	private static DelegateBridge __Hotfix0__RecycleEquipIfNot; // 0x640
	private static DelegateBridge __Hotfix0__AssignSkill; // 0x648
	private static DelegateBridge __Hotfix0__PreprocessSkin; // 0x650
	private static DelegateBridge __Hotfix0__PreprocessEquip; // 0x658
	private static DelegateBridge __Hotfix0__PreprocessTalents; // 0x660
	private static DelegateBridge __Hotfix0__AssignTalents; // 0x668
	private static DelegateBridge __Hotfix0__AssignTrait; // 0x670
	private static DelegateBridge __Hotfix0__PreprocessTrait; // 0x678
	private static DelegateBridge __Hotfix0__EquipProcessTalents; // 0x680
	private static DelegateBridge __Hotfix0__EquipProcessTrait; // 0x688
	private static DelegateBridge __Hotfix0__GetDefaultModeIndex; // 0x690
	private static DelegateBridge __Hotfix0__GetDefaultRangeId; // 0x698
	private static DelegateBridge __Hotfix0_OnEquipProcessed; // 0x6a0
	private static DelegateBridge __Hotfix0_GetCurrentAttackOrCombatAbility; // 0x6a8
	private static DelegateBridge __Hotfix0_GetCurrentModeSelector; // 0x6b0
	private static DelegateBridge __Hotfix0_GetSpecialModeAttack; // 0x6b8
	private static DelegateBridge __Hotfix0_get_ColliderRadius; // 0x6c0
	private static DelegateBridge __Hotfix0_OnRallyPointLikeReborn; // 0x6c8
	private static DelegateBridge __Hotfix0__ReactivateMainTriggerCollider; // 0x6d0
	private static DelegateBridge __Hotfix0_SetDontOccupyDeployCntFlag; // 0x6d8
	private static DelegateBridge __Hotfix0_SetDisableClickCharacterInfo; // 0x6e0
	private static DelegateBridge __Hotfix0_SetWithdrawCostRecoverRatio; // 0x6e8
	private static DelegateBridge __Hotfix0_UpdateMaxEs; // 0x6f0
	private static DelegateBridge __Hotfix0_OnEntityWillOverlap; // 0x6f8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x700

	protected virtual SideType initSideType { get; }
	public Transform skinHolder { get; }
	public override Transform graphicHolderTransform { get; }
	public override Boolean alive { get; }
	public override Boolean aliveOrDying { get; }
	public Boolean disableClickCharacterInfo { get; }
	public override UnitMode defaultMode { get; }
	public Int32 defaultModeIndex { get; }
	public UInt32 cardUid { get; set; }
	public UInt32 tokenOrHostUid { get; }
	public String characterId { get; }
	public Boolean playStartVocal { get; }
	public override Tile rootTile { get; }
	public override Tile oldTile { get; }
	public override UnitAnimator animator { get; }
	public override Boolean isInCombat { get; }
	public override FP hatred { get; }
	public override FP maxEs { get; }
	public FP maxEsRatio { get; }
	public override String talentRange { get; }
	public BuildCondition originBuildCondition { get; }
	public BuildCondition buildCondition { get; }
	public BuildableType additionalBuildType { get; }
	public AdvancedBuildableMask addtionalMask { get; }
	public override Ability attack { get; }
	public Ability rawAttackWithoutReplacement { get; }
	public override Ability combat { get; }
	public override Boolean hasCombat { get; }
	protected Ability rawCombatWithoutReplacement { get; }
	public override TargetTrigger attackTrigger { get; }
	public BasicSkill skill { get; }
	public SkillData skillData { get; }
	public virtual Boolean hideTileOption { get; }
	public Boolean hasSkill { get; }
	public Ability traitAbility { get; }
	public Boolean dontMoveCameraWhenFocus { get; }
	public Boolean disableCharInfoPanel { get; }
	public Ability traitOrTraitAsTalentAbility { get; }
	public Boolean traitAsTalent { get; }
	public override IDrawableRange rangeToShow { get; }
	public override String defaultRangeId { get; }
	public Boolean isToken { get; }
	public Boolean originOccupiedRemainingCharacterCnt { get; }
	public virtual Boolean occupiedRemainingCharacterCnt { get; }
	public virtual Int32 originRemainingCharacterCntVolume { get; set; }
	public virtual Int32 remainingCharacterCntVolume { get; }
	public Boolean overflowOccupiedCnt { get; }
	public virtual Boolean withdrawable { get; }
	public Boolean manuallyWithdrawable { get; }
	public override Boolean isMine { get; }
	public Boolean isBuiltPredefined { get; }
	protected Boolean isPlayerCharacter { get; }
	public override Transform directionTransform { get; }
	public IList`1 blockedEnemies { get; }
	public Int32 blockedTotalVolumn { get; }
	public Transform directionIndicator { get; }
	public virtual Single blockRadiusSquare { get; }
	public virtual Single minBlockDistToTarget { get; }
	public Blackboard traitBlackboard { get; }
	public MotionMode blockMode { get; }
	protected override Boolean isFixedRotation { get; }
	protected override Int32 initState { get; }
	protected override Single delayToRecycle { get; }
	protected virtual Boolean allowWithdrawGainCost { get; }
	protected HierachyStateMachine`3 stateMachine { get; }
	public BattleCharacterData data { get; set; }
	public SharedData sharedData { get; }
	public override List`1 managedProjectiles { get; }
	public override FP createdTime { get; }
	public FP deadTime { get; }
	protected virtual String startEffect { get; }
	protected virtual String deadEffect { get; }
	protected Boolean hasReplacement { get; }
	public override Boolean isInAttackState { get; }
	public override Boolean isInCombatState { get; }
	public override Boolean isInRebornState { get; }
	public Boolean isInIdletState { get; }
	public override Boolean isInDyingState { get; }
	public Boolean canBeReplace { get; }
	public override FP ColliderRadius { get; }

	// RVA: 0x1be0274 VA: 0x75941f8274
	protected virtual SideType get_initSideType() { }
	// RVA: 0x1be02ec VA: 0x75941f82ec
	public Transform get_skinHolder() { }
	// RVA: 0x1be0364 VA: 0x75941f8364
	public override Transform get_graphicHolderTransform() { }
	// RVA: 0x1be03dc VA: 0x75941f83dc
	public override Boolean get_alive() { }
	// RVA: 0x1be0494 VA: 0x75941f8494
	public override Boolean get_aliveOrDying() { }
	// RVA: 0x1be0550 VA: 0x75941f8550
	public Boolean get_disableClickCharacterInfo() { }
	// RVA: 0x1be0618 VA: 0x75941f8618
	public override UnitMode get_defaultMode() { }
	// RVA: 0x1be06b4 VA: 0x75941f86b4
	public Int32 get_defaultModeIndex() { }
	// RVA: 0x1be072c VA: 0x75941f872c
	public UInt32 get_cardUid() { }
	// RVA: 0x1be07a4 VA: 0x75941f87a4
	public Void set_cardUid(UInt32 value) { }
	// RVA: 0x1be0830 VA: 0x75941f8830
	public UInt32 get_tokenOrHostUid() { }
	// RVA: 0x1be08b8 VA: 0x75941f88b8
	public String get_characterId() { }
	// RVA: 0x1be0940 VA: 0x75941f8940
	public Boolean get_playStartVocal() { }
	// RVA: 0x1be09b8 VA: 0x75941f89b8
	public override Tile get_rootTile() { }
	// RVA: 0x1be0a30 VA: 0x75941f8a30
	public override Tile get_oldTile() { }
	// RVA: 0x1be0aa8 VA: 0x75941f8aa8
	public override UnitAnimator get_animator() { }
	// RVA: 0x1be0b20 VA: 0x75941f8b20
	public override Boolean get_isInCombat() { }
	// RVA: 0x1be0bb0 VA: 0x75941f8bb0
	public override FP get_hatred() { }
	// RVA: 0x1be0c28 VA: 0x75941f8c28
	public override FP get_maxEs() { }
	// RVA: 0x1be0d30 VA: 0x75941f8d30
	public FP get_maxEsRatio() { }
	// RVA: 0x1be0da8 VA: 0x75941f8da8
	public override String get_talentRange() { }
	// RVA: 0x1be0e20 VA: 0x75941f8e20
	public BuildCondition get_originBuildCondition() { }
	// RVA: 0x1bda2e4 VA: 0x75941f22e4
	public BuildCondition get_buildCondition() { }
	// RVA: 0x1be0ed4 VA: 0x75941f8ed4
	public BuildableType get_additionalBuildType() { }
	// RVA: 0x1be0f4c VA: 0x75941f8f4c
	public AdvancedBuildableMask get_addtionalMask() { }
	// RVA: 0x1be0fc4 VA: 0x75941f8fc4
	public override Ability get_attack() { }
	// RVA: 0x1be10bc VA: 0x75941f90bc
	public Ability get_rawAttackWithoutReplacement() { }
	// RVA: 0x1be1138 VA: 0x75941f9138
	public override Ability get_combat() { }
	// RVA: 0x1be1230 VA: 0x75941f9230
	public override Boolean get_hasCombat() { }
	// RVA: 0x1be12e4 VA: 0x75941f92e4
	protected Ability get_rawCombatWithoutReplacement() { }
	// RVA: 0x1be1360 VA: 0x75941f9360
	public override TargetTrigger get_attackTrigger() { }
	// RVA: 0x1bdf8bc VA: 0x75941f78bc
	public BasicSkill get_skill() { }
	// RVA: 0x1bdafac VA: 0x75941f2fac
	public SkillData get_skillData() { }
	// RVA: 0x1be1514 VA: 0x75941f9514
	public virtual Boolean get_hideTileOption() { }
	// RVA: 0x1be1588 VA: 0x75941f9588
	public Boolean get_hasSkill() { }
	// RVA: 0x1bd42cc VA: 0x75941ec2cc
	public Ability get_traitAbility() { }
	// RVA: 0x1be1630 VA: 0x75941f9630
	public Boolean get_dontMoveCameraWhenFocus() { }
	// RVA: 0x1be16a8 VA: 0x75941f96a8
	public Boolean get_disableCharInfoPanel() { }
	// RVA: 0x1bd7b94 VA: 0x75941efb94
	public Ability get_traitOrTraitAsTalentAbility() { }
	// RVA: 0x1be1720 VA: 0x75941f9720
	public Boolean get_traitAsTalent() { }
	// RVA: 0x1be17d4 VA: 0x75941f97d4
	public override IDrawableRange get_rangeToShow() { }
	// RVA: 0x1be18e0 VA: 0x75941f98e0
	public override String get_defaultRangeId() { }
	// RVA: 0x1be1958 VA: 0x75941f9958
	public Boolean get_isToken() { }
	// RVA: 0x1be19e0 VA: 0x75941f99e0
	public Boolean get_originOccupiedRemainingCharacterCnt() { }
	// RVA: 0x1be1a70 VA: 0x75941f9a70
	public virtual Boolean get_occupiedRemainingCharacterCnt() { }
	// RVA: 0x1be1b04 VA: 0x75941f9b04
	public virtual Int32 get_originRemainingCharacterCntVolume() { }
	// RVA: 0x1be1b7c VA: 0x75941f9b7c
	public virtual Void set_originRemainingCharacterCntVolume(Int32 value) { }
	// RVA: 0x1be1c08 VA: 0x75941f9c08
	public virtual Int32 get_remainingCharacterCntVolume() { }
	// RVA: 0x1be1cb4 VA: 0x75941f9cb4
	public Boolean get_overflowOccupiedCnt() { }
	// RVA: 0x1be1da0 VA: 0x75941f9da0
	public virtual Boolean get_withdrawable() { }
	// RVA: 0x1be1e20 VA: 0x75941f9e20
	public Boolean get_manuallyWithdrawable() { }
	// RVA: 0x1be1ef4 VA: 0x75941f9ef4
	public override Boolean get_isMine() { }
	// RVA: 0x1be1fac VA: 0x75941f9fac
	public Boolean IsControllable(PlayerSide opSide) { }
	// RVA: 0x1be2090 VA: 0x75941fa090
	public Boolean get_isBuiltPredefined() { }
	// RVA: 0x1be2108 VA: 0x75941fa108
	protected Boolean get_isPlayerCharacter() { }
	// RVA: 0x1be21b8 VA: 0x75941fa1b8
	public override Transform get_directionTransform() { }
	// RVA: 0x1be2230 VA: 0x75941fa230
	public IList`1 get_blockedEnemies() { }
	// RVA: 0x1be22b4 VA: 0x75941fa2b4
	public Int32 get_blockedTotalVolumn() { }
	// RVA: 0x1be2338 VA: 0x75941fa338
	public Transform get_directionIndicator() { }
	// RVA: 0x1be23b0 VA: 0x75941fa3b0
	public virtual Single get_blockRadiusSquare() { }
	// RVA: 0x1be24b8 VA: 0x75941fa4b8
	public virtual Single get_minBlockDistToTarget() { }
	// RVA: 0x1be2530 VA: 0x75941fa530
	public Blackboard get_traitBlackboard() { }
	// RVA: 0x1be2630 VA: 0x75941fa630
	public VoiceQuery GetVoiceQuery() { }
	// RVA: 0x1be2440 VA: 0x75941fa440
	public MotionMode get_blockMode() { }
	// RVA: 0x1be2728 VA: 0x75941fa728
	protected override Boolean get_isFixedRotation() { }
	// RVA: 0x1be27a0 VA: 0x75941fa7a0
	protected override Int32 get_initState() { }
	// RVA: 0x1be2818 VA: 0x75941fa818
	protected override Single get_delayToRecycle() { }
	// RVA: 0x1be2890 VA: 0x75941fa890
	protected virtual Boolean get_allowWithdrawGainCost() { }
	// RVA: 0x1be2930 VA: 0x75941fa930
	public Void SetExternWithdrawGainCostFlag(Boolean value) { }
	// RVA: 0x1be29c0 VA: 0x75941fa9c0
	protected HierachyStateMachine`3 get_stateMachine() { }
	// RVA: 0x1bd6c48 VA: 0x75941eec48
	public BattleCharacterData get_data() { }
	// RVA: 0x1be2a84 VA: 0x75941faa84
	private Void set_data(BattleCharacterData value) { }
	// RVA: 0x1bdb938 VA: 0x75941f3938
	public SharedData get_sharedData() { }
	// RVA: 0x1be2b18 VA: 0x75941fab18
	public override List`1 get_managedProjectiles() { }
	// RVA: 0x1be2c18 VA: 0x75941fac18
	public override FP get_createdTime() { }
	// RVA: 0x1be2c90 VA: 0x75941fac90
	public FP get_deadTime() { }
	// RVA: 0x1be2d08 VA: 0x75941fad08
	protected virtual String get_startEffect() { }
	// RVA: 0x1be2dd0 VA: 0x75941fadd0
	protected virtual String get_deadEffect() { }
	// RVA: 0x1be2e74 VA: 0x75941fae74
	protected Boolean get_hasReplacement() { }
	// RVA: 0x1be2ef4 VA: 0x75941faef4
	public override Boolean get_isInAttackState() { }
	// RVA: 0x1be2f80 VA: 0x75941faf80
	public override Boolean get_isInCombatState() { }
	// RVA: 0x1be300c VA: 0x75941fb00c
	public override Boolean get_isInRebornState() { }
	// RVA: 0x1be3098 VA: 0x75941fb098
	public Boolean get_isInIdletState() { }
	// RVA: 0x1be3124 VA: 0x75941fb124
	public override Boolean get_isInDyingState() { }
	// RVA: 0x1be31b0 VA: 0x75941fb1b0
	public Boolean get_canBeReplace() { }
	// RVA: 0x1be324c VA: 0x75941fb24c
	public Void PlayBornAnimationAndEffect(ref FP m_remainingTime, Action noBornAnimationFallBack, Boolean disableEffect) { }
	// RVA: 0x1be388c VA: 0x75941fb88c
	public Void StopBornAnimationAndEffect(String animationKey) { }
	// RVA: 0x1be368c VA: 0x75941fb68c
	private Void _PlayUniEquipEffect(Single playSpeed) { }
	// RVA: 0x1be39a0 VA: 0x75941fb9a0
	public Void BuildAt(Card card, Tile tile, Direction direction) { }
	// RVA: 0x1be3fbc VA: 0x75941fbfbc
	public Void BuildAsPredefined(BattleCharacterData data, Tile tile, Direction direction) { }
	// RVA: 0x1be4150 VA: 0x75941fc150
	public Void BuildAsRuntimeInst(BattleCharacterData data, Tile tile, Direction direction, SideType sideType, PlayerSide pSide) { }
	// RVA: 0x1be42c4 VA: 0x75941fc2c4
	public override Void Born() { }
	// RVA: 0x1be442c VA: 0x75941fc42c
	public Void MakeDummy(BattleCharacterData data, Direction direction, AdditionalBuildCondition additionalBuildCondition, PlayerSide deckPlayerSide) { }
	// RVA: 0x1be4960 VA: 0x75941fc960
	public Boolean OpTrigSkill(PlayerSide operationSide) { }
	// RVA: 0x1be4ac0 VA: 0x75941fcac0
	public Boolean RemoteTrigSkill() { }
	// RVA: 0x1be4b8c VA: 0x75941fcb8c
	public Boolean SwitchToAttackState() { }
	// RVA: 0x1be4d54 VA: 0x75941fcd54
	public Void SwitchToSkillState() { }
	// RVA: 0x1be4e54 VA: 0x75941fce54
	public Void SwitchOutFromSkillState() { }
	// RVA: 0x1be4f18 VA: 0x75941fcf18
	public Boolean CheckIsBornState() { }
	// RVA: 0x1be4fa8 VA: 0x75941fcfa8
	public virtual Boolean Withdraw(Boolean switchToDeadState, Boolean force, Boolean manual, Boolean logAutoWithdraw) { }
	// RVA: 0x1be5310 VA: 0x75941fd310
	public Boolean CheckBuildable(Tile tile, Direction direction, Boolean spawnManually, Boolean ignoreAdvancedBuildableMask) { }
	// RVA: 0x1be54a8 VA: 0x75941fd4a8
	public Boolean CheckRespawnSelfBuildable(Tile tile, Direction direction, Boolean spawnManually, Boolean ignoreAdvancedBuildableMask) { }
	// RVA: 0x1be5634 VA: 0x75941fd634
	public virtual Void LocateOnTile(Tile tile) { }
	// RVA: 0x1be56e4 VA: 0x75941fd6e4
	public Boolean RechargeToken(Int32 cnt, RechargeTiming timing, Boolean refreshRemainingCnt) { }
	// RVA: 0x1be5828 VA: 0x75941fd828
	public override Entity FetchHost() { }
	// RVA: 0x1be59ec VA: 0x75941fd9ec
	public Boolean TryGetAtkAsHostBased(out FP atk) { }
	// RVA: 0x1be5c6c VA: 0x75941fdc6c
	public Void ResetSearchBlockeeTicker() { }
	// RVA: 0x1be5cf4 VA: 0x75941fdcf4
	public Void SearchBlockeeImmediate() { }
	// RVA: 0x1bd32e8 VA: 0x75941eb2e8
	public Void FetchTokenOrHost(Int32 maxTargetNum, List`1 results, Func`2 validator) { }
	// RVA: 0x1be602c VA: 0x75941fe02c
	public String GetCurrentModeRangeId() { }
	// RVA: 0x1be60b8 VA: 0x75941fe0b8
	public override String GetModeRangeId(UnitMode mode, RangeIdUsage usage) { }
	// RVA: 0x1be62f4 VA: 0x75941fe2f4
	public IDrawableRange GetRangeOfSkill() { }
	// RVA: 0x1be63dc VA: 0x75941fe3dc
	public override Void PlayAudioSignal(String ev, Boolean ignorePredefined) { }
	// RVA: 0x1be65f0 VA: 0x75941fe5f0
	private String _GetCharacterSignal(String ev) { }
	// RVA: 0x1be68a0 VA: 0x75941fe8a0
	public override Void PreloadSpecialAudioSignals(String characterId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1be67a8 VA: 0x75941fe7a8
	protected Boolean CheckUseIdForAudioSignal(String ev) { }
	// RVA: 0x1be6a20 VA: 0x75941fea20
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1be6c64 VA: 0x75941fec64
	public override Void ChangeMotionMode(MotionMode mode) { }
	// RVA: 0x1be6df4 VA: 0x75941fedf4
	public override Void ResetMotionMode() { }
	// RVA: 0x1be6e78 VA: 0x75941fee78
	public Void ChangeBlockMode(MotionMode mode) { }
	// RVA: 0x1be6f08 VA: 0x75941fef08
	public Void ResetBlockMode() { }
	// RVA: 0x1be6f88 VA: 0x75941fef88
	protected override Void FinishMe(FinishReason reason) { }
	// RVA: 0x1be718c VA: 0x75941ff18c
	protected override Void DoFakeDeath(RebornData rebornData) { }
	// RVA: 0x1be7250 VA: 0x75941ff250
	protected override Void DoReborn(RebornData data) { }
	// RVA: 0x1be7328 VA: 0x75941ff328
	public Void ForceDying() { }
	// RVA: 0x1be73f8 VA: 0x75941ff3f8
	public Void RespawnSelf(Tile newTile, Direction newDirection, Boolean spawnManually, PlayerSide side, Boolean ignoreAdvancedBuildableMask) { }
	// RVA: 0x1be7544 VA: 0x75941ff544
	public Boolean MoveLikeRespawnSelf(Tile newTile, Direction newDirection, Boolean spawnManually, PlayerSide side, Boolean ignoreAdvancedBuildableMask) { }
	// RVA: 0x1be7764 VA: 0x75941ff764
	public Boolean MoveLikeRespawnSelf(Tile newTile, Direction newDirection, out Character charOrToken, Boolean spawnManually, PlayerSide side, Boolean ignoreAdvancedBuildableMask) { }
	// RVA: 0x1be798c VA: 0x75941ff98c
	public Character RespawnSelfAsPredefined(String alias, Tile newTile, Direction newDirection) { }
	// RVA: 0x1be7a7c VA: 0x75941ffa7c
	public Single GetDelayToRecycleTime() { }
	// RVA: 0x1be7b00 VA: 0x75941ffb00
	public Void FinishWithReplace(Character character) { }
	// RVA: 0x1be7dbc VA: 0x75941ffdbc
	protected override Void ClearAbilities() { }
	// RVA: 0x1be7e40 VA: 0x75941ffe40
	private Void _ClearAbilityProjectilesIfNeeded() { }
	// RVA: 0x1be3b2c VA: 0x75941fbb2c
	private Void _BuildAtInternal(BuildParam characterBuildParam) { }
	// RVA: 0x1be8094 VA: 0x7594200094
	private Void _InitAllModeDirection() { }
	// RVA: 0x1be8280 VA: 0x7594200280
	public Void LogSnapshotIfNot() { }
	// RVA: 0x1be8360 VA: 0x7594200360
	public override Boolean CheckHasFilterTag(String unitTag) { }
	// RVA: 0x1be83e8 VA: 0x75942003e8
	public Void SetAdditionalBuildCondition(BuildableType type, AdvancedBuildableMask mask) { }
	// RVA: 0x1be8480 VA: 0x7594200480
	public Void AddOverlapSourceId(String sourceId) { }
	// RVA: 0x1be851c VA: 0x759420051c
	public Void RemoveOverlapSourceId(String sourceId) { }
	// RVA: 0x1be85b8 VA: 0x75942005b8
	public override EffectReplacePair[] GetEffectReplacePairs() { }
	// RVA: 0x1be876c VA: 0x759420076c
	public override Boolean TryHookEffect(String originEffectKey, out String newEffectKey) { }
	// RVA: 0x1be88a4 VA: 0x75942008a4
	public override Boolean TryHookAudio(String signal, String subSignal, out String newSignal, out String newSubsignal) { }
	// RVA: 0x1be8a14 VA: 0x7594200a14
	public override Boolean TryHookProjectile(String originProjectile, out String graphicProjectileKey, out String logicProjectile, out MountPointType muzzlePoint) { }
	// RVA: 0x1be8b8c VA: 0x7594200b8c
	public Void RegisterReplacement(IReplacement replacement) { }
	// RVA: 0x1be8ee0 VA: 0x7594200ee0
	public Void UnregisterReplacement(IReplacement ability) { }
	// RVA: 0x1be8f88 VA: 0x7594200f88
	public Boolean CheckIsCurrentReplacement(IReplacement ability) { }
	// RVA: 0x1be8cac VA: 0x7594200cac
	public Void ClearReplacement() { }
	// RVA: 0x1be34a4 VA: 0x75941fb4a4
	public String GetStartEffect() { }
	// RVA: 0x1be901c VA: 0x759420101c
	public String GetDeadEffect() { }
	// RVA: 0x1be9130 VA: 0x7594201130
	public override Blackboard GetAttackBlackboard(UnitMode mode) { }
	// RVA: 0x1be4c64 VA: 0x75941fcc64
	private Boolean _CheckCanSwithToAttackState() { }
	// RVA: 0x1be93cc VA: 0x75942013cc
	private Boolean _SearchAttackTarget() { }
	// RVA: 0x1be92cc VA: 0x75942012cc
	private Enemy _FetchCombatTarget() { }
	// RVA: 0x1be955c VA: 0x759420155c
	public Void TryFaceToIdleDirection() { }
	// RVA: 0x1be9630 VA: 0x7594201630
	public override Boolean isStillMotionTargetFreeWithImmuneFlag(AbnormalFlag immuneFlag, AbnormalCombo immuneCombo, MotionMode sourceMotionMode) { }
	// RVA: 0x1be9704 VA: 0x7594201704
	public virtual Boolean CheckInBlockRange(Entity target, Single shrink) { }
	// RVA: 0x1be5d94 VA: 0x75941fdd94
	private Void _SearchBlockee(Boolean force) { }
	// RVA: 0x1be9938 VA: 0x7594201938
	private Boolean _CheckBlockable(Entity entity, Entity source, out FP weight, out Int32 volume) { }
	// RVA: 0x1be9b54 VA: 0x7594201b54
	public Boolean CheckBlockVolumeNotExceeded(Enemy enemy) { }
	// RVA: 0x1be6d00 VA: 0x75941fed00
	private Void _ClearAllBlockees() { }
	// RVA: 0x1be9808 VA: 0x7594201808
	private Void _AddBlockee(Enemy enemy) { }
	// RVA: 0x1be9c04 VA: 0x7594201c04
	public Void RemoveBlockee(Enemy enemy) { }
	// RVA: 0x1be9cdc VA: 0x7594201cdc
	public Void RecalculateBlockeesTotalVolume() { }
	// RVA: 0x1be9d60 VA: 0x7594201d60
	public Void UpdateBlockees() { }
	// RVA: 0x1be9e24 VA: 0x7594201e24
	protected Void SetupSkin(UnitAnimator skin, String name) { }
	// RVA: 0x1be9fb4 VA: 0x7594201fb4
	protected Void RecycleSkinIfNot() { }
	// RVA: 0x1bea0e0 VA: 0x75942020e0
	public override Void OnRecycle() { }
	// RVA: 0x1bea5c4 VA: 0x75942025c4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1bea750 VA: 0x7594202750
	protected override Void OnAwake() { }
	// RVA: 0x1bea9b8 VA: 0x75942029b8
	protected override Void OnInit(Single initHeight) { }
	// RVA: 0x1beac2c VA: 0x7594202c2c
	private Void _SpawnDeckBuffs() { }
	// RVA: 0x1beadb8 VA: 0x7594202db8
	protected override Void OnBorn() { }
	// RVA: 0x1beb0c0 VA: 0x75942030c0
	public override Void OnReborn(RebornData data) { }
	// RVA: 0x1beb1e0 VA: 0x75942031e0
	protected override Void OnHpZero(Boolean noSource, Boolean skipReborn) { }
	// RVA: 0x1beb340 VA: 0x7594203340
	protected override Void OnReset() { }
	// RVA: 0x1beb530 VA: 0x7594203530
	protected override Void OnLocate() { }
	// RVA: 0x1beb648 VA: 0x7594203648
	protected override Void OnFinish(FinishReason reason) { }
	// RVA: 0x1beb820 VA: 0x7594203820
	protected override StateMachine ConstructStateMachine() { }
	// RVA: 0x1beb89c VA: 0x759420389c
	protected override Void OnAttributeDirty(AttributeType attributeType, FP oldValue) { }
	// RVA: 0x1beb978 VA: 0x7594203978
	protected override Void OnDisappearChanged(Boolean newValue) { }
	// RVA: 0x1beba50 VA: 0x7594203a50
	protected Boolean CheckModeChangeBeforeAttack(Int32 oldModeIndex) { }
	// RVA: 0x1bebaec VA: 0x7594203aec
	protected Boolean OnBeforeAttack(Ability ability, Boolean isCombat) { }
	// RVA: 0x1bebd3c VA: 0x7594203d3c
	protected Void OnAfterAttack(Ability ability, Boolean isCombat, FinishReason reason) { }
	// RVA: 0x1bebf3c VA: 0x7594203f3c
	protected Boolean OnBeforeSkill(BasicSkill skill) { }
	// RVA: 0x1bec148 VA: 0x7594204148
	protected Void OnAfterSkill(BasicSkill skill, FinishReason reason) { }
	// RVA: 0x1bec334 VA: 0x7594204334
	public Void OnSkillStart() { }
	// RVA: 0x1bec434 VA: 0x7594204434
	public Void OnToggleSkillStart() { }
	// RVA: 0x1bec518 VA: 0x7594204518
	public Void OnSkillCastSucceed() { }
	// RVA: 0x1bec5b8 VA: 0x75942045b8
	public Void OnSkillFinish() { }
	// RVA: 0x1bec69c VA: 0x759420469c
	public override Void PopulateSnapshotToHashBuilder(HashCodeBuilder builder) { }
	// RVA: 0x1bec7d8 VA: 0x75942047d8
	public override Void PopulateSnapshotToStrBuilder(StringBuilder builder) { }
	// RVA: 0x1bec9d0 VA: 0x75942049d0
	protected virtual BasicSkill CreateSkill(SkillData data) { }
	// RVA: 0x1be7f44 VA: 0x75941fff44
	protected Void UpdateHatred() { }
	// RVA: 0x1beca84 VA: 0x7594204a84
	public Void UpdateHatred(Single newHatred) { }
	// RVA: 0x1becb40 VA: 0x7594204b40
	public Void EnsureSkillOnInAbnormalState() { }
	// RVA: 0x1be473c VA: 0x75941fc73c
	private Void _AssignData(BattleCharacterData data, SideType sideType, PlayerSide playerSide) { }
	// RVA: 0x1bed56c VA: 0x759420556c
	private Void _PreprocessSkill(SkillData data) { }
	// RVA: 0x1bea200 VA: 0x7594202200
	private Void _RecycleEquipIfNot() { }
	// RVA: 0x1bedcb4 VA: 0x7594205cb4
	private Void _AssignSkill(SkillData skillData, Blackboard externalBlackboard, Dictionary`2 talentMap) { }
	// RVA: 0x1bece6c VA: 0x7594204e6c
	private Void _PreprocessSkin(CharSkinData skinData) { }
	// RVA: 0x1becfd0 VA: 0x7594204fd0
	private Void _PreprocessEquip() { }
	// RVA: 0x1bed17c VA: 0x759420517c
	private Void _PreprocessTalents(IList`1 talentsData, TalentData traitTalentData, out Dictionary`2 talentMap, out Blackboard skillBlackboard) { }
	// RVA: 0x1bedefc VA: 0x7594205efc
	private Void _AssignTalents(Dictionary`2 talentMap) { }
	// RVA: 0x1bee1f0 VA: 0x75942061f0
	private Void _AssignTrait(TraitData traitData) { }
	// RVA: 0x1bed050 VA: 0x7594205050
	private Void _PreprocessTrait(TraitData traitData, out TalentData talentData) { }
	// RVA: 0x1bee53c VA: 0x759420653c
	private Void _EquipProcessTalents() { }
	// RVA: 0x1bee6d8 VA: 0x75942066d8
	private Void _EquipProcessTrait() { }
	// RVA: 0x1bed79c VA: 0x759420579c
	private Int32 _GetDefaultModeIndex(Dictionary`2 talentMap) { }
	// RVA: 0x1beda30 VA: 0x7594205a30
	private String _GetDefaultRangeId(Dictionary`2 talentMap) { }
	// RVA: 0x1bee91c VA: 0x759420691c
	private Void OnEquipProcessed(String equipOriginKey, GameObject equip) { }
	// RVA: 0x1bee9d8 VA: 0x75942069d8
	public override AbstractBasicAttack GetCurrentAttackOrCombatAbility() { }
	// RVA: 0x1beec24 VA: 0x7594206c24
	public TargetSelector GetCurrentModeSelector() { }
	// RVA: 0x1beed54 VA: 0x7594206d54
	public Ability GetSpecialModeAttack(Int32 modeIndex) { }
	// RVA: 0x1beee18 VA: 0x7594206e18
	public override FP get_ColliderRadius() { }
	// RVA: 0x1beee90 VA: 0x7594206e90
	public Void OnRallyPointLikeReborn() { }
	// RVA: 0x1beef98 VA: 0x7594206f98
	private Void _ReactivateMainTriggerCollider() { }
	// RVA: 0x1bef090 VA: 0x7594207090
	public Void SetDontOccupyDeployCntFlag(Boolean dontOccupyDeployCnt) { }
	// RVA: 0x1bef120 VA: 0x7594207120
	public Void SetDisableClickCharacterInfo(Boolean isDisable, DisableClickCharacterInfoReasonMask reason) { }
	// RVA: 0x1bef1dc VA: 0x75942071dc
	public Void SetWithdrawCostRecoverRatio(Single ratio, Boolean isReset, Boolean limitMaxWithdrawCostByDeployUse) { }
	// RVA: 0x1bef2a0 VA: 0x75942072a0
	public Void UpdateMaxEs(FP maxEsRatio) { }
	// RVA: 0x1bef32c VA: 0x759420732c
	public Void OnEntityWillOverlap(Entity entity, Direction direction) { }
	// RVA: 0x1bef3dc VA: 0x75942073dc
	public Void .ctor() { }
	// RVA: 0x1bef6d0 VA: 0x75942076d0
	private static Void .cctor() { }
	// RVA: 0x1bef760 VA: 0x7594207760
	private Transform <>xLuaBaseProxy_get_graphicHolderTransform() { }
	// RVA: 0x1bef768 VA: 0x7594207768
	private Boolean <>xLuaBaseProxy_get_alive() { }
	// RVA: 0x1bef770 VA: 0x7594207770
	private Boolean <>xLuaBaseProxy_get_aliveOrDying() { }
	// RVA: 0x1bef778 VA: 0x7594207778
	private UnitMode <>xLuaBaseProxy_get_defaultMode() { }
	// RVA: 0x1bef780 VA: 0x7594207780
	private UnitAnimator <>xLuaBaseProxy_get_animator() { }
	// RVA: 0x1bef788 VA: 0x7594207788
	private FP <>xLuaBaseProxy_get_maxEs() { }
	// RVA: 0x1bef790 VA: 0x7594207790
	private String <>xLuaBaseProxy_get_talentRange() { }
	// RVA: 0x1bef798 VA: 0x7594207798
	private Ability <>xLuaBaseProxy_get_attack() { }
	// RVA: 0x1bef7a0 VA: 0x75942077a0
	private Ability <>xLuaBaseProxy_get_combat() { }
	// RVA: 0x1bef7a8 VA: 0x75942077a8
	private Boolean <>xLuaBaseProxy_get_hasCombat() { }
	// RVA: 0x1bef7b0 VA: 0x75942077b0
	private TargetTrigger <>xLuaBaseProxy_get_attackTrigger() { }
	// RVA: 0x1bef7b8 VA: 0x75942077b8
	private IDrawableRange <>xLuaBaseProxy_get_rangeToShow() { }
	// RVA: 0x1bef7c0 VA: 0x75942077c0
	private String <>xLuaBaseProxy_get_defaultRangeId() { }
	// RVA: 0x1bef7c8 VA: 0x75942077c8
	private Boolean <>xLuaBaseProxy_get_isMine() { }
	// RVA: 0x1bef7d0 VA: 0x75942077d0
	private Transform <>xLuaBaseProxy_get_directionTransform() { }
	// RVA: 0x1bef7d8 VA: 0x75942077d8
	private Int32 <>xLuaBaseProxy_get_initState() { }
	// RVA: 0x1bef7e0 VA: 0x75942077e0
	private Single <>xLuaBaseProxy_get_delayToRecycle() { }
	// RVA: 0x1bef7e8 VA: 0x75942077e8
	private Void <>xLuaBaseProxy_Born() { }
	// RVA: 0x1bef7f0 VA: 0x75942077f0
	private Entity <>xLuaBaseProxy_FetchHost() { }
	// RVA: 0x1bef7f8 VA: 0x75942077f8
	private String <>xLuaBaseProxy_GetModeRangeId(UnitMode P0, RangeIdUsage P1) { }
	// RVA: 0x1bef800 VA: 0x7594207800
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
	// RVA: 0x1bef808 VA: 0x7594207808
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x1bef810 VA: 0x7594207810
	private Void <>xLuaBaseProxy_ChangeMotionMode(MotionMode P0) { }
	// RVA: 0x1bef818 VA: 0x7594207818
	private Void <>xLuaBaseProxy_ResetMotionMode() { }
	// RVA: 0x1bef820 VA: 0x7594207820
	private Void <>xLuaBaseProxy_FinishMe(FinishReason P0) { }
	// RVA: 0x1bef828 VA: 0x7594207828
	private Void <>xLuaBaseProxy_DoFakeDeath(RebornData P0) { }
	// RVA: 0x1bef85c VA: 0x759420785c
	private Void <>xLuaBaseProxy_DoReborn(RebornData P0) { }
	// RVA: 0x1bef890 VA: 0x7594207890
	private Void <>xLuaBaseProxy_ClearAbilities() { }
	// RVA: 0x1bef898 VA: 0x7594207898
	private EffectReplacePair[] <>xLuaBaseProxy_GetEffectReplacePairs() { }
	// RVA: 0x1bef8a0 VA: 0x75942078a0
	private Boolean <>xLuaBaseProxy_TryHookEffect(String P0, out String P1) { }
	// RVA: 0x1bef8a8 VA: 0x75942078a8
	private Boolean <>xLuaBaseProxy_TryHookAudio(String P0, String P1, out String P2, out String P3) { }
	// RVA: 0x1bef8b0 VA: 0x75942078b0
	private Boolean <>xLuaBaseProxy_TryHookProjectile(String P0, out String P1, out String P2, out MountPointType P3) { }
	// RVA: 0x1bef8b8 VA: 0x75942078b8
	private Blackboard <>xLuaBaseProxy_GetAttackBlackboard(UnitMode P0) { }
	// RVA: 0x1bef8c0 VA: 0x75942078c0
	private Boolean <>xLuaBaseProxy_isStillMotionTargetFreeWithImmuneFlag(AbnormalFlag P0, AbnormalCombo P1, MotionMode P2) { }
	// RVA: 0x1bef8c8 VA: 0x75942078c8
	private Void <>xLuaBaseProxy_OnRecycle() { }
	// RVA: 0x1bef8d0 VA: 0x75942078d0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1bef8d8 VA: 0x75942078d8
	private Void <>xLuaBaseProxy_OnAwake() { }
	// RVA: 0x1bef8e0 VA: 0x75942078e0
	private Void <>xLuaBaseProxy_OnInit(Single P0) { }
	// RVA: 0x1bef8e8 VA: 0x75942078e8
	private Void <>xLuaBaseProxy_OnBorn() { }
	// RVA: 0x1bef8f0 VA: 0x75942078f0
	private Void <>xLuaBaseProxy_OnReborn(RebornData P0) { }
	// RVA: 0x1bef924 VA: 0x7594207924
	private Void <>xLuaBaseProxy_OnHpZero(Boolean P0, Boolean P1) { }
	// RVA: 0x1bef934 VA: 0x7594207934
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x1bef93c VA: 0x759420793c
	private Void <>xLuaBaseProxy_OnLocate() { }
	// RVA: 0x1bef944 VA: 0x7594207944
	private Void <>xLuaBaseProxy_OnFinish(FinishReason P0) { }
	// RVA: 0x1bef94c VA: 0x759420794c
	private Void <>xLuaBaseProxy_OnAttributeDirty(AttributeType P0, FP P1) { }
	// RVA: 0x1bef954 VA: 0x7594207954
	private Void <>xLuaBaseProxy_OnDisappearChanged(Boolean P0) { }
	// RVA: 0x1bef960 VA: 0x7594207960
	private Void <>xLuaBaseProxy_PopulateSnapshotToHashBuilder(HashCodeBuilder P0) { }
	// RVA: 0x1bef968 VA: 0x7594207968
	private Void <>xLuaBaseProxy_PopulateSnapshotToStrBuilder(StringBuilder P0) { }
	// RVA: 0x1bef970 VA: 0x7594207970
	private AbstractBasicAttack <>xLuaBaseProxy_GetCurrentAttackOrCombatAbility() { }
}
```