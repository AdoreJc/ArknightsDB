# RacingEnemy

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 m_finishedRoundCount`

- `FP m_magnetSpeed`

- `RacingMoveController m_racingMoveController`

- `Tile m_lastValidTile`

- `RacingAttributesData m_attributesData`

- `RacingMode m_currentRacingMode`

- `Boolean m_ignoreCollisionSpeedLoss`

- `PeriodicTimer m_autoUseItemTimer`

- `RacingEnemyData m_racingData`

- `Tween m_falldownTween`

- `Int32 <ranking>k__BackingField`

- `Int32 <reverseRanking>k__BackingField`


## Properties

- `RacingEnemyData racingData`

- `FP racingMaxMoveSpeed`

- `FP racingAcceleration`

- `FP racingMaxHp`

- `FP racingEndurance`

- `FP racingMassLevel`

- `FP racingMoveSpeed`

- `FP moveSpeedAttribute`

- `RacingMode racingMode`

- `RacingAttributesData racingAttributes`

- `Boolean ignoreCollisionSpeedLoss`

- `Int32 finishedRoundCount`

- `FP racingProgress`

- `Int32 ranking`

- `Int32 reverseRanking`


## Methods

- `RacingEnemyData get_racingData()`

- `FP get_racingMaxMoveSpeed()`

- `FP get_racingAcceleration()`

- `FP get_racingMaxHp()`

- `FP get_racingEndurance()`

- `FP get_racingMassLevel()`

- `FP get_racingMoveSpeed()`

- `FP get_moveSpeedAttribute()`

- `RacingMode get_racingMode()`

- `RacingAttributesData get_racingAttributes()`

- `Boolean get_ignoreCollisionSpeedLoss()`

- `Void set_ignoreCollisionSpeedLoss(Boolean)`

- `Int32 get_finishedRoundCount()`

- `FP get_racingProgress()`

- `Int32 get_ranking()`

- `Void set_ranking(Int32)`

- `Int32 get_reverseRanking()`

- `Void set_reverseRanking(Int32)`

- `SandboxV2RacingItemInfo GetCurrentItem()`

- `Void UseCurrentItem()`

- `Void SetMagnetTarget(Entity, FP)`

- `Void SwitchRacingMode(RacingMode)`

- `Void OnTakeForce(RacingCollisionContext)`

- `Void OnOutputForce(RacingCollisionContext)`

- `Void OnCollision(RacingEnemy)`

- `Void OnCollision(Tile)`

- `Void CheckCheckpoint(Int32)`

- `Boolean _CheckValidTile(Tile)`

- `Void _OnRacingEnemyFallDown(MotionMode)`

- `Void _DoCollisionWithEnemyInternal(RacingEnemy)`

- `Void _DoCollisionWithTileInternal(Tile)`

- `Void _DoCollisionInternal(Vector2, Single, FP, FP)`

- `Void _DoCollisionHpLoss(FP)`

- `Void _DoCollisionSpeedLoss(FP)`

- `Void _UpdateRacingAttributes(Boolean)`

- `Void _TryUpdateAttribute(AttributeType, FP)`

- `Void _ClearMoveVelocity()`

- `Void _UpdateMoveSpeed(FP)`

- `Void _DoUpdateMoveSpeed(FP)`

- `Void _UpdateMagnet()`

- `Void _UpdateAutoUseItem(FP)`

- `Void <_OnRacingEnemyFallDown>b__79_1()`

- `Boolean <>xLuaBaseProxy_get_onlyCollideWhenUnbalance()`

- `Boolean <>xLuaBaseProxy_get_updateHpColor()`

- `Color <>xLuaBaseProxy_get_hpColor()`

- `Vector2 <>xLuaBaseProxy_get_velocity()`

- `Void <>xLuaBaseProxy_Spawn(EnemyData, EnemyHandBookData, SchedulerSnapshot, Route, Options)`

- `Void <>xLuaBaseProxy_AssignDynamicAbility(IList`1)`

- `Void <>xLuaBaseProxy_OnBorn()`

- `Void <>xLuaBaseProxy_OnRootTileChanged(Tile, Tile)`

- `Boolean <>xLuaBaseProxy_FallDown(Tile, MotionMode)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RacingEnemy : Enemy
{
	private List`1 m_checkedCheckpoints; // 0x4b8
	private Int32 m_finishedRoundCount; // 0x4c0
	private ObjectPtr`1 m_magnetTarget; // 0x4c8
	private FP m_magnetSpeed; // 0x4d8
	private RacingMoveController m_racingMoveController; // 0x4e0
	private Tile m_lastValidTile; // 0x4e8
	private RacingAttributesData m_attributesData; // 0x4f0
	private EventPool`1 m_racingEvPool; // 0x4f8
	private RacingMode m_currentRacingMode; // 0x500
	private Boolean m_ignoreCollisionSpeedLoss; // 0x504
	private PeriodicTimer m_autoUseItemTimer; // 0x508
	private RacingEnemyData m_racingData; // 0x510
	private Tween m_falldownTween; // 0x518
	private Int32 <ranking>k__BackingField; // 0x520
	private Int32 <reverseRanking>k__BackingField; // 0x524
	private static DelegateBridge __Hotfix0_get_racingData; // 0x0
	private static DelegateBridge __Hotfix0_get_racingMaxMoveSpeed; // 0x8
	private static DelegateBridge __Hotfix0_get_racingAcceleration; // 0x10
	private static DelegateBridge __Hotfix0_get_racingMaxHp; // 0x18
	private static DelegateBridge __Hotfix0_get_racingEndurance; // 0x20
	private static DelegateBridge __Hotfix0_get_racingMassLevel; // 0x28
	private static DelegateBridge __Hotfix0_get_racingMoveSpeed; // 0x30
	private static DelegateBridge __Hotfix0_get_moveSpeedAttribute; // 0x38
	private static DelegateBridge __Hotfix0_get_racingMode; // 0x40
	private static DelegateBridge __Hotfix0_get_racingAttributes; // 0x48
	private static DelegateBridge __Hotfix0_get_ignoreCollisionSpeedLoss; // 0x50
	private static DelegateBridge __Hotfix0_set_ignoreCollisionSpeedLoss; // 0x58
	private static DelegateBridge __Hotfix0_get_onlyCollideWhenUnbalance; // 0x60
	private static DelegateBridge __Hotfix0_get_updateHpColor; // 0x68
	private static DelegateBridge __Hotfix0_get_hpColor; // 0x70
	private static DelegateBridge __Hotfix0_get_racingEvPool; // 0x78
	private static DelegateBridge __Hotfix0_get_velocity; // 0x80
	private static DelegateBridge __Hotfix0_get_finishedRoundCount; // 0x88
	private static DelegateBridge __Hotfix0_get_racingProgress; // 0x90
	private static DelegateBridge __Hotfix0_get_ranking; // 0x98
	private static DelegateBridge __Hotfix0_set_ranking; // 0xa0
	private static DelegateBridge __Hotfix0_get_reverseRanking; // 0xa8
	private static DelegateBridge __Hotfix0_set_reverseRanking; // 0xb0
	private static DelegateBridge __Hotfix0_GetCurrentItem; // 0xb8
	private static DelegateBridge __Hotfix0_UseCurrentItem; // 0xc0
	private static DelegateBridge __Hotfix0_SetMagnetTarget; // 0xc8
	private static DelegateBridge __Hotfix0_SwitchRacingMode; // 0xd0
	private static DelegateBridge __Hotfix0_OnTakeForce; // 0xd8
	private static DelegateBridge __Hotfix0_OnOutputForce; // 0xe0
	private static DelegateBridge __Hotfix0_OnCollision; // 0xe8
	private static DelegateBridge __Hotfix1_OnCollision; // 0xf0
	private static DelegateBridge __Hotfix0_CheckCheckpoint; // 0xf8
	private static DelegateBridge __Hotfix0_Spawn; // 0x100
	private static DelegateBridge __Hotfix0_AssignDynamicAbility; // 0x108
	private static DelegateBridge __Hotfix0_OnBorn; // 0x110
	private static DelegateBridge __Hotfix0_OnRootTileChanged; // 0x118
	private static DelegateBridge __Hotfix0_FallDown; // 0x120
	private static DelegateBridge __Hotfix0_OnReset; // 0x128
	private static DelegateBridge __Hotfix0_OnTick; // 0x130
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0x138
	private static DelegateBridge __Hotfix0__CheckValidTile; // 0x140
	private static DelegateBridge __Hotfix0__OnRacingEnemyFallDown; // 0x148
	private static DelegateBridge __Hotfix0__DoCollisionWithEnemyInternal; // 0x150
	private static DelegateBridge __Hotfix0__DoCollisionWithTileInternal; // 0x158
	private static DelegateBridge __Hotfix0__DoCollisionInternal; // 0x160
	private static DelegateBridge __Hotfix0__DoCollisionHpLoss; // 0x168
	private static DelegateBridge __Hotfix0__DoCollisionSpeedLoss; // 0x170
	private static DelegateBridge __Hotfix0__UpdateRacingAttributes; // 0x178
	private static DelegateBridge __Hotfix0__TryUpdateAttribute; // 0x180
	private static DelegateBridge __Hotfix0__ClearMoveVelocity; // 0x188
	private static DelegateBridge __Hotfix0__UpdateMoveSpeed; // 0x190
	private static DelegateBridge __Hotfix0__DoUpdateMoveSpeed; // 0x198
	private static DelegateBridge __Hotfix0__UpdateMagnet; // 0x1a0
	private static DelegateBridge __Hotfix0__UpdateAutoUseItem; // 0x1a8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1b0

	public RacingEnemyData racingData { get; }
	public FP racingMaxMoveSpeed { get; }
	public FP racingAcceleration { get; }
	public FP racingMaxHp { get; }
	public FP racingEndurance { get; }
	public FP racingMassLevel { get; }
	public FP racingMoveSpeed { get; }
	public FP moveSpeedAttribute { get; }
	public RacingMode racingMode { get; }
	public RacingAttributesData racingAttributes { get; }
	public Boolean ignoreCollisionSpeedLoss { get; set; }
	protected override Boolean onlyCollideWhenUnbalance { get; }
	public override Boolean updateHpColor { get; }
	public override Color hpColor { get; }
	public EventPool`1 racingEvPool { get; }
	public override Vector2 velocity { get; }
	public Int32 finishedRoundCount { get; }
	public FP racingProgress { get; }
	public Int32 ranking { get; set; }
	public Int32 reverseRanking { get; set; }

	// RVA: 0x40b613c VA: 0x75966ce13c
	public RacingEnemyData get_racingData() { }
	// RVA: 0x40b61a4 VA: 0x75966ce1a4
	public FP get_racingMaxMoveSpeed() { }
	// RVA: 0x40b621c VA: 0x75966ce21c
	public FP get_racingAcceleration() { }
	// RVA: 0x40b6294 VA: 0x75966ce294
	public FP get_racingMaxHp() { }
	// RVA: 0x40b646c VA: 0x75966ce46c
	public FP get_racingEndurance() { }
	// RVA: 0x40b64e4 VA: 0x75966ce4e4
	public FP get_racingMassLevel() { }
	// RVA: 0x40b6578 VA: 0x75966ce578
	public FP get_racingMoveSpeed() { }
	// RVA: 0x40b6618 VA: 0x75966ce618
	public FP get_moveSpeedAttribute() { }
	// RVA: 0x40b6698 VA: 0x75966ce698
	public RacingMode get_racingMode() { }
	// RVA: 0x40b6700 VA: 0x75966ce700
	public RacingAttributesData get_racingAttributes() { }
	// RVA: 0x40b6768 VA: 0x75966ce768
	public Boolean get_ignoreCollisionSpeedLoss() { }
	// RVA: 0x40b67d0 VA: 0x75966ce7d0
	public Void set_ignoreCollisionSpeedLoss(Boolean value) { }
	// RVA: 0x40b6850 VA: 0x75966ce850
	protected override Boolean get_onlyCollideWhenUnbalance() { }
	// RVA: 0x40b68b4 VA: 0x75966ce8b4
	public override Boolean get_updateHpColor() { }
	// RVA: 0x40b691c VA: 0x75966ce91c
	public override Color get_hpColor() { }
	// RVA: 0x40b69c4 VA: 0x75966ce9c4
	public EventPool`1 get_racingEvPool() { }
	// RVA: 0x40b6a2c VA: 0x75966cea2c
	public override Vector2 get_velocity() { }
	// RVA: 0x40b6b20 VA: 0x75966ceb20
	public Int32 get_finishedRoundCount() { }
	// RVA: 0x40b6b88 VA: 0x75966ceb88
	public FP get_racingProgress() { }
	// RVA: 0x40b6c7c VA: 0x75966cec7c
	public Int32 get_ranking() { }
	// RVA: 0x40b6ce4 VA: 0x75966cece4
	public Void set_ranking(Int32 value) { }
	// RVA: 0x40b6d60 VA: 0x75966ced60
	public Int32 get_reverseRanking() { }
	// RVA: 0x40b6dc8 VA: 0x75966cedc8
	public Void set_reverseRanking(Int32 value) { }
	// RVA: 0x40b6e44 VA: 0x75966cee44
	public SandboxV2RacingItemInfo GetCurrentItem() { }
	// RVA: 0x40b7058 VA: 0x75966cf058
	public Void UseCurrentItem() { }
	// RVA: 0x40b70e8 VA: 0x75966cf0e8
	public Void SetMagnetTarget(Entity target, FP speed) { }
	// RVA: 0x40b71a4 VA: 0x75966cf1a4
	public Void SwitchRacingMode(RacingMode mode) { }
	// RVA: 0x40b7278 VA: 0x75966cf278
	public Void OnTakeForce(RacingCollisionContext context) { }
	// RVA: 0x40b731c VA: 0x75966cf31c
	public Void OnOutputForce(RacingCollisionContext context) { }
	// RVA: 0x40b73c0 VA: 0x75966cf3c0
	public Void OnCollision(RacingEnemy another) { }
	// RVA: 0x40b7590 VA: 0x75966cf590
	public Void OnCollision(Tile tile) { }
	// RVA: 0x40b7760 VA: 0x75966cf760
	public Void CheckCheckpoint(Int32 checkpointId) { }
	// RVA: 0x40b7a94 VA: 0x75966cfa94
	public override Void Spawn(EnemyData data, EnemyHandBookData handbookData, SchedulerSnapshot snapshot, Route route, Options options) { }
	// RVA: 0x40b7c34 VA: 0x75966cfc34
	protected override Void AssignDynamicAbility(IList`1 dynamicAbilities) { }
	// RVA: 0x40b81d4 VA: 0x75966d01d4
	protected override Void OnBorn() { }
	// RVA: 0x40b8488 VA: 0x75966d0488
	protected override Void OnRootTileChanged(Tile newTile, Tile oldTile) { }
	// RVA: 0x40b8630 VA: 0x75966d0630
	public override Boolean FallDown(Tile tile, MotionMode mode) { }
	// RVA: 0x40b8a58 VA: 0x75966d0a58
	protected override Void OnReset() { }
	// RVA: 0x40b8ae8 VA: 0x75966d0ae8
	public override Void OnTick(FP fixedDeltaTime) { }
	// RVA: 0x40b9214 VA: 0x75966d1214
	public override Void PreloadSpecialAudioSignals(String unitId, String tmplId, Action`2 preloader) { }
	// RVA: 0x40b8538 VA: 0x75966d0538
	private Boolean _CheckValidTile(Tile tile) { }
	// RVA: 0x40b874c VA: 0x75966d074c
	private Void _OnRacingEnemyFallDown(MotionMode motionMode) { }
	// RVA: 0x40b7440 VA: 0x75966cf440
	private Void _DoCollisionWithEnemyInternal(RacingEnemy another) { }
	// RVA: 0x40b7610 VA: 0x75966cf610
	private Void _DoCollisionWithTileInternal(Tile tile) { }
	// RVA: 0x40b9424 VA: 0x75966d1424
	private Void _DoCollisionInternal(Vector2 kbDir, Single force, FP speedLoss, FP hpLoss) { }
	// RVA: 0x40b9670 VA: 0x75966d1670
	private Void _DoCollisionHpLoss(FP hpLoss) { }
	// RVA: 0x40b9778 VA: 0x75966d1778
	private Void _DoCollisionSpeedLoss(FP speedLoss) { }
	// RVA: 0x40b83c0 VA: 0x75966d03c0
	private Void _UpdateRacingAttributes(Boolean init) { }
	// RVA: 0x40b635c VA: 0x75966ce35c
	private Void _TryUpdateAttribute(AttributeType attributeType, FP value) { }
	// RVA: 0x40b930c VA: 0x75966d130c
	private Void _ClearMoveVelocity() { }
	// RVA: 0x40b8bb0 VA: 0x75966d0bb0
	private Void _UpdateMoveSpeed(FP fixedDeltaTime) { }
	// RVA: 0x40b98c4 VA: 0x75966d18c4
	private Void _DoUpdateMoveSpeed(FP newMoveSpeed) { }
	// RVA: 0x40b8dac VA: 0x75966d0dac
	private Void _UpdateMagnet() { }
	// RVA: 0x40b9048 VA: 0x75966d1048
	private Void _UpdateAutoUseItem(FP deltaTime) { }
	// RVA: 0x40b9978 VA: 0x75966d1978
	public Void .ctor() { }
	// RVA: 0x40b9b34 VA: 0x75966d1b34
	private Void <_OnRacingEnemyFallDown>b__79_1() { }
	// RVA: 0x40b9b60 VA: 0x75966d1b60
	private Boolean <>xLuaBaseProxy_get_onlyCollideWhenUnbalance() { }
	// RVA: 0x40b9b68 VA: 0x75966d1b68
	private Boolean <>xLuaBaseProxy_get_updateHpColor() { }
	// RVA: 0x40b9b70 VA: 0x75966d1b70
	private Color <>xLuaBaseProxy_get_hpColor() { }
	// RVA: 0x40b9b78 VA: 0x75966d1b78
	private Vector2 <>xLuaBaseProxy_get_velocity() { }
	// RVA: 0x40b9b80 VA: 0x75966d1b80
	private Void <>xLuaBaseProxy_Spawn(EnemyData P0, EnemyHandBookData P1, SchedulerSnapshot P2, Route P3, Options P4) { }
	// RVA: 0x40b9bc4 VA: 0x75966d1bc4
	private Void <>xLuaBaseProxy_AssignDynamicAbility(IList`1 P0) { }
	// RVA: 0x40b9bcc VA: 0x75966d1bcc
	private Void <>xLuaBaseProxy_OnBorn() { }
	// RVA: 0x40b9bd4 VA: 0x75966d1bd4
	private Void <>xLuaBaseProxy_OnRootTileChanged(Tile P0, Tile P1) { }
	// RVA: 0x40b9bdc VA: 0x75966d1bdc
	private Boolean <>xLuaBaseProxy_FallDown(Tile P0, MotionMode P1) { }
	// RVA: 0x40b9be4 VA: 0x75966d1be4
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x40b9bec VA: 0x75966d1bec
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x40b9bf4 VA: 0x75966d1bf4
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
}
```