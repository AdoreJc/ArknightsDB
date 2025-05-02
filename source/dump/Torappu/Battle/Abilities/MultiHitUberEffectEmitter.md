# MultiHitUberEffectEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _useRandomHitEffect`


## Methods

- `Void <>xLuaBaseProxy_Init(AbilityStandard)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiHitUberEffectEmitter : UberEffectEmitter
{
	private Boolean _useRandomHitEffect; // 0x58
	private HitEffectGroup[] _hitGroups; // 0x60
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x8
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x10
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x18
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1ec7d4c VA: 0x75944dfd4c
	public override Void Init(AbilityStandard ability) { }
	// RVA: 0x1ec7eb0 VA: 0x75944dfeb0
	public override Void OnCastStart() { }
	// RVA: 0x1ec8004 VA: 0x75944e0004
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ec8164 VA: 0x75944e0164
	public override Void OnCastOnTarget(Entity target) { }
	// RVA: 0x1ec834c VA: 0x75944e034c
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ec865c VA: 0x75944e065c
	public Void .ctor() { }
	// RVA: 0x1ec86c8 VA: 0x75944e06c8
	private Void <>xLuaBaseProxy_Init(AbilityStandard P0) { }
	// RVA: 0x1ec86cc VA: 0x75944e06cc
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ec86d0 VA: 0x75944e06d0
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
	// RVA: 0x1ec86d4 VA: 0x75944e06d4
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0) { }
	// RVA: 0x1ec86d8 VA: 0x75944e06d8
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```