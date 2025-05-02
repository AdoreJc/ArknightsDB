# GlazeTalentAbilityTrigger

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `BuffData _buff`


## Methods

- `Boolean <>xLuaBaseProxy_Preprocess(Entity, Entity, Ability, Blackboard)`

- `Boolean <>xLuaBaseProxy_ApplyAttackAction(Entity, Entity, Ability, Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class GlazeTalentAbilityTrigger : SelfAbilityTrigger
{
	private BuffData _buff; // 0x28
	private static DelegateBridge __Hotfix0_Preprocess; // 0x0
	private static DelegateBridge __Hotfix0_ApplyAttackAction; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1ebc0c8 VA: 0x75944d40c8
	protected override Boolean Preprocess(Entity target, Entity owner, Ability ability, Blackboard blackboard) { }
	// RVA: 0x1ebc2e8 VA: 0x75944d42e8
	protected override Boolean ApplyAttackAction(Entity target, Entity owner, Ability ability, Blackboard blackboard) { }
	// RVA: 0x1ebc3d4 VA: 0x75944d43d4
	public Void .ctor() { }
	// RVA: 0x1ebc4b0 VA: 0x75944d44b0
	private Boolean <>xLuaBaseProxy_Preprocess(Entity P0, Entity P1, Ability P2, Blackboard P3) { }
	// RVA: 0x1ebc554 VA: 0x75944d4554
	private Boolean <>xLuaBaseProxy_ApplyAttackAction(Entity P0, Entity P1, Ability P2, Blackboard P3) { }
}
```