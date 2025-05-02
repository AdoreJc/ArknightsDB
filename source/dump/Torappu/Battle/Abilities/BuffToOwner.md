# BuffToOwner

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `ExtraCondition _extraCondition`

- `Event _extraConditionTiming`

- `Int32 _maxTarget`

- `Boolean _loadMaxTargetFromBlackboard`

- `Event _runActionOnEvent`

- `Boolean _onlyRunOnce`

- `Boolean m_run`

- `Int32 m_maxTargetNum`

- `Boolean m_extraConditionFlag`


## Properties

- `Boolean ExtraConditionNotNone`

- `Boolean ExtraCondition1`


## Methods

- `Boolean get_ExtraConditionNotNone()`

- `Boolean get_ExtraCondition1()`

- `Void _AddBuffs()`

- `Void GatherBuffs(List`1)`

- `Void GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_OnCastStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BuffToOwner : Behaviour, IEffectSource, IBuffSource
{
	private ExtraCondition _extraCondition; // 0x20
	private Event _extraConditionTiming; // 0x24
	private Int32 _maxTarget; // 0x28
	private Boolean _loadMaxTargetFromBlackboard; // 0x2c
	private Event _runActionOnEvent; // 0x30
	private BuffData[] _buffs; // 0x38
	private Boolean _onlyRunOnce; // 0x40
	private Boolean m_run; // 0x41
	private Int32 m_maxTargetNum; // 0x44
	private Boolean m_extraConditionFlag; // 0x48
	private static DelegateBridge __Hotfix0_get_ExtraConditionNotNone; // 0x0
	private static DelegateBridge __Hotfix0_get_ExtraCondition1; // 0x8
	private static DelegateBridge __Hotfix0_SetData; // 0x10
	private static DelegateBridge __Hotfix0_OnEvent; // 0x18
	private static DelegateBridge __Hotfix0__AddBuffs; // 0x20
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x28
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x30
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Boolean ExtraConditionNotNone { get; }
	private Boolean ExtraCondition1 { get; }

	// RVA: 0x1ebe908 VA: 0x75944d6908
	private Boolean get_ExtraConditionNotNone() { }
	// RVA: 0x1ebe978 VA: 0x75944d6978
	private Boolean get_ExtraCondition1() { }
	// RVA: 0x1ebe9e8 VA: 0x75944d69e8
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ebeac4 VA: 0x75944d6ac4
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ebecf8 VA: 0x75944d6cf8
	private Void _AddBuffs() { }
	// RVA: 0x1ebee90 VA: 0x75944d6e90
	public override Void OnCastStart() { }
	// RVA: 0x1ebeef8 VA: 0x75944d6ef8
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ebef98 VA: 0x75944d6f98
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ebf01c VA: 0x75944d701c
	public Void .ctor() { }
	// RVA: 0x1ebf0e4 VA: 0x75944d70e4
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ebf0ec VA: 0x75944d70ec
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ebf0f4 VA: 0x75944d70f4
	private Void <>xLuaBaseProxy_OnCastStart() { }
}
```