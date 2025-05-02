# TriggerAudioSignalBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _preDelay`

- `Boolean _useAbilityPlaybackSpeed`

- `String _customAbilityAlias`

- `AbilityStandard m_standardAbility`

- `Single m_preDelay`


## Properties

- `Boolean useAbilityPlaybackSpeed`

- `Single abilityPlaybackSpeed`


## Methods

- `Boolean get_useAbilityPlaybackSpeed()`

- `Single get_abilityPlaybackSpeed()`

- `IEnumerator _DoEmitAudioSignal(Vector3)`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`

- `Void <>xLuaBaseProxy_OnProjectileBorn()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class TriggerAudioSignalBehaviour : Behaviour
{
	private Single _preDelay; // 0x24
	private Boolean _useAbilityPlaybackSpeed; // 0x28
	private String _customAbilityAlias; // 0x30
	private AbilityStandard m_standardAbility; // 0x38
	private Single m_preDelay; // 0x40
	private static DelegateBridge __Hotfix0_get_useAbilityPlaybackSpeed; // 0x0
	private static DelegateBridge __Hotfix0_get_abilityPlaybackSpeed; // 0x8
	private static DelegateBridge __Hotfix0__DoEmitAudioSignal; // 0x10
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x18
	private static DelegateBridge __Hotfix0_OnProjectileBorn; // 0x20
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Boolean useAbilityPlaybackSpeed { get; }
	private Single abilityPlaybackSpeed { get; }

	// RVA: 0x1d96010 VA: 0x75943ae010
	private Boolean get_useAbilityPlaybackSpeed() { }
	// RVA: 0x1d96078 VA: 0x75943ae078
	private Single get_abilityPlaybackSpeed() { }
	// RVA: 0x1d96140 VA: 0x75943ae140
	private IEnumerator _DoEmitAudioSignal(Vector3 pos) { }
	// RVA: 0x1d9624c VA: 0x75943ae24c
	public override Void OnHitTarget(Entity target) { }
	// RVA: 0x1d9642c VA: 0x75943ae42c
	public override Void OnProjectileBorn() { }
	// RVA: 0x1d9663c VA: 0x75943ae63c
	public override Void OnProjectileStop() { }
	// RVA: 0x1d966dc VA: 0x75943ae6dc
	public Void .ctor() { }
	// RVA: 0x1d9674c VA: 0x75943ae74c
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
	// RVA: 0x1d96754 VA: 0x75943ae754
	private Void <>xLuaBaseProxy_OnProjectileBorn() { }
	// RVA: 0x1d9675c VA: 0x75943ae75c
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```