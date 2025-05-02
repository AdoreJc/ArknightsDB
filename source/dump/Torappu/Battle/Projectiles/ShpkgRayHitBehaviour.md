# ShpkgRayHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Int32 m_currentRow`

- `Act27SideBattleManager m_manager`

- `Tile m_targetTile`


## Methods

- `Void _ShpkgRaySelectTargetToHit()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class ShpkgRayHitBehaviour : SelectorHitBehaviour
{
	private Int32 m_currentRow; // 0x80
	private Act27SideBattleManager m_manager; // 0x88
	private Tile m_targetTile; // 0x90
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_DoSelectTargetToHit; // 0x8
	private static DelegateBridge __Hotfix0__ShpkgRaySelectTargetToHit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d75360 VA: 0x759438d360
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d755f8 VA: 0x759438d5f8
	protected override Void DoSelectTargetToHit(Vector2 inputPos) { }
	// RVA: 0x1d7567c VA: 0x759438d67c
	private Void _ShpkgRaySelectTargetToHit() { }
	// RVA: 0x1d757f8 VA: 0x759438d7f8
	public Void .ctor() { }
	// RVA: 0x1d75864 VA: 0x759438d864
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d75868 VA: 0x759438d868
	private Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2 P0) { }
}
```