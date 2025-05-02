# PositionBasedLineRenderer

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `String _mainEffect`

- `Vector3 _startWorldOffset`

- `Vector3 _endWorldOffset`

- `Vector3 _endWorldOffsetWhenNotHit`

- `Boolean _stopToNearestHitTarget`

- `Boolean _excludeInactiveRallyPoint`

- `Boolean _useMuzzlePointOffset`

- `Vector3 _extraOffsetLeft`

- `Vector3 _extraOffsetRight`

- `Vector3 m_startMountPoint`

- `Vector3 m_endMountPoint`

- `Boolean m_isProjectileReached`

- `Vector3 m_startWorldOffset`

- `Vector3 m_endWorldOffset`

- `Vector3 m_endWorldOffsetWhenNotHit`


## Properties

- `Boolean useMuzzlePointOffset`

- `Boolean stopToNearestHitTarget`


## Methods

- `Boolean get_useMuzzlePointOffset()`

- `Boolean get_stopToNearestHitTarget()`

- `Void _ApplyLineRenderPositions()`

- `Boolean _CheckRallyPointInactive(RallyPoint)`

- `Void GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnHitTarget(Entity)`

- `Void <>xLuaBaseProxy_OnProjectileReached()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class PositionBasedLineRenderer : Behaviour, IEffectSource
{
	private String _mainEffect; // 0x28
	private Vector3 _startWorldOffset; // 0x30
	private Vector3 _endWorldOffset; // 0x3c
	private Vector3 _endWorldOffsetWhenNotHit; // 0x48
	private Boolean _stopToNearestHitTarget; // 0x54
	private Boolean _excludeInactiveRallyPoint; // 0x55
	private Boolean _useMuzzlePointOffset; // 0x56
	private Vector3 _extraOffsetLeft; // 0x58
	private Vector3 _extraOffsetRight; // 0x64
	private ObjectPtr`1 m_nearestHitTarget; // 0x70
	private ObjectPtr`1 m_mainEffect; // 0x80
	private LineRenderer[] m_lineRenderers; // 0x90
	private Vector3 m_startMountPoint; // 0x98
	private Vector3 m_endMountPoint; // 0xa4
	private Vector3[] m_positions; // 0xb0
	private Boolean m_isProjectileReached; // 0xb8
	private Vector3 m_startWorldOffset; // 0xbc
	private Vector3 m_endWorldOffset; // 0xc8
	private Vector3 m_endWorldOffsetWhenNotHit; // 0xd4
	private static DelegateBridge __Hotfix0_get_useMuzzlePointOffset; // 0x0
	private static DelegateBridge __Hotfix0_get_stopToNearestHitTarget; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnHitTarget; // 0x18
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x20
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x28
	private static DelegateBridge __Hotfix0_OnTick; // 0x30
	private static DelegateBridge __Hotfix0__ApplyLineRenderPositions; // 0x38
	private static DelegateBridge __Hotfix0__CheckRallyPointInactive; // 0x40
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Boolean useMuzzlePointOffset { get; }
	public Boolean stopToNearestHitTarget { get; }

	// RVA: 0x1d6bd1c VA: 0x7594383d1c
	public Boolean get_useMuzzlePointOffset() { }
	// RVA: 0x1d6bd84 VA: 0x7594383d84
	public Boolean get_stopToNearestHitTarget() { }
	// RVA: 0x1d6bdec VA: 0x7594383dec
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d6c540 VA: 0x7594384540
	public override Void OnHitTarget(Entity target) { }
	// RVA: 0x1d6cb70 VA: 0x7594384b70
	public override Void OnProjectileReached() { }
	// RVA: 0x1d6cbe8 VA: 0x7594384be8
	public override Void OnProjectileStop() { }
	// RVA: 0x1d6ccec VA: 0x7594384cec
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d6c92c VA: 0x759438492c
	private Void _ApplyLineRenderPositions() { }
	// RVA: 0x1d6c858 VA: 0x7594384858
	private Boolean _CheckRallyPointInactive(RallyPoint rally) { }
	// RVA: 0x1d6cd78 VA: 0x7594384d78
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d6ce8c VA: 0x7594384e8c
	public Void .ctor() { }
	// RVA: 0x1d6cfc4 VA: 0x7594384fc4
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d6cfcc VA: 0x7594384fcc
	private Void <>xLuaBaseProxy_OnHitTarget(Entity P0) { }
	// RVA: 0x1d6cfd4 VA: 0x7594384fd4
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
	// RVA: 0x1d6cfdc VA: 0x7594384fdc
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x1d6cfe4 VA: 0x7594384fe4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```