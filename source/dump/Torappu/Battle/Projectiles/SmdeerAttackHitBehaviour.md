# SmdeerAttackHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `String _projectileKey`

- `Direction _defaultDirection`

- `Vector2 m_startPos`

- `Vector2 m_direction`

- `Single m_bombDist`

- `Int32 m_currentBombIndex`

- `Single m_subAtkScale`


## Methods

- `Void _CheckDistanceToEmitProjectile()`

- `Void EmitSubProjectile(ILocatable)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class SmdeerAttackHitBehaviour : Behaviour
{
	private String _projectileKey; // 0x28
	private Direction _defaultDirection; // 0x30
	private Vector2 m_startPos; // 0x34
	private Vector2 m_direction; // 0x3c
	private Single m_bombDist; // 0x44
	private Int32 m_currentBombIndex; // 0x48
	private Single m_subAtkScale; // 0x4c
	private List`1 m_damageNodeReplacedActionNodes; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0__CheckDistanceToEmitProjectile; // 0x10
	private static DelegateBridge __Hotfix0_EmitSubProjectile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1d7586c VA: 0x759438d86c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d75bd0 VA: 0x759438dbd0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d75c8c VA: 0x759438dc8c
	private Void _CheckDistanceToEmitProjectile() { }
	// RVA: 0x1d75f24 VA: 0x759438df24
	private Void EmitSubProjectile(ILocatable pos) { }
	// RVA: 0x1d760fc VA: 0x759438e0fc
	public Void .ctor() { }
	// RVA: 0x1d76174 VA: 0x759438e174
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d7617c VA: 0x759438e17c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```