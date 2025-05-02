# BuffAfterAffecting

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean m_waitForAffectingEnd`


## Methods

- `Void GatherBuffs(List`1)`

- `Void GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BuffAfterAffecting : Behaviour, IEffectSource, IBuffSource
{
	private BuffData[] _buffs; // 0x20
	private Boolean m_waitForAffectingEnd; // 0x28
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_OnEvent; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1ebce60 VA: 0x75944d4e60
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ebceec VA: 0x75944d4eec
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ebcf84 VA: 0x75944d4f84
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ebd024 VA: 0x75944d5024
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ebd0a8 VA: 0x75944d50a8
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1ebd224 VA: 0x75944d5224
	public Void .ctor() { }
	// RVA: 0x1ebd2d0 VA: 0x75944d52d0
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ebd2d8 VA: 0x75944d52d8
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ebd2e0 VA: 0x75944d52e0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```