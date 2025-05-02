# Thorn2S2AdvancedMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _extraMoveSpeed`

- `FP m_extraMoveSpeed`

- `FP m_moveEndTime`

- `Vector3 m_cachedDirect`

- `PeriodicTimer m_moveTimer`

- `Vector3 m_cachedOwnerPos`


## Methods

- `Boolean <>xLuaBaseProxy_get_comeBack()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_DealReached()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class Thorn2S2AdvancedMovement : AdvancedMovement
{
	private Single _extraMoveSpeed; // 0x114
	private FP m_extraMoveSpeed; // 0x118
	private FP m_moveEndTime; // 0x120
	private Vector3 m_cachedDirect; // 0x128
	private PeriodicTimer m_moveTimer; // 0x138
	private Vector3 m_cachedOwnerPos; // 0x140
	private static DelegateBridge __Hotfix0_get_comeBack; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_DealReached; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Boolean comeBack { get; }

	// RVA: 0x1dad39c VA: 0x75943c539c
	public override Boolean get_comeBack() { }
	// RVA: 0x1dad400 VA: 0x75943c5400
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1dad614 VA: 0x75943c5614
	protected override Void DealReached() { }
	// RVA: 0x1dad858 VA: 0x75943c5858
	public override Void OnProjectileStop() { }
	// RVA: 0x1dad8d8 VA: 0x75943c58d8
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1dadaa0 VA: 0x75943c5aa0
	public Void .ctor() { }
	// RVA: 0x1dadba4 VA: 0x75943c5ba4
	private Boolean <>xLuaBaseProxy_get_comeBack() { }
	// RVA: 0x1dadbac VA: 0x75943c5bac
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1dadbb4 VA: 0x75943c5bb4
	private Void <>xLuaBaseProxy_DealReached() { }
	// RVA: 0x1dadbbc VA: 0x75943c5bbc
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x1dadbc4 VA: 0x75943c5bc4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```