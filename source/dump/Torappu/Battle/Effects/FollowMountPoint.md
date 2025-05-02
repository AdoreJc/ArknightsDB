# FollowMountPoint

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `MountPointType _mountPointType`

- `Boolean _followScaleSign`

- `Boolean _followScale`

- `Boolean _pauseWhenMountPointInvalid`

- `Boolean _onlyPauseWhenMountPointInvalid`

- `Boolean _keepOriginRotation`

- `Boolean _useBehaviourPause`


## Methods

- `Void LateUpdate()`

- `Void _FollowMountPoint(Entity)`

- `Void <>xLuaBaseProxy_OnPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class FollowMountPoint : Behaviour
{
	private MountPointType _mountPointType; // 0x20
	private Boolean _followScaleSign; // 0x24
	private Boolean _followScale; // 0x25
	private Boolean _pauseWhenMountPointInvalid; // 0x26
	private Boolean _onlyPauseWhenMountPointInvalid; // 0x27
	private Boolean _keepOriginRotation; // 0x28
	private Boolean _useBehaviourPause; // 0x29
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_LateUpdate; // 0x8
	private static DelegateBridge __Hotfix0__FollowMountPoint; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1ffc694 VA: 0x7594614694
	public override Void OnPlay() { }
	// RVA: 0x1ffc9d0 VA: 0x75946149d0
	private Void LateUpdate() { }
	// RVA: 0x1ffc778 VA: 0x7594614778
	private Void _FollowMountPoint(Entity owner) { }
	// RVA: 0x1ffcaac VA: 0x7594614aac
	public Void .ctor() { }
	// RVA: 0x1ffcb20 VA: 0x7594614b20
	private Void <>xLuaBaseProxy_OnPlay() { }
}
```