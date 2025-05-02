# EnemyGiantBoss

**Namespace:** `Torappu.Battle`


## Fields

- `Single _delayToAppear`

- `String _locateTileEffectKey`

- `AdvancedCharacterInst _tokenToSpawn`

- `Boolean _lockHudPosition`

- `Vector2 _bossHudOffset`

- `Vector3 _bossHudScale`

- `Vector2 _bossAvatarOffset`

- `Vector2 _bossAvatarSize`

- `Boolean _hideAvatarBackground`

- `Boolean _enableSpSliderWarning`

- `Single _hudDelayToAppear`

- `Boolean _hideHpSlider`

- `GiantBossInfoType _giantBossInfoType`

- `FP m_delayToAppear`

- `FP m_delayToAppearRemain`

- `Int32 m_delayToWaitOtherFinish`


## Properties

- `Boolean delayToAppear`

- `Boolean inDelayAppear`

- `Vector2 bossHudOffset`

- `Vector3 bossHudScale`

- `Vector2 bossAvatarOffset`

- `Vector2 bossAvatarSize`

- `Boolean hideAvatarBackground`

- `Boolean enableSpSliderWarning`

- `Boolean lockHudPosition`

- `Single hudDelayToAppear`

- `Boolean hideHpSlider`

- `GiantBossInfoType giantBossInfoType`

- `Boolean isSkillAffecting`

- `Boolean isSpCostSkill`

- `FP skillRemainingProgress`

- `Boolean epIsFull`

- `ElementType minEpTypeToShow`

- `EPController epController`

- `FP maxEp`

- `Boolean isInEpBreakRecovery`


## Methods

- `Boolean get_delayToAppear()`

- `Boolean get_inDelayAppear()`

- `Vector2 get_bossHudOffset()`

- `Vector3 get_bossHudScale()`

- `Vector2 get_bossAvatarOffset()`

- `Vector2 get_bossAvatarSize()`

- `Boolean get_hideAvatarBackground()`

- `Boolean get_enableSpSliderWarning()`

- `Boolean get_lockHudPosition()`

- `Single get_hudDelayToAppear()`

- `Boolean get_hideHpSlider()`

- `GiantBossInfoType get_giantBossInfoType()`

- `Boolean get_isSkillAffecting()`

- `Boolean get_isSpCostSkill()`

- `FP get_skillRemainingProgress()`

- `Boolean get_epIsFull()`

- `ElementType get_minEpTypeToShow()`

- `EPController get_epController()`

- `FP get_maxEp()`

- `Boolean get_isInEpBreakRecovery()`

- `Void set_actionOnTakeDamage(Action`1)`

- `Void _OnOtherUnitDestroyed(Object)`

- `Void _DoDelayAppear()`

- `Void _DoBorn()`

- `Boolean <>xLuaBaseProxy_get_isGiantBoss()`

- `FP <>xLuaBaseProxy_get_maxEs()`

- `Boolean <>xLuaBaseProxy_get_alive()`

- `Void <>xLuaBaseProxy_OnInit(Single)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnBorn()`

- `Void <>xLuaBaseProxy_OnFinish(FinishReason)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnTakeDamage(ref, Boolean)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnemyGiantBoss : Enemy, IUseGiantBossInfoPanel, IPtrObject
{
	private Single _delayToAppear; // 0x4b8
	private String _locateTileEffectKey; // 0x4c0
	private AdvancedCharacterInst _tokenToSpawn; // 0x4c8
	private Boolean _lockHudPosition; // 0x4d0
	private Vector2 _bossHudOffset; // 0x4d4
	private Vector3 _bossHudScale; // 0x4dc
	private Vector2 _bossAvatarOffset; // 0x4e8
	private Vector2 _bossAvatarSize; // 0x4f0
	private Boolean _hideAvatarBackground; // 0x4f8
	private Boolean _enableSpSliderWarning; // 0x4f9
	private Single _hudDelayToAppear; // 0x4fc
	private Boolean _hideHpSlider; // 0x500
	private GiantBossInfoType _giantBossInfoType; // 0x504
	private Action`1 <actionOnTakeDamage>k__BackingField; // 0x508
	private FP m_delayToAppear; // 0x510
	private FP m_delayToAppearRemain; // 0x518
	private Int32 m_delayToWaitOtherFinish; // 0x520
	private static DelegateBridge __Hotfix0_get_delayToAppear; // 0x0
	private static DelegateBridge __Hotfix0_get_inDelayAppear; // 0x8
	private static DelegateBridge __Hotfix0_get_isGiantBoss; // 0x10
	private static DelegateBridge __Hotfix0_get_maxEs; // 0x18
	private static DelegateBridge __Hotfix0_get_alive; // 0x20
	private static DelegateBridge __Hotfix0_get_bossHudOffset; // 0x28
	private static DelegateBridge __Hotfix0_get_bossHudScale; // 0x30
	private static DelegateBridge __Hotfix0_get_bossAvatarOffset; // 0x38
	private static DelegateBridge __Hotfix0_get_bossAvatarSize; // 0x40
	private static DelegateBridge __Hotfix0_get_hideAvatarBackground; // 0x48
	private static DelegateBridge __Hotfix0_get_enableSpSliderWarning; // 0x50
	private static DelegateBridge __Hotfix0_get_lockHudPosition; // 0x58
	private static DelegateBridge __Hotfix0_get_hudDelayToAppear; // 0x60
	private static DelegateBridge __Hotfix0_get_hideHpSlider; // 0x68
	private static DelegateBridge __Hotfix0_get_giantBossInfoType; // 0x70
	private static DelegateBridge __Hotfix0_get_isSkillAffecting; // 0x78
	private static DelegateBridge __Hotfix0_get_isSpCostSkill; // 0x80
	private static DelegateBridge __Hotfix0_get_skillRemainingProgress; // 0x88
	private static DelegateBridge __Hotfix0_get_epIsFull; // 0x90
	private static DelegateBridge __Hotfix0_get_minEpTypeToShow; // 0x98
	private static DelegateBridge __Hotfix0_get_epArrayToShow; // 0xa0
	private static DelegateBridge __Hotfix0_get_epController; // 0xa8
	private static DelegateBridge __Hotfix0_get_maxEp; // 0xb0
	private static DelegateBridge __Hotfix0_get_isInEpBreakRecovery; // 0xb8
	private static DelegateBridge __Hotfix0_get_actionOnTakeDamage; // 0xc0
	private static DelegateBridge __Hotfix0_set_actionOnTakeDamage; // 0xc8
	private static DelegateBridge __Hotfix0_OnInit; // 0xd0
	private static DelegateBridge __Hotfix0_OnReset; // 0xd8
	private static DelegateBridge __Hotfix0_OnBorn; // 0xe0
	private static DelegateBridge __Hotfix0_OnFinish; // 0xe8
	private static DelegateBridge __Hotfix0__OnOtherUnitDestroyed; // 0xf0
	private static DelegateBridge __Hotfix0_OnTick; // 0xf8
	private static DelegateBridge __Hotfix0__DoDelayAppear; // 0x100
	private static DelegateBridge __Hotfix0_OnTakeDamage; // 0x108
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x110
	private static DelegateBridge __Hotfix0__DoBorn; // 0x118
	private static DelegateBridge _c__Hotfix0_ctor; // 0x120

	private Boolean delayToAppear { get; }
	private Boolean inDelayAppear { get; }
	public override Boolean isGiantBoss { get; }
	public override FP maxEs { get; }
	public override Boolean alive { get; }
	public Vector2 bossHudOffset { get; }
	public Vector3 bossHudScale { get; }
	public Vector2 bossAvatarOffset { get; }
	public Vector2 bossAvatarSize { get; }
	public Boolean hideAvatarBackground { get; }
	public Boolean enableSpSliderWarning { get; }
	public Boolean lockHudPosition { get; }
	public Single hudDelayToAppear { get; }
	public Boolean hideHpSlider { get; }
	public GiantBossInfoType giantBossInfoType { get; }
	public Boolean isSkillAffecting { get; }
	public Boolean isSpCostSkill { get; }
	public FP skillRemainingProgress { get; }
	public Boolean epIsFull { get; }
	public ElementType minEpTypeToShow { get; }
	public FP[] epArrayToShow { get; }
	public EPController epController { get; }
	public FP maxEp { get; }
	public Boolean isInEpBreakRecovery { get; }
	public Action`1 actionOnTakeDamage { get; set; }

	// RVA: 0x1c18c88 VA: 0x7594230c88
	private Boolean get_delayToAppear() { }
	// RVA: 0x1c18d2c VA: 0x7594230d2c
	private Boolean get_inDelayAppear() { }
	// RVA: 0x1c18dd0 VA: 0x7594230dd0
	public override Boolean get_isGiantBoss() { }
	// RVA: 0x1c18e38 VA: 0x7594230e38
	public override FP get_maxEs() { }
	// RVA: 0x1c18ea4 VA: 0x7594230ea4
	public override Boolean get_alive() { }
	// RVA: 0x1c18f2c VA: 0x7594230f2c
	public Vector2 get_bossHudOffset() { }
	// RVA: 0x1c18f94 VA: 0x7594230f94
	public Vector3 get_bossHudScale() { }
	// RVA: 0x1c19000 VA: 0x7594231000
	public Vector2 get_bossAvatarOffset() { }
	// RVA: 0x1c19068 VA: 0x7594231068
	public Vector2 get_bossAvatarSize() { }
	// RVA: 0x1c190d0 VA: 0x75942310d0
	public Boolean get_hideAvatarBackground() { }
	// RVA: 0x1c19138 VA: 0x7594231138
	public Boolean get_enableSpSliderWarning() { }
	// RVA: 0x1c191a0 VA: 0x75942311a0
	public Boolean get_lockHudPosition() { }
	// RVA: 0x1c19208 VA: 0x7594231208
	public Single get_hudDelayToAppear() { }
	// RVA: 0x1c19270 VA: 0x7594231270
	public Boolean get_hideHpSlider() { }
	// RVA: 0x1c192d8 VA: 0x75942312d8
	public GiantBossInfoType get_giantBossInfoType() { }
	// RVA: 0x1c19340 VA: 0x7594231340
	public Boolean get_isSkillAffecting() { }
	// RVA: 0x1c1942c VA: 0x759423142c
	public Boolean get_isSpCostSkill() { }
	// RVA: 0x1c19504 VA: 0x7594231504
	public FP get_skillRemainingProgress() { }
	// RVA: 0x1c195c4 VA: 0x75942315c4
	public Boolean get_epIsFull() { }
	// RVA: 0x1c19630 VA: 0x7594231630
	public ElementType get_minEpTypeToShow() { }
	// RVA: 0x1c1969c VA: 0x759423169c
	public FP[] get_epArrayToShow() { }
	// RVA: 0x1c19708 VA: 0x7594231708
	public EPController get_epController() { }
	// RVA: 0x1c19774 VA: 0x7594231774
	public FP get_maxEp() { }
	// RVA: 0x1c197e0 VA: 0x75942317e0
	public Boolean get_isInEpBreakRecovery() { }
	// RVA: 0x1c1984c VA: 0x759423184c
	public Action`1 get_actionOnTakeDamage() { }
	// RVA: 0x1c198b4 VA: 0x75942318b4
	public Void set_actionOnTakeDamage(Action`1 value) { }
	// RVA: 0x1c19938 VA: 0x7594231938
	protected override Void OnInit(Single initHeight) { }
	// RVA: 0x1c19ae4 VA: 0x7594231ae4
	protected override Void OnReset() { }
	// RVA: 0x1c19b88 VA: 0x7594231b88
	protected override Void OnBorn() { }
	// RVA: 0x1c1a03c VA: 0x759423203c
	protected override Void OnFinish(FinishReason reason) { }
	// RVA: 0x1c1a168 VA: 0x7594232168
	private Void _OnOtherUnitDestroyed(Object arg) { }
	// RVA: 0x1c1a29c VA: 0x759423229c
	public override Void OnTick(FP fixedDeltaTime) { }
	// RVA: 0x1c1a3e4 VA: 0x75942323e4
	private Void _DoDelayAppear() { }
	// RVA: 0x1c1a4d8 VA: 0x75942324d8
	protected override Void OnTakeDamage(ref Modifier modifier, Boolean force) { }
	// RVA: 0x1c1a5e0 VA: 0x75942325e0
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1c19cd8 VA: 0x7594231cd8
	private Void _DoBorn() { }
	// RVA: 0x1c1a704 VA: 0x7594232704
	public Void .ctor() { }
	// RVA: 0x1c1a904 VA: 0x7594232904
	private Boolean <>xLuaBaseProxy_get_isGiantBoss() { }
	// RVA: 0x1c1a90c VA: 0x759423290c
	private FP <>xLuaBaseProxy_get_maxEs() { }
	// RVA: 0x1c1a914 VA: 0x7594232914
	private Boolean <>xLuaBaseProxy_get_alive() { }
	// RVA: 0x1c1a91c VA: 0x759423291c
	private Void <>xLuaBaseProxy_OnInit(Single P0) { }
	// RVA: 0x1c1a924 VA: 0x7594232924
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x1c1a92c VA: 0x759423292c
	private Void <>xLuaBaseProxy_OnBorn() { }
	// RVA: 0x1c1a934 VA: 0x7594232934
	private Void <>xLuaBaseProxy_OnFinish(FinishReason P0) { }
	// RVA: 0x1c1a93c VA: 0x759423293c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1c1a944 VA: 0x7594232944
	private Void <>xLuaBaseProxy_OnTakeDamage(ref Modifier P0, Boolean P1) { }
	// RVA: 0x1c1a950 VA: 0x7594232950
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```