# SelectorHitBehaviourWithAllyBlockedEnemy

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `TargetSelector _allySelector`


## Methods

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class SelectorHitBehaviourWithAllyBlockedEnemy : SelectorHitBehaviour
{
	private TargetSelector _allySelector; // 0x80
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_DoSelectTargetToHit; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1d7353c VA: 0x759438b53c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d736a4 VA: 0x759438b6a4
	protected override Void DoSelectTargetToHit(Vector2 inputPos) { }
	// RVA: 0x1d6bcac VA: 0x7594383cac
	public Void .ctor() { }
	// RVA: 0x1d73bc8 VA: 0x759438bbc8
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d73bcc VA: 0x759438bbcc
	private Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2 P0) { }
}
```