# ProbReplaceNextAtkTalent

**Namespace:** `Torappu.Battle`


## Fields

- `TargetTrigger _trigger`

- `FamilyGroupMask _familyMask`

- `String _probKey`

- `Boolean _isModeTalent`

- `String _syncProbWithBuffKey`

- `Single m_prob`

- `Buff m_probSyncBuff`


## Properties

- `TargetTrigger trigger`

- `String probKey`

- `Blackboard probBlackboard`


## Methods

- `TargetTrigger get_trigger()`

- `String get_probKey()`

- `Blackboard get_probBlackboard()`

- `Boolean TryHookSearchTarget(out)`

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Boolean <>xLuaBaseProxy_OnBeforeAttack(Ability, Boolean)`

- `Void <>xLuaBaseProxy_OnAfterAttack(Ability, Boolean, FinishReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ProbReplaceNextAtkTalent : Talent, IReplacement
{
	private TargetTrigger _trigger; // 0x88
	private FamilyGroupMask _familyMask; // 0x90
	private String _probKey; // 0x98
	private Boolean _isModeTalent; // 0xa0
	private String _syncProbWithBuffKey; // 0xa8
	private Single m_prob; // 0xb0
	private Buff m_probSyncBuff; // 0xb8
	private static DelegateBridge __Hotfix0_get_trigger; // 0x0
	private static DelegateBridge __Hotfix0_get_probKey; // 0x8
	private static DelegateBridge __Hotfix0_get_probBlackboard; // 0x10
	private static DelegateBridge __Hotfix0_AssignData; // 0x18
	private static DelegateBridge __Hotfix0_DoAttach; // 0x20
	private static DelegateBridge __Hotfix0_DoDetach; // 0x28
	private static DelegateBridge __Hotfix0_OnBeforeAttack; // 0x30
	private static DelegateBridge __Hotfix0_OnAfterAttack; // 0x38
	private static DelegateBridge __Hotfix0_TryHookSearchTarget; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public TargetTrigger trigger { get; }
	public String probKey { get; }
	private Blackboard probBlackboard { get; }

	// RVA: 0x1b7d738 VA: 0x7594195738
	public TargetTrigger get_trigger() { }
	// RVA: 0x1b7d7a0 VA: 0x75941957a0
	public String get_probKey() { }
	// RVA: 0x1b7d834 VA: 0x7594195834
	private Blackboard get_probBlackboard() { }
	// RVA: 0x1b7d984 VA: 0x7594195984
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b7da7c VA: 0x7594195a7c
	protected override Void DoAttach() { }
	// RVA: 0x1b7dae0 VA: 0x7594195ae0
	protected override Void DoDetach() { }
	// RVA: 0x1b7dbb0 VA: 0x7594195bb0
	public override Boolean OnBeforeAttack(Ability oldAbility, Boolean isCombat) { }
	// RVA: 0x1b7de5c VA: 0x7594195e5c
	public override Void OnAfterAttack(Ability oldAbility, Boolean isCombat, FinishReason reason) { }
	// RVA: 0x1b7dfa4 VA: 0x7594195fa4
	public Boolean TryHookSearchTarget(out Boolean isFound) { }
	// RVA: 0x1b7e020 VA: 0x7594196020
	public Void .ctor() { }
	// RVA: 0x1b7e0d4 VA: 0x75941960d4
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
	// RVA: 0x1b7e0d8 VA: 0x75941960d8
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b7e0dc VA: 0x75941960dc
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1b7e0e0 VA: 0x75941960e0
	private Boolean <>xLuaBaseProxy_OnBeforeAttack(Ability P0, Boolean P1) { }
	// RVA: 0x1b7e0e8 VA: 0x75941960e8
	private Void <>xLuaBaseProxy_OnAfterAttack(Ability P0, Boolean P1, FinishReason P2) { }
}
```