# SubProjectileToTileBeforeReachBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `String _projectileKey`

- `Boolean m_hasFirstEmit`


## Methods

- `Void EmitSubProjectile(ILocatable)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class SubProjectileToTileBeforeReachBehaviour : Behaviour
{
	private String _projectileKey; // 0x28
	private Boolean m_hasFirstEmit; // 0x30
	private HashSet`1 m_emittedTiles; // 0x38
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_EmitSubProjectile; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d78638 VA: 0x7594390638
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d78708 VA: 0x7594390708
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d788d8 VA: 0x75943908d8
	private Void EmitSubProjectile(ILocatable pos) { }
	// RVA: 0x1d78a9c VA: 0x7594390a9c
	public Void .ctor() { }
	// RVA: 0x1d78b60 VA: 0x7594390b60
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d78b68 VA: 0x7594390b68
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```