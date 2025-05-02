# RoguelikeDuelCameraPlugin

**Namespace:** `Torappu.Battle.Roguelike.Duel`


## Fields

- `Tween m_cachedCameraTween`

- `Tween m_cachedSequence`


## Properties

- `Vector3 cameraOffset`


## Methods

- `Vector3 get_cameraOffset()`

- `Void _OnTweenComplete()`

- `Void <DoMoveCameraDirectly>b__5_0()`

- `Void <>xLuaBaseProxy_DoMoveCameraDirectly(Vector3, Boolean)`

- `Vector3 <>xLuaBaseProxy_CalculateCameraFocusPos(Vector3)`

- `Vector3 <>xLuaBaseProxy_CalculateCameraOffset(Vector3)`

- `Boolean <>xLuaBaseProxy_TrySetCameraPosition(CameraPosition, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike.Duel
public class RoguelikeDuelCameraPlugin : Plugin
{
	private const Single MOVE_TIME; // 0x0
	private Tween m_cachedCameraTween; // 0x20
	private Tween m_cachedSequence; // 0x28
	private static DelegateBridge __Hotfix0_get_cameraOffset; // 0x0
	private static DelegateBridge __Hotfix0_DoMoveCameraDirectly; // 0x8
	private static DelegateBridge __Hotfix0__OnTweenComplete; // 0x10
	private static DelegateBridge __Hotfix0_CalculateCameraFocusPos; // 0x18
	private static DelegateBridge __Hotfix0_CalculateCameraOffset; // 0x20
	private static DelegateBridge __Hotfix0_TrySetCameraPosition; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Vector3 cameraOffset { get; }

	// RVA: 0x1d4aafc VA: 0x7594362afc
	private Vector3 get_cameraOffset() { }
	// RVA: 0x1d4ab8c VA: 0x7594362b8c
	public override Void DoMoveCameraDirectly(Vector3 targetPos, Boolean tween) { }
	// RVA: 0x1d4aec0 VA: 0x7594362ec0
	private Void _OnTweenComplete() { }
	// RVA: 0x1d4afc4 VA: 0x7594362fc4
	public override Vector3 CalculateCameraFocusPos(Vector3 targetPos) { }
	// RVA: 0x1d4b060 VA: 0x7594363060
	public override Vector3 CalculateCameraOffset(Vector3 originPos) { }
	// RVA: 0x1d4b0fc VA: 0x75943630fc
	public override Boolean TrySetCameraPosition(CameraPosition cameraPos, Boolean tween) { }
	// RVA: 0x1d4b4dc VA: 0x75943634dc
	public Void .ctor() { }
	// RVA: 0x1d4b54c VA: 0x759436354c
	private Void <DoMoveCameraDirectly>b__5_0() { }
	// RVA: 0x1d4b550 VA: 0x7594363550
	private Void <>xLuaBaseProxy_DoMoveCameraDirectly(Vector3 P0, Boolean P1) { }
	// RVA: 0x1d4b55c VA: 0x759436355c
	private Vector3 <>xLuaBaseProxy_CalculateCameraFocusPos(Vector3 P0) { }
	// RVA: 0x1d4b564 VA: 0x7594363564
	private Vector3 <>xLuaBaseProxy_CalculateCameraOffset(Vector3 P0) { }
	// RVA: 0x1d4b56c VA: 0x759436356c
	private Boolean <>xLuaBaseProxy_TrySetCameraPosition(CameraPosition P0, Boolean P1) { }
}
```