# MuzzleGroupEffectEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _muzzleEffect`

- `Event _event`

- `RangedAttack m_rangedAttack`


## Methods

- `Void <>xLuaBaseProxy_Init(AbilityStandard)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MuzzleGroupEffectEmitter : AbstractEffectEmitter
{
	private String _muzzleEffect; // 0x20
	private Event _event; // 0x28
	private RangedAttack m_rangedAttack; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnEvent; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1ec8778 VA: 0x75944e0778
	public override Void Init(AbilityStandard ability) { }
	// RVA: 0x1ec888c VA: 0x75944e088c
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ec8ad4 VA: 0x75944e0ad4
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ec8be8 VA: 0x75944e0be8
	public Void .ctor() { }
	// RVA: 0x1ec8c60 VA: 0x75944e0c60
	private Void <>xLuaBaseProxy_Init(AbilityStandard P0) { }
	// RVA: 0x1ec8c68 VA: 0x75944e0c68
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```