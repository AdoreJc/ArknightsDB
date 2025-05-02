# SelfAbilityTrigger

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TriggerTiming _timing`

- `FamilyGroupMask _mask`


## Properties

- `FamilyGroupMask mask`


## Methods

- `FamilyGroupMask get_mask()`

- `Void Apply(Entity, Entity, Ability, Blackboard)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class SelfAbilityTrigger : Behaviour, IAbilityAttachment
{
	private TriggerTiming _timing; // 0x20
	private FamilyGroupMask _mask; // 0x24
	private static DelegateBridge __Hotfix0_get_mask; // 0x0
	private static DelegateBridge __Hotfix0_Preprocess; // 0x8
	private static DelegateBridge __Hotfix0_ApplyAttackAction; // 0x10
	private static DelegateBridge __Hotfix0_OnEvent; // 0x18
	private static DelegateBridge __Hotfix0_Apply; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public FamilyGroupMask mask { get; }

	// RVA: 0x1ebc620 VA: 0x75944d4620
	public FamilyGroupMask get_mask() { }
	// RVA: 0x1ebc4b4 VA: 0x75944d44b4
	protected virtual Boolean Preprocess(Entity target, Entity owner, Ability ability, Blackboard blackboard) { }
	// RVA: 0x1ebc558 VA: 0x75944d4558
	protected virtual Boolean ApplyAttackAction(Entity target, Entity owner, Ability ability, Blackboard blackboard) { }
	// RVA: 0x1ebc688 VA: 0x75944d4688
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ebc78c VA: 0x75944d478c
	public Void Apply(Entity target, Entity owner, Ability ability, Blackboard blackboard) { }
	// RVA: 0x1ebc440 VA: 0x75944d4440
	public Void .ctor() { }
	// RVA: 0x1ebc890 VA: 0x75944d4890
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```