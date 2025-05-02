# AbilityEventCounter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Event _countEvent`

- `Boolean _useAnotherBBKey`

- `Int32 _triggerTimeCount`

- `Int32 _expendPerTrigger`

- `Boolean _resetAfterEnd`

- `Boolean _resetImmediatelyWhenProgressEnd`

- `Boolean _resetWhenAttackFinished`

- `Int32 m_eventCount`

- `Int32 m_maxCount`

- `Int32 m_maxAdditionCount`

- `Boolean m_readyToReset`

- `Boolean m_notCountNext`

- `Boolean m_triggerOnce`


## Properties

- `Event countEvent`

- `Int32 maxCount`

- `Int32 remainingCount`

- `Int32 progressCount`

- `Boolean readyToReset`

- `Boolean reachEnd`


## Methods

- `Event get_countEvent()`

- `Int32 get_maxCount()`

- `Int32 get_remainingCount()`

- `Int32 get_progressCount()`

- `Boolean get_readyToReset()`

- `Boolean get_reachEnd()`

- `Boolean ResetCount()`

- `Void DoResetCount()`

- `Void DiscardRemainingCount()`

- `Void DiscardRemainingCountSoft()`

- `Void NotCountTimes(Boolean)`

- `Void RecoverEventCount(Int32)`

- `Void SetMaxAdditionCount(Int32)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AbilityEventCounter : Behaviour
{
	private Event _countEvent; // 0x20
	private Boolean _useAnotherBBKey; // 0x24
	private Int32 _triggerTimeCount; // 0x28
	private Int32 _expendPerTrigger; // 0x2c
	private Boolean _resetAfterEnd; // 0x30
	private Boolean _resetImmediatelyWhenProgressEnd; // 0x31
	private Boolean _resetWhenAttackFinished; // 0x32
	private Int32 m_eventCount; // 0x34
	private Int32 m_maxCount; // 0x38
	private Int32 m_maxAdditionCount; // 0x3c
	private Boolean m_readyToReset; // 0x40
	private Boolean m_notCountNext; // 0x41
	private Boolean m_triggerOnce; // 0x42
	private static DelegateBridge __Hotfix0_get_countEvent; // 0x0
	private static DelegateBridge __Hotfix0_get_maxCount; // 0x8
	private static DelegateBridge __Hotfix0_get_remainingCount; // 0x10
	private static DelegateBridge __Hotfix0_get_progressCount; // 0x18
	private static DelegateBridge __Hotfix0_get_readyToReset; // 0x20
	private static DelegateBridge __Hotfix0_get_reachEnd; // 0x28
	private static DelegateBridge __Hotfix0_SetData; // 0x30
	private static DelegateBridge __Hotfix0_OnEvent; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0_OnCountEvent; // 0x48
	private static DelegateBridge __Hotfix0_ResetCount; // 0x50
	private static DelegateBridge __Hotfix0_DoResetCount; // 0x58
	private static DelegateBridge __Hotfix0_OnCountReset; // 0x60
	private static DelegateBridge __Hotfix0_GetProgress; // 0x68
	private static DelegateBridge __Hotfix0_DiscardRemainingCount; // 0x70
	private static DelegateBridge __Hotfix0_DiscardRemainingCountSoft; // 0x78
	private static DelegateBridge __Hotfix0_NotCountTimes; // 0x80
	private static DelegateBridge __Hotfix0_RecoverEventCount; // 0x88
	private static DelegateBridge __Hotfix0_SetMaxAdditionCount; // 0x90
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	protected Event countEvent { get; }
	public Int32 maxCount { get; }
	public Int32 remainingCount { get; }
	public Int32 progressCount { get; }
	public Boolean readyToReset { get; }
	protected Boolean reachEnd { get; }

	// RVA: 0x1ebfea4 VA: 0x75944d7ea4
	protected Event get_countEvent() { }
	// RVA: 0x1ebff0c VA: 0x75944d7f0c
	public Int32 get_maxCount() { }
	// RVA: 0x1ebff80 VA: 0x75944d7f80
	public Int32 get_remainingCount() { }
	// RVA: 0x1ebfff4 VA: 0x75944d7ff4
	public Int32 get_progressCount() { }
	// RVA: 0x1ec005c VA: 0x75944d805c
	public Boolean get_readyToReset() { }
	// RVA: 0x1ec00c4 VA: 0x75944d80c4
	protected Boolean get_reachEnd() { }
	// RVA: 0x1ec0240 VA: 0x75944d8240
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ec03a8 VA: 0x75944d83a8
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ec06b4 VA: 0x75944d86b4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1ec0758 VA: 0x75944d8758
	protected virtual Void OnCountEvent(Event ev, Int32 triggerTimeCount, Boolean notCount) { }
	// RVA: 0x1ec07ec VA: 0x75944d87ec
	public Boolean ResetCount() { }
	// RVA: 0x1ec032c VA: 0x75944d832c
	private Void DoResetCount() { }
	// RVA: 0x1ec086c VA: 0x75944d886c
	protected virtual Void OnCountReset() { }
	// RVA: 0x1ec08d0 VA: 0x75944d88d0
	public virtual FP GetProgress() { }
	// RVA: 0x1ec09f0 VA: 0x75944d89f0
	public Void DiscardRemainingCount() { }
	// RVA: 0x1ec0a68 VA: 0x75944d8a68
	public Void DiscardRemainingCountSoft() { }
	// RVA: 0x1ec0ad8 VA: 0x75944d8ad8
	public Void NotCountTimes(Boolean notCount) { }
	// RVA: 0x1ec0b58 VA: 0x75944d8b58
	public Void RecoverEventCount(Int32 count) { }
	// RVA: 0x1ec0be8 VA: 0x75944d8be8
	public Void SetMaxAdditionCount(Int32 count) { }
	// RVA: 0x1ec0c64 VA: 0x75944d8c64
	public override Void PreloadSpecialAudioSignals(String abilityId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1ec0d54 VA: 0x75944d8d54
	public Void .ctor() { }
	// RVA: 0x1ec0dd4 VA: 0x75944d8dd4
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ec0ddc VA: 0x75944d8ddc
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ec0de4 VA: 0x75944d8de4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1ec0dec VA: 0x75944d8dec
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
}
```