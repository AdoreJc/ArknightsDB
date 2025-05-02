# SequenceEffectBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Boolean _useAbilityPlaybackSpeed`

- `String _customAbilityAlias`

- `Int32 _effectGroupStartIndex`

- `Boolean _enableOverloadEffect`

- `Int32 m_currentEffectGroupIndex`

- `AbilityStandard m_ability`


## Properties

- `Boolean useAbilityPlaybackSpeed`

- `Boolean enableOverloadEffect`

- `Single abilityPlaybackSpeed`


## Methods

- `Boolean get_useAbilityPlaybackSpeed()`

- `Boolean get_enableOverloadEffect()`

- `Single get_abilityPlaybackSpeed()`

- `Void <>xLuaBaseProxy_OnProjectileBorn()`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class SequenceEffectBehaviour : EffectBehaviour
{
	private Boolean _useAbilityPlaybackSpeed; // 0x90
	private String _customAbilityAlias; // 0x98
	private Int32 _effectGroupStartIndex; // 0xa0
	private EffectGroup[] _effectGroups; // 0xa8
	private Boolean _enableOverloadEffect; // 0xb0
	private EffectGroup[] _overloadGroups; // 0xb8
	private Int32 m_currentEffectGroupIndex; // 0xc0
	private AbilityStandard m_ability; // 0xc8
	private static DelegateBridge __Hotfix0_get_useAbilityPlaybackSpeed; // 0x0
	private static DelegateBridge __Hotfix0_get_enableOverloadEffect; // 0x8
	private static DelegateBridge __Hotfix0_get_abilityPlaybackSpeed; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileBorn; // 0x18
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x20
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Boolean useAbilityPlaybackSpeed { get; }
	private Boolean enableOverloadEffect { get; }
	private Single abilityPlaybackSpeed { get; }

	// RVA: 0x1d73bd0 VA: 0x759438bbd0
	private Boolean get_useAbilityPlaybackSpeed() { }
	// RVA: 0x1d73c38 VA: 0x759438bc38
	private Boolean get_enableOverloadEffect() { }
	// RVA: 0x1d73ca0 VA: 0x759438bca0
	private Single get_abilityPlaybackSpeed() { }
	// RVA: 0x1d73d68 VA: 0x759438bd68
	public override Void OnProjectileBorn() { }
	// RVA: 0x1d73f80 VA: 0x759438bf80
	public override Void OnHitTarget(Entity target) { }
	// RVA: 0x1d7452c VA: 0x759438c52c
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d74614 VA: 0x759438c614
	public Void .ctor() { }
	// RVA: 0x1d74684 VA: 0x759438c684
	private Void <>xLuaBaseProxy_OnProjectileBorn() { }
	// RVA: 0x1d7468c VA: 0x759438c68c
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
	// RVA: 0x1d74694 VA: 0x759438c694
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```