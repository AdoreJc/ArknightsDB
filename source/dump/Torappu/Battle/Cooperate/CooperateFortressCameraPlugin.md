# CooperateFortressCameraPlugin

**Namespace:** `Torappu.Battle.Cooperate`


## Fields

- `CooperateMoveCameraAVGCommand m_moveCameraAVGCommand`

- `CooperateLockCameraAVGCommand m_lockCameraAVGCommand`


## Methods

- `Void <>xLuaBaseProxy__InitIfNot()`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `Void <>xLuaBaseProxy__UpdateCamera()`

- `Void <>xLuaBaseProxy__OnBeginDrag(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Cooperate
public class CooperateFortressCameraPlugin : DraggableCameraPlugin
{
	private CooperateMoveCameraAVGCommand m_moveCameraAVGCommand; // 0xc0
	private CooperateLockCameraAVGCommand m_lockCameraAVGCommand; // 0xc8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0__UpdateCamera; // 0x10
	private static DelegateBridge __Hotfix0__OnBeginDrag; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1c64b40 VA: 0x759427cb40
	protected override Void _InitIfNot() { }
	// RVA: 0x1c64c6c VA: 0x759427cc6c
	protected override Void OnDestroy() { }
	// RVA: 0x1c64d40 VA: 0x759427cd40
	protected override Void _UpdateCamera() { }
	// RVA: 0x1c64dc8 VA: 0x759427cdc8
	protected override Void _OnBeginDrag(Object arg) { }
	// RVA: 0x1c64ef4 VA: 0x759427cef4
	public Void .ctor() { }
	// RVA: 0x1c64fd8 VA: 0x759427cfd8
	private Void <>xLuaBaseProxy__InitIfNot() { }
	// RVA: 0x1c64fe0 VA: 0x759427cfe0
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x1c64fe8 VA: 0x759427cfe8
	private Void <>xLuaBaseProxy__UpdateCamera() { }
	// RVA: 0x1c64ff0 VA: 0x759427cff0
	private Void <>xLuaBaseProxy__OnBeginDrag(Object P0) { }
}
```