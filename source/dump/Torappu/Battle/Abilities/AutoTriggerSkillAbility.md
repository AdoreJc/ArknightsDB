# AutoTriggerSkillAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `BasicSkill m_skill`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AutoTriggerSkillAbility : PassiveBuffAbility
{
	private ObjectPtr`1 m_character; // 0x110
	private BasicSkill m_skill; // 0x120
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1e62024 VA: 0x759447a024
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e62284 VA: 0x759447a284
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e62414 VA: 0x759447a414
	public Void .ctor() { }
	// RVA: 0x1e62480 VA: 0x759447a480
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e624a8 VA: 0x759447a4a8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```