# BuffToCastTargets

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _limitTargetNum`

- `Int32 _maxNum`

- `FilterType _postFilter`

- `ExtraCondition _extraCondition`

- `Boolean _clearBuffWhenChangeTarget`

- `Boolean _alsoClearBuffWhenCastInterrupted`

- `Int32 m_maxTargetNum`


## Properties

- `Boolean NotFilterTypeAll`

- `Boolean NotFilterTypeAllAndLimitTargetNum`

- `Boolean castTargetsEqualToOne`

- `Boolean clearBuffWhenChangeTarget`


## Methods

- `Boolean get_NotFilterTypeAll()`

- `Boolean get_NotFilterTypeAllAndLimitTargetNum()`

- `Boolean get_castTargetsEqualToOne()`

- `Boolean get_clearBuffWhenChangeTarget()`

- `Void GatherBuffs(List`1)`

- `Void GatherEffects(List`1)`

- `Void _RemoveLastTargetBuffsAndClear()`

- `Void _ResetTarget(Entity)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity)`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BuffToCastTargets : Behaviour, IEffectSource, IBuffSource
{
	private Boolean _limitTargetNum; // 0x20
	private Int32 _maxNum; // 0x24
	private FilterType _postFilter; // 0x28
	private ExtraCondition _extraCondition; // 0x2c
	private Boolean _clearBuffWhenChangeTarget; // 0x30
	private Boolean _alsoClearBuffWhenCastInterrupted; // 0x31
	private BuffData[] _buffs; // 0x38
	private Int32 m_maxTargetNum; // 0x40
	private readonly List`1 m_validCastTargets; // 0x48
	private ObjectPtr`1 m_lastTarget; // 0x50
	private List`1 m_lastTargetBuffUids; // 0x60
	private static DelegateBridge __Hotfix0_get_NotFilterTypeAll; // 0x0
	private static DelegateBridge __Hotfix0_get_NotFilterTypeAllAndLimitTargetNum; // 0x8
	private static DelegateBridge __Hotfix0_get_castTargetsEqualToOne; // 0x10
	private static DelegateBridge __Hotfix0_get_clearBuffWhenChangeTarget; // 0x18
	private static DelegateBridge __Hotfix0_SetData; // 0x20
	private static DelegateBridge __Hotfix0_OnEvent; // 0x28
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x30
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x38
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x40
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x48
	private static DelegateBridge __Hotfix0__RemoveLastTargetBuffsAndClear; // 0x50
	private static DelegateBridge __Hotfix0__ResetTarget; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Boolean NotFilterTypeAll { get; }
	private Boolean NotFilterTypeAllAndLimitTargetNum { get; }
	private Boolean castTargetsEqualToOne { get; }
	private Boolean clearBuffWhenChangeTarget { get; }

	// RVA: 0x1ebdbc8 VA: 0x75944d5bc8
	private Boolean get_NotFilterTypeAll() { }
	// RVA: 0x1ebdc38 VA: 0x75944d5c38
	private Boolean get_NotFilterTypeAllAndLimitTargetNum() { }
	// RVA: 0x1ebdcb8 VA: 0x75944d5cb8
	private Boolean get_castTargetsEqualToOne() { }
	// RVA: 0x1ebdd28 VA: 0x75944d5d28
	private Boolean get_clearBuffWhenChangeTarget() { }
	// RVA: 0x1ebdd90 VA: 0x75944d5d90
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ebde68 VA: 0x75944d5e68
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ebe290 VA: 0x75944d6290
	public override Void OnCastOnTarget(Entity target) { }
	// RVA: 0x1ebe600 VA: 0x75944d6600
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ebe6b0 VA: 0x75944d66b0
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ebe750 VA: 0x75944d6750
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ebe158 VA: 0x75944d6158
	private Void _RemoveLastTargetBuffsAndClear() { }
	// RVA: 0x1ebe4f0 VA: 0x75944d64f0
	private Void _ResetTarget(Entity target) { }
	// RVA: 0x1ebe7d4 VA: 0x75944d67d4
	public Void .ctor() { }
	// RVA: 0x1ebe8e8 VA: 0x75944d68e8
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ebe8f0 VA: 0x75944d68f0
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ebe8f8 VA: 0x75944d68f8
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0) { }
	// RVA: 0x1ebe900 VA: 0x75944d6900
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
}
```