# Enemy

**Namespace:** `Torappu.Battle`


## Fields

- `Vector2 m_lastMoveDirVec`

- `SideTypeIndex _sideTypeIndex`

- `Range _locateRange`

- `Boolean _isFixedRotation`

- `BodyDirectionPolicy _bodyDirectionPolicy`

- `Boolean _scaleMoveBySpeed`

- `Vector2 _scaleMoveAnimationRange`

- `Boolean _showSpAsBulletMode`

- `Boolean _alwaysShowHp`

- `Boolean _alwaysHideHp`

- `Boolean _keepMoveAnimScale`

- `Boolean _useSpecificDeadAnim`

- `Boolean _useSpecificReachExitAnim`

- `Boolean _disableBornTweenColor`

- `Single _height`

- `Single _delayToBorn`

- `String _startEffect`

- `String _deadEffect`

- `Int32 _blockVolume`

- `SpecialBlockCondition _specialBlockCondition`

- `Boolean _dontSetEnemyFaceByCursorWhenBorn`

- `Boolean _idleWhenBorn`

- `Boolean _disableTriggerWhenDisappear`

- `Boolean _canNotExit`

- `Boolean _hideShadowOnReset`

- `Int32 m_defaultModeIndex`

- `Single m_totalMoveDist`

- `Boolean m_blinkHideUIFlag`

- `Boolean m_fogHideUIFlag`

- `Boolean m_showSpUIFlag`

- `Boolean m_alwaysShowHpFlag`

- `Tile m_currentTile`

- `Tile m_oldTile`

- `DirectionCursor m_cursor`

- `Route m_cachedRoute`

- `Int32 m_cachedCursorIndex`

- `BaseTraceTargetAbility m_traceTargetAbility`

- `TracePositionCursor m_traceTargetCursor`

- `MoveController m_moveController`

- `PeriodicTicker m_updatePosTicker`

- `HeightController m_heightCtrl`

- `SpineAnimator m_spineAnimator`

- `SpecialBlockCondition m_changealeSpecialBlockCondition`

- `Boolean m_disableAppearTweenColor`

- `FearController m_fearController`

- `ITweenHandler m_blockTween`

- `Tween m_tweenToRecycle`

- `Vector2 m_blockPosition`

- `Vector2 m_contDirAfterEnd`

- `Vector2 m_posInLastFrame`

- `Collider2D m_nonTriggerCollider`

- `Collider2D m_mainTriggerCollider`

- `FP m_mainTriggerColliderRadius`

- `RebornData m_rebornData`

- `Boolean m_isInvalidKilled`

- `Boolean m_isOverrideKillCnt`

- `Int32 m_overrideKillCnt`

- `Int32 m_blockVolumeAddition`

- `Boolean m_disableSwitchFaceByMove`

- `FP m_createdTime`

- `Single m_delayToRecycle`

- `UInt32 m_hostUid`

- `Ability m_attackAbilityCasted`

- `Ability m_combatAbilityCasted`

- `FP m_combatNextEscapeTime`

- `Boolean <disableUIHud>k__BackingField`

- `Int32 <lifePointReduce>k__BackingField`

- `Single <defaultRangeRadius>k__BackingField`

- `EnemyData <data>k__BackingField`

- `Options <options>k__BackingField`

- `Rigidbody2D <rigidbody2D>k__BackingField`

- `AttackWrapper <attackWrapper>k__BackingField`

- `CombatWrapper <combatWrapper>k__BackingField`

- `Single m_frictionFactor`

- `Single m_frictionFactorAdditional`


## Properties

- `Direction lastMoveDirection`

- `Vector2 lastMoveDirVec`

- `SpecialBlockCondition specialBlockCondition`

- `Boolean disableAppearTweenColor`

- `FearController fearController`

- `BodyDirectionPolicy bodyDirectionPolicy`

- `Ability attackAbilityCasted`

- `Ability combatAbilityCasted`

- `UInt32 hostUid`

- `Collider2D nonTriggerCollider`

- `MoveController moveController`

- `Single distToExit`

- `Single distToExitPrecise`

- `Boolean uiHideFlag`

- `Boolean hideHp`

- `Boolean alwaysHideHp`

- `Boolean showSpUIFlag`

- `Boolean alwaysShowHpFlag`

- `Boolean fogHideUIFlag`

- `Single spineHeight`

- `Single originHeight`

- `Boolean disableUIHud`

- `Single totalMoveDist`

- `Character blocker`

- `Int32 lifePointReduce`

- `Single defaultRangeRadius`

- `MotionMode essentialMotionMode`

- `EnemyData data`

- `Boolean isInMoveState`

- `Boolean isInBlinkState`

- `Boolean isInBornState`

- `Boolean isBoss`

- `IDrawableRange locateRange`

- `Int32 blockVolume`

- `Int32 blockVolumeAddition`

- `Boolean showSpAsBulletMode`

- `Boolean disableBulletSp`

- `Boolean combatable`

- `Vector2 footMapPosition`

- `Vector2 offsetMapPosition`

- `Vector2 stableBlockPosition`

- `Options options`

- `Boolean isInvalidKilled`

- `Boolean isOverrideKillCnt`

- `Int32 overrideKillCnt`

- `Single delayToBorn`

- `Boolean isInEnemySide`

- `Single mass`

- `Rigidbody2D rigidbody2D`

- `AttackWrapper attackWrapper`

- `CombatWrapper combatWrapper`

- `Ability lastAttackOrCombatAbility`

- `Ability mainCombatAbility`

- `EnemySkill lastSkill`

- `String deadEffect`

- `String startEffect`

- `Single moveSpdTotalScale`

- `TracePositionCursor traceTargetCursor`

- `BaseTraceTargetAbility traceTargetAbility`

- `Single frictionFactor`

- `Boolean disableSwitchFaceByMove`

- `Boolean scaleMoveBySpeed`

- `Route originRoute`

- `Int32 originCursorIndex`


## Methods

- `Direction get_lastMoveDirection()`

- `Vector2 get_lastMoveDirVec()`

- `Void set_lastMoveDirVec(Vector2)`

- `SpecialBlockCondition get_specialBlockCondition()`

- `Boolean get_disableAppearTweenColor()`

- `Void set_disableAppearTweenColor(Boolean)`

- `FearController get_fearController()`

- `Void SetSpecialBlockCondition(Type, BuffKeyPair[], String[])`

- `Void SetEnemyCombatWrapperInterrupted()`

- `BodyDirectionPolicy get_bodyDirectionPolicy()`

- `Ability get_attackAbilityCasted()`

- `Ability get_combatAbilityCasted()`

- `Void set_combatAbilityCasted(Ability)`

- `UInt32 get_hostUid()`

- `Void set_hostUid(UInt32)`

- `Collider2D get_nonTriggerCollider()`

- `MoveController get_moveController()`

- `Single get_distToExit()`

- `Single get_distToExitPrecise()`

- `Boolean get_uiHideFlag()`

- `Boolean get_hideHp()`

- `Boolean get_alwaysHideHp()`

- `Boolean get_showSpUIFlag()`

- `Boolean get_alwaysShowHpFlag()`

- `Void set_alwaysShowHpFlag(Boolean)`

- `Boolean get_fogHideUIFlag()`

- `Void set_fogHideUIFlag(Boolean)`

- `Single get_spineHeight()`

- `Single get_originHeight()`

- `Boolean get_disableUIHud()`

- `Void set_disableUIHud(Boolean)`

- `Single get_totalMoveDist()`

- `Character get_blocker()`

- `Int32 get_lifePointReduce()`

- `Void set_lifePointReduce(Int32)`

- `Single get_defaultRangeRadius()`

- `Void set_defaultRangeRadius(Single)`

- `MotionMode get_essentialMotionMode()`

- `EnemyData get_data()`

- `Void set_data(EnemyData)`

- `Boolean get_isInMoveState()`

- `Boolean get_isInBlinkState()`

- `Boolean get_isInBornState()`

- `Boolean get_isBoss()`

- `IDrawableRange get_locateRange()`

- `Int32 get_blockVolume()`

- `Int32 get_blockVolumeAddition()`

- `Void set_blockVolumeAddition(Int32)`

- `Boolean get_showSpAsBulletMode()`

- `Boolean get_disableBulletSp()`

- `Boolean get_combatable()`

- `Vector2 get_footMapPosition()`

- `Vector2 get_offsetMapPosition()`

- `Vector2 get_stableBlockPosition()`

- `Options get_options()`

- `Void set_options(Options)`

- `Void DontCountAsFinished()`

- `Void MarkUnharmful()`

- `Void DontLogInEnemyStatsWhenFinished()`

- `Boolean get_isInvalidKilled()`

- `Boolean get_isOverrideKillCnt()`

- `Int32 get_overrideKillCnt()`

- `Single get_delayToBorn()`

- `Boolean get_isInEnemySide()`

- `Single get_mass()`

- `Rigidbody2D get_rigidbody2D()`

- `Void set_rigidbody2D(Rigidbody2D)`

- `AttackWrapper get_attackWrapper()`

- `Void set_attackWrapper(AttackWrapper)`

- `CombatWrapper get_combatWrapper()`

- `Void set_combatWrapper(CombatWrapper)`

- `Ability get_lastAttackOrCombatAbility()`

- `Ability get_mainCombatAbility()`

- `EnemySkill get_lastSkill()`

- `String get_deadEffect()`

- `String get_startEffect()`

- `Single get_moveSpdTotalScale()`

- `TracePositionCursor get_traceTargetCursor()`

- `BaseTraceTargetAbility get_traceTargetAbility()`

- `Void set_traceTargetAbility(BaseTraceTargetAbility)`

- `Single get_frictionFactor()`

- `Boolean get_disableSwitchFaceByMove()`

- `Void set_disableSwitchFaceByMove(Boolean)`

- `Boolean get_scaleMoveBySpeed()`

- `Void UpdateFrictionFactor(Single)`

- `Void RestoreFrictionFactor()`

- `Void _UpdateFrictionFactorAdditional(Single)`

- `Boolean RestoreCachedRoute()`

- `Boolean TryReassignRouteAndCacheOrigin(Route)`

- `Route get_originRoute()`

- `Int32 get_originCursorIndex()`

- `Void InterruptLastAbilityIfNot(Boolean)`

- `Boolean TriggerEnemySkill(Ability, Entity, EnemySkill, Boolean)`

- `Boolean CheckEnemySkillAffecting()`

- `Boolean CheckBlockable(Character)`

- `Boolean CheckBlockableWithoutCheckRange(Character)`

- `Boolean _CheckMotionModeBlockable(Character)`

- `Boolean _CheckSpecialBlockCondition(Character)`

- `Boolean RegisterBlocker(Character, Vector2)`

- `Void UnregisterBlocker(Character)`

- `Void OnBlockVolumeChanged()`

- `Void DisableCurrentStillPull()`

- `Boolean StillPull(BObject, Vector2, Single)`

- `Boolean TryEarlyStopPull(BObject)`

- `Boolean CheckReadyToFallDown()`

- `Void PlayMoveAnim()`

- `Void _RemoveInvalidPullSources()`

- `Boolean Blink(Single, Single, Boolean, Boolean, Boolean)`

- `Boolean Blink(GridPosition)`

- `Void BlinkWithoutSwitchToBlinkState(Single, Boolean)`

- `Void BlinkToGridPositionWithoutSwitchToBlinkState(GridPosition)`

- `Boolean TryGetDistanceToNextCheckpoint(out)`

- `Boolean TryGetDistanceToMapPosInCheckpointsAhead(GridPosition, out)`

- `Void ClearTraceIfExist()`

- `Void ReassignRoute(Route, Int32)`

- `Void ReconstructRoute(GridPosition, CheckpointData[])`

- `Void ReconstructRouteWithTargetGridMove(GridPosition)`

- `Void TransportInternal(Vector2, Route, Int32, Vector2)`

- `Boolean TryGetNextAppearCheckpoint(out, out)`

- `Void SwitchToDeadState()`

- `Void InitFaceTo()`

- `Void SetBodyDirectionWithPolicy(Vector2, Boolean)`

- `Void _MoveToFixedDirection(Vector2, FP)`

- `Vector2 _MoveByCursor(DirectionCursor, Single, out)`

- `Void ReleaseFromBlocker()`

- `Void _ResetPhysicsStatus()`

- `Void _ReactivateMainTriggerCollider()`

- `Boolean _SearchAttackTarget()`

- `Void _InitCurrentTile()`

- `Boolean _CheckTileCanExit(Tile)`

- `Void UpdateCurrentTile(Boolean)`

- `EnemySkill TryGetFirstAttachedSkill(String)`

- `Void _UpdateCurrentTile(Boolean)`

- `Void SetHeightDirectly(Single, Boolean)`

- `Void SetEnemyHeightOffset(Single, Boolean, Boolean)`

- `Void AdjustEnemyHeightByInitial(Single, Boolean)`

- `Void SetHeightImmediatelyChange()`

- `Void SetEnemyLevitateOffset(Single)`

- `Boolean IsHanging()`

- `Boolean IsStayStill()`

- `Void ModifySpUIFlag(Boolean)`

- `Void _MoveToBlockPosition(Vector2)`

- `Void FaceToCalculateDirection(Vector2)`

- `Void ReachExit()`

- `Vector2 _CalculateFaceDirection(Vector2)`

- `Boolean _CheckUseIdForAudioSignal(String)`

- `Void _AssignData(EnemyData, EnemyHandBookData)`

- `Void _AssignSkill(IList`1)`

- `Void _AssignTalent(Blackboard)`

- `Int32 _GetDefaultModeIndex()`

- `Boolean TryFindFirstEnabledEnemySkill(String, out, Boolean)`

- `Void OnTickAfterDead(FP)`

- `Void OnBeforeAttack(Ability, Boolean)`

- `Void OnAfterAttack(Ability, Boolean, FinishReason)`

- `Boolean CheckTargetInAttackRange(Entity)`

- `Void _InitPhysics()`

- `Boolean TryUpdateEnemySkillSelector(String, Boolean, String, FP)`

- `SpData _GenerateSpData(EnemyData)`

- `Void <_MoveToBlockPosition>b__414_0(Vector2)`

- `Void <_MoveToBlockPosition>b__414_1()`

- `Vector2 <_MoveToBlockPosition>b__414_2()`

- `Void <_MoveToBlockPosition>b__414_3(Vector2)`

- `Void <_MoveToBlockPosition>b__414_4()`

- `SourceApplyWay <>xLuaBaseProxy_get_allApplyWay()`

- `FP <>xLuaBaseProxy_get_maxEp()`

- `UnitMode <>xLuaBaseProxy_get_defaultMode()`

- `Boolean <>xLuaBaseProxy_get_hasCombat()`

- `Boolean <>xLuaBaseProxy_get_isMovingBySelf()`

- `Int32 <>xLuaBaseProxy_get_initState()`

- `Single <>xLuaBaseProxy_get_delayToRecycle()`

- `Void <>xLuaBaseProxy_Born()`

- `Single <>xLuaBaseProxy_GetModeRangeRadius(UnitMode)`

- `AbstractBasicAttack <>xLuaBaseProxy_GetCurrentAttackOrCombatAbility()`

- `Boolean <>xLuaBaseProxy_TryHookAudio(String, String, out, out)`

- `Entity <>xLuaBaseProxy_FetchHost()`

- `Void <>xLuaBaseProxy_PopulateSnapshotToHashBuilder(HashCodeBuilder)`

- `Void <>xLuaBaseProxy_PopulateSnapshotToStrBuilder(StringBuilder)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_ChangePathMotionMode(MotionMode)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnBorn()`

- `Void <>xLuaBaseProxy_OnReborn(RebornData)`

- `Void <>xLuaBaseProxy_SetBodyAndFaceDirection(Vector2, Boolean)`

- `Boolean <>xLuaBaseProxy_TryIgnoreEffect(String)`

- `Void <>xLuaBaseProxy_OnFaceChanged(Vector2, Vector2, Boolean, Boolean)`

- `Void <>xLuaBaseProxy_OnDisappearChanged(Boolean)`

- `Void <>xLuaBaseProxy_OnSwitchMode(UnitMode, UnitMode, Boolean)`

- `Void <>xLuaBaseProxy_OnHpZero(Boolean, Boolean)`

- `Void <>xLuaBaseProxy_OnAttributeDirty(AttributeType, FP)`

- `Void <>xLuaBaseProxy_FinishMe(FinishReason)`

- `Void <>xLuaBaseProxy_DoFakeDeath(RebornData)`

- `Void <>xLuaBaseProxy_DoReborn(RebornData)`

- `Void <>xLuaBaseProxy_SetHeight(Single)`

- `Void <>xLuaBaseProxy_FinishWithReachExit(Boolean)`

- `Blackboard <>xLuaBaseProxy_GetAttackBlackboard(UnitMode)`

- `Void <>xLuaBaseProxy_OnAwake()`

- `Void <>xLuaBaseProxy_OnInit(Single)`

- `Void <>xLuaBaseProxy_OnFinish(FinishReason)`

- `Void <>xLuaBaseProxy_OnRecycle()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_ChangeMotionMode(MotionMode)`

- `Void <>xLuaBaseProxy_ResetMotionMode()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Enemy : Unit, IMovable, ILocatable
{
	private const Int32 UPDATE_POS_TICK; // 0x0
	private const Single BLOCKING_TWEEN_DURATION; // 0x0
	protected const Single HATRED_VALUE_GAP; // 0x0
	private const Single MIN_BLINK_DISTANCE; // 0x0
	protected Vector2 m_lastMoveDirVec; // 0x250
	private static List`1 s_sharedList; // 0x0
	private SideTypeIndex _sideTypeIndex; // 0x258
	protected Range _locateRange; // 0x260
	private Boolean _isFixedRotation; // 0x268
	private BodyDirectionPolicy _bodyDirectionPolicy; // 0x26c
	private Boolean _scaleMoveBySpeed; // 0x270
	private Vector2 _scaleMoveAnimationRange; // 0x274
	private Boolean _showSpAsBulletMode; // 0x27c
	private List`1 _hideBulletSpModes; // 0x280
	private Boolean _alwaysShowHp; // 0x288
	private Boolean _alwaysHideHp; // 0x289
	private Boolean _keepMoveAnimScale; // 0x28a
	private Boolean _useSpecificDeadAnim; // 0x28b
	private Boolean _useSpecificReachExitAnim; // 0x28c
	private Boolean _disableBornTweenColor; // 0x28d
	private Single _height; // 0x290
	private Single _delayToBorn; // 0x294
	private String _startEffect; // 0x298
	private String _deadEffect; // 0x2a0
	private Int32 _blockVolume; // 0x2a8
	private SpecialBlockCondition _specialBlockCondition; // 0x2b0
	private Boolean _dontSetEnemyFaceByCursorWhenBorn; // 0x2b8
	private Boolean _idleWhenBorn; // 0x2b9
	private Boolean _disableTriggerWhenDisappear; // 0x2ba
	private Boolean _canNotExit; // 0x2bb
	private Boolean _hideShadowOnReset; // 0x2bc
	private Int32 m_defaultModeIndex; // 0x2c0
	private Single m_totalMoveDist; // 0x2c4
	protected Boolean m_blinkHideUIFlag; // 0x2c8
	protected Boolean m_fogHideUIFlag; // 0x2c9
	protected Boolean m_showSpUIFlag; // 0x2ca
	protected Boolean m_alwaysShowHpFlag; // 0x2cb
	protected Tile m_currentTile; // 0x2d0
	protected Tile m_oldTile; // 0x2d8
	private DirectionCursor m_cursor; // 0x2e0
	private Route m_cachedRoute; // 0x2e8
	private Int32 m_cachedCursorIndex; // 0x2f0
	private BaseTraceTargetAbility m_traceTargetAbility; // 0x2f8
	private TracePositionCursor m_traceTargetCursor; // 0x300
	protected MoveController m_moveController; // 0x308
	private ObjectPtr`1 m_blocker; // 0x310
	private PeriodicTicker m_updatePosTicker; // 0x320
	private HeightController m_heightCtrl; // 0x328
	private SpineAnimator m_spineAnimator; // 0x330
	private SpecialBlockCondition m_changealeSpecialBlockCondition; // 0x338
	private Boolean m_disableAppearTweenColor; // 0x340
	private FearController m_fearController; // 0x348
	private ITweenHandler m_blockTween; // 0x350
	private Tween m_tweenToRecycle; // 0x358
	private Vector2 m_blockPosition; // 0x360
	private Vector2 m_contDirAfterEnd; // 0x368
	private Vector2 m_posInLastFrame; // 0x370
	private Collider2D m_nonTriggerCollider; // 0x378
	private Collider2D m_mainTriggerCollider; // 0x380
	public FP m_mainTriggerColliderRadius; // 0x388
	private ListSet`1 m_pullSources; // 0x390
	private ListSet`1 m_disabledPullSources; // 0x398
	private List`1 m_managedProjectiles; // 0x3a0
	private EnemySkill[] m_allSkills; // 0x3a8
	private RebornData m_rebornData; // 0x3b0
	private Boolean m_isInvalidKilled; // 0x3f8
	private Boolean m_isOverrideKillCnt; // 0x3f9
	private Int32 m_overrideKillCnt; // 0x3fc
	private Int32 m_blockVolumeAddition; // 0x400
	protected Boolean m_disableSwitchFaceByMove; // 0x404
	private FP m_createdTime; // 0x408
	private Single m_delayToRecycle; // 0x410
	protected List`1 m_ExtraLogIds; // 0x418
	private UInt32 m_hostUid; // 0x420
	private List`1 m_skills; // 0x428
	private List`1 m_currentSubTiles; // 0x430
	private Ability m_attackAbilityCasted; // 0x438
	private Ability m_combatAbilityCasted; // 0x440
	private FP m_combatNextEscapeTime; // 0x448
	private Boolean <disableUIHud>k__BackingField; // 0x450
	private Int32 <lifePointReduce>k__BackingField; // 0x454
	private Single <defaultRangeRadius>k__BackingField; // 0x458
	private EnemyData <data>k__BackingField; // 0x460
	private Options <options>k__BackingField; // 0x468
	private Rigidbody2D <rigidbody2D>k__BackingField; // 0x498
	private AttackWrapper <attackWrapper>k__BackingField; // 0x4a0
	private CombatWrapper <combatWrapper>k__BackingField; // 0x4a8
	private const Single DEFAULT_FRICTION_FACTOR; // 0x0
	private Single m_frictionFactor; // 0x4b0
	private Single m_frictionFactorAdditional; // 0x4b4
	private static DelegateBridge __Hotfix0_get_lastMoveDirection; // 0x8
	private static DelegateBridge __Hotfix0_get_lastMoveDirVec; // 0x10
	private static DelegateBridge __Hotfix0_set_lastMoveDirVec; // 0x18
	private static DelegateBridge __Hotfix0_get_specialBlockCondition; // 0x20
	private static DelegateBridge __Hotfix0_get_disableAppearTweenColor; // 0x28
	private static DelegateBridge __Hotfix0_set_disableAppearTweenColor; // 0x30
	private static DelegateBridge __Hotfix0_get_allApplyWay; // 0x38
	private static DelegateBridge __Hotfix0_get_fearController; // 0x40
	private static DelegateBridge __Hotfix0_SetSpecialBlockCondition; // 0x48
	private static DelegateBridge __Hotfix0_SetEnemyCombatWrapperInterrupted; // 0x50
	private static DelegateBridge __Hotfix0_get_ColliderRadius; // 0x58
	private static DelegateBridge __Hotfix0_get_onlyCollideWhenUnbalance; // 0x60
	private static DelegateBridge __Hotfix0_get_bodyDirectionPolicy; // 0x68
	private static DelegateBridge __Hotfix0_get_attackAbilityCasted; // 0x70
	private static DelegateBridge __Hotfix0_get_combatAbilityCasted; // 0x78
	private static DelegateBridge __Hotfix0_set_combatAbilityCasted; // 0x80
	private static DelegateBridge __Hotfix0_get_hostUid; // 0x88
	private static DelegateBridge __Hotfix0_set_hostUid; // 0x90
	private static DelegateBridge __Hotfix0_get_nonTriggerCollider; // 0x98
	private static DelegateBridge __Hotfix0_get_moveController; // 0xa0
	private static DelegateBridge __Hotfix0_get_distToExit; // 0xa8
	private static DelegateBridge __Hotfix0_get_distToExitPrecise; // 0xb0
	private static DelegateBridge __Hotfix0_get_uiHideFlag; // 0xb8
	private static DelegateBridge __Hotfix0_get_hideHp; // 0xc0
	private static DelegateBridge __Hotfix0_get_alwaysHideHp; // 0xc8
	private static DelegateBridge __Hotfix0_get_showSpUIFlag; // 0xd0
	private static DelegateBridge __Hotfix0_get_alwaysShowHpFlag; // 0xd8
	private static DelegateBridge __Hotfix0_set_alwaysShowHpFlag; // 0xe0
	private static DelegateBridge __Hotfix0_get_fogHideUIFlag; // 0xe8
	private static DelegateBridge __Hotfix0_set_fogHideUIFlag; // 0xf0
	private static DelegateBridge __Hotfix0_get_spineHeight; // 0xf8
	private static DelegateBridge __Hotfix0_get_originHeight; // 0x100
	private static DelegateBridge __Hotfix0_get_disableUIHud; // 0x108
	private static DelegateBridge __Hotfix0_set_disableUIHud; // 0x110
	private static DelegateBridge __Hotfix0_get_disableUIUnitHud; // 0x118
	private static DelegateBridge __Hotfix0_get_hatred; // 0x120
	private static DelegateBridge __Hotfix0_get_totalMoveDist; // 0x128
	private static DelegateBridge __Hotfix0_get_blocker; // 0x130
	private static DelegateBridge __Hotfix0_get_managedProjectiles; // 0x138
	private static DelegateBridge __Hotfix0_get_rootTile; // 0x140
	private static DelegateBridge __Hotfix0_get_oldTile; // 0x148
	private static DelegateBridge __Hotfix0_get_rootSubTiles; // 0x150
	private static DelegateBridge __Hotfix0_get_lifePointReduce; // 0x158
	private static DelegateBridge __Hotfix0_set_lifePointReduce; // 0x160
	private static DelegateBridge __Hotfix0_get_defaultRangeRadius; // 0x168
	private static DelegateBridge __Hotfix0_set_defaultRangeRadius; // 0x170
	private static DelegateBridge __Hotfix0_get_massLevel; // 0x178
	private static DelegateBridge __Hotfix0_get_maxEp; // 0x180
	private static DelegateBridge __Hotfix0_get_essentialMotionMode; // 0x188
	private static DelegateBridge __Hotfix0_get_enemyTags; // 0x190
	private static DelegateBridge __Hotfix0_get_data; // 0x198
	private static DelegateBridge __Hotfix0_set_data; // 0x1a0
	private static DelegateBridge __Hotfix0_get_isUnbalanced; // 0x1a8
	private static DelegateBridge __Hotfix0_get_isInAttackState; // 0x1b0
	private static DelegateBridge __Hotfix0_get_isInCombatState; // 0x1b8
	private static DelegateBridge __Hotfix0_get_isInRebornState; // 0x1c0
	private static DelegateBridge __Hotfix0_get_isInMoveState; // 0x1c8
	private static DelegateBridge __Hotfix0_get_isInBlinkState; // 0x1d0
	private static DelegateBridge __Hotfix0_get_isInBornState; // 0x1d8
	private static DelegateBridge __Hotfix0_get_isInDyingState; // 0x1e0
	private static DelegateBridge __Hotfix0_get_isBoss; // 0x1e8
	private static DelegateBridge __Hotfix0_get_isGiantBoss; // 0x1f0
	private static DelegateBridge __Hotfix0_get_isEnemyLikeNeutral; // 0x1f8
	private static DelegateBridge __Hotfix0_get_locateRange; // 0x200
	private static DelegateBridge __Hotfix0_get_blockVolume; // 0x208
	private static DelegateBridge __Hotfix0_get_blockVolumeAddition; // 0x210
	private static DelegateBridge __Hotfix0_set_blockVolumeAddition; // 0x218
	private static DelegateBridge __Hotfix0_get_showSpAsBulletMode; // 0x220
	private static DelegateBridge __Hotfix0_get_disableBulletSp; // 0x228
	private static DelegateBridge __Hotfix0_get_defaultMode; // 0x230
	private static DelegateBridge __Hotfix0_get_hasCombat; // 0x238
	private static DelegateBridge __Hotfix0_get_combatable; // 0x240
	private static DelegateBridge __Hotfix0_get_isInCombat; // 0x248
	private static DelegateBridge __Hotfix0_get_isMovingBySelf; // 0x250
	private static DelegateBridge __Hotfix0_get_footMapPosition; // 0x258
	private static DelegateBridge __Hotfix0_get_offsetMapPosition; // 0x260
	private static DelegateBridge __Hotfix0_get_stableBlockPosition; // 0x268
	private static DelegateBridge __Hotfix0_get_options; // 0x270
	private static DelegateBridge __Hotfix0_set_options; // 0x278
	private static DelegateBridge __Hotfix0_DontCountAsFinished; // 0x280
	private static DelegateBridge __Hotfix0_MarkUnharmful; // 0x288
	private static DelegateBridge __Hotfix0_DontLogInEnemyStatsWhenFinished; // 0x290
	private static DelegateBridge __Hotfix0_get_isInvalidKilled; // 0x298
	private static DelegateBridge __Hotfix0_get_isOverrideKillCnt; // 0x2a0
	private static DelegateBridge __Hotfix0_get_overrideKillCnt; // 0x2a8
	private static DelegateBridge __Hotfix0_get_stateMachine; // 0x2b0
	private static DelegateBridge __Hotfix0_get_isFixedRotation; // 0x2b8
	private static DelegateBridge __Hotfix0_get_initState; // 0x2c0
	private static DelegateBridge __Hotfix0_get_delayToRecycle; // 0x2c8
	private static DelegateBridge __Hotfix0_get_sideTypeIndex; // 0x2d0
	private static DelegateBridge __Hotfix0_get_delayToBorn; // 0x2d8
	private static DelegateBridge __Hotfix0_get_createdTime; // 0x2e0
	private static DelegateBridge __Hotfix0_get_isInEnemySide; // 0x2e8
	private static DelegateBridge __Hotfix0_get_mass; // 0x2f0
	private static DelegateBridge __Hotfix0_get_velocity; // 0x2f8
	private static DelegateBridge __Hotfix0_set_velocity; // 0x300
	private static DelegateBridge __Hotfix0_get_rigidbody2D; // 0x308
	private static DelegateBridge __Hotfix0_set_rigidbody2D; // 0x310
	private static DelegateBridge __Hotfix0_get_attackWrapper; // 0x318
	private static DelegateBridge __Hotfix0_set_attackWrapper; // 0x320
	private static DelegateBridge __Hotfix0_get_combatWrapper; // 0x328
	private static DelegateBridge __Hotfix0_set_combatWrapper; // 0x330
	private static DelegateBridge __Hotfix0_get_lastAttackOrCombatAbility; // 0x338
	private static DelegateBridge __Hotfix0_get_mainCombatAbility; // 0x340
	private static DelegateBridge __Hotfix0_get_lastSkill; // 0x348
	private static DelegateBridge __Hotfix0_get_deadEffect; // 0x350
	private static DelegateBridge __Hotfix0_get_startEffect; // 0x358
	private static DelegateBridge __Hotfix0_get_moveSpdTotalScale; // 0x360
	private static DelegateBridge __Hotfix0_get_traceTargetCursor; // 0x368
	private static DelegateBridge __Hotfix0_get_cursor; // 0x370
	private static DelegateBridge __Hotfix0_get_moveCursor; // 0x378
	private static DelegateBridge __Hotfix0_get_traceTargetAbility; // 0x380
	private static DelegateBridge __Hotfix0_set_traceTargetAbility; // 0x388
	private static DelegateBridge __Hotfix0_get_usingTraceCursor; // 0x390
	private static DelegateBridge __Hotfix0_get_traceTarget; // 0x398
	private static DelegateBridge __Hotfix0_get_frictionFactor; // 0x3a0
	private static DelegateBridge __Hotfix0_get_preloadCnt; // 0x3a8
	private static DelegateBridge __Hotfix0_get_disableSwitchFaceByMove; // 0x3b0
	private static DelegateBridge __Hotfix0_set_disableSwitchFaceByMove; // 0x3b8
	private static DelegateBridge __Hotfix0_get_scaleMoveBySpeed; // 0x3c0
	private static DelegateBridge __Hotfix0_get_updateHpColor; // 0x3c8
	private static DelegateBridge __Hotfix0_get_hpColor; // 0x3d0
	private static DelegateBridge __Hotfix0_UpdateFrictionFactor; // 0x3d8
	private static DelegateBridge __Hotfix0_RestoreFrictionFactor; // 0x3e0
	private static DelegateBridge __Hotfix0__UpdateFrictionFactorAdditional; // 0x3e8
	private static DelegateBridge __Hotfix0_RestoreCachedRoute; // 0x3f0
	private static DelegateBridge __Hotfix0_TryReassignRouteAndCacheOrigin; // 0x3f8
	private static DelegateBridge __Hotfix0_get_originRoute; // 0x400
	private static DelegateBridge __Hotfix0_get_originCursorIndex; // 0x408
	private static DelegateBridge __Hotfix0_InterruptLastAbilityIfNot; // 0x410
	private static DelegateBridge __Hotfix0_Spawn; // 0x418
	private static DelegateBridge __Hotfix0_Born; // 0x420
	private static DelegateBridge __Hotfix0_GetModeRangeRadius; // 0x428
	private static DelegateBridge __Hotfix0_GetCurrentAttackOrCombatAbility; // 0x430
	private static DelegateBridge __Hotfix0_PlayAudioSignal; // 0x438
	private static DelegateBridge __Hotfix0_TryHookAudio; // 0x440
	private static DelegateBridge __Hotfix0_CheckHasFilterTag; // 0x448
	private static DelegateBridge __Hotfix0_TriggerEnemySkill; // 0x450
	private static DelegateBridge __Hotfix0_CheckEnemySkillAffecting; // 0x458
	private static DelegateBridge __Hotfix0_FetchHost; // 0x460
	private static DelegateBridge __Hotfix0_CheckBlockable; // 0x468
	private static DelegateBridge __Hotfix0_CheckBlockableWithoutCheckRange; // 0x470
	private static DelegateBridge __Hotfix0__CheckMotionModeBlockable; // 0x478
	private static DelegateBridge __Hotfix0__CheckSpecialBlockCondition; // 0x480
	private static DelegateBridge __Hotfix0_RegisterBlocker; // 0x488
	private static DelegateBridge __Hotfix0_UnregisterBlocker; // 0x490
	private static DelegateBridge __Hotfix0_OnBlockVolumeChanged; // 0x498
	private static DelegateBridge __Hotfix0_KnockBack; // 0x4a0
	private static DelegateBridge __Hotfix0_DisableCurrentStillPull; // 0x4a8
	private static DelegateBridge __Hotfix0_BeginPull; // 0x4b0
	private static DelegateBridge __Hotfix0_StillPull; // 0x4b8
	private static DelegateBridge __Hotfix0_TryEarlyStopPull; // 0x4c0
	private static DelegateBridge __Hotfix0_EndPull; // 0x4c8
	private static DelegateBridge __Hotfix0_FallDown; // 0x4d0
	private static DelegateBridge __Hotfix0_CheckReadyToFallDown; // 0x4d8
	private static DelegateBridge __Hotfix0_PlayMoveAnim; // 0x4e0
	private static DelegateBridge __Hotfix0__RemoveInvalidPullSources; // 0x4e8
	private static DelegateBridge __Hotfix0_Blink; // 0x4f0
	private static DelegateBridge __Hotfix1_Blink; // 0x4f8
	private static DelegateBridge __Hotfix0_BlinkWithoutSwitchToBlinkState; // 0x500
	private static DelegateBridge __Hotfix0_BlinkToGridPositionWithoutSwitchToBlinkState; // 0x508
	private static DelegateBridge __Hotfix0_TryGetDistanceToNextCheckpoint; // 0x510
	private static DelegateBridge __Hotfix0_TryGetDistanceToMapPosInCheckpointsAhead; // 0x518
	private static DelegateBridge __Hotfix0_ClearTraceIfExist; // 0x520
	private static DelegateBridge __Hotfix0_ReassignRoute; // 0x528
	private static DelegateBridge __Hotfix0_ReconstructRoute; // 0x530
	private static DelegateBridge __Hotfix0_ReconstructRouteWithTargetGridMove; // 0x538
	private static DelegateBridge __Hotfix0_TransportInternal; // 0x540
	private static DelegateBridge __Hotfix0_TryGetNextAppearCheckpoint; // 0x548
	private static DelegateBridge __Hotfix0_SwitchToDeadState; // 0x550
	private static DelegateBridge __Hotfix0_PopulateSnapshotToHashBuilder; // 0x558
	private static DelegateBridge __Hotfix0_PopulateSnapshotToStrBuilder; // 0x560
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x568
	private static DelegateBridge __Hotfix0_Init; // 0x570
	private static DelegateBridge __Hotfix0_ChangePathMotionMode; // 0x578
	private static DelegateBridge __Hotfix0_OnReset; // 0x580
	private static DelegateBridge __Hotfix0_OnBorn; // 0x588
	private static DelegateBridge __Hotfix0_InitFaceTo; // 0x590
	private static DelegateBridge __Hotfix0_OnReborn; // 0x598
	private static DelegateBridge __Hotfix0_SetBodyAndFaceDirection; // 0x5a0
	private static DelegateBridge __Hotfix0_TryIgnoreEffect; // 0x5a8
	private static DelegateBridge __Hotfix0_OnFaceChanged; // 0x5b0
	private static DelegateBridge __Hotfix0_SetBodyDirectionWithPolicy; // 0x5b8
	private static DelegateBridge __Hotfix0_OnDisappearChanged; // 0x5c0
	private static DelegateBridge __Hotfix0_OnSwitchMode; // 0x5c8
	private static DelegateBridge __Hotfix0_OnHpZero; // 0x5d0
	private static DelegateBridge __Hotfix0_OnAttributeDirty; // 0x5d8
	private static DelegateBridge __Hotfix0_ConstructStateMachine; // 0x5e0
	private static DelegateBridge __Hotfix0_FinishMe; // 0x5e8
	private static DelegateBridge __Hotfix0_DoFakeDeath; // 0x5f0
	private static DelegateBridge __Hotfix0_DoReborn; // 0x5f8
	private static DelegateBridge __Hotfix0__MoveByRoute; // 0x600
	private static DelegateBridge __Hotfix0__MoveInFearArea; // 0x608
	private static DelegateBridge __Hotfix0__MoveToFixedDirection; // 0x610
	private static DelegateBridge __Hotfix0__MoveByCursor; // 0x618
	private static DelegateBridge __Hotfix0_ReleaseFromBlocker; // 0x620
	private static DelegateBridge __Hotfix0__ResetPhysicsStatus; // 0x628
	private static DelegateBridge __Hotfix0__ReactivateMainTriggerCollider; // 0x630
	private static DelegateBridge __Hotfix0__SearchAttackTarget; // 0x638
	private static DelegateBridge __Hotfix0__InitCurrentTile; // 0x640
	private static DelegateBridge __Hotfix0__CheckTileCanExit; // 0x648
	private static DelegateBridge __Hotfix0_UpdateCurrentTile; // 0x650
	private static DelegateBridge __Hotfix0_TryGetFirstAttachedSkill; // 0x658
	private static DelegateBridge __Hotfix0__UpdateCurrentTile; // 0x660
	private static DelegateBridge __Hotfix0_SetHeightDirectly; // 0x668
	private static DelegateBridge __Hotfix0_SetHeight; // 0x670
	private static DelegateBridge __Hotfix0_SetEnemyHeightOffset; // 0x678
	private static DelegateBridge __Hotfix0_AdjustEnemyHeightByInitial; // 0x680
	private static DelegateBridge __Hotfix0_SetHeightImmediatelyChange; // 0x688
	private static DelegateBridge __Hotfix0_SetEnemyLevitateOffset; // 0x690
	private static DelegateBridge __Hotfix0_IsHanging; // 0x698
	private static DelegateBridge __Hotfix0_IsStayStill; // 0x6a0
	private static DelegateBridge __Hotfix0_OnRootTileChanged; // 0x6a8
	private static DelegateBridge __Hotfix0_PlayUnbalanceAnimation; // 0x6b0
	private static DelegateBridge __Hotfix0_ModifySpUIFlag; // 0x6b8
	private static DelegateBridge __Hotfix0__MoveToBlockPosition; // 0x6c0
	private static DelegateBridge __Hotfix0_FaceToCalculateDirection; // 0x6c8
	private static DelegateBridge __Hotfix0_ReachExit; // 0x6d0
	private static DelegateBridge __Hotfix0_FinishWithReachExit; // 0x6d8
	private static DelegateBridge __Hotfix0__CalculateFaceDirection; // 0x6e0
	private static DelegateBridge __Hotfix0__CheckUseIdForAudioSignal; // 0x6e8
	private static DelegateBridge __Hotfix0__AssignData; // 0x6f0
	private static DelegateBridge __Hotfix0__AssignSkill; // 0x6f8
	private static DelegateBridge __Hotfix0__AssignTalent; // 0x700
	private static DelegateBridge __Hotfix0__GetDefaultModeIndex; // 0x708
	private static DelegateBridge __Hotfix0_GetAttackBlackboard; // 0x710
	private static DelegateBridge __Hotfix0_TryFindFirstEnabledEnemySkill; // 0x718
	private static DelegateBridge __Hotfix0_OnAwake; // 0x720
	private static DelegateBridge __Hotfix0_OnInit; // 0x728
	private static DelegateBridge __Hotfix0_OnFinish; // 0x730
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x738
	private static DelegateBridge __Hotfix0_OnTick; // 0x740
	private static DelegateBridge __Hotfix0_ClearStaticVariables; // 0x748
	private static DelegateBridge __Hotfix0_OnTickAfterDead; // 0x750
	private static DelegateBridge __Hotfix0_OnBeforeAttack; // 0x758
	private static DelegateBridge __Hotfix0_OnAfterAttack; // 0x760
	private static DelegateBridge __Hotfix0_CheckTargetInAttackRange; // 0x768
	private static DelegateBridge __Hotfix0__InitPhysics; // 0x770
	private static DelegateBridge __Hotfix0_TryUpdateEnemySkillSelector; // 0x778
	private static DelegateBridge __Hotfix0__GenerateSpData; // 0x780
	private static DelegateBridge __Hotfix0_ChangeMotionMode; // 0x788
	private static DelegateBridge __Hotfix0_ResetMotionMode; // 0x790
	private static DelegateBridge _c__Hotfix0_ctor; // 0x798

	public Direction lastMoveDirection { get; }
	public Vector2 lastMoveDirVec { get; set; }
	public SpecialBlockCondition specialBlockCondition { get; }
	public Boolean disableAppearTweenColor { get; set; }
	public override SourceApplyWay allApplyWay { get; }
	public FearController fearController { get; }
	public override FP ColliderRadius { get; }
	protected virtual Boolean onlyCollideWhenUnbalance { get; }
	public BodyDirectionPolicy bodyDirectionPolicy { get; }
	public Ability attackAbilityCasted { get; }
	public Ability combatAbilityCasted { get; set; }
	public UInt32 hostUid { get; set; }
	protected Collider2D nonTriggerCollider { get; }
	protected MoveController moveController { get; }
	public Single distToExit { get; }
	public Single distToExitPrecise { get; }
	public Boolean uiHideFlag { get; }
	public Boolean hideHp { get; }
	public Boolean alwaysHideHp { get; }
	public Boolean showSpUIFlag { get; }
	public Boolean alwaysShowHpFlag { get; set; }
	public Boolean fogHideUIFlag { get; set; }
	public Single spineHeight { get; }
	public Single originHeight { get; }
	public Boolean disableUIHud { get; set; }
	public virtual Boolean disableUIUnitHud { get; }
	public override FP hatred { get; }
	public Single totalMoveDist { get; }
	public Character blocker { get; }
	public override List`1 managedProjectiles { get; }
	public override Tile rootTile { get; }
	public override Tile oldTile { get; }
	public List`1 rootSubTiles { get; }
	public Int32 lifePointReduce { get; set; }
	public Single defaultRangeRadius { get; set; }
	public virtual Int32 massLevel { get; }
	public override FP maxEp { get; }
	public MotionMode essentialMotionMode { get; }
	public String[] enemyTags { get; }
	public EnemyData data { get; set; }
	public virtual Boolean isUnbalanced { get; }
	public override Boolean isInAttackState { get; }
	public override Boolean isInCombatState { get; }
	public override Boolean isInRebornState { get; }
	public Boolean isInMoveState { get; }
	public Boolean isInBlinkState { get; }
	public Boolean isInBornState { get; }
	public override Boolean isInDyingState { get; }
	public Boolean isBoss { get; }
	public virtual Boolean isGiantBoss { get; }
	public virtual Boolean isEnemyLikeNeutral { get; }
	public IDrawableRange locateRange { get; }
	public Int32 blockVolume { get; }
	public Int32 blockVolumeAddition { get; set; }
	public Boolean showSpAsBulletMode { get; }
	public Boolean disableBulletSp { get; }
	public override UnitMode defaultMode { get; }
	public override Boolean hasCombat { get; }
	public Boolean combatable { get; }
	public override Boolean isInCombat { get; }
	public override Boolean isMovingBySelf { get; }
	public Vector2 footMapPosition { get; }
	public Vector2 offsetMapPosition { get; }
	public Vector2 stableBlockPosition { get; }
	public Options options { get; set; }
	public Boolean isInvalidKilled { get; }
	public Boolean isOverrideKillCnt { get; }
	public Int32 overrideKillCnt { get; }
	protected HierachyStateMachine`3 stateMachine { get; }
	protected override Boolean isFixedRotation { get; }
	protected override Int32 initState { get; }
	protected override Single delayToRecycle { get; }
	protected virtual SideTypeIndex sideTypeIndex { get; }
	public Single delayToBorn { get; }
	public override FP createdTime { get; }
	public Boolean isInEnemySide { get; }
	public Single mass { get; }
	public virtual Vector2 velocity { get; set; }
	protected Rigidbody2D rigidbody2D { get; set; }
	protected AttackWrapper attackWrapper { get; set; }
	protected CombatWrapper combatWrapper { get; set; }
	public Ability lastAttackOrCombatAbility { get; }
	public Ability mainCombatAbility { get; }
	public EnemySkill lastSkill { get; }
	protected String deadEffect { get; }
	protected String startEffect { get; }
	protected Single moveSpdTotalScale { get; }
	public TracePositionCursor traceTargetCursor { get; }
	public virtual DirectionCursor cursor { get; }
	public virtual DirectionCursor moveCursor { get; }
	public BaseTraceTargetAbility traceTargetAbility { get; set; }
	public virtual Boolean usingTraceCursor { get; }
	public virtual Entity traceTarget { get; }
	public Single frictionFactor { get; }
	public virtual Int32 preloadCnt { get; }
	public Boolean disableSwitchFaceByMove { get; set; }
	private Boolean scaleMoveBySpeed { get; }
	public virtual Boolean updateHpColor { get; }
	public virtual Color hpColor { get; }
	public Route originRoute { get; }
	public Int32 originCursorIndex { get; }

	// RVA: 0x1bf7d88 VA: 0x759420fd88
	public Direction get_lastMoveDirection() { }
	// RVA: 0x1bf7e44 VA: 0x759420fe44
	public Vector2 get_lastMoveDirVec() { }
	// RVA: 0x1bf7ebc VA: 0x759420febc
	public Void set_lastMoveDirVec(Vector2 value) { }
	// RVA: 0x1bf7f54 VA: 0x759420ff54
	public SpecialBlockCondition get_specialBlockCondition() { }
	// RVA: 0x1bf7fd4 VA: 0x759420ffd4
	public Boolean get_disableAppearTweenColor() { }
	// RVA: 0x1bf804c VA: 0x759421004c
	public Void set_disableAppearTweenColor(Boolean value) { }
	// RVA: 0x1bf80dc VA: 0x75942100dc
	public override SourceApplyWay get_allApplyWay() { }
	// RVA: 0x1bf81dc VA: 0x75942101dc
	public FearController get_fearController() { }
	// RVA: 0x1bf8254 VA: 0x7594210254
	public Void SetSpecialBlockCondition(Type type, BuffKeyPair[] buffKeyPairs, String[] filterTags) { }
	// RVA: 0x1bf835c VA: 0x759421035c
	public Void SetEnemyCombatWrapperInterrupted() { }
	// RVA: 0x1bf8460 VA: 0x7594210460
	public override FP get_ColliderRadius() { }
	// RVA: 0x1bf84d8 VA: 0x75942104d8
	protected virtual Boolean get_onlyCollideWhenUnbalance() { }
	// RVA: 0x1bf8550 VA: 0x7594210550
	public BodyDirectionPolicy get_bodyDirectionPolicy() { }
	// RVA: 0x1bf85c8 VA: 0x75942105c8
	public Ability get_attackAbilityCasted() { }
	// RVA: 0x1bf8640 VA: 0x7594210640
	public Ability get_combatAbilityCasted() { }
	// RVA: 0x1bf86b8 VA: 0x75942106b8
	public Void set_combatAbilityCasted(Ability value) { }
	// RVA: 0x1bf874c VA: 0x759421074c
	public UInt32 get_hostUid() { }
	// RVA: 0x1bf87c4 VA: 0x75942107c4
	public Void set_hostUid(UInt32 value) { }
	// RVA: 0x1bf8914 VA: 0x7594210914
	protected Collider2D get_nonTriggerCollider() { }
	// RVA: 0x1bf898c VA: 0x759421098c
	protected MoveController get_moveController() { }
	// RVA: 0x1bf8a04 VA: 0x7594210a04
	public Single get_distToExit() { }
	// RVA: 0x1bf8ac4 VA: 0x7594210ac4
	public Single get_distToExitPrecise() { }
	// RVA: 0x1bf8b84 VA: 0x7594210b84
	public Boolean get_uiHideFlag() { }
	// RVA: 0x1bf8ca4 VA: 0x7594210ca4
	public Boolean get_hideHp() { }
	// RVA: 0x1bf8d64 VA: 0x7594210d64
	public Boolean get_alwaysHideHp() { }
	// RVA: 0x1bf8ddc VA: 0x7594210ddc
	public Boolean get_showSpUIFlag() { }
	// RVA: 0x1bf8e54 VA: 0x7594210e54
	public Boolean get_alwaysShowHpFlag() { }
	// RVA: 0x1bf8ecc VA: 0x7594210ecc
	public Void set_alwaysShowHpFlag(Boolean value) { }
	// RVA: 0x1bf8c2c VA: 0x7594210c2c
	public Boolean get_fogHideUIFlag() { }
	// RVA: 0x1bf8f5c VA: 0x7594210f5c
	public Void set_fogHideUIFlag(Boolean value) { }
	// RVA: 0x1bf8fec VA: 0x7594210fec
	public Single get_spineHeight() { }
	// RVA: 0x1bf9074 VA: 0x7594211074
	public Single get_originHeight() { }
	// RVA: 0x1bf90ec VA: 0x75942110ec
	public Boolean get_disableUIHud() { }
	// RVA: 0x1bf9164 VA: 0x7594211164
	public Void set_disableUIHud(Boolean value) { }
	// RVA: 0x1bf91f4 VA: 0x75942111f4
	public virtual Boolean get_disableUIUnitHud() { }
	// RVA: 0x1bf926c VA: 0x759421126c
	public override FP get_hatred() { }
	// RVA: 0x1bf93e4 VA: 0x75942113e4
	public Single get_totalMoveDist() { }
	// RVA: 0x1bf945c VA: 0x759421145c
	public Character get_blocker() { }
	// RVA: 0x1bf9524 VA: 0x7594211524
	public override List`1 get_managedProjectiles() { }
	// RVA: 0x1bf959c VA: 0x759421159c
	public override Tile get_rootTile() { }
	// RVA: 0x1bf9614 VA: 0x7594211614
	public override Tile get_oldTile() { }
	// RVA: 0x1bf968c VA: 0x759421168c
	public List`1 get_rootSubTiles() { }
	// RVA: 0x1bf9704 VA: 0x7594211704
	public Int32 get_lifePointReduce() { }
	// RVA: 0x1bf977c VA: 0x759421177c
	private Void set_lifePointReduce(Int32 value) { }
	// RVA: 0x1bf9808 VA: 0x7594211808
	public Single get_defaultRangeRadius() { }
	// RVA: 0x1bf9880 VA: 0x7594211880
	private Void set_defaultRangeRadius(Single value) { }
	// RVA: 0x1bf990c VA: 0x759421190c
	public virtual Int32 get_massLevel() { }
	// RVA: 0x1bf999c VA: 0x759421199c
	public override FP get_maxEp() { }
	// RVA: 0x1bf9ae0 VA: 0x7594211ae0
	public MotionMode get_essentialMotionMode() { }
	// RVA: 0x1bf9b68 VA: 0x7594211b68
	public String[] get_enemyTags() { }
	// RVA: 0x1bf8164 VA: 0x7594210164
	public EnemyData get_data() { }
	// RVA: 0x1bf9bf0 VA: 0x7594211bf0
	private Void set_data(EnemyData value) { }
	// RVA: 0x1bf9c84 VA: 0x7594211c84
	public virtual Boolean get_isUnbalanced() { }
	// RVA: 0x1bf9dd8 VA: 0x7594211dd8
	public override Boolean get_isInAttackState() { }
	// RVA: 0x1bf9e64 VA: 0x7594211e64
	public override Boolean get_isInCombatState() { }
	// RVA: 0x1bf9ef0 VA: 0x7594211ef0
	public override Boolean get_isInRebornState() { }
	// RVA: 0x1bf9f7c VA: 0x7594211f7c
	public Boolean get_isInMoveState() { }
	// RVA: 0x1bfa008 VA: 0x7594212008
	public Boolean get_isInBlinkState() { }
	// RVA: 0x1bfa094 VA: 0x7594212094
	public Boolean get_isInBornState() { }
	// RVA: 0x1bfa120 VA: 0x7594212120
	public override Boolean get_isInDyingState() { }
	// RVA: 0x1bfa194 VA: 0x7594212194
	public Boolean get_isBoss() { }
	// RVA: 0x1bfa234 VA: 0x7594212234
	public virtual Boolean get_isGiantBoss() { }
	// RVA: 0x1bfa2a8 VA: 0x75942122a8
	public virtual Boolean get_isEnemyLikeNeutral() { }
	// RVA: 0x1bfa31c VA: 0x759421231c
	public IDrawableRange get_locateRange() { }
	// RVA: 0x1bf78d8 VA: 0x759420f8d8
	public Int32 get_blockVolume() { }
	// RVA: 0x1bfa394 VA: 0x7594212394
	public Int32 get_blockVolumeAddition() { }
	// RVA: 0x1bfa40c VA: 0x759421240c
	public Void set_blockVolumeAddition(Int32 value) { }
	// RVA: 0x1bfa580 VA: 0x7594212580
	public Boolean get_showSpAsBulletMode() { }
	// RVA: 0x1bfa5f8 VA: 0x75942125f8
	public Boolean get_disableBulletSp() { }
	// RVA: 0x1bfa6bc VA: 0x75942126bc
	public override UnitMode get_defaultMode() { }
	// RVA: 0x1bfa758 VA: 0x7594212758
	public override Boolean get_hasCombat() { }
	// RVA: 0x1bfa80c VA: 0x759421280c
	public Boolean get_combatable() { }
	// RVA: 0x1bfa8a8 VA: 0x75942128a8
	public override Boolean get_isInCombat() { }
	// RVA: 0x1bfa95c VA: 0x759421295c
	public override Boolean get_isMovingBySelf() { }
	// RVA: 0x1bfaa34 VA: 0x7594212a34
	public Vector2 get_footMapPosition() { }
	// RVA: 0x1bfaac0 VA: 0x7594212ac0
	public Vector2 get_offsetMapPosition() { }
	// RVA: 0x1bfab80 VA: 0x7594212b80
	public Vector2 get_stableBlockPosition() { }
	// RVA: 0x1bf8870 VA: 0x7594210870
	public Options get_options() { }
	// RVA: 0x1bfac98 VA: 0x7594212c98
	private Void set_options(Options value) { }
	// RVA: 0x1bfad5c VA: 0x7594212d5c
	public Void DontCountAsFinished() { }
	// RVA: 0x1bfae58 VA: 0x7594212e58
	public Void MarkUnharmful() { }
	// RVA: 0x1bfaf4c VA: 0x7594212f4c
	public Void DontLogInEnemyStatsWhenFinished() { }
	// RVA: 0x1bfb034 VA: 0x7594213034
	public Boolean get_isInvalidKilled() { }
	// RVA: 0x1bfb0ac VA: 0x75942130ac
	public Boolean get_isOverrideKillCnt() { }
	// RVA: 0x1bfb124 VA: 0x7594213124
	public Int32 get_overrideKillCnt() { }
	// RVA: 0x1bf9d14 VA: 0x7594211d14
	protected HierachyStateMachine`3 get_stateMachine() { }
	// RVA: 0x1bfb19c VA: 0x759421319c
	protected override Boolean get_isFixedRotation() { }
	// RVA: 0x1bfb214 VA: 0x7594213214
	protected override Int32 get_initState() { }
	// RVA: 0x1bfb28c VA: 0x759421328c
	protected override Single get_delayToRecycle() { }
	// RVA: 0x1bfb304 VA: 0x7594213304
	protected virtual SideTypeIndex get_sideTypeIndex() { }
	// RVA: 0x1bfb37c VA: 0x759421337c
	public Single get_delayToBorn() { }
	// RVA: 0x1bfb3f4 VA: 0x75942133f4
	public override FP get_createdTime() { }
	// RVA: 0x1bfb46c VA: 0x759421346c
	public Boolean get_isInEnemySide() { }
	// RVA: 0x1bfb510 VA: 0x7594213510
	public Single get_mass() { }
	// RVA: 0x1bfb610 VA: 0x7594213610
	public virtual Vector2 get_velocity() { }
	// RVA: 0x1bfb698 VA: 0x7594213698
	public virtual Void set_velocity(Vector2 value) { }
	// RVA: 0x1bfb598 VA: 0x7594213598
	protected Rigidbody2D get_rigidbody2D() { }
	// RVA: 0x1bfb744 VA: 0x7594213744
	private Void set_rigidbody2D(Rigidbody2D value) { }
	// RVA: 0x1bfb7d8 VA: 0x75942137d8
	protected AttackWrapper get_attackWrapper() { }
	// RVA: 0x1bfb850 VA: 0x7594213850
	private Void set_attackWrapper(AttackWrapper value) { }
	// RVA: 0x1bf83e8 VA: 0x75942103e8
	protected CombatWrapper get_combatWrapper() { }
	// RVA: 0x1bfb8e4 VA: 0x75942138e4
	private Void set_combatWrapper(CombatWrapper value) { }
	// RVA: 0x1bfb978 VA: 0x7594213978
	public Ability get_lastAttackOrCombatAbility() { }
	// RVA: 0x1bfba34 VA: 0x7594213a34
	public Ability get_mainCombatAbility() { }
	// RVA: 0x1bfbabc VA: 0x7594213abc
	public EnemySkill get_lastSkill() { }
	// RVA: 0x1bfbb78 VA: 0x7594213b78
	protected String get_deadEffect() { }
	// RVA: 0x1bfbc1c VA: 0x7594213c1c
	protected String get_startEffect() { }
	// RVA: 0x1bfbc94 VA: 0x7594213c94
	protected Single get_moveSpdTotalScale() { }
	// RVA: 0x1bfbd9c VA: 0x7594213d9c
	public TracePositionCursor get_traceTargetCursor() { }
	// RVA: 0x1bfbf24 VA: 0x7594213f24
	public virtual DirectionCursor get_cursor() { }
	// RVA: 0x1bfbf9c VA: 0x7594213f9c
	public virtual DirectionCursor get_moveCursor() { }
	// RVA: 0x1bfc060 VA: 0x7594214060
	public BaseTraceTargetAbility get_traceTargetAbility() { }
	// RVA: 0x1bfc0d8 VA: 0x75942140d8
	public Void set_traceTargetAbility(BaseTraceTargetAbility value) { }
	// RVA: 0x1bfc16c VA: 0x759421416c
	public virtual Boolean get_usingTraceCursor() { }
	// RVA: 0x1bfc288 VA: 0x7594214288
	public virtual Entity get_traceTarget() { }
	// RVA: 0x1bfc370 VA: 0x7594214370
	public Single get_frictionFactor() { }
	// RVA: 0x1bfc3f8 VA: 0x75942143f8
	public virtual Int32 get_preloadCnt() { }
	// RVA: 0x1bfc470 VA: 0x7594214470
	public Boolean get_disableSwitchFaceByMove() { }
	// RVA: 0x1bfc4e8 VA: 0x75942144e8
	public Void set_disableSwitchFaceByMove(Boolean value) { }
	// RVA: 0x1bfc578 VA: 0x7594214578
	private Boolean get_scaleMoveBySpeed() { }
	// RVA: 0x1bfc5f0 VA: 0x75942145f0
	public virtual Boolean get_updateHpColor() { }
	// RVA: 0x1bfc664 VA: 0x7594214664
	public virtual Color get_hpColor() { }
	// RVA: 0x1bfc708 VA: 0x7594214708
	public Void UpdateFrictionFactor(Single value) { }
	// RVA: 0x1bfc794 VA: 0x7594214794
	public Void RestoreFrictionFactor() { }
	// RVA: 0x1bfc810 VA: 0x7594214810
	private Void _UpdateFrictionFactorAdditional(Single value) { }
	// RVA: 0x1bfc89c VA: 0x759421489c
	public Boolean RestoreCachedRoute() { }
	// RVA: 0x1bfca4c VA: 0x7594214a4c
	public Boolean TryReassignRouteAndCacheOrigin(Route route) { }
	// RVA: 0x1bfcbc8 VA: 0x7594214bc8
	public Route get_originRoute() { }
	// RVA: 0x1bfcc70 VA: 0x7594214c70
	public Int32 get_originCursorIndex() { }
	// RVA: 0x1bfcd18 VA: 0x7594214d18
	public Void InterruptLastAbilityIfNot(Boolean resetCooldown) { }
	// RVA: 0x1bfcef4 VA: 0x7594214ef4
	public virtual Void Spawn(EnemyData data, EnemyHandBookData handbookData, SchedulerSnapshot snapshot, Route route, Options options) { }
	// RVA: 0x1bfd078 VA: 0x7594215078
	public override Void Born() { }
	// RVA: 0x1bfd728 VA: 0x7594215728
	public override Single GetModeRangeRadius(UnitMode mode) { }
	// RVA: 0x1bfd7b4 VA: 0x75942157b4
	public override AbstractBasicAttack GetCurrentAttackOrCombatAbility() { }
	// RVA: 0x1bfd97c VA: 0x759421597c
	public override Void PlayAudioSignal(String ev, Boolean ignorePredefined) { }
	// RVA: 0x1bfdbd0 VA: 0x7594215bd0
	public override Boolean TryHookAudio(String signal, String subSignal, out String newSignal, out String newSubsignal) { }
	// RVA: 0x1bfdd40 VA: 0x7594215d40
	public override Boolean CheckHasFilterTag(String enemyTag) { }
	// RVA: 0x1bfde08 VA: 0x7594215e08
	public Boolean TriggerEnemySkill(Ability ability, Entity target, EnemySkill skill, Boolean assignCombatAbility) { }
	// RVA: 0x1bfe0f0 VA: 0x75942160f0
	public Boolean CheckEnemySkillAffecting() { }
	// RVA: 0x1bfe1d4 VA: 0x75942161d4
	public override Entity FetchHost() { }
	// RVA: 0x1bfe3b8 VA: 0x75942163b8
	public Boolean CheckBlockable(Character blocker) { }
	// RVA: 0x1bfe4a8 VA: 0x75942164a8
	public Boolean CheckBlockableWithoutCheckRange(Character blocker) { }
	// RVA: 0x1bfe59c VA: 0x759421659c
	private Boolean _CheckMotionModeBlockable(Character blocker) { }
	// RVA: 0x1bfe650 VA: 0x7594216650
	private Boolean _CheckSpecialBlockCondition(Character blocker) { }
	// RVA: 0x1bfe714 VA: 0x7594216714
	public Boolean RegisterBlocker(Character blocker, Vector2 offset) { }
	// RVA: 0x1bfec08 VA: 0x7594216c08
	public Void UnregisterBlocker(Character blocker) { }
	// RVA: 0x1bfa49c VA: 0x759421249c
	private Void OnBlockVolumeChanged() { }
	// RVA: 0x1bfed54 VA: 0x7594216d54
	public virtual Void KnockBack(Vector2 direction, Single force, Boolean changeFaceByDirection) { }
	// RVA: 0x1bfefbc VA: 0x7594216fbc
	public Void DisableCurrentStillPull() { }
	// RVA: 0x1bff090 VA: 0x7594217090
	public virtual Boolean BeginPull(BObject source, Vector2 direction, Single force) { }
	// RVA: 0x1bff3bc VA: 0x75942173bc
	public Boolean StillPull(BObject source, Vector2 direction, Single force) { }
	// RVA: 0x1bff578 VA: 0x7594217578
	public Boolean TryEarlyStopPull(BObject source) { }
	// RVA: 0x1bff8c0 VA: 0x75942178c0
	public virtual Void EndPull(BObject source) { }
	// RVA: 0x1bffb5c VA: 0x7594217b5c
	public virtual Boolean FallDown(Tile tile, MotionMode mode) { }
	// RVA: 0x1bffcc0 VA: 0x7594217cc0
	public Boolean CheckReadyToFallDown() { }
	// RVA: 0x1bffe10 VA: 0x7594217e10
	public Void PlayMoveAnim() { }
	// RVA: 0x1bff720 VA: 0x7594217720
	private Void _RemoveInvalidPullSources() { }
	// RVA: 0x1c00008 VA: 0x7594218008
	public Boolean Blink(Single distance, Single hideTime, Boolean blinkUseAnimTime, Boolean withoutSwitchToBlinkState, Boolean skipDisappearCheckpoint) { }
	// RVA: 0x1c00618 VA: 0x7594218618
	public Boolean Blink(GridPosition grid) { }
	// RVA: 0x1c00488 VA: 0x7594218488
	protected Void BlinkWithoutSwitchToBlinkState(Single distance, Boolean skipDisappearCheckpoint) { }
	// RVA: 0x1c00724 VA: 0x7594218724
	protected Void BlinkToGridPositionWithoutSwitchToBlinkState(GridPosition grid) { }
	// RVA: 0x1c008b4 VA: 0x75942188b4
	public Boolean TryGetDistanceToNextCheckpoint(out Single distance) { }
	// RVA: 0x1c00960 VA: 0x7594218960
	public Boolean TryGetDistanceToMapPosInCheckpointsAhead(GridPosition gridPos, out Single distance) { }
	// RVA: 0x1c00a18 VA: 0x7594218a18
	public Void ClearTraceIfExist() { }
	// RVA: 0x1bfc994 VA: 0x7594214994
	public Void ReassignRoute(Route route, Int32 cursorIndex) { }
	// RVA: 0x1c00aa4 VA: 0x7594218aa4
	public Void ReconstructRoute(GridPosition endGridPos, CheckpointData[] checkPointDataArray) { }
	// RVA: 0x1c00ba8 VA: 0x7594218ba8
	public Void ReconstructRouteWithTargetGridMove(GridPosition targetPosition) { }
	// RVA: 0x1c00de0 VA: 0x7594218de0
	public Void TransportInternal(Vector2 dir, Route route, Int32 cursorIndex, Vector2 targetPos) { }
	// RVA: 0x1c00fa0 VA: 0x7594218fa0
	public Boolean TryGetNextAppearCheckpoint(out Int32 nextAppearCp, out Vector2 mapPos) { }
	// RVA: 0x1c010a0 VA: 0x75942190a0
	public Void SwitchToDeadState() { }
	// RVA: 0x1c01184 VA: 0x7594219184
	public override Void PopulateSnapshotToHashBuilder(HashCodeBuilder builder) { }
	// RVA: 0x1c01238 VA: 0x7594219238
	public override Void PopulateSnapshotToStrBuilder(StringBuilder builder) { }
	// RVA: 0x1c013d0 VA: 0x75942193d0
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1c016a0 VA: 0x75942196a0
	protected virtual Void Init(EnemyData data, EnemyHandBookData handbookData, SchedulerSnapshot snapshot, Route route) { }
	// RVA: 0x1c01e30 VA: 0x7594219e30
	public override Void ChangePathMotionMode(MotionMode mode) { }
	// RVA: 0x1c02120 VA: 0x759421a120
	protected override Void OnReset() { }
	// RVA: 0x1c0249c VA: 0x759421a49c
	protected override Void OnBorn() { }
	// RVA: 0x1c02640 VA: 0x759421a640
	public Void InitFaceTo() { }
	// RVA: 0x1c02700 VA: 0x759421a700
	public override Void OnReborn(RebornData data) { }
	// RVA: 0x1c02824 VA: 0x759421a824
	public override Void SetBodyAndFaceDirection(Vector2 direction, Boolean force) { }
	// RVA: 0x1c02a10 VA: 0x759421aa10
	public override Boolean TryIgnoreEffect(String originEffectKey) { }
	// RVA: 0x1c02b2c VA: 0x759421ab2c
	protected override Void OnFaceChanged(Vector2 newDir, Vector2 oldDir, Boolean force, Boolean isIdle) { }
	// RVA: 0x1c028f8 VA: 0x759421a8f8
	protected Void SetBodyDirectionWithPolicy(Vector2 dir, Boolean force) { }
	// RVA: 0x1c02c54 VA: 0x759421ac54
	protected override Void OnDisappearChanged(Boolean newValue) { }
	// RVA: 0x1c02fb0 VA: 0x759421afb0
	protected override Void OnSwitchMode(UnitMode next, UnitMode last, Boolean restartFSM) { }
	// RVA: 0x1c03180 VA: 0x759421b180
	protected override Void OnHpZero(Boolean noSource, Boolean skipReborn) { }
	// RVA: 0x1c03310 VA: 0x759421b310
	protected override Void OnAttributeDirty(AttributeType attributeType, FP oldValue) { }
	// RVA: 0x1c03474 VA: 0x759421b474
	protected override StateMachine ConstructStateMachine() { }
	// RVA: 0x1c034f0 VA: 0x759421b4f0
	protected override Void FinishMe(FinishReason reason) { }
	// RVA: 0x1c03bbc VA: 0x759421bbbc
	protected override Void DoFakeDeath(RebornData rebornData) { }
	// RVA: 0x1c03c80 VA: 0x759421bc80
	protected override Void DoReborn(RebornData data) { }
	// RVA: 0x1c03de4 VA: 0x759421bde4
	protected virtual Vector2 _MoveByRoute(Single deltaTime, out Boolean isHanging) { }
	// RVA: 0x1c043b4 VA: 0x759421c3b4
	protected virtual Vector2 _MoveInFearArea(Single deltaTime, out Boolean isHanging) { }
	// RVA: 0x1c04488 VA: 0x759421c488
	private Void _MoveToFixedDirection(Vector2 direction, FP deltaTime) { }
	// RVA: 0x1c03ea4 VA: 0x759421bea4
	private Vector2 _MoveByCursor(DirectionCursor cursor, Single deltaTime, out Boolean isHanging) { }
	// RVA: 0x1c00334 VA: 0x7594218334
	public Void ReleaseFromBlocker() { }
	// RVA: 0x1c045dc VA: 0x759421c5dc
	private Void _ResetPhysicsStatus() { }
	// RVA: 0x1c047d0 VA: 0x759421c7d0
	private Void _ReactivateMainTriggerCollider() { }
	// RVA: 0x1c048c8 VA: 0x759421c8c8
	private Boolean _SearchAttackTarget() { }
	// RVA: 0x1c01cf8 VA: 0x7594219cf8
	private Void _InitCurrentTile() { }
	// RVA: 0x1c04970 VA: 0x759421c970
	private Boolean _CheckTileCanExit(Tile tile) { }
	// RVA: 0x1c00f10 VA: 0x7594218f10
	public Void UpdateCurrentTile(Boolean force) { }
	// RVA: 0x1c04ba0 VA: 0x759421cba0
	public EnemySkill TryGetFirstAttachedSkill(String skillName) { }
	// RVA: 0x1bfd18c VA: 0x759421518c
	private Void _UpdateCurrentTile(Boolean force) { }
	// RVA: 0x1c04c40 VA: 0x759421cc40
	public Void SetHeightDirectly(Single height, Boolean isDirectly) { }
	// RVA: 0x1c04d6c VA: 0x759421cd6c
	public override Void SetHeight(Single height) { }
	// RVA: 0x1c04e08 VA: 0x759421ce08
	public Void SetEnemyHeightOffset(Single offset, Boolean instant, Boolean isSet) { }
	// RVA: 0x1c04ec8 VA: 0x759421cec8
	public Void AdjustEnemyHeightByInitial(Single offset, Boolean instant) { }
	// RVA: 0x1c04f7c VA: 0x759421cf7c
	public Void SetHeightImmediatelyChange() { }
	// RVA: 0x1c05000 VA: 0x759421d000
	protected Void SetEnemyLevitateOffset(Single offset) { }
	// RVA: 0x1c0509c VA: 0x759421d09c
	public Boolean IsHanging() { }
	// RVA: 0x1c051d8 VA: 0x759421d1d8
	public Boolean IsStayStill() { }
	// RVA: 0x1c052b8 VA: 0x759421d2b8
	protected virtual Void OnRootTileChanged(Tile newTile, Tile oldTile) { }
	// RVA: 0x1c05374 VA: 0x759421d374
	public virtual Void PlayUnbalanceAnimation() { }
	// RVA: 0x1c0541c VA: 0x759421d41c
	public Void ModifySpUIFlag(Boolean isShow) { }
	// RVA: 0x1bfe858 VA: 0x7594216858
	private Void _MoveToBlockPosition(Vector2 mapPos) { }
	// RVA: 0x1c054ac VA: 0x759421d4ac
	public Void FaceToCalculateDirection(Vector2 moveDir) { }
	// RVA: 0x1c05568 VA: 0x759421d568
	public Void ReachExit() { }
	// RVA: 0x1c05620 VA: 0x759421d620
	public override Void FinishWithReachExit(Boolean switchState) { }
	// RVA: 0x1c02db8 VA: 0x759421adb8
	protected Vector2 _CalculateFaceDirection(Vector2 moveDir) { }
	// RVA: 0x1bfdac4 VA: 0x7594215ac4
	private Boolean _CheckUseIdForAudioSignal(String ev) { }
	// RVA: 0x1c01940 VA: 0x7594219940
	private Void _AssignData(EnemyData data, EnemyHandBookData handbookData) { }
	// RVA: 0x1c056f0 VA: 0x759421d6f0
	private Void _AssignSkill(IList`1 skillsData) { }
	// RVA: 0x1c05c34 VA: 0x759421dc34
	private Void _AssignTalent(Blackboard talentBlackboard) { }
	// RVA: 0x1c05f6c VA: 0x759421df6c
	private Int32 _GetDefaultModeIndex() { }
	// RVA: 0x1c06154 VA: 0x759421e154
	public override Blackboard GetAttackBlackboard(UnitMode mode) { }
	// RVA: 0x1c062ac VA: 0x759421e2ac
	public Boolean TryFindFirstEnabledEnemySkill(String skillKey, out EnemySkill skillFound, Boolean checkActivate) { }
	// RVA: 0x1c06448 VA: 0x759421e448
	protected override Void OnAwake() { }
	// RVA: 0x1c06a20 VA: 0x759421ea20
	protected override Void OnInit(Single initHeight) { }
	// RVA: 0x1c06c60 VA: 0x759421ec60
	protected override Void OnFinish(FinishReason reason) { }
	// RVA: 0x1c07024 VA: 0x759421f024
	public override Void OnRecycle() { }
	// RVA: 0x1c07134 VA: 0x759421f134
	public override Void OnTick(FP fixedDeltaTime) { }
	// RVA: 0x1c0758c VA: 0x759421f58c
	public static Void ClearStaticVariables() { }
	// RVA: 0x1c07480 VA: 0x759421f480
	protected Void OnTickAfterDead(FP fixedDeltaTime) { }
	// RVA: 0x1c07654 VA: 0x759421f654
	protected Void OnBeforeAttack(Ability ability, Boolean isCombat) { }
	// RVA: 0x1c077dc VA: 0x759421f7dc
	protected Void OnAfterAttack(Ability ability, Boolean isCombat, FinishReason reason) { }
	// RVA: 0x1c0797c VA: 0x759421f97c
	public Boolean CheckTargetInAttackRange(Entity entity) { }
	// RVA: 0x1c06778 VA: 0x759421e778
	private Void _InitPhysics() { }
	// RVA: 0x1c07a94 VA: 0x759421fa94
	public Boolean TryUpdateEnemySkillSelector(String skillKey, Boolean checkActivate, String blackboardKey, FP value) { }
	// RVA: 0x1c01c10 VA: 0x7594219c10
	protected SpData _GenerateSpData(EnemyData data) { }
	// RVA: 0x1c07c5c VA: 0x759421fc5c
	public override Void ChangeMotionMode(MotionMode mode) { }
	// RVA: 0x1c07cf8 VA: 0x759421fcf8
	public override Void ResetMotionMode() { }
	// RVA: 0x1c07d7c VA: 0x759421fd7c
	public Void .ctor() { }
	// RVA: 0x1c08120 VA: 0x7594220120
	private static Void .cctor() { }
	// RVA: 0x1c081b8 VA: 0x75942201b8
	private Void <_MoveToBlockPosition>b__414_0(Vector2 pos) { }
	// RVA: 0x1c081c0 VA: 0x75942201c0
	private Void <_MoveToBlockPosition>b__414_1() { }
	// RVA: 0x1c081d4 VA: 0x75942201d4
	private Vector2 <_MoveToBlockPosition>b__414_2() { }
	// RVA: 0x1c081dc VA: 0x75942201dc
	private Void <_MoveToBlockPosition>b__414_3(Vector2 val) { }
	// RVA: 0x1c081e4 VA: 0x75942201e4
	private Void <_MoveToBlockPosition>b__414_4() { }
	// RVA: 0x1c081f8 VA: 0x75942201f8
	private SourceApplyWay <>xLuaBaseProxy_get_allApplyWay() { }
	// RVA: 0x1c08200 VA: 0x7594220200
	private FP <>xLuaBaseProxy_get_maxEp() { }
	// RVA: 0x1c08208 VA: 0x7594220208
	private UnitMode <>xLuaBaseProxy_get_defaultMode() { }
	// RVA: 0x1c08210 VA: 0x7594220210
	private Boolean <>xLuaBaseProxy_get_hasCombat() { }
	// RVA: 0x1c08218 VA: 0x7594220218
	private Boolean <>xLuaBaseProxy_get_isMovingBySelf() { }
	// RVA: 0x1c08220 VA: 0x7594220220
	private Int32 <>xLuaBaseProxy_get_initState() { }
	// RVA: 0x1c08228 VA: 0x7594220228
	private Single <>xLuaBaseProxy_get_delayToRecycle() { }
	// RVA: 0x1c08230 VA: 0x7594220230
	private Void <>xLuaBaseProxy_Born() { }
	// RVA: 0x1c08238 VA: 0x7594220238
	private Single <>xLuaBaseProxy_GetModeRangeRadius(UnitMode P0) { }
	// RVA: 0x1c08240 VA: 0x7594220240
	private AbstractBasicAttack <>xLuaBaseProxy_GetCurrentAttackOrCombatAbility() { }
	// RVA: 0x1c08248 VA: 0x7594220248
	private Boolean <>xLuaBaseProxy_TryHookAudio(String P0, String P1, out String P2, out String P3) { }
	// RVA: 0x1c08250 VA: 0x7594220250
	private Entity <>xLuaBaseProxy_FetchHost() { }
	// RVA: 0x1c08258 VA: 0x7594220258
	private Void <>xLuaBaseProxy_PopulateSnapshotToHashBuilder(HashCodeBuilder P0) { }
	// RVA: 0x1c08260 VA: 0x7594220260
	private Void <>xLuaBaseProxy_PopulateSnapshotToStrBuilder(StringBuilder P0) { }
	// RVA: 0x1c08268 VA: 0x7594220268
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x1c08270 VA: 0x7594220270
	private Void <>xLuaBaseProxy_ChangePathMotionMode(MotionMode P0) { }
	// RVA: 0x1c08278 VA: 0x7594220278
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x1c08280 VA: 0x7594220280
	private Void <>xLuaBaseProxy_OnBorn() { }
	// RVA: 0x1c08288 VA: 0x7594220288
	private Void <>xLuaBaseProxy_OnReborn(RebornData P0) { }
	// RVA: 0x1c082bc VA: 0x75942202bc
	private Void <>xLuaBaseProxy_SetBodyAndFaceDirection(Vector2 P0, Boolean P1) { }
	// RVA: 0x1c082c8 VA: 0x75942202c8
	private Boolean <>xLuaBaseProxy_TryIgnoreEffect(String P0) { }
	// RVA: 0x1c082d0 VA: 0x75942202d0
	private Void <>xLuaBaseProxy_OnFaceChanged(Vector2 P0, Vector2 P1, Boolean P2, Boolean P3) { }
	// RVA: 0x1c082e0 VA: 0x75942202e0
	private Void <>xLuaBaseProxy_OnDisappearChanged(Boolean P0) { }
	// RVA: 0x1c082ec VA: 0x75942202ec
	private Void <>xLuaBaseProxy_OnSwitchMode(UnitMode P0, UnitMode P1, Boolean P2) { }
	// RVA: 0x1c082f8 VA: 0x75942202f8
	private Void <>xLuaBaseProxy_OnHpZero(Boolean P0, Boolean P1) { }
	// RVA: 0x1c08308 VA: 0x7594220308
	private Void <>xLuaBaseProxy_OnAttributeDirty(AttributeType P0, FP P1) { }
	// RVA: 0x1c08310 VA: 0x7594220310
	private Void <>xLuaBaseProxy_FinishMe(FinishReason P0) { }
	// RVA: 0x1c08318 VA: 0x7594220318
	private Void <>xLuaBaseProxy_DoFakeDeath(RebornData P0) { }
	// RVA: 0x1c0834c VA: 0x759422034c
	private Void <>xLuaBaseProxy_DoReborn(RebornData P0) { }
	// RVA: 0x1c08380 VA: 0x7594220380
	private Void <>xLuaBaseProxy_SetHeight(Single P0) { }
	// RVA: 0x1c08388 VA: 0x7594220388
	private Void <>xLuaBaseProxy_FinishWithReachExit(Boolean P0) { }
	// RVA: 0x1c08394 VA: 0x7594220394
	private Blackboard <>xLuaBaseProxy_GetAttackBlackboard(UnitMode P0) { }
	// RVA: 0x1c0839c VA: 0x759422039c
	private Void <>xLuaBaseProxy_OnAwake() { }
	// RVA: 0x1c083a4 VA: 0x75942203a4
	private Void <>xLuaBaseProxy_OnInit(Single P0) { }
	// RVA: 0x1c083ac VA: 0x75942203ac
	private Void <>xLuaBaseProxy_OnFinish(FinishReason P0) { }
	// RVA: 0x1c083b4 VA: 0x75942203b4
	private Void <>xLuaBaseProxy_OnRecycle() { }
	// RVA: 0x1c083bc VA: 0x75942203bc
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1c083c4 VA: 0x75942203c4
	private Void <>xLuaBaseProxy_ChangeMotionMode(MotionMode P0) { }
	// RVA: 0x1c083cc VA: 0x75942203cc
	private Void <>xLuaBaseProxy_ResetMotionMode() { }
}
```