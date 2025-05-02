# CastSkill

**Namespace:** `Torappu.Battle`


## Fields

- `TargetTrigger _trigger`

- `Boolean _switchToState`

- `Boolean _uninterruptibleOnAbilityPredelay`

- `Boolean _canSwitchDuringBorn`

- `Boolean _canCastDuringBorn`

- `Boolean _checkHasTargetBeforeDoCast`

- `Boolean _useTriggerInManualMode`

- `Boolean _allowNoTarget`

- `Boolean _shouldCastLikeAttack`

- `Boolean _isRemoteControlled`

- `Boolean _hideRangeToShow`

- `Boolean _forceUseBaseShowRange`

- `TargetSelector _rangeToShow`

- `Boolean _recoverSpIfNoTarget`

- `Boolean _resetAbilityCooldownWhenCastEnd`

- `Boolean _onlyAvailableWhenTokenValid`

- `Boolean _hasUniStackColor`


## Properties

- `Boolean NotHideRangeToShow`

- `Boolean switchToState`


## Methods

- `Boolean get_NotHideRangeToShow()`

- `Boolean get_switchToState()`

- `Boolean _IsTokenValid()`

- `Void _RecoverSp(Int32)`

- `Boolean _CheckIfSkillStateUninterruptible()`

- `Boolean <>xLuaBaseProxy_get_stateUninterruptible()`

- `Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide)`

- `Boolean <>xLuaBaseProxy_get_shouldCastLikeAttack()`

- `Boolean <>xLuaBaseProxy_get_shouldChangeToChargeColor()`

- `Boolean <>xLuaBaseProxy_get_isRemoteControlled()`

- `Boolean <>xLuaBaseProxy_get_forceUseBaseShowRange()`

- `Boolean <>xLuaBaseProxy_get_canCastCheck()`

- `Boolean <>xLuaBaseProxy_CanCastCheckBeforeStart()`

- `IDrawableRange <>xLuaBaseProxy_get_rangeToShow()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_AssignData(SkillData, Character, Blackboard, Delta)`

- `Void <>xLuaBaseProxy_OnCastFinish(Ability, FinishReason, Boolean)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Boolean <>xLuaBaseProxy_get_isAvailableToShowStackCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CastSkill : BasicSkill
{
	protected TargetTrigger _trigger; // 0xf8
	private Boolean _switchToState; // 0x100
	private Boolean _uninterruptibleOnAbilityPredelay; // 0x101
	private Boolean _canSwitchDuringBorn; // 0x102
	private Boolean _canCastDuringBorn; // 0x103
	private Boolean _checkHasTargetBeforeDoCast; // 0x104
	protected Boolean _useTriggerInManualMode; // 0x105
	protected Boolean _allowNoTarget; // 0x106
	private Boolean _shouldCastLikeAttack; // 0x107
	private Boolean _isRemoteControlled; // 0x108
	private Boolean _hideRangeToShow; // 0x109
	private Boolean _forceUseBaseShowRange; // 0x10a
	private TargetSelector _rangeToShow; // 0x110
	private Boolean _recoverSpIfNoTarget; // 0x118
	private Boolean _resetAbilityCooldownWhenCastEnd; // 0x119
	private Boolean _onlyAvailableWhenTokenValid; // 0x11a
	private Boolean _hasUniStackColor; // 0x11b
	private static readonly Int32 MIN_STACK_COUNT_TO_CHANGE_COLOR; // 0x0
	private static DelegateBridge __Hotfix0_get_NotHideRangeToShow; // 0x8
	private static DelegateBridge __Hotfix0_get_switchToState; // 0x10
	private static DelegateBridge __Hotfix0_get_stateUninterruptible; // 0x18
	private static DelegateBridge __Hotfix0_IsAvailable; // 0x20
	private static DelegateBridge __Hotfix0__IsTokenValid; // 0x28
	private static DelegateBridge __Hotfix0_get_shouldCastLikeAttack; // 0x30
	private static DelegateBridge __Hotfix0_get_shouldChangeToChargeColor; // 0x38
	private static DelegateBridge __Hotfix0_get_isRemoteControlled; // 0x40
	private static DelegateBridge __Hotfix0_get_forceUseBaseShowRange; // 0x48
	private static DelegateBridge __Hotfix0_get_canCastCheck; // 0x50
	private static DelegateBridge __Hotfix0_CanCastCheckBeforeStart; // 0x58
	private static DelegateBridge __Hotfix0_get_rangeToShow; // 0x60
	private static DelegateBridge __Hotfix0_OnInit; // 0x68
	private static DelegateBridge __Hotfix0_AssignData; // 0x70
	private static DelegateBridge __Hotfix0_DoCast; // 0x78
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x80
	private static DelegateBridge __Hotfix0_UseSkill; // 0x88
	private static DelegateBridge __Hotfix0_OnTick; // 0x90
	private static DelegateBridge __Hotfix0__RecoverSp; // 0x98
	private static DelegateBridge __Hotfix0__CheckIfSkillStateUninterruptible; // 0xa0
	private static DelegateBridge __Hotfix0_get_isAvailableToShowStackCount; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	private Boolean NotHideRangeToShow { get; }
	private Boolean switchToState { get; }
	public override Boolean stateUninterruptible { get; }
	public override Boolean shouldCastLikeAttack { get; }
	public override Boolean shouldChangeToChargeColor { get; }
	public override Boolean isRemoteControlled { get; }
	protected override Boolean forceUseBaseShowRange { get; }
	public override Boolean canCastCheck { get; }
	public override IDrawableRange rangeToShow { get; }
	public override Boolean isAvailableToShowStackCount { get; }

	// RVA: 0x40f0224 VA: 0x7596708224
	private Boolean get_NotHideRangeToShow() { }
	// RVA: 0x40f02a4 VA: 0x75967082a4
	private Boolean get_switchToState() { }
	// RVA: 0x40f031c VA: 0x759670831c
	public override Boolean get_stateUninterruptible() { }
	// RVA: 0x40e9fa8 VA: 0x7596701fa8
	public override Boolean IsAvailable(PlayerSide operationSide) { }
	// RVA: 0x40f043c VA: 0x759670843c
	private Boolean _IsTokenValid() { }
	// RVA: 0x40f052c VA: 0x759670852c
	public override Boolean get_shouldCastLikeAttack() { }
	// RVA: 0x40f05a4 VA: 0x75967085a4
	public override Boolean get_shouldChangeToChargeColor() { }
	// RVA: 0x40f06bc VA: 0x75967086bc
	public override Boolean get_isRemoteControlled() { }
	// RVA: 0x40f0734 VA: 0x7596708734
	protected override Boolean get_forceUseBaseShowRange() { }
	// RVA: 0x40f07ac VA: 0x75967087ac
	public override Boolean get_canCastCheck() { }
	// RVA: 0x40f0890 VA: 0x7596708890
	public override Boolean CanCastCheckBeforeStart() { }
	// RVA: 0x40f0974 VA: 0x7596708974
	public override IDrawableRange get_rangeToShow() { }
	// RVA: 0x40f0ad0 VA: 0x7596708ad0
	public override Void OnInit() { }
	// RVA: 0x40f0c78 VA: 0x7596708c78
	public override Void AssignData(SkillData data, Character owner, Blackboard externalBlackboard, Delta modifier) { }
	// RVA: 0x40f0dcc VA: 0x7596708dcc
	protected override Boolean DoCast(FinishCallbackDelegate finishCb, PlayerSide operationSide) { }
	// RVA: 0x40ef838 VA: 0x7596707838
	protected override Void OnCastFinish(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x40f1318 VA: 0x7596709318
	public override Boolean UseSkill(PlayerSide operationSide) { }
	// RVA: 0x40e9d50 VA: 0x7596701d50
	protected override Void OnTick(FP deltaTime) { }
	// RVA: 0x40f1180 VA: 0x7596709180
	private Void _RecoverSp(Int32 delta) { }
	// RVA: 0x40f0394 VA: 0x7596708394
	private Boolean _CheckIfSkillStateUninterruptible() { }
	// RVA: 0x40f1470 VA: 0x7596709470
	public override Boolean get_isAvailableToShowStackCount() { }
	// RVA: 0x40e9f14 VA: 0x7596701f14
	public Void .ctor() { }
	// RVA: 0x40f1510 VA: 0x7596709510
	private static Void .cctor() { }
	// RVA: 0x40f155c VA: 0x759670955c
	private Boolean <>xLuaBaseProxy_get_stateUninterruptible() { }
	// RVA: 0x40f1560 VA: 0x7596709560
	private Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide P0) { }
	// RVA: 0x40f1564 VA: 0x7596709564
	private Boolean <>xLuaBaseProxy_get_shouldCastLikeAttack() { }
	// RVA: 0x40f1568 VA: 0x7596709568
	private Boolean <>xLuaBaseProxy_get_shouldChangeToChargeColor() { }
	// RVA: 0x40f156c VA: 0x759670956c
	private Boolean <>xLuaBaseProxy_get_isRemoteControlled() { }
	// RVA: 0x40f1570 VA: 0x7596709570
	private Boolean <>xLuaBaseProxy_get_forceUseBaseShowRange() { }
	// RVA: 0x40f1574 VA: 0x7596709574
	private Boolean <>xLuaBaseProxy_get_canCastCheck() { }
	// RVA: 0x40f1578 VA: 0x7596709578
	private Boolean <>xLuaBaseProxy_CanCastCheckBeforeStart() { }
	// RVA: 0x40f157c VA: 0x759670957c
	private IDrawableRange <>xLuaBaseProxy_get_rangeToShow() { }
	// RVA: 0x40f1580 VA: 0x7596709580
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x40f1584 VA: 0x7596709584
	private Void <>xLuaBaseProxy_AssignData(SkillData P0, Character P1, Blackboard P2, Delta P3) { }
	// RVA: 0x40f1588 VA: 0x7596709588
	private Void <>xLuaBaseProxy_OnCastFinish(Ability P0, FinishReason P1, Boolean P2) { }
	// RVA: 0x40f1590 VA: 0x7596709590
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x40f1594 VA: 0x7596709594
	private Boolean <>xLuaBaseProxy_get_isAvailableToShowStackCount() { }
}
```