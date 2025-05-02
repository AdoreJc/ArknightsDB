# PhenxiS2Behaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `String _projectileKey`

- `Boolean m_useHookProjectile`

- `String m_logicProjectileKey`

- `String m_graphicProjectileKey`

- `Single m_subAtkScale`

- `Vector2 m_targetPos`

- `Vector2 m_startPos`

- `Vector2 m_direction`

- `Single m_bombDist`

- `Int32 m_currentBombIndex`

- `Boolean m_tooClose`


## Methods

- `Void _CheckDistanceToEmitProjectile()`

- `Void EmitSubProjectile(ILocatable)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class PhenxiS2Behaviour : Behaviour
{
	private String _projectileKey; // 0x28
	private Boolean m_useHookProjectile; // 0x30
	private String m_logicProjectileKey; // 0x38
	private String m_graphicProjectileKey; // 0x40
	private Single m_subAtkScale; // 0x48
	private List`1 m_damageNodeReplacedActionNodes; // 0x50
	private Vector2 m_targetPos; // 0x58
	private Vector2 m_startPos; // 0x60
	private Vector2 m_direction; // 0x68
	private Single m_bombDist; // 0x70
	private Int32 m_currentBombIndex; // 0x74
	private Boolean m_tooClose; // 0x78
	private const Single TOO_CLOSE_DISTANCE; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0__CheckDistanceToEmitProjectile; // 0x10
	private static DelegateBridge __Hotfix0_EmitSubProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1d6aa34 VA: 0x7594382a34
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d6af40 VA: 0x7594382f40
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d6afcc VA: 0x7594382fcc
	private Void _CheckDistanceToEmitProjectile() { }
	// RVA: 0x1d6b30c VA: 0x759438330c
	private Void EmitSubProjectile(ILocatable pos) { }
	// RVA: 0x1d6b71c VA: 0x759438371c
	public Void .ctor() { }
	// RVA: 0x1d6b78c VA: 0x759438378c
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d6b794 VA: 0x7594383794
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```