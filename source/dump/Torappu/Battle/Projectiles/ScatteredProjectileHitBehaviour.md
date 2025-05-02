# ScatteredProjectileHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `String _projectileKey`

- `Boolean m_useHookProjectile`

- `String m_logicProjectileKey`

- `String m_graphicProjectileKey`

- `Single m_subAtkScale`

- `Int32 m_maxTargetNum`

- `Int32 m_targetHit`


## Methods

- `Void EmitScatteredProjectile(Entity)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class ScatteredProjectileHitBehaviour : SelectorHitBehaviour
{
	private String _projectileKey; // 0x80
	private Boolean m_useHookProjectile; // 0x88
	private String m_logicProjectileKey; // 0x90
	private String m_graphicProjectileKey; // 0x98
	private Single m_subAtkScale; // 0xa0
	private List`1 m_damageNodeReplacedActionNodes; // 0xa8
	private Int32 m_maxTargetNum; // 0xb0
	private Int32 m_targetHit; // 0xb4
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_EmitScatteredProjectile; // 0x8
	private static DelegateBridge __Hotfix0_DoSelectTargetToHit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d70e6c VA: 0x7594388e6c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d7169c VA: 0x759438969c
	private Void EmitScatteredProjectile(Entity entity) { }
	// RVA: 0x1d718e4 VA: 0x75943898e4
	protected override Void DoSelectTargetToHit(Vector2 inputPos) { }
	// RVA: 0x1d71bb8 VA: 0x7594389bb8
	public Void .ctor() { }
	// RVA: 0x1d71d20 VA: 0x7594389d20
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d71d24 VA: 0x7594389d24
	private Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2 P0) { }
}
```