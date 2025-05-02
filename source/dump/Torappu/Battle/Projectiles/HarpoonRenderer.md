# HarpoonRenderer

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `String _mainEffect`

- `Boolean _throwEffect`

- `Boolean _includeInactive`

- `Boolean _useEndPointAsStartPos`

- `Boolean _hookStartPoint`

- `MountPointType _hookedStartPointType`

- `Boolean _finishOnMountPointInvalid`

- `Boolean _spawnOnSource`

- `Boolean _independentUpdateAfterReached`

- `MountPoint m_startMountPoint`

- `MountPoint m_endMountPoint`

- `Boolean m_isProjectileReached`


## Properties

- `Boolean hookStartPoint`


## Methods

- `Boolean get_hookStartPoint()`

- `Void _UpdatePosition()`

- `Void Update()`

- `Void GatherEffects(List`1)`

- `Boolean _TryHookStartPoint(out)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Void <>xLuaBaseProxy_OnProjectileReached()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class HarpoonRenderer : Behaviour, IEffectSource
{
	private String _mainEffect; // 0x28
	private Boolean _throwEffect; // 0x30
	private Boolean _includeInactive; // 0x31
	private Boolean _useEndPointAsStartPos; // 0x32
	private Boolean _hookStartPoint; // 0x33
	private MountPointType _hookedStartPointType; // 0x34
	private Boolean _finishOnMountPointInvalid; // 0x38
	private Boolean _spawnOnSource; // 0x39
	private Boolean _independentUpdateAfterReached; // 0x3a
	private ObjectPtr`1 m_mainEffect; // 0x40
	private LineRenderer[] m_lineRenderers; // 0x50
	private MountPoint m_startMountPoint; // 0x58
	private MountPoint m_endMountPoint; // 0x60
	private Boolean m_isProjectileReached; // 0x68
	private Vector3[] m_positions; // 0x70
	private static DelegateBridge __Hotfix0_get_hookStartPoint; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge __Hotfix0__UpdatePosition; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x38
	private static DelegateBridge __Hotfix0__TryHookStartPoint; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Boolean hookStartPoint { get; }

	// RVA: 0x1d65f0c VA: 0x759437df0c
	private Boolean get_hookStartPoint() { }
	// RVA: 0x1d65f74 VA: 0x759437df74
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d665c4 VA: 0x759437e5c4
	public override Void OnProjectileStop() { }
	// RVA: 0x1d6671c VA: 0x759437e71c
	public override Void OnProjectileReached() { }
	// RVA: 0x1d66794 VA: 0x759437e794
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d66930 VA: 0x759437e930
	private Void _UpdatePosition() { }
	// RVA: 0x1d66a9c VA: 0x759437ea9c
	private Void Update() { }
	// RVA: 0x1d66b38 VA: 0x759437eb38
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d6644c VA: 0x759437e44c
	private Boolean _TryHookStartPoint(out MountPoint startPoint) { }
	// RVA: 0x1d66c4c VA: 0x759437ec4c
	public Void .ctor() { }
	// RVA: 0x1d66cf8 VA: 0x759437ecf8
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d66d00 VA: 0x759437ed00
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x1d66d08 VA: 0x759437ed08
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
	// RVA: 0x1d66d10 VA: 0x759437ed10
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```