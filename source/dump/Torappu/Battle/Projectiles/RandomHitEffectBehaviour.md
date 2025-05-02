# RandomHitEffectBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Methods

- `String _SelectEffectForRandom()`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class RandomHitEffectBehaviour : EffectBehaviour, IEffectSource
{
	private String[] _randomEffectsWhenHit; // 0x90
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x0
	private static DelegateBridge __Hotfix0__SelectEffectForRandom; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1d6eb58 VA: 0x7594386b58
	public override Void OnHitTarget(Entity target) { }
	// RVA: 0x1d6f060 VA: 0x7594387060
	private String _SelectEffectForRandom() { }
	// RVA: 0x1d6f190 VA: 0x7594387190
	public Void .ctor() { }
	// RVA: 0x1d6f23c VA: 0x759438723c
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
}
```