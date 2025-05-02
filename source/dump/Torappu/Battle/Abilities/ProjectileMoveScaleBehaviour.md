# ProjectileMoveScaleBehaviour

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _moveScale`

- `FP m_moveScale`


## Methods

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnProjectileEnter(Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileExit(Projectile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ProjectileMoveScaleBehaviour : ProjectileAuraBehaviour
{
	private Single _moveScale; // 0x20
	private FP m_moveScale; // 0x28
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_OnProjectileEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnProjectileExit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1ed10a4 VA: 0x75944e90a4
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ed1198 VA: 0x75944e9198
	public override Void OnProjectileEnter(Projectile projectile) { }
	// RVA: 0x1ed12a0 VA: 0x75944e92a0
	public override Void OnProjectileExit(Projectile projectile) { }
	// RVA: 0x1ed13a8 VA: 0x75944e93a8
	public Void .ctor() { }
	// RVA: 0x1ed1420 VA: 0x75944e9420
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ed1428 VA: 0x75944e9428
	private Void <>xLuaBaseProxy_OnProjectileEnter(Projectile P0) { }
	// RVA: 0x1ed1430 VA: 0x75944e9430
	private Void <>xLuaBaseProxy_OnProjectileExit(Projectile P0) { }
}
```