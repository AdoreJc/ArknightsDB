# ProjectileBBIncreaseByTimeBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Boolean _onlyIncreaseReached`

- `Single _interval`

- `String _intervalKey`

- `String _syncProjectileScaleBbKey`

- `PeriodicTimer m_timer`


## Methods

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class ProjectileBBIncreaseByTimeBehaviour : Behaviour
{
	private BBGroup[] _bbGroups; // 0x28
	private Boolean _onlyIncreaseReached; // 0x30
	private Single _interval; // 0x34
	private String _intervalKey; // 0x38
	private String _syncProjectileScaleBbKey; // 0x40
	private PeriodicTimer m_timer; // 0x48
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d6d344 VA: 0x7594385344
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d6d6a4 VA: 0x75943856a4
	public override Void OnProjectileStop() { }
	// RVA: 0x1d6d7b0 VA: 0x75943857b0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d6da78 VA: 0x7594385a78
	public Void .ctor() { }
	// RVA: 0x1d6dae8 VA: 0x7594385ae8
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d6daf0 VA: 0x7594385af0
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x1d6daf8 VA: 0x7594385af8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```