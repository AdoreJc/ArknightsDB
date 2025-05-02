# ConstrainedTalent

**Namespace:** `Torappu.Battle`


## Methods

- `Boolean <>xLuaBaseProxy_OnBeforeAttack(Ability, Boolean)`

- `Void <>xLuaBaseProxy_OnAfterAttack(Ability, Boolean, FinishReason)`

- `Boolean <>xLuaBaseProxy_CheckReborn(out)`

- `Void <>xLuaBaseProxy_ProcessTraitBlackboard(Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ConstrainedTalent : Talent
{
	private static DelegateBridge __Hotfix0_OnBeforeAttack; // 0x0
	private static DelegateBridge __Hotfix0_OnAfterAttack; // 0x8
	private static DelegateBridge __Hotfix0_CheckReborn; // 0x10
	private static DelegateBridge __Hotfix0_ProcessTraitBlackboard; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1b777a8 VA: 0x759418f7a8
	public sealed override Boolean OnBeforeAttack(Ability ability, Boolean isCombat) { }
	// RVA: 0x1b77834 VA: 0x759418f834
	public sealed override Void OnAfterAttack(Ability ability, Boolean isCombat, FinishReason reason) { }
	// RVA: 0x1b778d8 VA: 0x759418f8d8
	public sealed override Boolean CheckReborn(out RebornData respawnData) { }
	// RVA: 0x1b77958 VA: 0x759418f958
	public sealed override Void ProcessTraitBlackboard(Blackboard blackboard) { }
	// RVA: 0x1b779d8 VA: 0x759418f9d8
	public Void .ctor() { }
	// RVA: 0x1b77a44 VA: 0x759418fa44
	private Boolean <>xLuaBaseProxy_OnBeforeAttack(Ability P0, Boolean P1) { }
	// RVA: 0x1b77a4c VA: 0x759418fa4c
	private Void <>xLuaBaseProxy_OnAfterAttack(Ability P0, Boolean P1, FinishReason P2) { }
	// RVA: 0x1b77a54 VA: 0x759418fa54
	private Boolean <>xLuaBaseProxy_CheckReborn(out RebornData P0) { }
	// RVA: 0x1b77a58 VA: 0x759418fa58
	private Void <>xLuaBaseProxy_ProcessTraitBlackboard(Blackboard P0) { }
}
```