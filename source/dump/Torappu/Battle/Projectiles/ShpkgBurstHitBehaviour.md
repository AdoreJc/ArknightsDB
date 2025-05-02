# ShpkgBurstHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Int32 m_currentCol`

- `Act27SideBattleManager m_manager`

- `Int32 m_hitInterval`


## Methods

- `Void _ShpkgBurstSelectTargetToHit()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class ShpkgBurstHitBehaviour : SelectorHitBehaviour
{
	private Int32 m_currentCol; // 0x80
	private Act27SideBattleManager m_manager; // 0x88
	private Int32 m_hitInterval; // 0x90
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_DoSelectTargetToHit; // 0x8
	private static DelegateBridge __Hotfix0__ShpkgBurstSelectTargetToHit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d74e44 VA: 0x759438ce44
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d75068 VA: 0x759438d068
	protected override Void DoSelectTargetToHit(Vector2 inputPos) { }
	// RVA: 0x1d7510c VA: 0x759438d10c
	private Void _ShpkgBurstSelectTargetToHit() { }
	// RVA: 0x1d752e4 VA: 0x759438d2e4
	public Void .ctor() { }
	// RVA: 0x1d75358 VA: 0x759438d358
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d7535c VA: 0x759438d35c
	private Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2 P0) { }
}
```