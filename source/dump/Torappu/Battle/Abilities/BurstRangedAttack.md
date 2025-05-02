# BurstRangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `AbilityEventCounter _abilityEventCounter`


## Methods

- `Void _StackActionsByRemainingCount(IList`1)`

- `String <>xLuaBaseProxy_GetProjectileKey()`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable, out)`

- `Void <>xLuaBaseProxy_PreprocessActionsForProjectile(IList`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BurstRangedAttack : RangedAttackWithConditionalActions
{
	private AbilityEventCounter _abilityEventCounter; // 0x268
	private List`1 s_actionsBuffer; // 0x270
	private List`1 _burstProjectiles; // 0x278
	private static DelegateBridge __Hotfix0_GetProjectileKey; // 0x0
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x8
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x10
	private static DelegateBridge __Hotfix0_CreateProjectile; // 0x18
	private static DelegateBridge __Hotfix0_PreprocessActionsForProjectile; // 0x20
	private static DelegateBridge __Hotfix0__StackActionsByRemainingCount; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1e08788 VA: 0x7594420788
	protected override String GetProjectileKey() { }
	// RVA: 0x1e08860 VA: 0x7594420860
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e08944 VA: 0x7594420944
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e08a00 VA: 0x7594420a00
	protected override Projectile CreateProjectile(ILocatable target, out Projectile fakeProjectile) { }
	// RVA: 0x1e08ab4 VA: 0x7594420ab4
	protected override Void PreprocessActionsForProjectile(IList`1 projectileActions) { }
	// RVA: 0x1e08b80 VA: 0x7594420b80
	private Void _StackActionsByRemainingCount(IList`1 projectileActions) { }
	// RVA: 0x1e08c90 VA: 0x7594420c90
	public Void .ctor() { }
	// RVA: 0x1e08d54 VA: 0x7594420d54
	private String <>xLuaBaseProxy_GetProjectileKey() { }
	// RVA: 0x1e08d5c VA: 0x7594420d5c
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
	// RVA: 0x1e08d64 VA: 0x7594420d64
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e08d6c VA: 0x7594420d6c
	private Projectile <>xLuaBaseProxy_CreateProjectile(ILocatable P0, out Projectile P1) { }
	// RVA: 0x1e08d74 VA: 0x7594420d74
	private Void <>xLuaBaseProxy_PreprocessActionsForProjectile(IList`1 P0) { }
}
```