# BurstCastSkill

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _burstOnOverload`

- `Boolean m_isDuringBurstAttack`

- `BurstAttackGroup m_burstAttackGroup`


## Properties

- `BurstAttackGroup burstAttackGroup`


## Methods

- `BurstAttackGroup get_burstAttackGroup()`

- `Void FinishCallbackDelegate(Ability, FinishReason, Boolean)`

- `Boolean <>xLuaBaseProxy_get_canUseDiscardAbility()`

- `Boolean <>xLuaBaseProxy_OnBeforeAttack(Ability, Boolean)`

- `Boolean <>xLuaBaseProxy_IsDiscardable()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnCastFinish(Ability, FinishReason, Boolean)`

- `Boolean <>xLuaBaseProxy_UseDiscardAbility()`

- `Void <>xLuaBaseProxy_OnDiscard()`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BurstCastSkill : CastSkillWithLimitTimes
{
	private Boolean _burstOnOverload; // 0x158
	private BuffData[] _buffWhenDiscardWithBullet; // 0x160
	private Boolean m_isDuringBurstAttack; // 0x168
	private BurstAttackGroup m_burstAttackGroup; // 0x170
	private static DelegateBridge __Hotfix0_get_burstAttackGroup; // 0x0
	private static DelegateBridge __Hotfix0_get_canUseDiscardAbility; // 0x8
	private static DelegateBridge __Hotfix0_OnBeforeAttack; // 0x10
	private static DelegateBridge __Hotfix0_IsDiscardable; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x28
	private static DelegateBridge __Hotfix0_UseDiscardAbility; // 0x30
	private static DelegateBridge __Hotfix0_FinishCallbackDelegate; // 0x38
	private static DelegateBridge __Hotfix0_OnDiscard; // 0x40
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public BurstAttackGroup burstAttackGroup { get; }
	public override Boolean canUseDiscardAbility { get; }

	// RVA: 0x40ef06c VA: 0x759670706c
	public BurstAttackGroup get_burstAttackGroup() { }
	// RVA: 0x40ef2f4 VA: 0x75967072f4
	public override Boolean get_canUseDiscardAbility() { }
	// RVA: 0x40ef440 VA: 0x7596707440
	public override Boolean OnBeforeAttack(Ability ability, Boolean isCombat) { }
	// RVA: 0x40ef4e8 VA: 0x75967074e8
	public override Boolean IsDiscardable() { }
	// RVA: 0x40ef640 VA: 0x7596707640
	public override Void OnInit() { }
	// RVA: 0x40ef78c VA: 0x759670778c
	protected override Void OnCastFinish(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x40ef974 VA: 0x7596707974
	protected override Boolean UseDiscardAbility() { }
	// RVA: 0x40efb84 VA: 0x7596707b84
	private Void FinishCallbackDelegate(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x40efca8 VA: 0x7596707ca8
	protected override Void OnDiscard() { }
	// RVA: 0x40efef4 VA: 0x7596707ef4
	public override Void GatherBuffs(List`1 result) { }
	// RVA: 0x40effa0 VA: 0x7596707fa0
	public Void .ctor() { }
	// RVA: 0x40f0198 VA: 0x7596708198
	private Boolean <>xLuaBaseProxy_get_canUseDiscardAbility() { }
	// RVA: 0x40f0200 VA: 0x7596708200
	private Boolean <>xLuaBaseProxy_OnBeforeAttack(Ability P0, Boolean P1) { }
	// RVA: 0x40f0208 VA: 0x7596708208
	private Boolean <>xLuaBaseProxy_IsDiscardable() { }
	// RVA: 0x40f020c VA: 0x759670820c
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x40f0210 VA: 0x7596708210
	private Void <>xLuaBaseProxy_OnCastFinish(Ability P0, FinishReason P1, Boolean P2) { }
	// RVA: 0x40f0218 VA: 0x7596708218
	private Boolean <>xLuaBaseProxy_UseDiscardAbility() { }
	// RVA: 0x40f021c VA: 0x759670821c
	private Void <>xLuaBaseProxy_OnDiscard() { }
	// RVA: 0x40f0220 VA: 0x7596708220
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```