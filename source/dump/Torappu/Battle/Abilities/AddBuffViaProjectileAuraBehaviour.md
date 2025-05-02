# AddBuffViaProjectileAuraBehaviour

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `ProjectileAuraAbility m_auraAbility`


## Methods

- `Void GatherEffects(List`1)`

- `Void GatherBuffs(List`1)`

- `Void _ClearBuffs()`

- `Void <>xLuaBaseProxy_Init(AbilityStandard)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AddBuffViaProjectileAuraBehaviour : ProjectileAuraBehaviour, IEffectSource, IBuffSource
{
	private BuffData[] _buffs; // 0x20
	private ProjectileAuraAbility m_auraAbility; // 0x28
	private List`1 m_buffUid; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge __Hotfix0__ClearBuffs; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1ecddc8 VA: 0x75944e5dc8
	public override Void Init(AbilityStandard ability) { }
	// RVA: 0x1ecdfac VA: 0x75944e5fac
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1ece27c VA: 0x75944e627c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ece300 VA: 0x75944e6300
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ece18c VA: 0x75944e618c
	private Void _ClearBuffs() { }
	// RVA: 0x1ece3a0 VA: 0x75944e63a0
	public Void .ctor() { }
	// RVA: 0x1ece4a0 VA: 0x75944e64a0
	private Void <>xLuaBaseProxy_Init(AbilityStandard P0) { }
	// RVA: 0x1ece4a8 VA: 0x75944e64a8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```