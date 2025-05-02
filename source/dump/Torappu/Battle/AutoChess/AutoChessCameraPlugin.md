# AutoChessCameraPlugin

**Namespace:** `Torappu.Battle.AutoChess`


## Fields

- `Ease _moveTween`

- `Ease _scaleTween`

- `Coroutine m_coroutine`

- `CameraOption m_option`

- `CameraController m_controller`


## Properties

- `Vector3 defaultCameraPos`

- `Vector3 battletCameraPos`


## Methods

- `Vector3 get_defaultCameraPos()`

- `Vector3 get_battletCameraPos()`

- `Void MoveTo(CameraPosition, Boolean)`

- `Void SetOption(CameraOption)`

- `Void _MoveTo(Vector3, Single, Boolean)`

- `IEnumerator SetCamerPosAfterFocus(Single, Vector3, Single)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.AutoChess
public class AutoChessCameraPlugin : Plugin
{
	private Ease _moveTween; // 0x20
	private Ease _scaleTween; // 0x24
	private Coroutine m_coroutine; // 0x28
	private CameraOption m_option; // 0x30
	private CameraController m_controller; // 0x58
	private static DelegateBridge __Hotfix0_get_defaultCameraPos; // 0x0
	private static DelegateBridge __Hotfix0_get_battletCameraPos; // 0x8
	private static DelegateBridge __Hotfix0_MoveTo; // 0x10
	private static DelegateBridge __Hotfix0_SetOption; // 0x18
	private static DelegateBridge __Hotfix0__MoveTo; // 0x20
	private static DelegateBridge __Hotfix0_SetCamerPosAfterFocus; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Vector3 defaultCameraPos { get; }
	public Vector3 battletCameraPos { get; }

	// RVA: 0x1c88c40 VA: 0x75942a0c40
	public Vector3 get_defaultCameraPos() { }
	// RVA: 0x1c88ca8 VA: 0x75942a0ca8
	public Vector3 get_battletCameraPos() { }
	// RVA: 0x1c88d10 VA: 0x75942a0d10
	public Void MoveTo(CameraPosition pos, Boolean tween) { }
	// RVA: 0x1c88f90 VA: 0x75942a0f90
	public Void SetOption(CameraOption option) { }
	// RVA: 0x1c88dec VA: 0x75942a0dec
	public Void _MoveTo(Vector3 targetPos, Single size, Boolean tween) { }
	// RVA: 0x1c89028 VA: 0x75942a1028
	private IEnumerator SetCamerPosAfterFocus(Single time, Vector3 rootPos, Single size) { }
	// RVA: 0x1c89154 VA: 0x75942a1154
	private Void OnDestroy() { }
	// RVA: 0x1c891d4 VA: 0x75942a11d4
	public Void .ctor() { }
}
```