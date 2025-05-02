# ChantBeforeSkill

**Namespace:** `Torappu.Battle.Skills`


## Fields

- `AnimationBundle _animation`

- `Boolean _suspendableWhenMainChant`

- `Boolean _suspendableWhenExtraChant`

- `Boolean _finishBuffWhenSkillEnd`

- `Boolean m_started`

- `Single m_duration`

- `Single m_extraDuration`

- `Single m_totalDuration`

- `PeriodicTimer m_durationTimer`

- `PeriodicTimer m_extraDurationTimer`


## Properties

- `Single chantProgress`

- `Boolean isInChant`

- `Boolean isInExtraChant`

- `Boolean chantAvailable`

- `Boolean suspendable`


## Methods

- `Void GatherBuffs(List`1)`

- `Void GatherEffects(List`1)`

- `Single get_chantProgress()`

- `Boolean get_isInChant()`

- `Boolean get_isInExtraChant()`

- `Boolean get_chantAvailable()`

- `Boolean get_suspendable()`

- `IEnumerator StartChant()`

- `Void _OnChantStart()`

- `Void _OnChantEnd()`

- `Void _OnMainChantSucceed()`

- `Void _OnExtraChantSucceed()`

- `Void InterruptChantIfNot()`

- `Void _ResetChant()`

- `Void _ClearBuffs()`

- `Void _PlayMainChantEffects()`

- `Void _PlayExtraChantEffects()`

- `Void _PlayBeforeEndEffects()`

- `Void _PlayChantSuccessEffects()`

- `Void _ClearChantDuringEffects()`

- `Void <>xLuaBaseProxy_AssignData(Blackboard)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnCastSucceed()`

- `Void <>xLuaBaseProxy_OnSkillEnd()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Skills
public class ChantBeforeSkill : Behaviour, IEffectSource, IBuffSource
{
	private AnimationBundle _animation; // 0x20
	private Boolean _suspendableWhenMainChant; // 0x38
	private Boolean _suspendableWhenExtraChant; // 0x39
	private Boolean _finishBuffWhenSkillEnd; // 0x3a
	private BuffData[] _buffsWhenStartChant; // 0x40
	private BuffData[] _buffsWhenMainChantEnd; // 0x48
	private BuffData[] _buffsWhenExtraChantEnd; // 0x50
	private String[] _mainChantEffects; // 0x58
	private String[] _extraChantEffects; // 0x60
	private String[] _chantSuccessEffects; // 0x68
	private String[] _beforeEndEffects; // 0x70
	private Boolean m_started; // 0x78
	private Single m_duration; // 0x7c
	private Single m_extraDuration; // 0x80
	private Single m_totalDuration; // 0x84
	private PeriodicTimer m_durationTimer; // 0x88
	private PeriodicTimer m_extraDurationTimer; // 0x90
	private List`1 m_buffUids; // 0x98
	private List`1 m_mainChantEffectList; // 0xa0
	private List`1 m_extraChantEffectList; // 0xa8
	private AudioAtom[] m_atoms; // 0xb0
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_get_chantProgress; // 0x10
	private static DelegateBridge __Hotfix0_get_isInChant; // 0x18
	private static DelegateBridge __Hotfix0_get_isInExtraChant; // 0x20
	private static DelegateBridge __Hotfix0_get_chantAvailable; // 0x28
	private static DelegateBridge __Hotfix0_get_suspendable; // 0x30
	private static DelegateBridge __Hotfix0_AssignData; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0_OnCastSucceed; // 0x48
	private static DelegateBridge __Hotfix0_OnSkillEnd; // 0x50
	private static DelegateBridge __Hotfix0_StartChant; // 0x58
	private static DelegateBridge __Hotfix0__OnChantStart; // 0x60
	private static DelegateBridge __Hotfix0__OnChantEnd; // 0x68
	private static DelegateBridge __Hotfix0__OnMainChantSucceed; // 0x70
	private static DelegateBridge __Hotfix0__OnExtraChantSucceed; // 0x78
	private static DelegateBridge __Hotfix0_InterruptChantIfNot; // 0x80
	private static DelegateBridge __Hotfix0__ResetChant; // 0x88
	private static DelegateBridge __Hotfix0__ClearBuffs; // 0x90
	private static DelegateBridge __Hotfix0__PlayMainChantEffects; // 0x98
	private static DelegateBridge __Hotfix0__PlayExtraChantEffects; // 0xa0
	private static DelegateBridge __Hotfix0__PlayBeforeEndEffects; // 0xa8
	private static DelegateBridge __Hotfix0__PlayChantSuccessEffects; // 0xb0
	private static DelegateBridge __Hotfix0__ClearChantDuringEffects; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public Single chantProgress { get; }
	public Boolean isInChant { get; }
	public Boolean isInExtraChant { get; }
	public Boolean chantAvailable { get; }
	public Boolean suspendable { get; }

	// RVA: 0x1d30b2c VA: 0x7594348b2c
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1d30c48 VA: 0x7594348c48
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d30d98 VA: 0x7594348d98
	public Single get_chantProgress() { }
	// RVA: 0x1d30f60 VA: 0x7594348f60
	public Boolean get_isInChant() { }
	// RVA: 0x1d30ff8 VA: 0x7594348ff8
	public Boolean get_isInExtraChant() { }
	// RVA: 0x1d3106c VA: 0x759434906c
	public Boolean get_chantAvailable() { }
	// RVA: 0x1d310e8 VA: 0x75943490e8
	public Boolean get_suspendable() { }
	// RVA: 0x1d31194 VA: 0x7594349194
	public override Void AssignData(Blackboard blackboard) { }
	// RVA: 0x1d3128c VA: 0x759434928c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d3192c VA: 0x759434992c
	public override Void OnCastSucceed() { }
	// RVA: 0x1d31abc VA: 0x7594349abc
	public override Void OnSkillEnd() { }
	// RVA: 0x1d31c34 VA: 0x7594349c34
	public IEnumerator StartChant() { }
	// RVA: 0x1d31d08 VA: 0x7594349d08
	private Void _OnChantStart() { }
	// RVA: 0x1d319a0 VA: 0x75943499a0
	private Void _OnChantEnd() { }
	// RVA: 0x1d3147c VA: 0x759434947c
	private Void _OnMainChantSucceed() { }
	// RVA: 0x1d317f4 VA: 0x75943497f4
	private Void _OnExtraChantSucceed() { }
	// RVA: 0x1d322c8 VA: 0x759434a2c8
	public Void InterruptChantIfNot() { }
	// RVA: 0x1d32240 VA: 0x759434a240
	public Void _ResetChant() { }
	// RVA: 0x1d31b44 VA: 0x7594349b44
	private Void _ClearBuffs() { }
	// RVA: 0x1d32340 VA: 0x759434a340
	private Void _PlayMainChantEffects() { }
	// RVA: 0x1d315a8 VA: 0x75943495a8
	private Void _PlayExtraChantEffects() { }
	// RVA: 0x1d3258c VA: 0x759434a58c
	private Void _PlayBeforeEndEffects() { }
	// RVA: 0x1d31f18 VA: 0x7594349f18
	private Void _PlayChantSuccessEffects() { }
	// RVA: 0x1d320e0 VA: 0x759434a0e0
	private Void _ClearChantDuringEffects() { }
	// RVA: 0x1d32754 VA: 0x759434a754
	public Void .ctor() { }
	// RVA: 0x1d32968 VA: 0x759434a968
	private Void <>xLuaBaseProxy_AssignData(Blackboard P0) { }
	// RVA: 0x1d32970 VA: 0x759434a970
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d32978 VA: 0x759434a978
	private Void <>xLuaBaseProxy_OnCastSucceed() { }
	// RVA: 0x1d32980 VA: 0x759434a980
	private Void <>xLuaBaseProxy_OnSkillEnd() { }
}
```