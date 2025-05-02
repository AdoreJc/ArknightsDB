# CastSkillWithLimitTimes

**Namespace:** `Torappu.Battle`


## Fields

- `AbilityEventCounter _progressSource`

- `Boolean _fetchFromMainAttack`

- `Boolean _fromMainRawAttack`

- `Int32 _modeIndex`

- `Boolean _useExtraModeProgress`

- `Boolean _finishSkillWithProgress`

- `Boolean _canDiscardRemainingCount`

- `Boolean _hideProgressOnAffect`

- `Boolean _isOverloadSkill`

- `AbilityEventCounter m_progressSource`


## Properties

- `Boolean fetchFromMainAttack`

- `Int32 progressCount`

- `Int32 remainingCount`

- `Int32 maxCount`

- `Boolean ownerIsInBulletMode`


## Methods

- `Boolean get_fetchFromMainAttack()`

- `Int32 get_progressCount()`

- `Int32 get_remainingCount()`

- `Int32 get_maxCount()`

- `FP _GetProgress()`

- `Void _FetchCounterSource()`

- `Void _FetchExtraCounter()`

- `Boolean _ResetExtraModeCount()`

- `Boolean _ExtraModeCanReset()`

- `Boolean get_ownerIsInBulletMode()`

- `String GetCountProgress()`

- `Void RecoverEventCount(Int32)`

- `Void SetMaxAdditionCount(Buff, Int32)`

- `Boolean <>xLuaBaseProxy_get_isOverloadSkill()`

- `FP <>xLuaBaseProxy_get_remainingProgress()`

- `Boolean <>xLuaBaseProxy_get_hideProgressFlag()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Boolean <>xLuaBaseProxy_IsDiscardable()`

- `Boolean <>xLuaBaseProxy_UseSkill(PlayerSide)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CastSkillWithLimitTimes : CastSkill
{
	private AbilityEventCounter _progressSource; // 0x120
	private Boolean _fetchFromMainAttack; // 0x128
	private Boolean _fromMainRawAttack; // 0x129
	private Int32 _modeIndex; // 0x12c
	private Int32[] _extraModeIndex; // 0x130
	private Boolean _useExtraModeProgress; // 0x138
	private Boolean _finishSkillWithProgress; // 0x139
	private Boolean _canDiscardRemainingCount; // 0x13a
	private Boolean _hideProgressOnAffect; // 0x13b
	private Boolean _isOverloadSkill; // 0x13c
	private AbilityEventCounter m_progressSource; // 0x140
	private Dictionary`2 m_extraProgressSources; // 0x148
	private Dictionary`2 m_eventCounterMaxCountModifier; // 0x150
	private static DelegateBridge __Hotfix0_get_isOverloadSkill; // 0x0
	private static DelegateBridge __Hotfix0_get_fetchFromMainAttack; // 0x8
	private static DelegateBridge __Hotfix0_get_remainingProgress; // 0x10
	private static DelegateBridge __Hotfix0_get_progressCount; // 0x18
	private static DelegateBridge __Hotfix0_get_remainingCount; // 0x20
	private static DelegateBridge __Hotfix0_get_maxCount; // 0x28
	private static DelegateBridge __Hotfix0_get_hideProgressFlag; // 0x30
	private static DelegateBridge __Hotfix0_get_canUseDiscardAbility; // 0x38
	private static DelegateBridge __Hotfix0_OnInit; // 0x40
	private static DelegateBridge __Hotfix0__GetProgress; // 0x48
	private static DelegateBridge __Hotfix0__FetchCounterSource; // 0x50
	private static DelegateBridge __Hotfix0__FetchExtraCounter; // 0x58
	private static DelegateBridge __Hotfix0__ResetExtraModeCount; // 0x60
	private static DelegateBridge __Hotfix0__ExtraModeCanReset; // 0x68
	private static DelegateBridge __Hotfix0_get_ownerIsInBulletMode; // 0x70
	private static DelegateBridge __Hotfix0_OnTick; // 0x78
	private static DelegateBridge __Hotfix0_IsDiscardable; // 0x80
	private static DelegateBridge __Hotfix0_UseSkill; // 0x88
	private static DelegateBridge __Hotfix0_UseDiscardAbility; // 0x90
	private static DelegateBridge __Hotfix0_OnDiscard; // 0x98
	private static DelegateBridge __Hotfix0_GetCountProgress; // 0xa0
	private static DelegateBridge __Hotfix0_NotCountTimes; // 0xa8
	private static DelegateBridge __Hotfix0_RecoverEventCount; // 0xb0
	private static DelegateBridge __Hotfix0_SetMaxAdditionCount; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public override Boolean isOverloadSkill { get; }
	protected Boolean fetchFromMainAttack { get; }
	public override FP remainingProgress { get; }
	private Int32 progressCount { get; }
	public Int32 remainingCount { get; }
	public Int32 maxCount { get; }
	public override Boolean hideProgressFlag { get; }
	public virtual Boolean canUseDiscardAbility { get; }
	protected Boolean ownerIsInBulletMode { get; }

	// RVA: 0x40f2650 VA: 0x759670a650
	public override Boolean get_isOverloadSkill() { }
	// RVA: 0x40f26b8 VA: 0x759670a6b8
	protected Boolean get_fetchFromMainAttack() { }
	// RVA: 0x40f2720 VA: 0x759670a720
	public override FP get_remainingProgress() { }
	// RVA: 0x40f2920 VA: 0x759670a920
	private Int32 get_progressCount() { }
	// RVA: 0x40efe10 VA: 0x7596707e10
	public Int32 get_remainingCount() { }
	// RVA: 0x40f2b74 VA: 0x759670ab74
	public Int32 get_maxCount() { }
	// RVA: 0x40f2c34 VA: 0x759670ac34
	public override Boolean get_hideProgressFlag() { }
	// RVA: 0x40f019c VA: 0x759670819c
	public virtual Boolean get_canUseDiscardAbility() { }
	// RVA: 0x40ef6c0 VA: 0x75967076c0
	public override Void OnInit() { }
	// RVA: 0x40f27d4 VA: 0x759670a7d4
	private FP _GetProgress() { }
	// RVA: 0x40f2cc0 VA: 0x759670acc0
	private Void _FetchCounterSource() { }
	// RVA: 0x40f2fd4 VA: 0x759670afd4
	private Void _FetchExtraCounter() { }
	// RVA: 0x40f347c VA: 0x759670b47c
	private Boolean _ResetExtraModeCount() { }
	// RVA: 0x40f375c VA: 0x759670b75c
	private Boolean _ExtraModeCanReset() { }
	// RVA: 0x40ef1d0 VA: 0x75967071d0
	protected Boolean get_ownerIsInBulletMode() { }
	// RVA: 0x40f3914 VA: 0x759670b914
	protected override Void OnTick(FP deltaTime) { }
	// RVA: 0x40ef56c VA: 0x759670756c
	public override Boolean IsDiscardable() { }
	// RVA: 0x40f3af8 VA: 0x759670baf8
	public override Boolean UseSkill(PlayerSide operationSide) { }
	// RVA: 0x40efb20 VA: 0x7596707b20
	protected virtual Boolean UseDiscardAbility() { }
	// RVA: 0x40efdac VA: 0x7596707dac
	protected virtual Void OnDiscard() { }
	// RVA: 0x40f3e90 VA: 0x759670be90
	public String GetCountProgress() { }
	// RVA: 0x40f3fd0 VA: 0x759670bfd0
	public virtual Void NotCountTimes(Boolean notCount) { }
	// RVA: 0x40f4140 VA: 0x759670c140
	public Void RecoverEventCount(Int32 count) { }
	// RVA: 0x40f42a8 VA: 0x759670c2a8
	public Void SetMaxAdditionCount(Buff buff, Int32 count) { }
	// RVA: 0x40f0048 VA: 0x7596708048
	public Void .ctor() { }
	// RVA: 0x40f43e0 VA: 0x759670c3e0
	private Boolean <>xLuaBaseProxy_get_isOverloadSkill() { }
	// RVA: 0x40f43e4 VA: 0x759670c3e4
	private FP <>xLuaBaseProxy_get_remainingProgress() { }
	// RVA: 0x40f43e8 VA: 0x759670c3e8
	private Boolean <>xLuaBaseProxy_get_hideProgressFlag() { }
	// RVA: 0x40f43ec VA: 0x759670c3ec
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x40f43f0 VA: 0x759670c3f0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x40f43f4 VA: 0x759670c3f4
	private Boolean <>xLuaBaseProxy_IsDiscardable() { }
	// RVA: 0x40f43f8 VA: 0x759670c3f8
	private Boolean <>xLuaBaseProxy_UseSkill(PlayerSide P0) { }
}
```