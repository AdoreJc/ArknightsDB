# AttachToTarget

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Boolean _keepUpdate`

- `Boolean _attachToMountPoint`

- `Boolean _ignoreMountPointHeight`

- `MountPointType _mountPointType`

- `Boolean _checkReached`

- `Boolean _delayAfterReached`

- `Boolean _updateDelayTimeOnlyOnce`

- `Single _delayTime`

- `Single _extraDelayTime`

- `Single _delayToStart`

- `Boolean _immediatelyReach`

- `Boolean _stopIfTargetDead`

- `Boolean _stopIfTargetDisappeared`

- `Boolean _followTarget`

- `MountPoint m_mountPoint`

- `FP m_delayTime`

- `Single m_delayToStart`

- `Boolean m_alreadyUpdateAfterDelay`


## Properties

- `Boolean delayAfterReached`

- `Boolean attachToMountPoint`


## Methods

- `Boolean get_delayAfterReached()`

- `Boolean get_attachToMountPoint()`

- `Void _OnBeforeAppearOrDisappear(Object)`

- `Boolean CheckStartTick(Single)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Boolean <>xLuaBaseProxy_DoCheckReachedInternal()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class AttachToTarget : BasicMovement
{
	private Boolean _keepUpdate; // 0x94
	private Boolean _attachToMountPoint; // 0x95
	private Boolean _ignoreMountPointHeight; // 0x96
	private MountPointType _mountPointType; // 0x98
	private Boolean _checkReached; // 0x9c
	private Boolean _delayAfterReached; // 0x9d
	private Boolean _updateDelayTimeOnlyOnce; // 0x9e
	private Single _delayTime; // 0xa0
	private Single _extraDelayTime; // 0xa4
	private Single _delayToStart; // 0xa8
	private Boolean _immediatelyReach; // 0xac
	private Boolean _stopIfTargetDead; // 0xad
	private Boolean _stopIfTargetDisappeared; // 0xae
	private Boolean _followTarget; // 0xaf
	private MountPoint m_mountPoint; // 0xb0
	private FP m_delayTime; // 0xb8
	private Single m_delayToStart; // 0xc0
	private Boolean m_alreadyUpdateAfterDelay; // 0xc4
	private static DelegateBridge __Hotfix0_get_delayAfterReached; // 0x0
	private static DelegateBridge __Hotfix0_get_attachToMountPoint; // 0x8
	private static DelegateBridge __Hotfix0_get_movementAdjustable; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0__OnBeforeAppearOrDisappear; // 0x28
	private static DelegateBridge __Hotfix0_DoCheckReachedInternal; // 0x30
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x38
	private static DelegateBridge __Hotfix0_CheckStartTick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected Boolean delayAfterReached { get; }
	private Boolean attachToMountPoint { get; }
	public override Boolean movementAdjustable { get; }

	// RVA: 0x1d9d200 VA: 0x75943b5200
	protected Boolean get_delayAfterReached() { }
	// RVA: 0x1d9d268 VA: 0x75943b5268
	private Boolean get_attachToMountPoint() { }
	// RVA: 0x1d9d2d0 VA: 0x75943b52d0
	public override Boolean get_movementAdjustable() { }
	// RVA: 0x1d9d334 VA: 0x75943b5334
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1d9d938 VA: 0x75943b5938
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1d9dd34 VA: 0x75943b5d34
	private Void _OnBeforeAppearOrDisappear(Object arg) { }
	// RVA: 0x1d9de40 VA: 0x75943b5e40
	protected override Boolean DoCheckReachedInternal() { }
	// RVA: 0x1d9ded8 VA: 0x75943b5ed8
	public override Void OnProjectileStop() { }
	// RVA: 0x1d9d85c VA: 0x75943b585c
	protected Boolean CheckStartTick(Single deltaTime) { }
	// RVA: 0x1d9e03c VA: 0x75943b603c
	public Void .ctor() { }
	// RVA: 0x1d9e0e8 VA: 0x75943b60e8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d9e0f0 VA: 0x75943b60f0
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1d9e0f8 VA: 0x75943b60f8
	private Boolean <>xLuaBaseProxy_DoCheckReachedInternal() { }
	// RVA: 0x1d9e100 VA: 0x75943b6100
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```