# ProbAdditionNextAtkTalent

**Namespace:** `Torappu.Battle`


## Fields

- `FamilyGroupMask _familyMask`

- `String _probKey`

- `Single m_prob`


## Methods

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Boolean <>xLuaBaseProxy_OnBeforeAttack(Ability, Boolean)`

- `Void <>xLuaBaseProxy_OnAfterAttack(Ability, Boolean, FinishReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ProbAdditionNextAtkTalent : Talent
{
	private FamilyGroupMask _familyMask; // 0x88
	private String _probKey; // 0x90
	private Single m_prob; // 0x98
	private static DelegateBridge __Hotfix0_AssignData; // 0x0
	private static DelegateBridge __Hotfix0_DoAttach; // 0x8
	private static DelegateBridge __Hotfix0_DoDetach; // 0x10
	private static DelegateBridge __Hotfix0_OnBeforeAttack; // 0x18
	private static DelegateBridge __Hotfix0_OnAfterAttack; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1b7d238 VA: 0x7594195238
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b7d344 VA: 0x7594195344
	protected override Void DoAttach() { }
	// RVA: 0x1b7d3a8 VA: 0x75941953a8
	protected override Void DoDetach() { }
	// RVA: 0x1b7d444 VA: 0x7594195444
	public override Boolean OnBeforeAttack(Ability nextAbility, Boolean isCombat) { }
	// RVA: 0x1b7d5cc VA: 0x75941955cc
	public override Void OnAfterAttack(Ability lastAbility, Boolean isCombat, FinishReason reason) { }
	// RVA: 0x1b7d6a0 VA: 0x75941956a0
	public Void .ctor() { }
	// RVA: 0x1b7d71c VA: 0x759419571c
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
	// RVA: 0x1b7d720 VA: 0x7594195720
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b7d724 VA: 0x7594195724
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1b7d728 VA: 0x7594195728
	private Boolean <>xLuaBaseProxy_OnBeforeAttack(Ability P0, Boolean P1) { }
	// RVA: 0x1b7d730 VA: 0x7594195730
	private Void <>xLuaBaseProxy_OnAfterAttack(Ability P0, Boolean P1, FinishReason P2) { }
}
```